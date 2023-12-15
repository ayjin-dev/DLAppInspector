# DLAppInspector

## *Accepted to TrustCom-2023*

## Abstract

Recent years have witnessed an astonishing explosion in the evolution of mobile applications powered by deep learning (DL)  technologies. Considering that inference of DL models in the cloud requires transferring user data to server, which is prone to the risk of user privacy leakage, many developers choose to deploy the models on local devices for executing the inference process. However, this also raises a number of other security issues, such as adversarial attacks, model stealing attacks, etc.

To explore the security issues that exist in deep learning applications (DL apps) in the wild, we conducted the first comprehensive comparative study of the top 200 DL apps and Non-DL apps in each category on Google Play.

We built DLApplnspector, a vulnerability detection tool that combines dynamic and static analysis methods for dissecting apps, which helped us automate our empirical study on real-world mobile DL apps.First, we identify DL apps and extract their models by using DL Checker. Subsequently, Static Scoper is provided to detect encryption and reusability of DL models, as well as checking the sensitive permissions of apps.  Finally, within Dynamic Scoper, we use reverse engineering techniques on the network traffic to parse out the packets and collect side-channel information during application runtime.

Our research shows that the majority of developers prefer to use open-source models, **with almost 92% of models successfully parsed**. This suggests that most models are unprotected. **DL apps are more likely to grant sensitive permissions, upload user behaviour and collect private data than Non-DL apps**. In addition, we observed that DL apps rely much more heavily on 3rd party libraries than Non-DL apps.  We also found potential security vulnerabilities through a comparison with publicly available CVE vulnerability databases. We provide security recommendations for developers and users to address the issues discovered.

---

***If you need the apk dataset.
Please contact with us by email: ouyangjin334@gmail.com***



**We will continue to update this repo constantly, so stay tuned!**
