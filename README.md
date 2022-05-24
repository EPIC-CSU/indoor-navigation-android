# Indoor navigation with machine learning models integrated into an Android app

Global Navigation Satellite Systems (GNSS) have transformed the way that people navigate, travel, automate, and gather information about the world around them. Indoor localization systems have the potential to similarly change how people function in locations where satellite-based localization systems are rendered ineffective. There is a need for systems that can bridge this gap and create continuity in localization regardless of location. However, indoor localization is a challenging problem, particularly in complex indoor spaces such as shopping malls, schools, high-rise buildings, hospitals, subways, tunnels, and mines. These variety of locales involve differing ambient environments, obstructions, architectures, and materials, which makes accurate localization difficult. There are also challenges associated with the movement of people, machinery, furniture, and equipment that cause variation and interference. There are many different approaches to localizing indoors, but unfortunately there is currently no definitive standard to meet all the needs and challenges for localization in every indoor environment. The ability to track people and equipment indoors has applications in many areas. Factory and warehouse automation through asset tracking and optimization analysis can serve to increase productivity by effectively scheduling resources and equipment. Hospitals can track patients, employees, and equipment to enhance navigation and allow for the automation of hospital information systems. Retail stores can use beacons to announce sales, customize displays to the shopper, collect shopping pattern data, and assist customers in finding products. Parking garages and underground parking structures could track fill capacity, direct vehicles to open spots, locate vehicles, and ultimately enhance autonomous vehicle routing. Tracking people can not only help to find family or friends in a crowd but could also be used by emergency responders in the case of a disaster.

This simple app provides a seamless way to continue the navigation aspects of people's lives into the indoor space. As GPS does not have the accuracy we desire in buildings, therefore we use fingerprinting and dead reckoning. Fingerprinting employs a machine learning model and uses Wi-Fi signals as inputs to determine the user's location. Dead reckoning detects steps to move the cursor between fingerprinting scans. 

![Android app](https://github.com/EPIC-CSU/indoor-navigation-android/blob/main/indoor-nav.jpg)

This app was the foundation for extensions in various works, including:

S. Tiku, S. Pasricha, “Siamese Neural Encoders for Long-Term Indoor Localization with Mobile Devices”,  IEEE/ACM Design, Automation and Test in Europe (DATE) Conference and Exhibition, Mar 2022.

L. Wang, S. Tiku, S. Pasricha, “CHISEL: Compression-Aware High-Accuracy Embedded Indoor Localization with Deep Learning”, IEEE Embedded System Letters, 2021. 

S. Tiku, P. Kale, S. Pasricha, “QuickLoc: Adaptive Deep-Learning for Fast Indoor Localization with Mobile Devices”, ACM Transactions on Cyber-Physical Systems (TCPS), 2021. 

S. Tiku, S. Pasricha, B. Notaros, Q. Han,“A Hidden Markov Model based Smartphone Heterogeneity Resilient Portable Indoor Localization Framework”, Journal of Systems Architecture, Vol 108, Sep 2020.

S. Tiku, S. Pasricha, “Overcoming Security Vulnerabilities in Deep Learning Based Indoor Localization on Mobile Devices”, ACM Transactions on Embedded Computing Systems (TECS), Vol. 18, Iss. 6, Jan 2020

S. Tiku, S. Pasricha, “PortLoc: A Portable Data-driven Indoor Localization Framework for Smartphones”, IEEE Design and Test, Vol. 36, Iss. 5, Oct 2019

S. Tiku, S. Pasricha, B. Notaros, Q. Han, “SHERPA: A Lightweight Smartphone Heterogeneity Resilient Portable Indoor Localization Framework“, IEEE International Conference on Embedded Software and Systems (ICESS), Las Vegas, NV, USA, Jun. 2019

A. Mittal, S. Tiku, S. Pasricha, “Adapting Convolutional Neural Networks for Indoor Localization with Smart Mobile Devices,” ACM Great Lakes Symposium on VLSI (GLSVLSI), May 2018. (Best Paper Award)

C. Langlois, S. Tiku, S. Pasricha, “Indoor localization with smartphones”, 6(4), IEEE Consumer Electronics, Oct 2017.

S. Tiku, S. Pasricha, “Energy-Efficient and Robust Middleware Prototyping for Smart Mobile Computing,” IEEE International Symposium on Rapid System Prototyping (RSP), Oct 2017.

S. Pasricha, J. Doppa, K. Chakrabarty, S. Tiku, D. Dauwe, S. Jin, P. Pande, “Data Analytics Enables Energy-Efficiency and Robustness: From Mobile to Manycores, Datacenters, and Networks”, ACM/IEEE International Conference on Hardware/Software Codesign and System Synthesis (CODES+ISSS), Oct 2017.

S. Pasricha, V. Ugave, Q. Han and C. Anderson, “LearnLoc: A Framework for Smart Indoor Localization with Embedded Mobile Devices,” ACM/IEEE International Conference on Hardware/Software Codesign and System Synthesis (CODES+ISSS), Oct 2015.
