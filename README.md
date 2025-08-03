# 🟠 Solid Game – HTC Vive + Encrypted Telemetry Demo

**Solid Game** is a Unity-based VR demo created as part of my Master's thesis defense. It showcases a simple yet powerful simulation where users interact with three spheres in virtual space using an HTC Vive controller. The project highlights secure telemetry capture and real-time encrypted analytics.

---

## 🎮 What This Project Does

- Enables interaction with three spheres using the **hand controller**
- Captures motion and interaction telemetry in real time
- Demonstrates **original vs encrypted** telemetry results at the end of the session
- Showcases how homomorphic encryption can be used to preserve user privacy in VR

---

## 🛠️ Technologies Used

- **Unity 2022.3.5f1**
- **C#**
- **HTC Vive + SteamVR SDK**
- **Custom telemetry logger**
- **Homomorphic Encryption for secure analytics**

---

## 🧪 How to Run the Project

### 1. Prerequisites

- Unity Hub + Unity 2022.3.5f1
- HTC Vive setup (with SteamVR running)
- SteamVR Unity Plugin installed


### 2. Clone and Open

```bash
git clone https://github.com/YOUR-USERNAME/solid-game.git
cd solid-game
```

- Open the project in Unity Hub
- Load the main scene (usually under `Assets/Scenes/Main.unity`)
- Connect your HTC Vive headset
- Press **Play** in the Unity Editor

---

## 📊 Telemetry Demo Details

- Tracks right-hand controller movement
- Computes and logs motion data throughout interaction
- At the end, visualizes:
  - **Raw (unencrypted) telemetry**
  - **Encrypted analytics output** (demo only, for thesis proof)

---

## 📸 Screenshots / Demo

Here is the game demo:

https://github.com/user-attachments/assets/fab89402-7b32-4801-924c-ba73d0facbd7

---

## 👩‍💻 Author

Created by [Jayasri](https://github.com/jayasrisng)  
Part of a Master's thesis in privacy-preserving VR analytics

🎓 Full thesis demo: [https://youtu.be/FNfVxRWXWUY](https://youtu.be/FNfVxRWXWUY)

If you use this work in academic or applied settings, please cite:
Guthula, J. S. N. (2025). Secure frameworks for user motion data in virtual reality (Order No. 32038728). Available from Dissertations & Theses @ University of Arkansas at Little Rock; ProQuest Central. (3233907256).
[Access via ProQuest](https://go.openathens.net/redirector/ualr.edu?url=https://www.proquest.com/dissertations-theses/secure-frameworks-user-motion-data-virtual/docview/3233907256/se-2)

---

## 📄 License

MIT License — use, remix, or build upon it with credit.

---

## ⭐ Contribute
Feel free to fork this project or reference it in your own XR and privacy-related work.
Feedback and thoughtful contributions are always welcome.
