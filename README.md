# MIXXX & DDJ-REV1 Documentation

<img src="https://img.shields.io/badge/DJ-Music-c9c9c9" /> <img src="https://img.shields.io/badge/MIXXX-2.5.6+-orange" /> <img src="https://img.shields.io/badge/DDJ-Rev1-blue" /> <img src="https://img.shields.io/badge/CAN-X.1569D-949885" />

```py
MIXXX VERSION: Windows/Linux Release 2.5.6 - PIONEER DDJ-REV1 Firmware: 1.0
UPDATED 06/2026 - by Uriel Deveaud [AK25 / The Skywatchers / NR] - Languages: EN
```

*"Hi, this repository is my full documentation and archives, using the open source DJ software **Mixxx**[^1] and the **Pioneer ddj rev1** midi controller[^2]. I decided to write this documentation for several reasons. The first was that the main documentation is not enough specific for the use of this controller. The second was that all the files available for this controllers are existing in multiple versions and over various websites and repositories. The third was that I wanted to get my own documentation with my personal approach and learning curve :raising_hand:

> [!IMPORTANT]
> THIS PAGE IS ACTUALLY IN MAINTENANCE MODE, CONTENTS MAY BE UNCOMPLETE OR DISTRIBUTED OVER MULTIPLE PAGES.  
> PLEASE, CONTACT ME IF YOU NEED MORE INFORMATIONS ABOUT IT.

---

<table>
<tr>
<th align="center", width="880">Hardware: PIONEER DDJ-REV1</th>
</tr>
</table>

The Pioneer DDJ-REV1 is a four-channel battle-style USB controller with an integrated audio interface. The DDJ-REV1 matches perfectly with the free and open-source MIXXX software, boasting a battle-style layout. The design of this 2-channel DJ controller emulates a professional DJM-S mixer + PLX turntable setup, including specialized features for open-format and scratch DJs. The product is accessible (cheap compared with the middle price market), it costs around 250 euros in any on-line shops (2025/2026), but it includes most of the midi controls you need to perform and have fun, within a compact size unit and without external power supply unit. 

- Dimensions (W × D × H) = 526.0 × 255.5 × 59.2 mm
- Main unit weight = 2.1 kg
- Power supply = DC 5V - USB
- built-in 4-channel sound card with master output.
- MIC input: 1/4" TR jack.
- Master output: RCA pin jacks.
- Headphones: 3.5 mm stereo jack.

- Links: [Manufacturer's product page](https://www.pioneerdj.com/en/product/controller/ddj-rev1/black/overview/l) - [Manufacturer's manual](https://downloads.support.alphatheta.com/manuals/DDJ_REV1_DRI1744B_manual/) - [MIDI message list (PDF)](https://downloads.support.alphatheta.com/software_info/dj-controllers/DDJ-REV1/DDJ-REV1_MIDI_Message_List_E1.pdf)

<img alt="ddjrev1_top" src="/images/ddjrev1_hardwareGui.png">

Here are the main features and sections over the front panel interface:

- **Headphone and Master output levels**
- **Mixing decks**:
  - Play/CUE buttons
  - Speed control (%)
  - Loop Start and settings
- **Mixer**:
  - Channel volumes, Gains and EQs
  - Cross-fader, 
  - Filter Knob per channel


---

<table>
<tr>
<th align="center", width="880">Software: MIXXX 2.5x/2.6</th>
</tr>
</table>

Mixxx integrates the tools DJs need to perform creative live mixes with digital music files.
Whether you are a new DJ with just a laptop or an experienced turntablist, Mixxx can support your style and techniques of mixing.

Mixxx is free open-source software and entirely community-driven. There is no company behind Mixxx — the development is shouldered by passionate DJs and programmers that dedicate their free time to working on their favorite DJ software. Mixxx is and always will be free!

<img alt="mixxx software" src="/images/captureMixxx_02.png">

---

## Setup

In **Preferences → Sound Hardware**, configure outputs as
follows:

| Output channel | Assign to |
|----------------|-----------|
| 1–2 | Main |
| 3–4 | Headphones |

| Input Channels | Assign to |
|----------------|-----------|
| 1-2 (Input 1) | Microphone 1 |

---



<table>
<tr>
<th align="center", width="880">SECTIONS & FEATURES</th>
</tr>
</table>

- **General overview**
- **File browser a.k.a the Library**:
  - Folder Navigation and Selection
  - Files Navigation and Loading
  - File Search Bar
- **Music Player**:
  - Transport Buttons
  - Waveform preview
  - Track options
  - Infos
  - Deck disc
- **Mixer** (channels, Main, Headphones, Boost, Filters, EQs)
- **Audio Effects** (Multi-FX)
  - **Filter per channel**
  - **FX Slots and Depth value**
- **Pads Section:**
  - **Samplers** (Audio Files)
  - **Saved Loops** (Settings)
  - **Scratch Banks** (Audio Files)
  - **Stems** (Audio Files)

---

## :radio_button: Files

- **Midi Mapping for DDJ REV1**: made by AKOI
- **DDJ REV! Skin**: made by me
- **This documentation**: PDF File

---

<table>
<tr>
<th align="center", width="880">Data Processing</th>
</tr>
</table>

<ul>
      <li><b>Real-time Support</b>
        <ul>
          <li>Suggest a serie of optional processes and combos</li>
          <li>Suggest a serie of optional Shortcuts</li>
          <li>Suggest a serie of optional parametric objects</li>
          <li>Suggest a serie of optional Texturing processes</li>
        </ul>
      </li>
      <li><b>Real-time Auto-Correct</b>
        <ul>
          <li>Show errors based on 3 main error types*</li>
        </ul>
      </li>
</ul>

<img alt="preview_v135" src="/images/ddjrev1_FXsection.png">

---

## :radio_button: Infos

* Author: **Uriel Deveaud** - [Kore Teknology](https://github.com/KoreTeknology)
* License: This project is released under the GPL License.
* This work is dedicated to all Mixxx users around the world ;)

---

[^1]: **MIXXX** is the free and open source DJ software. It supports nearly any external Midi controller. Please, visit the [Mixxx Github page](https://github.com/mixxxdj/mixxx).

[^2]: **DDJ-REV1** is a Midi DJ controller made by Pioneer. Please, visit the [Pioneer DDJ-REV! product page](https://www.pioneerdj.com/en/product/dj-controllers/ddj-rev1/)
