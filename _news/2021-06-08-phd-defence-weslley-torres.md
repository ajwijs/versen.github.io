---
layout: news
picture: "default.png"
title: "Ph.D. defence of Weslley Torres - Supporting Multi-Domain Model Management"
---

On September 21, 2021 [Weslley Torres](https://research.tue.nl/en/persons/weslley-torres), M.Sc. from Eindhoven University of Technology will defend his PhD thesis entitled *"Supporting Multi-Domain Model Management"*. Weslley has been supervised by prof. Alexander Serebrenik and prof. Mark van den Brand.

Model-driven engineering has been used in different domains such as software engineering, robotics, and automotive. This approach has models as the primary artifacts, and it is expected to improve quality of system specification and design, as well as the communication among the development team.

Managing models that belong to the same domain might not be a complex task because of the features provided by the available development tools. However, managing interrelated models of different domains is challenging. A robot is an example of such a multi-domain system. To develop it one might need to combine models created by experts from mechanics, electronics and software domains. These models might be created using domain specific tools of each domain, and a change in one model of one domain might impact a model from a different domain causing inconsistency in the entire system.

This thesis therefore aims to facilitate the evolution of the models in this multi-domain setting. It starts with a systematic literature review in order to identify the open issues, and strategies used to manage models from different domains. We identified that making explicit the relationship between models from different domains can support the models maintenance, making it easy to recognize affected models because of a change. The following step was to investigate ways of extracting information from different engineering models that were created using different modeling notations. For this goal, we required a uniform approach that would be independent from the peculiarities of the notations. This uniform approach can only be based on elements typically present in various modeling notations, i.e., text, boxes, and lines. Thus, we investigated the suitability of optical character recognition (OCR) for extracting textual elements from models from different domains. We also identified the common errors made by the off-the-shelf OCR services, and we proposed two approaches to correct one of these errors. After that, we used name matching techniques on the textual elements extracted by OCR to identify relationships between models from different domains. 

To conclude, we created an infrastructure that combines all the previous elements into one single tool that can also store the relationships in a structured manner making it easier to maintain the consistency of an entire system. We evaluated it by means of an observational study with a multidisciplinary team that builds autonomous robots designed to play football.


