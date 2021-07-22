# SaMD
Evolving Regulatory Framework for Software as a Medical Device based on Machine Learning

**1 SaMD Overview**

Software is one of the most important components of the healthcare industry. Before we dig into more details, we must distinguish mainly between the two types of software: 
1. Software used for medical purposes, such as
- Clinical decision making (e.g. detection of anomalies in Lung CT scans)
2. Software used for non-medical purposes, such as
- Calculator/data processing modules that maintain and retrieve laboratory data
- Continuous glucose monitor secondary displays
- Medical device data systems, 
- Home uterine monitors
- Medical image storage devices, 
- Medical image communication devices 
- Any administrative service (e.g. hospital billing services) 
- Software used to make or maintain a device (e.g. testing, source code management, servicing, etc.)

Software used for medical purposes could further be divided into two categories:
**Category 1:**
- Software in a medical device (often referred to as “embedded” or “part of”); In general, software in a medical device is part of hardware medical devices.
-- e.g.: Software which drives or controls the motors or pumps any kind of medication in an infusion pump; or software that is used in closed loop control in an implantable medical device such as pacemaker

**Category 2:**
- Software as a medical device (SaMD). In general, SaMD is a standalone software which performs its intended use on its own.
-- e.g.: Software which allows a doctor to view images obtained from a CT scanner for diagnostic purposes by performing image post-processing to help detect lung anomalies and disease patterns such as emphysema, nodular pattern, etc.

In this brief article, we will only concentrate on SaMD. 
**Different Definitions for SaMD**
For instance, according to the definition of IMDRF (International Medical Device Regulators Forum): 
- “SaMD is software intended to be used for one or more medical purposes that perform these purposes without being part of a hardware medical device.”

While MDCG (Medical Device Coordination Group) defines SaMD as the following:
- “Medical device software is software that is intended to be used, alone or in combination, for a purpose as specified in the definition of a “medical device” in the medical devices regulation or in vitro diagnostic medical devices regulation.”

In general, software is SaMD if it provides the means to help mitigate a disease, if it provides support for detection, diagnosis, monitoring or treatment of physiological conditions, or if it helps in determining predisposition, prognosis, prediction or physiological status.

Furthermore, IMDRF provides an important mechanism (see table below) for categorizing a SaMD on the basis of its intended use and the state of the healthcare situation or condition.


| State of healthcare situation or condition | Significance of information provided by SaMD to a healthcare decision |
|                                            | Treat or diagnose | Drive Clinical management | Inform clinical management |
|Critical                                    | IV                | III                       | II                         |




