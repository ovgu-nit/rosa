---
title: "RoSA: Concept for an Intuitive Multi-Modal and Multi-Device Interaction System"
description: Conceptual framework for RoSA — a multi-modal, multi-device human–robot interaction assistant with speech, gesture, and facial recognition.
background: /assets/theme/images/rosa_header.png
image: /assets/theme/images/concept.png
author: "Dominykas Strazdas, Jan Hintz, Aly Khalifa, Ayoub Al-Hamadi"
categories: [Publication, Conference, RoSA]
conference: "**IEEE International Conference on Human-Machine Systems (ICHMS), 2021**"
tags: [Conference, IEEE, RoSA, HRI, Multimodal, Telerobotics]
---

## Toward Natural Multimodal Human–Robot Interaction with RoSA

This paper introduces the **Robot System Assistant (RoSA)**, a concept for a flexible, intuitive human–robot interaction framework combining **speech, gesture, facial recognition, and attention monitoring**.  

Building on a previous Wizard-of-Oz study with 36 participants, RoSA aims to transfer the most frequently used modalities (97% speech, 75% pointing gestures) into a real, contactless, multimodal system.  

**Key elements of the RoSA concept:**

- **Speech recognition** with offline-capable models (Mozilla DeepSpeech)  
- **Gesture recognition**, including pointing gestures with projected visual feedback (a “virtual laser pointer”)  
- **Facial recognition** to identify users, manage access levels (guest, operator, admin), and track attention  
- **Attention-based session control**, automatically engaging or logging off users based on face recognition and head pose  
- **Multi-device setup** based on ROS, supporting:  
  - WS1: UR5e cobot with gripper, cubes, projector  
  - WS2: smart touchscreen workstation  
  - WS3: mobile robot with cameras  
- A contactless concept to enable switching between workstations without logging in/out

## Planned Evaluation

Experimental studies will include tasks like:  

- requesting a block from the robot  
- spelling a word with colored cubes  
- building a layered block pyramid  

Participants will be assessed with standardized user experience questionnaires (SUS, UMUX, PSSUQ, ASQ), comparing results to the previous Wizard-of-Oz study.  

The goal is a **natural, robust, multi-user, multi-device HRI platform** for industrial and social settings.

![](/rosa/assets/theme/images/concept.png)

---

## Best Presentation Award

This paper won the ICHMS 2021 Best Presentation Award

## Fulltext Access  
[https://doi.org/10.1109/ICHMS53169.2021.9582663](https://doi.org/10.1109/ICHMS53169.2021.9582663)

---

## Citing

```bibtex
@inproceedings{RoSA_Concept2021,
  author={Strazdas, Dominykas and Hintz, Jan and Khalifa, Aly and Al-Hamadi, Ayoub},
  title={Robot System Assistant (RoSA): Concept for an Intuitive Multi-Modal and Multi-Device Interaction System},
  booktitle={2021 IEEE International Conference on Human-Machine Systems (ICHMS)},
  year={2021},
  doi={10.1109/ICHMS53169.2021.9582663}
}
```