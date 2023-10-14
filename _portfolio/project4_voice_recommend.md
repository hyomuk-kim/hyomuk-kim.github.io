---
title: "Voice Command Recommendation"
excerpt: " <b>To assist users in learning how to use the AI assistant effectively.</b>"
collection: portfolio
---
<!-- <br/><img src='/images/500x300.png'> -->

> Info.  
  _Jan. 2020 ~ Aug. 2020 at Global AI Center with 4 members._

**Enhancing Ambient AI User Experience with Adaptive Interfaces**

### Goal

The objective of this research project is to enhance the usability of devices within an ambient AI environment. The challenge we seek to address is the difficulty users encounter when attempting to seamlessly adapt to multiple AI interfaces in these environments. Rather than mandating that users learn each AI interface independently, our goal is to develop adaptive interfaces that enable users to naturally assimilate interface interactions while using the device. We plan to achieve this by interpreting user intentions within the context of interactions and providing relevant voice command recommendations. Our aim is to promote the proactive use of AI agents when engaging with specific functions or applications.

### Need

As ambient AI becomes increasingly integrated into our daily lives through smart devices, creating user-friendly and adaptable interfaces is crucial. Existing AI interfaces often require users to learn complex voice commands or memorize specific interactions. This hampers user engagement and can lead to frustration. To make ambient AI more accessible and intuitive, we need to develop interfaces that adapt to users' needs without the requirement for extensive learning or memorization.

### Approach

Our approach encompasses several key steps:

1. Goal and Utterance Extractor (Capsule Learning)
  Extracts goal(interaction) and utterance lists based on trained speech data in capsules.

2. Tag Extractor
  Removes unnecessary tags by filtering them based on collected logs for all interactions

3. Dictionary Generator
  Builds a dictionary for each goal based on the embedding vector of tag messages' impact factor (TF-IDF Score).

4. End Point Detector
  Extracts logs that correspond to the endpoint of actions for each goal after tag-based filtering

5. Real-Time Operation
   - Log Filtering: Tag-based filtering is applied to user input in real time. Logs that match the user's actions are extracted and saved in a queue. The endpoint of actions is detected during this process.
   - Embedding Generator: Impact factor values are calculated for the logs based on the embedding dictionary. This results in an embedding vector.
   - Embedding Score: The similarity between the generated embedding and the embedding of each goal stored in the database is measured.
   - Utterance Generator: The utterance with the highest similarity to the user's action is recommended.

### Insights

This research project introduces a novel approach to ambient AI user interfaces. By leveraging real-time data and adaptive interfaces, we aim to enhance the user experience, allowing users to intuitively interact with AI agents without the need for extensive training or memorization. Our research provides valuable insights into improving the usability of AI-driven devices in ambient environments, ultimately making technology more accessible and user-friendly.


> Even though I moved to the AI Center to work on developing a multimodal interaction framework for "robots" and AR/VR, the project was assigned to another overseas research institute, and I had to participate in a different project. (Well, you know, life doesn't always go as planned.) My research direction was then redirected toward next-generation interactions, so while preparing a research proposal for Brain-Machine Interface studies, I also became involved in this voice command proposal project.
