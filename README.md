# Yak-Recognition-and-Tracking-in-High-Altitudes-of-Arunachal-Pradesh(CV)

Official repository for the paper: **"Yak-Recognition-and-Tracking-in-High-Altitudes-of-Arunachal-Pradesh(CV)"**.

[**Project Page**](https://bmiu-labs.github.io/Yak-Recognition-and-Tracking-in-High-Altitudes-of-Arunachal-Pradesh--CV-/) | [**Dataset (Google Drive)**](https://drive.google.com/drive/folders/1HJnFmLmLPgELafp5ZUwZfM0NJf6Yf9M1?usp=sharing)

---

## Publication Status & Code Availability

*   **Paper Preprint**: Will be uploaded soon, upon confirmation of publication.
*   **Source Code**: Will be uploaded soon, upon confirmation of publication.

---

## Abstract

Automating the monitoring of individual yaks in remote, high-altitude shelters is critical for precision livestock farming, yet traditional physical tagging and manual headcounts are highly challenging to implement. In this work, we present **YakFlow**, an end-to-end computer vision framework that automates shelter occupancy tracking by detecting, tracking, and recognizing individual yaks from CCTV footage. 

The proposed pipeline integrates a domain-adapted YOLO11n object detector, a ByteTrack multi-object tracker to maintain frame-to-frame identity, and a ResNet50 re-identification embedding network to resolve long-term appearance matching. Using a custom dataset of 7,169 images annotated at the ICAR-National Research Centre on Yak (Dirang, Arunachal Pradesh, India), the fine-tuned YOLO11n detector achieves an exceptional precision of 0.9995, a recall of 0.9987, and an mAP@0.5:0.95 of 0.987 across 10 individual yak classes. To track shelter events, a coordinate-defined virtual gate registers entry and exit crossings with a five-second suppression window. The framework automatically outputs annotated tracking streams and structured Excel logs, providing farm managers with a robust, non-invasive solution for retrospective herd analysis in extreme high-altitude environments.

---

## Dataset

The dataset used in this work contains 7,169 annotated images of yaks across 10 distinct classes. It is hosted on Google Drive and can be accessed here:
👉 [Google Drive Dataset Link](https://drive.google.com/drive/folders/1HJnFmLmLPgELafp5ZUwZfM0NJf6Yf9M1?usp=sharing)

---

## Authors

*   **Prasenjit Kherkatary** - Department of Computer Science, Assam Don Bosco University, Guwahati, Assam, India
*   **Sningrik D Sangma** - Department of Computer Science, Assam Don Bosco University, Guwahati, Assam, India
*   **Laiphrakpam Indrason Meitei** - Department of Computer Science, Assam Don Bosco University, Guwahati, Assam, India
*   **Rupesh Mandal** - Animal Physiology, ICAR-National Research Centre on Yak, Dirang, Arunachal Pradesh, India
