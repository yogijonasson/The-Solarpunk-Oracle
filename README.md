# 🌱 The Solarpunk Oracle: A Multimodal Installation for Reflective Futures

The **Solarpunk Oracle** is an interactive installation that invites visitors to explore hopeful futures through symbolic gestures and poetic AI responses. Inspired by Solarpunk aesthetics and ethics, the Oracle blends physical computing with ambient design to create a moment of multisensory reflection.

## 📹 Demo Video

[![Watch the video](https://img.youtube.com/vi/brxwXBemLDk/0.jpg)](https://www.youtube.com/watch?v=brxwXBemLDk)

## 🌟 Project Goals

* Reimagine AI as a poetic, non-dystopian companion.
* Encourage reflective, emotional, and ethical interaction with technology.
* Translate Solarpunk values—sustainability, interdependence, imagination—into a tangible, embodied experience.

## 🔮 Interaction Design

| Interaction | Sensor              | Symbolic Meaning      | Output                       |
| ----------- | ------------------- | --------------------- | ---------------------------- |
| Step        | Piezoelectric mat   | Awakening / Energy    | LED activation + visual cue  |
| Wave        | IR proximity sensor | Transformation / Wind | GPT-generated poetic insight |

## 💡 System Architecture

1. **Piezo sensor** detects user step to activate the Oracle.
2. **IR sensor** detects a wave gesture to trigger the response.
3. **Arduino** sends signals to a Python script running on a connected laptop.
4. The Python script sends prompts to **Gemini API** based on predefined themes.
5. The Oracle's response is displayed as glowing text or played as audio.
6. Ambient LED lighting reacts to the event, creating an atmospheric experience.

## 🔧 Materials

* 🧠 **Microcontroller**: Arduino Uno
* 🦶 **Piezo Sensor**: For detecting presence and activation
* 🌬️ **Ultrasounds Sensor**: Triggers poetic response upon wave gesture
* 💡 **WS2812B LEDs**: Ambient lighting effects
* 🔊 **Optional Speaker**: For voice output (text-to-speech)
* 🖥️ **Laptop**: Runs Python logic and Gemini AI integration

## 🛠️ Development Timeline

| Week | Milestone                                        |
| ---- | ------------------------------------------------ |
| 1    | Finalize concept & order components              |
| 2    | Build & test piezo and Ultrasound circuits               |
| 3    | Set up Gemini communication via Python script       |
| 4    | Program lighting & output logic                  |
| 5    | Build physical installation (base, casing, etc.) |
| 6    | User testing, refinement, documentation          |

## ✨ Sample Experience

A visitor steps onto a moss-textured mat—light pulses gently around them.
With a wave of the hand, the Oracle awakens and speaks:

> *"The soil remembers you. Grow wild, and you will not be forgotten."*

## 🎁 Contribution

This project explores poetic, embodied interaction with AI. It offers a hopeful and human-centric perspective on technology by evoking emotion, presence, and imagination—rooted in the values of the Solarpunk movement.


