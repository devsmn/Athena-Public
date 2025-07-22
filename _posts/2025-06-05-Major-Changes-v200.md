---
layout: post
title: Major changes for v2.0.0
subtitle: Planned changes for the upcoming version v2.0.0
tags: [news]
author: Simon Pflaum
---

In the previous releases we focused on establishing and improving the core functionality.
With version v1.2.0, we were able to create a flexible and yet stable base for further development.

For the next version we are planning some major changes, focusing on even more productivity and reacting to feedback we have received.
Some of the highlights include:

### More safety by encrypting the data, not just restricting access to the app 🛡️ 
**Update 2025-07-04**: *This feature is implemented and will be released in v2.0.0.*

Most apps add a layer of security by restricting access to the app with biometric or other forms of validation.
While this is sufficient in some cases, this kind of security does not protect your data. 
If someone manages to get access to your phone, the intruder can easily access your local data - because even if the app is protected with a password, the data itself is not.
We take a different, more secure approach: We protect the data itself, not the app. Any access to the data requires biometric or other forms of validation beforehand.

### Improved scanning technology 📷 
**Update 2025-07-04**: *This feature is currently in progress.*

Currently, scanning a document requires manual cropping. In the future, this will be done automatically.
Additionally, the brightness, perspective and other parameters are adjusted to ensure a high quality document.

### Summaries 🗎 
Optionally, documents can be summarized to quickly get an overview of the content.

### Transforming handwritten notes 📝 
Handwritten notes can be transformed into proper documents.

### Translation of documents 🌐 
Documents can be translated into different languages.

### Create Flashcards/quizzes ❔ 
We received some feedback that students use the app to organize and prepare for exams.
To further support this, flashcards or quizzes can be generated for documents which can be used to test your knowledge.

### Financial tracking 💵 
Receipts and other financial documents can be tracked to keep an eye on your expenses. Relevant information is extracted automatically with our OCR and NER technology.

### Structured export 📁 
Documents can be exported with the full folder structure.
