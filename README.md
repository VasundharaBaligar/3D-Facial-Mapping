# 🎭 Metaverse Avatar Emotion Mapper

A real-time facial retargeting system that captures human facial expressions via webcam and maps them instantly to a 3D avatar in Blender. Designed to enhance immersion for Metaverse applications, online interactions, and VR gaming.

*(The architecture utilizes a webcam feed to extract 68 facial landmarks and retargets them to a rigged 3D model)*

## 🚀 Features

* **Real-Time Retargeting:** Low-latency mapping of user expressions to digital avatars using OpenCV and Blender's modal operators.
* **68-Point Landmark Detection:** High-fidelity tracking of eyes, mouth, jaw, and eyebrows utilizing the Dlib shape predictor.
* **Dynamic Expression Support:** Capable of rendering complex states like "Mouth Wide Open," "Eyes Closed," and "Head Tilt" by manipulating specific bone controls (e.g., `mouth_ctrl`, `head_fk`).
* **Blender Integration:** Seamless pipeline using rigged 3D models for high-quality rendering directly within the Blender Viewport.

## 🛠️ Tech Stack

* **Core:** Python, OpenCV (`cv2`)
* **3D Engine:** Blender API (`bpy`)
* **Computer Vision:** Dlib / MediaPipe (68 Facial Landmarks)
* **Hardware:** Standard Webcam (approx. 60cm distance recommended)
