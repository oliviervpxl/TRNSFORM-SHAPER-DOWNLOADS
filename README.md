# TRNSFORM SHAPER

A VST3 sidechain tool for rhythmic volume ducking, tempo-synced curves, and pumping effects in modern music production.

TRNSFORM SHAPER gives producers control over rhythmic volume movement through editable curves and tempo-synchronised ducking. Both the Basic (Free) and upcoming Pro editions share the same codebase and project state format, meaning projects saved with the Basic edition will open seamlessly in the Pro edition.

<img width="598" height="418" alt="image" src="https://github.com/user-attachments/assets/57d2ba0d-64b6-4b3a-865b-08d41893a2f6" />


## Features — Basic (Free) Edition
The Basic edition is designed for producers who want fast, click-free control over rhythmic pumping without setting up a compressor sidechain.

*   **Tempo-Synced Ducking:** Shape volume in musical cycles of 1/8, 1/4, 1/2, or 1 BAR, locked tightly to the DAW transport.
*   **Interactive Multi-Node Curve Editor:** Add, move, and remove breakpoints (up to 64 nodes), adjust per-segment curve tension, and snap to a 4, 8, 16, or 32 division grid.
*   **16 Curve Slots:** Keep 16 different shapes ready inside each plugin instance. Includes per-slot Undo/Redo (up to 100 steps).
*   **Core Envelope Controls:** Sculpt the envelope with Amount, Slope, Recovery, Shift, and anti-click Smoothing.
*   **User Curve Library:** Save custom curves as portable `.curve` files and load them into any project.
*   **Project Recall & Host Automation:** All slots and parameters are saved with your DAW project and exposed for host automation.

## Coming Soon: TRNSFORM SHAPER PRO (€5)

<img width="590" height="395" alt="image" src="https://github.com/user-attachments/assets/3f14ae38-3332-43c3-b497-c041a9aec15f" />

The upcoming Pro Edition expands the core shaper into a surgical sidechain and multiband dynamics processor. It will be available for €5 and introduces the following advanced features:


*   **3 Trigger Modes [ SYNC | AUDIO | MIDI ]:** Expand beyond standard sync with Triplet, Dotted, and Swing (50–75%) timing. Use sample-accurate MIDI Note-On triggering, or use external audio (Bus 1) with a 0-lag peak envelope detector (18 ms peak-hold).
*   **Sidechain EQ Filter & Real-Time Visualizer:** Isolate trigger transients with a 12 dB/oct HPF/LPF filter and Threshold control. View the post-filter signal in real-time (60 FPS) on the Curve Editor background, complete with a Playhead Hit-Flash.
*   **Lookahead Pre-Delay:** Selectable 0, 2, 5, or 10 ms lookahead with automatic DAW latency compensation (PDC) for zero-click transient ducking.
*   **Split-Band / Frequency-Specific Ducking:** Phase-compensated 24 dB/oct Linkwitz-Riley (LR4) crossover. Duck only the sub/low-bass (20–120 Hz) while leaving mids and highs completely untouched.
*   **Mid/Side Processing:** Apply volume shaping to the full stereo signal (L/R), exclusively to the mono center (MID), or exclusively to the stereo edges (SIDE).
*   **Global Shape Modifiers:** Warp the entire active curve in real-time with global TENSION and SKEW controls without moving individual nodes.
*   **A/B State Comparison:** Instantly compare two complete setups (including all 16 curve slots and all DSP parameters) using [A], [B], and [COPY A>B].

## Download
**TRNSFORM SHAPER (Basic Edition)**
Requires 64-bit Windows and a DAW that supports VST3 plugins.
[Download TRNSFORM SHAPER](https://github.com/oliviervpxl/TRNSFORM-SHAPER-DOWNLOADS/releases/latest/download/TRNSFORM_SHAPER_Setup_x64.exe)

## Authors
Olivier Vleeschouwers & Bas Engelborghs

## License
TRNSFORM SHAPER is proprietary software. See [LICENSE](LICENSE) for the applicable usage and redistribution terms. Third-party components remain subject to their respective licences.
