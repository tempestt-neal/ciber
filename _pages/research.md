---
title: "CIBeR Lab @ USF - Research"
layout: textlay
excerpt: "CIBeR Lab @ USF -- Research"
sitemap: false
permalink: /research/
---

# Research

Our research is largely inspired by the ubiquitous nature of today's technologies, and how smart sensing enabled by these technologies can be used to understand how people interact with the technology itself, interact with each other, and behave in different environments. To do so, we generally rely on applied artificial intelligence, statistics, and human-centered computing techniques to answer research questions which focus on
- **usable and inclusive cybersecurity systems for personally-owned computing devices, particularly related to identity and access management**
- **interdisciplinary applications of human behavior analysis through smart sensing**

## Here are some themes and techniques that we currently work on:

<details>
  <summary>Click me</summary>
  
  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Javascript
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>

### Mobile Biometrics
Commercial mobile devices currently employ point-of-entry (PoE) authentication methods such as face recognition and personal identification numbers. Several studies show that knowledge-based authenticators are ineffective due to increased memory load, poorly chosen alphanumeric combinations, and repetitive use of passcodes across many applications. PoE and knowledge-based authenticators are both ineffective throughout sessions of use; once the user is authenticated, the device and its content remain available to the current user. In this research, we explored various data based on usage of a mobile device as behavioral biometric modalities, including patterns in application use, networking activity (i.e., Bluetooth and Wi-Fi sightings), and communication through calling and text messaging, which can continuously and passively authenticate a device’s owner. 

*Significant findings and methods developed throughout this research include:*
*	We demonstrated the use of association rules as a feature representation for application, Bluetooth, and Wi-Fi data which outperformed previously employed frequency-based features. Our findings suggest that patterns in application and Bluetooth traffic are more distinct than those in Wi-Fi patterns with up to 91% accuracy. Performance obtained in this study were consistent with implementations of keystroke dynamics and touch gestures for biometric authentication, a significant indication that passive modalities are as viable as their physical counterparts.
*	We provided empirically-supported evidence of gender-based usage patterns, including higher activity levels of female compared to male users in application use and the differentiation between the two groups based on transitions between sports, navigation, and system-related apps and number of revisitations to apps within sessions.
*	We developed temporally-derived replay attack simulations to assess system performance under threatening conditions in which the legitimate user is easily observed or their usage data is remotely accessed. The intercepted data is then intelligently combined with some level of noise to avoid the replay of an exact copy of legitimate data by an attacker. The attacker’s data thus maintains a level of similarity with the legitimate data. Our experiments show that our attack models can lead to false positive rates ranging from 30 to 50%, while in some cases, zero-effort attacks lead to much lower, and thus misleading, error rates.
*	We introduced an easily interpretable profiling technique as a feature representation for user-device interaction data that contextualizes mobile device usage patterns. Our experiments show that these profiles allow better separation of legitimate and impostor behavior. Error rates associated with behavior profiles either improved or were not affected by the amount of data provided for authentication, while those associated with frequency-based features, which are seen in several research studies, worsened. 
*	We developed a novel ranking function which quantifies the informativeness of a soft biometric class for search space reduction. The function relies on the rank-1 recognition accuracy for the class, a score quantifying the permanence of the class, and a cost derived from the ratio of misclassifications to the number of subjects in the soft biometric class.
 
**This project has resulted in the following publications:**
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

<hr />

### Age-Aware User Authentication
Current software for user authentication relies on the user to directly initiate some interaction (i.e., active authentication). However, active authentication systems are not accessible to individuals across all age groups. Continuous authentication schemes transparently observe a user's natural multimodal behaviors to leverage all possible signals as input for authentication, and hence do not require explicit authentication interactions to be initiated by the user, and are thus a promising framework for authentication by individuals of different age groups. This project's novelties are 1) to advance understanding of how individuals of different age groups use and perceive existing authentication methods, especially concerning users' mental models and acceptance of monitoring for the purposes of continuous authentication, and 2) to collect and analyze a variety of user signals in multiple behavioral and physiological modalities for age-aware continuous authentication on personal computing devices. This research also informs the design of continuous authentication interactions in other contexts such as public spaces and other smart environments, in which continuous authentication might be useful. The research includes three phases. (1) Elicit the mental models multi-generational users have of what it means to authenticate to a system, if and when they expect the system to re-authenticate them to confirm their identity as they continue to interact, and if and how they expect to receive feedback of authentication attempts. (2) Produce a novel dataset of behavioral and physiological data, such as touch gestures, keystroke dynamics, heart-rate variability, and skin temperature, through a series of data collection sessions wherein individuals of different age groups will be recruited to complete a diverse set of tasks. (3) Develop fundamental knowledge of age-aware continuous authentication through the analysis of these data using state-of-the-art machine and deep learning techniques. 

