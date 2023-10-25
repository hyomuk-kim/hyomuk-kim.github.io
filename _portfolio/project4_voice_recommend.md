---
title: "Voice Command Recommendation"
sideinfo: "<i>Jan. 2020 ~ Aug. 2020 @ Global AI Center</i>"
excerpt: "<b>To assist users in learning how to use the AI assistant effectively.</b>"
collection: portfolio
---
<!-- <br/><img src='/images/500x300.png'> -->

> **Info.**  
  _Jan. 2020 ~ Aug. 2020 at Global AI Center with 4 members._

### Enhancing Ambient AI User Experience with Adaptive Interfaces

## Goal

The objective of this research project was to enhance the usability of devices within an ambient AI environment. The challenge we sought to address was the difficulty users encounter when attempting to seamlessly adapt to multiple AI interfaces in these environments. Rather than mandating that users learn each AI interface independently, our goal was to develop adaptive interfaces that enable users to naturally assimilate interface interactions while using the device. We planed to achieve this by interpreting user intentions within the context of interactions and providing relevant voice command recommendations. Our aim was to promote the proactive use of AI agents when engaging with specific functions or applications.

## Need

As ambient AI becomes increasingly integrated into our daily lives through smart devices, creating user-friendly and adaptable interfaces is crucial. Existing AI interfaces often require users to learn complex voice commands or memorize specific interactions. This hampers user engagement and can lead to frustration. To make ambient AI more accessible and intuitive, we needed to develop interfaces that adapt to users' needs without the requirement for extensive learning or memorization.

## Approach

Our approach encompasses several key steps:

**1. Goal and Utterance Extractor** (Capsule Learning)  
  Extracts goals(interactions) and utterances list based on pretrained speech data in capsules.

**2. Tag Extractor**  
  Removes unnecessary tags to get useful tags by filtering them based on collected logs for all interactions

**3. Dictionary Generator**  
  Builds a dictionary of embedding vectors for each goal, which will be used for calculating tag messages' impact factor (TF-IDF Score).

**4. End Point Detector**  
  Extracts logs that correspond to the endpoint of goals(interactions) after tag-based filtering

**5. Real-Time Operation**
   - Log Filtering: Tag-based filtering is applied to user input in real time. Logs that match the user's actions are extracted and saved in a queue. The endpoint of actions is detected during this process.
   - Embedding Generator: Impact factor values are calculated for the logs based on the embedding dictionary. This results in an embedding vector.
   - Embedding Score: The similarity between the generated embedding and the embedding of each goal stored in the database is measured.
   - Utterance Generator: The utterance with the highest similarity to the user's action is recommended.

## Insights

This research project introduced a novel approach to ambient AI user interfaces. By leveraging real-time data and adaptive interfaces, we aimed to enhance the user experience, allowing users to intuitively interact with AI agents without the need for extensive training or memorization. Our research provided valuable insights into improving the usability of AI-driven devices in ambient environments, ultimately making technology more accessible and user-friendly.

***

> Even though I moved to the AI Center to work on developing a multimodal interaction framework for "robots" and AR/VR, the project was assigned to another overseas research institute, and I had to participate in a different project. (Well, you know, life doesn't always go as planned.) My research direction was then redirected toward next-generation interactions, so while preparing a research proposal for Brain-Machine Interface studies, I also became involved in this voice command proposal project.
