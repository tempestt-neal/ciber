---
title: "CIBeR Lab @ USF - Research"
layout: textlay
excerpt: "CIBeR Lab @ USF -- Research"
sitemap: false
permalink: /research/
---

# Research

Our research is largely inspired by the ubiquitous nature of today's technologies, and how smart sensing enabled by these technologies can be used to understand how people interact with the technology itself, interact with each other, and behave in different environments. To do so, we generally rely on applied artificial intelligence, statistics, and human-centered computing techniques to answer research questions which focus on
- usable and inclusive cybersecurity systems, particularly related to identity and access management
- interdisciplinary applications of human behavior analysis through smart sensing

Here are some themes and techniques that we currently work on:

**Mobile Biometrics.** Commercial mobile devices currently employ point-of-entry (PoE) authentication methods such as face recognition and personal identification numbers. Several studies show that knowledge-based authenticators are ineffective due to increased memory load, poorly chosen alphanumeric combinations, and repetitive use of passcodes across many applications. PoE and knowledge-based authenticators are both ineffective throughout sessions of use; once the user is authenticated, the device and its content remain available to the current user. In this research, we explored various data based on usage of a mobile device as behavioral biometric modalities, including patterns in application use, networking activity (i.e., Bluetooth and Wi-Fi sightings), and communication through calling and text messaging, which can continuously and passively authenticate a device’s owner. 

*Significant findings and methods developed throughout this research include:*
*	We demonstrated the use of association rules as a feature representation for application, Bluetooth, and Wi-Fi data which outperformed previously employed frequency-based features. Our findings suggest that patterns in application and Bluetooth traffic are more distinct than those in Wi-Fi patterns with up to 91% accuracy. Performance obtained in this study were consistent with implementations of keystroke dynamics and touch gestures for biometric authentication, a significant indication that passive modalities are as viable as their physical counterparts.
*	We provided empirically-supported evidence of gender-based usage patterns, including higher activity levels of female compared to male users in application use and the differentiation between the two groups based on transitions between sports, navigation, and system-related apps and number of revisitations to apps within sessions.
*	We developed temporally-derived replay attack simulations to assess system performance under threatening conditions in which the legitimate user is easily observed or their usage data is remotely accessed. The intercepted data is then intelligently combined with some level of noise to avoid the replay of an exact copy of legitimate data by an attacker. The attacker’s data thus maintains a level of similarity with the legitimate data. Our experiments show that our attack models can lead to false positive rates ranging from 30 to 50%, while in some cases, zero-effort attacks lead to much lower, and thus misleading, error rates.
*	We introduced an easily interpretable profiling technique as a feature representation for user-device interaction data that contextualizes mobile device usage patterns. Our experiments show that these profiles allow better separation of legitimate and impostor behavior. Error rates associated with behavior profiles either improved or were not affected by the amount of data provided for authentication, while those associated with frequency-based features, which are seen in several research studies, worsened. 
*	We developed a novel ranking function which quantifies the informativeness of a soft biometric class for search space reduction. The function relies on the rank-1 recognition accuracy for the class, a score quantifying the permanence of the class, and a cost derived from the ratio of misclassifications to the number of subjects in the soft biometric class.
 
