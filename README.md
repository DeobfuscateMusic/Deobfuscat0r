# 𝐃𝐞𝐨𝐟𝐮𝐬𝐜𝐚𝐭𝟎𝐫 - 𝐋𝐢𝐯𝐞 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞 𝐈𝐧𝐭𝐞𝐫𝐟𝐚𝐜𝐞

> _Centralized MIDI Hub & Harmonic Quantizer. Precision controls for complex hardware synthesizer rigs and live performances. Harmonizes and quantized frequencies for smooth transitions._

![Under Development](https://img.shields.io/badge/Status-Under%20Development-orange)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Universal%20Silicon%20%26%20Intel-black?labelColor=606060&style=flat-square&logo=apple&logoColor=white)
![Format](https://img.shields.io/badge/Format-Standalone-00CED1?style=flat-square)

---

https://github.com/user-attachments/assets/ea3b8827-1438-4fd5-9ee5-0b61651490d4

---

## 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

- **10 Channels Hub**: Pre-configured MIDI architecture for professional hardware rigs.
- **Generative Engine**: Real-time control over trigger probability and micro-timing jitter.
- **Harmonic Constrainer**: Advanced scale quantization logic for melodic synchronization.
- **Drift Visualization**: Real-time oscilloscopes for monitoring LFO, S&H, and Random modulation sources.

---

## 𝐏𝐚𝐫𝐚𝐦𝐞𝐭𝐞𝐫𝐬

- **Performance Strips**: Four critical parameters per channel for tactile sequencing: **PRB** (Probability/Likelihood), **TIM** (Timing/Jitter), **VEL** (Velocity Layers), and **GAT** (Gate/Note Length).

- **Harmonic Constrainer**: A mathematical scale engine that forces incoming MIDI data into specific musical modes. It "snaps" erratic or random inputs to the nearest note in a chosen scale (Aeolian, Phrygian, etc.), ensuring melodic coherence across all connected gear.

- **Drift Visualization**: Dedicated channel oscilloscopes that visualize internal modulation movement. Monitor the behavior of your hardware's LFOs and Random sources in real-time to maintain control over evolving textures.

- **MIDI Learn System**: Intelligent CC mapping protocol. Assign software sliders to physical hardware knobs instantly via the high-visibility "LEARN" indicator and the Map CC utility.

- **Global Clock**: High-stability MIDI transport locked to 129.00 BPM with dedicated Play/Pause/Stop controls.

---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: 14.0 (Sonoma), 15.0 (Sequoia), or 16.0 (Tahoe).
- **Architecture**: Intel & Apple Silicon (Universal).
- **Hardware**: Multi-port MIDI Interface and MIDI-capable synthesizers.
- **Permissions**: Requires MIDI Device Access (for hardware communication) and MIDI SysEx (for advanced configuration).

---

## 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

1. Download the latest `Deobfuscat0r`
2. Extract & Drag `Deobfuscat0r` to your `Applications` folder.
3. Connect your MIDI Interface via USB before launching the application.
- _Note: Fill the Permissions tutorial below for first-time setup._
3. Configure your synthesizers to their designated MIDI channels (see Routing Table Examples).
4. Click on **PLAY**. It will start the MIDI engine and transport.

---

### 𝟏. 𝐌𝐈𝐃𝐈 𝐃𝐞𝐯𝐢𝐜𝐞 𝐀𝐜𝐜𝐞𝐬𝐬
Required to send and receive note/CC data from your hardware.
- `Settings` > `Privacy & Security` > `Site Settings` > `MIDI devices` > Enable `DEOBFUSCAT0R`.

### 𝟐. 𝐒𝐲𝐬𝐄𝐱 𝐌𝐞𝐬𝐬𝐚𝐠𝐞𝐬
Required for deep integration and mapping with specific hardware protocols.
- Click **Allow** for "Use System Exclusive Messages."

---

## 𝐑𝐨𝐮𝐭𝐢𝐧𝐠 𝐓𝐚𝐛𝐥𝐞 𝐄𝐱𝐚𝐦𝐩𝐥𝐞𝐬

| **𝐈𝐧𝐬𝐭𝐫𝐮𝐦𝐞𝐧𝐭** | **𝐂𝐡𝐚𝐧𝐧𝐞𝐥** | **𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧** |
| :--- | :--- | :--- |
| **OPSIX** | CH 01 | Lead / FM Textures |
| **ANALOG FOUR** | CH 02 | Bass / Pads |
| **BASSLINE** | CH 03 | Acid Bass |
| **ANALOG RYTM** | CH 04 | Percussion |
| **TYPHON** | CH 05 | Analog Mono |
| **DIGITONE** | CH 06 | FM Melodic |
| **SH-01** | CH 07 | Classic Lead |
| **TR 9** | CH 09 | Main Drums |
| **PERKONS HD** | CH 10 | Industrial Kick |
| **LXR-02** | CH 11 | Digital Percussion |

---

## 𝐂𝐨𝐧𝐭𝐫𝐨𝐥𝐬

- **MAP CC**: Enter mapping mode to link software parameters to physical knobs.
- **LEARN**: Visual feedback when MIDI data is successfully received.
- **SCALE**: Select the target musical mode for the Harmonic Constrainer.
- **DRIFT**: Toggle oscilloscope visualization for specific modulation sources.
- **STOP**: Immediate MIDI All-Notes-Off and transport kill.

---

_This software is free. Don't forget to give it a ⭐ on Github if you liked the project._

---

<p align="center"><code>𝕯𝖊𝖔𝖇𝖋𝖚𝖘𝖈𝖆𝖙𝖊</code></p>
<p align="center">2026</p>
