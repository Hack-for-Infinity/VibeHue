# 👋 Welcome to Hack for Infinity – Infinity 2K26!

Hey team! 🎉 Welcome to your dedicated repository for the **Infinity 2K26 Hackathon** organized by the **IEEE Computer Society OUCE Student Chapter**.

This is your team's space to build, commit, and submit your project. Organizers have access to this repo and will review your **commit history** to verify the project was built during hackathon hours — so make sure you're committing regularly throughout the day!

> ⏰ **The repository will be locked at 5:30 PM. No pushes will be accepted after that.**

---

## 📅 Quick Schedule

| Time               | Activity                             |
| ------------------ | ------------------------------------ |
| 8:30 – 9:00 AM     | Reporting & registration             |
| 9:00 – 10:00 AM    | Opening briefing & kickoff           |
| 10:00 AM – 1:00 PM | Development session                  |
| 1:00 – 2:00 PM     | Lunch break & **Round 1 evaluation** |
| 2:00 – 5:30 PM     | Development session & final prep     |
| 5:30 – 6:00 PM     | **Final judging & presentations**    |

---

## ✅ Things to Remember

* Commit your code **frequently** throughout the day
* AI tools (ChatGPT, Copilot, etc.) are allowed — but be ready to **explain your code** to the judges
* Pre-built or plagiarised projects will be **disqualified**
* Bring your laptops, chargers, and any hardware you need
* Include a **project document** in this repo (see required sections below)

---

## 📋 Judging Criteria

Projects will be evaluated on:

* 💡 Innovation and originality
* 🛠️ Technical implementation
* 🌍 Practical impact and usefulness
* 🎨 User experience and design
* 🗣️ Clarity of presentation and explanation

---

# 📁 Project Details

## 🏷️ Problem Statement – PS 02: Accessible Entertainment

Music and live performances are largely designed around audio experiences. However, for the **Deaf and Hard-of-Hearing community**, the emotional energy, rhythm, and atmosphere of music often remain inaccessible.

The excitement of a concert, the intensity of bass drops, and the overall mood of music are usually perceived through sound. Without an alternative sensory bridge, individuals who cannot hear the audio miss out on a major part of this shared entertainment experience.

Our project aims to address this challenge by translating sound into **visual and tactile feedback**, enabling users to feel the rhythm and mood of music through vibrations and dynamic visual cues.

---

# 🎵 Haptix

**Haptix** is an accessibility-focused web application that converts music into **real-time visual and haptic feedback**.

Instead of hearing music, users can **feel the rhythm through device vibrations and see the energy through dynamic colour changes** on the screen. By mapping audio frequencies and intensity into tactile and visual responses, Haptix creates an alternative way to experience music.

The goal of Haptix is to make concerts, live performances, and music more **inclusive and engaging** for Deaf and Hard-of-Hearing individuals.

---

## 👥 Team Members

| Name                  | GitHub Username |
| --------------------- | --------------- |
| Mansoor Khan          | Mansoor Khan    |
| Abdul Faatih Siddiqui | Abfa41          |
| Ramu Ellaboina        | RamEllaboina    |

---

## ❓ Problem Statement

Live entertainment such as concerts and festivals relies heavily on audio. While hearing audiences experience music through sound, Deaf and Hard-of-Hearing individuals often cannot access the emotional energy and rhythm of the performance.

This creates a barrier that prevents many people from fully participating in one of the most widely shared cultural experiences.

**Haptix** solves this by translating sound into **visual colours and rhythmic vibrations**, allowing users to perceive music through touch and sight rather than hearing.

---

## 🏗️ System Architecture / Design

*Describe or diagram how your system is structured. What are the main components and how do they interact?*

---

## 🛠️ Technologies Used

* **JavaScript**
* **Web Audio API** – real-time audio analysis
* **Vibration API** – generating rhythmic phone vibrations
* **HTML5** – application structure
* **CSS Animations / Transitions** – smooth dynamic visual effects

---

## ⭐ Key Features

* 🎵 **Real-Time Audio Analysis**
  Captures and processes audio input to detect sound intensity and frequency patterns.

* 📳 **Haptic Feedback (Vibration)**
  Bass frequencies trigger device vibrations, allowing users to physically feel the rhythm of the music.

* 🎨 **Dynamic Visual Feedback**
  Screen colours change based on audio intensity and mood (e.g., calm → blue, energetic → red/pink).

* 🌍 **Accessibility Focused**
  Designed to make music experiences more inclusive for Deaf and Hard-of-Hearing users.

* ⚡ **Lightweight Web Application**
  Runs directly in the browser without requiring special hardware or installations.

---

## ⚙️ How It Works

1. The application captures audio input through the device microphone.
2. The **Web Audio API** analyzes the sound in real time to extract frequency and amplitude data.
3. The system processes this audio data to determine sound intensity and bass levels.
4. Based on the detected values:

   * **Bass frequencies trigger device vibrations** using the Vibration API.
   * **Audio intensity and mood control the screen colour**, creating dynamic visual feedback.
5. CSS animations smoothly transition between colours, producing a visually immersive representation of the music.

Through synchronized vibrations and colour changes, Haptix enables users to **experience the rhythm and emotional energy of music through touch and visuals instead of sound**.

---

## 🚀 How to Run

```bash
git clone https://github.com/Hack-for-Infinity/VibeHue.git
cd VibeHue
```
