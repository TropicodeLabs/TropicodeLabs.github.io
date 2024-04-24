---
layout: single
title: "Euphonia"
permalink: /euphonia/
---

Euphonia is a mobile application created to enable the annotation of spectrograms on mobile devices (iOS and Android). It aims to harness community involvement in conservation and sustainability efforts utilizing bioacoustics. The app allows users to download audio files, hear the sounds represented in the spectrogram by double-tapping, scroll through the spectrogram by sliding their fingertips horizontally, draw selection boxes over signals of interest, select appropriate labels for these signals, and send the annotated data to a centralized server for analysis by the scientific team. This design facilitates seamless collaboration between local experts, stakeholders, and the scientific team involved in passive acoustic monitoring projects.

<figure>
    <img src="/assets/images/Euphonia_Annotate_Screenshot.png" alt="Euphonia">
    <figcaption>Passive acoustic monitoring audioclip loaded in Euphonia, showing a hand-drawn selection over a portion of a call. An 'Unknown' label is added by default, which users may tap to select the species name (not shown). Tapping on the gray button labeled 'Unknown' allows changing the default label. The blue button in the upper right corner enables users to draw selection boxes by tapping and sliding over signals of interest in the spectrogram. The yellow icon in the top left corner provides access to a menu for changing settings, sending annotated data to the server, or logging out.</figcaption>
</figure>

### Current state of the project

Euphonia was an experiment to test the feasibility of developing a mobile app for bioacoustic annotation. The current implementation cannot be used in production as it is not maintained, and the server that stored the annotated data is no longer available. The app was developed using Unity3D, and the backend was implemented in Google Firebase. It was created by Álvaro Vega-Hidalgo (see the full list of acknowledgments below) in collaboration with developers and designers from Tropicode Labs, Cornell Lab of Ornithology, and the Nespresso AAA Sustainable Quality Program.

### Future work

**Euphonia App for Annotations**

We are planning to release a new version of the Euphonia app under an open-source license, inviting the global community to actively participate in its development. This upgrade will transition from Unity to Flutter, enhancing the app’s ability to operate seamlessly across multiple platforms. This change aims to preserve the existing functionalities while significantly boosting the app’s stability and performance.

**Euphonia AI Reviewer for Machine Learning Verifications:**

Developed by Álvaro Vega-Hidalgo, the Euphonia AI Reviewer app is an innovative tool that allows users to assess and refine annotations suggested by machine learning models. This functionality is crucial for ensuring the accuracy and reliability of data used in conservation efforts. The app is currently in the beta testing phase and will soon be available as an open-source project, further fostering collaboration and transparency in the development process.

### Acknowledgements

- Álvaro Vega-Hidalgo: Lead app design and development.
- Tropicode Labs Team:
  - Luis Lara, Mariela Vega, Dayanna Pérez, Enrico Barbieri, David Vega, Germán Ureña, Nikol Vega, Natalia Barquero, Victor Yeom: App design and development.
- Cornell Lab of Ornithology:
  - Dr. Viviana Ruiz, Dr. Laurel Symes, MSc. Ingrid Molina: Academic collaboration.
- Universidad de Costa Rica:
  - Dr. Luis Sandoval: Academic collaboration.
- Nespresso AAA Sustainable Quality Program: Financial support.