This project resulted in the following publications:
1.	T. Neal, D. Woodard and A. D. Striegel. Mobile device application, Bluetooth, and Wi-Fi usage data as behavioral biometric traits, 2015 IEEE 7th International Conference on Biometrics Theory, Applications and Systems (BTAS), Arlington, VA, 2015, pp. 1-6. doi: 10.1109/BTAS.2015.7358777 
2.	T. Neal and D. L. Woodard. Spoofing analysis of mobile device data as behavioral biometric modalities, 2017 IEEE International Joint Conference on Biometrics (IJCB), Denver, CO, 2017, pp. 62-70. doi: 10.1109/BTAS.2017.8272683 
3.	T. Neal and D. L. Woodard. Using associative classification to authenticate mobile device users, 2017 IEEE International Joint Conference on Biometrics (IJCB), Denver, CO, 2017, pp. 71-79. doi: 10.1109/BTAS.2017.8272684 
4.	T. Neal and D. L. Woodard. A gender-specific behavioral analysis of mobile device usage data, 2018 IEEE 4th International Conference on Identity, Security, and Behavior Analysis (ISBA), Singapore, 2018, pp. 1-8. doi: 10.1109/ISBA.2018.8311459 
5.	T. Neal and D. L. Woodard. (2018) On the Use of Mobile Calling Patterns for Soft Biometric Classification, IEEE 9th International Conference on Biometrics Theory, Applications and Systems (BTAS 2018), Los Angeles, California.
6.	T. Neal and D. L. Woodard. Mobile Biometrics, Replay Attacks, and Behavior Profiling: An Empirical Analysis of Impostor Detection. 12th IAPR International Conference on Biometrics (ICB 2019), Crete, Greece.
7.	T. Neal and Woodard, D. L. (2016). Surveying biometric authentication for mobile device security. Journal of Pattern Recognition Research, 1, 74-110. doi:10.13176/11.764.
8.	T. Neal and D. Woodard, "You’re Not Acting Like Yourself: A Study on Soft Biometric Classification, Person Identification, and Mobile Device Use," in IEEE Transactions on Biometrics, Behavior, and Identity Science. doi: 10.1109/TBIOM.2019.2905868.
9.	T. Neal and D. L. Woodard. “Adversarial Attacks in Mobile Environments.” Eds. T. Bourlai, P. Karampelas, and V. Patel. Securing Social Identity in Mobile Platforms, Technologies for Social Network Analysis and Identity Management. Springer, expected 2019.
10.	T. Neal, Woodard, Damon L., and Striegel, Aaron D. Mobile device usage data as behavioral biometrics (Security, 2017), ‘Mobile Biometrics’, Chap. 7, pp. 177-207, DOI: 10.1049/PBSE003E ch7.

**Inclusive Identity and Access Management.** Questions of interest include: (i), How does the Mott state collapse upon doping and how is this related to the complex phase diagram of high-temperature superconductors? (ii), What is the strange metal phase seen in correlated electron systems? Is this an exotic long-range entangled state? What is the mechanism of dissipation in that state? (iii), Why is the transition temperature in high-temperature superconductors so high? We have worked on iridates, rhodates, and cuprates.

**Automated Deception Detection and Suicide**.
![]({{ site.url }}{{ site.baseurl }}/images/respic/SmartTip.png){: style="width: 250px; float: left; margin: 0px  10px"}
One of the  projects back from my job-proposal is to develop nanofabricated STM tips. The idea behind these “smart tips” is to use the technologies that were developed over decades in nanofabrication and make them available for scanning probe by using a nano-device instead of the traditional STM tungsten tip. One gains the flexibility of using different functionalities that are known from the fields of nanofabrication and mesoscopic physics. We are collaborating with the group Simon Groeblacher at TU Delft to realize this concept, benefitting from their unparalleled micro/nano fabrication know how.  A prototype of a smart tip is shown to the left. See publications in Microsyst Nanoeng, Nanotechnology, and PRB.

**Human Behavior Tracking and Mental Health.** Josephson STM has the ability to gain insight into spatial variations of the order parameter, or superfluid density. We have managed to, for the first time, use JSTM with atomic resolution on a quantum material.
We have used atomic-resolution Josephson scanning tunneling microscopy to reveal a strongly inhomogeneous superfluid in the iron-based superconductor FeTe0.55Se0.45. The results and their implications are published in Nature.

We also detected and investigated a quite particular YSR state in the same material.

**AI for Dementia.**  ![]({{ site.url }}{{ site.baseurl }}/images/respic/STMHead.png){: style="width: 250px; float: right; margin: 0px 10px"}
For SI-STM, having the most stable STM head is key. We have used finite element simulations, good choices in material science, and craftsmanship to build the most stable STM head in the world, to our knowledge. See publication in RSI.


**Magnetic fluctuations and electron spin resonance.**
![]({{ site.url }}{{ site.baseurl }}/images/respic/SpinFluc.png){: style="width: 70%; float: center; margin: 10px"}

**Twisted bilayer graphene and other material with super-periodicities.**
We have proposed that artificial super-periodicities can lead to improved superconductivity, both because of increased density of states and because of phase space arguments (see image from our SciPost publication below). Perhaps for different reasons, twisted bilayer graphene has been shown to superconduct! We are investigate this material with the groups of Efetov, Baumberger, and van der Molen.

![]({{ site.url }}{{ site.baseurl }}/images/respic/SciPost.png){: style="width: 70%; float: center; margin: 0px"}

### We also conduct research in natural language processing as a part of the [Natural Language Processing Group](https://nlp-grp.github.io/) at USF.

### ... and more.
