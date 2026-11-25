# Lucamammone.github.io

Personal hardware & embedded engineering portfolio of **Luca Mammone** — live at **[https://Lucamammone.github.io](https://Lucamammone.github.io)**

Plain HTML and CSS with no build step, hosted on GitHub Pages. Each project lives in its own folder with its page, images, and source code.

## Projects
- **8–16 MHz Class-D SDR Power Amplifier** — Switching Class-D RF power amplifier and 5-pole LC filter PCB for an 8–16 MHz Software-Defined Radio (0.73% THD, <0.4 W idle power).
- **PixelDraw Optical Tracking Canvas** — 30 FPS Python/OpenCV HSV marker tracker streaming over JTAG UART to bare-metal C firmware on a Nios V RISC-V soft processor driving VGA on a DE1-SoC board.
- **Hardware Blackjack Engine (DE1-SoC)** — Synthesizable Verilog RTL Blackjack game featuring finite state machines, a hardware LFSR card dealer, PS/2 input, and VGA gameplay graphics.

## Repository Structure
```text
├── index.html          # Main landing page and project overview
├── style.css           # Stylesheet
├── resume.pdf          # Resume
├── assets/             # Shared images and bench captures
└── projects/           # Project pages, media, and source code
    ├── sdr-power-amp/
    ├── pixeldraw/
    └── fpga-blackjack/
