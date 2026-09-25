<h1 align="center">Harinarayanan R</h1>

<p align="center">
  <strong>AI/ML student · systems-minded builder · photographer</strong><br>
  Kochi, Kerala · Jain University
</p>

<p align="center">
  <a href="https://hariforreal.in">Website</a> ·
  <a href="mailto:rharinarayanan69@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/hari456">LinkedIn</a> ·
  <a href="https://x.com/zephyrr248">X</a>
</p>

I build tools that make difficult systems visible: a browser that treats local development as a first-class workspace, a computer-vision safety system for mine vehicles, a lunar-image registration pipeline, and a welfare navigator that turns scattered government rules into a usable Malayalam and English journey.

I like the layer underneath the framework: file I/O, concurrency, crash recovery, model behaviour, embedded devices, and the small decisions that make software trustworthy. I also shoot portraits, landscapes, stages, and quiet things.

## Selected work

### [Forge](https://github.com/hxr4/forge_brow)

**A macOS browser built around local development.** Swift, AppKit, WebKit, CEF, Chromium, Objective-C++

Forge treats the browser as part of the developer’s desk instead of a window that gets opened and closed. It includes tab suspension, a scriptable command bar, host-level request visibility, popup blocking, and native macOS foundations.

### [VISOR](https://github.com/hxr4/visor)

**Visibility-Indexed Safe Operating Range for mine vehicles.** Python, OpenCV, Raspberry Pi

In fog, a vehicle cannot safely choose a speed without knowing how far its sensors can see. VISOR combines simulated radar, camera, and thermal inputs to estimate a safe operating range. Built for SIH 2026, PS SIH26007.

### [LunarReg](https://github.com/hxr4/lunareg)

**Registration and quality checking for Chandrayaan-2 imagery.** Python, PyTorch, GDAL

LunarReg aligns images captured by different cameras, at different resolutions and sun angles, then exposes the result through a mission console so the registration can be inspected instead of blindly trusted.

### [Welfare Navigator](https://github.com/hxr4/welfarenavigator)

**A source-backed welfare screener for Kerala.** Next.js, React, TypeScript, Zod

Welfare Navigator helps fishing and plantation families find schemes they may be eligible for. It uses a deterministic rules engine, adaptive questioning, Malayalam and English support, official source quotations, document checklists, and district-office routing. No AI model decides eligibility.

### [OPPU](https://github.com/hxr4/oppu)

**Offline-first student concession verification.** TypeScript, WebCrypto ECDSA P-256, IndexedDB, Vite

OPPU lets a conductor verify a student concession card on a moving bus, even without a network connection. The design treats QR screenshots, sibling lookalikes, and offline verification as real security problems.

### [Aashan](https://github.com/hxr4/aashan_fintech)

**A privacy-conscious financial ledger.** Python, FastAPI, PostgreSQL, SQLite

Aashan reconciles observations from different financial sources into one canonical ledger, so the same lunch seen by two accounts does not become two expenses. The architecture keeps source observations separate from user-owned aggregates.

### [Mine Worker Safety Node](https://github.com/hxr4/mine-worker-node)

**An embedded safety sensor prototype.** ESP32, Arduino, Web Serial, MQTT

A small sensor node for detecting events such as impact, shock, flame, temperature changes, and pulse-count changes when nobody is watching directly.

## The thread through all of it

I keep returning to the same question:

> What should the system do when the obvious answer is incomplete, delayed, or wrong?

That leads to offline verification in OPPU, uncertainty-aware screening in Welfare Navigator, inspectable image registration in LunarReg, and recovery-oriented tooling in Forge.

## Current toolkit

`Python` `C` `C++` `Swift` `TypeScript` `React` `Next.js` `PyTorch` `OpenCV` `FastAPI` `PostgreSQL` `SQLite` `WebCrypto` `ESP32` `Raspberry Pi` `Linux` `ADB`

## Outside the code

I photograph stages, portraits, landscapes, festivals, and quiet details. I listen to music obsessively, prefer the terminal to a dashboard when the terminal is enough, and keep a long-running Minecraft survival world under the name `zephyr`.

## Contact

If you want to talk about systems software, applied ML, computer vision, embedded work, or a project that has to survive the real world:

**[Email me](mailto:rharinarayanan69@gmail.com)** · **[hariforreal.in](https://hariforreal.in)**
