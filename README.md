# Motion Intent & LLM Orientation Body-Relative Guidance Understanding Paper Code
Research Work Application for Body-Relative Guidance LLM Paper.

Note for reviewers of our repository: Any comments within the code pointing to names, repositories, or URLs are simply acknolwedgements for library usages and are <b><u>*NOT*</u></b> affiliated to the authors or this research. Everything created by the authors is anoymous otherwise.


Here is the repo guide.


Repo Guide
---

* APMotionCollection: The initial test app for AirPod motion and head pose detection (left and right only; up and down is in the Playgrounds app). 
* Wayfinding - MI: The app that lets you build the world-to-graph abstraction model.
* App Screenshots: Demonstration screenshots of the proof-of-concept app in-deployment from the enrollment process to the guidance.
* <b>*Graph Data Reports: The reports created from examining the LLM responses for each question, for each room, in addition to the stats. Look under the folder for more info.*</b>
* Sample: A sample output from one of the LLMs for some of the questions in our experiments.
* TinyVit.mlpackage/TinyVit.mlmodelc: The ML model used (TinyViT) for cosine similarity-based room ID (in zip file form).
* automation.py: Our Python-based simulator using a real world-to-graph from the application to scale our experiments.
* timm_coreml.py: The code to convert TinyViT from timm into an embedding model for CoreML.

---


This application is our tool and a proof-of-concept for interacting with LLMs using wearable devices and abstracting the world into graph-based representations for easy interactions with LLMs.
