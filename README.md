# 🤖 Hanwha_pickandplace_shape_sorter

Welcome to our project for the **LeRobot Worldwide Hackathon 2025**!

We're excited to share our work on creating a **real-world dataset** using the **Hanwha Robotics HCR-5** collaborative robot arm, focused specifically on **pick-and-place tasks** in a **shape sorter setup**.

## 📦 Dataset Overview

To build this dataset, we:

- Set up the system for **teleoperation, recording, and calibration**
- Collected **50 episodes** of high-quality **human demonstrations**

These demonstrations serve as the foundation for training imitation learning policies in real-world robotic manipulation tasks.

👉 **Download the dataset here**:  
🔗 [https://lnkd.in/eWfNtmh](https://lnkd.in/eWfNtmh)

## 🧠 Policies Trained

We trained two state-of-the-art policies using this dataset:

- **ACT (Action Chunking Transformer)**  
- **Smol VLA** from Hugging Face’s **LeRobot** library

### 📈 Results

- **Smol VLA** showed strong performance across our setup, with consistent and successful pick-and-place executions.
- **ACT** struggled particularly with the **grasping phase**, likely due to the complexity of object shapes and placement angles.


---

## 🔧 Tech Stack

- **Robot:** Hanwha Robotics HCR-5
- **Library:** Hugging Face [LeRobot](https://huggingface.co/lerobot)
- **Policies:** ACT, Smol VLA
- **Data Collection:** Teleoperated control with custom calibration pipeline

---

## 🧑‍💻 Team

Made with 💡 during the **LeRobot Worldwide Hackathon 2025** by [Vishnu,Siddharth,Edil,Anshul].