This project is a collaboration between the CIBeR Lab, the [Affective Vision Lab](https://scanavan.github.io/), the [Intelligent Natural Interaction Technology Lab](http://init.cise.ufl.edu/), and the [Ruiz Human-Computer Interaction Lab](https://ruizlab.org/).

#### [Here's a research talk](https://cse.usf.edu/~tjneal/media/PNNL%20-%20Nov%202021.mp4) that Dr. Neal gave at the [Pacific Northwest National Laboratory](https://www.pnnl.gov/) focused on this project.

> **We are currently collecting data for this project! [We need your help!](https://tempestt-neal.github.io/ciber/participate/)**

**This project has resulted in the following publications:**
1. Tempestt Neal, Lisa Anthony, Shaun Canavan, Jaime Ruiz, Saandeep Aathreya, Meghna Chaudhary, Yu-Peng Chen, Heting Wang, Rodrigo Calvo, Liza Jivnani and Nicolas Ng Wai. "[Toward Understanding Children's Use and Understanding of User Authentication Systems: Work-in-Progress.](https://cuts.soic.indiana.edu/KOPSpapers/KOPS_2022_paper_8074.pdf)" USENIX Symposium on Usable Privacy and Security (SOUPS) 2022. SOUPS 2022: Workshop on Kids' Online Privacy and Safety.

*The material produced in this project is based upon work supported by the National Science Foundation under Grant No. 2039373 and 2039379. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation. This study has been approved by the USF IRB board #STUDY002291.*
<hr />

### Human Behavior Tracking and Mental Health

This project focuses on the Up To Me program, a three lesson, disclosure-based stigma reduction program meant to reduce barriers to community living and participation for college students with psychiatric disabilities. Anticipated outcomes of this project for college students include improvements in 1) self-stigma (self-esteem and self-efficacy), 2) empowerment and self-determination, 3) appraisals of stigma as a stressor, 4) student engagement on campus, 5) sense of campus belonging, and 6) care seeking/service engagement for mental illness. The CIBeR Lab's contributions lies in the investigation of the use of sensor data collected from a smartphone as a proxy of behavior to substantiate self-report data on outcomes. 

This project is a collaboration between the [Stigma Action Research Lab](https://www.usf.edu/cbcs/mhlp/centers/star-lab/) and the CIBeR Lab.

**This project has resulted in the following publications:**
1. King S, Lebert J, Karpisek L, Phillips A, Neal T, Kosyluk K. "Characterizing User Experiences With an SMS Text Messaging–Based mHealth Intervention: Mixed Methods Study" JMIR Form Res 2022;6(5):e35699 URL: https://formative.jmir.org/2022/5/e35699 DOI: 10.2196/35699

*This award (90IFRE0056) is supported by the Administration for Community Living (ACL), U.S. Department of Health and Human Services (HHS) as part of a financial assistance award totaling $600,000 with 100 percent funding by ACL/HHS. The contents are those of the author(s) and do not necessarily represent the official views of, nor an endorsement, by ACL/HHS, or the U.S. Government.*

<hr />

### Transportation Behavior Analysis via Smart Sensing

Multimodal transportation, such as transit, bike, walk, ride-hailing (e.g., Uber, Lyft), car-share, and bike-share, are vital to supporting livable communities. However, activity data of travelers using these modes have been difficult to acquire. This research leverages ground truth data to develop intelligent models to infer missing and incomplete travel behavior characteristics from the OneBusAway data to provide trip origin, destination, and mode. The research team will deploy these models to provide an enhanced picture of the travel behavior of OneBusAway users in Mayaguez, Puerto Rico. The team will use the database generated by the intelligent model and additional transportation system information to conduct demand analysis and identify demand patterns and their impact on traffic congestion. The resulting model and tools will be immediately applicable to all nine cities that have deployed OneBusAway to better understand the relationship between multimodal travel behavior and traffic congestion. Using crowdsourcing, big data science, and machine learning, these tools will help transportation agencies deploy new, automated strategies to improve congested multimodal systems in the immediate future.

This project is a collaboration between the [Center for Urban Transportation at USF](https://www.cutr.usf.edu/), the [University of Puerto Rico at Mayaguez](https://www.uprm.edu/portada/), and the CIBeR Lab.

*This project, [3-7: Transforming multimodal travel behavior data from an open-source platform to support traffic congestion reduction strategies](https://nicr.usf.edu/2022/05/18/3-7_transforming_multimodal_travel_behavior/), is supported by the National Institute for Congestion Research.*

<hr />

### We also conduct research in natural language processing as a part of the [Natural Language Processing Group](https://nlp-grp.github.io/) at USF.
