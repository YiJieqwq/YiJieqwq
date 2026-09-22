# 👋 Hi, I'm YiJieqwq

**Android system-level tooling** — kernel modules, native overlays, and both sides of root detection & bypass.

[![Followers](https://img.shields.io/github/followers/YiJieqwq?style=flat-square&label=Followers&color=0e75b6)](https://github.com/YiJieqwq?tab=followers)
[![Profile views](https://komarev.com/ghpvc/?username=YiJieqwq&style=flat-square&label=Profile%20views&color=0e75b6)](https://github.com/YiJieqwq)

---

## 🚀 Featured

### [Android-Native-Overlay](https://github.com/YiJieqwq/Android-Native-Overlay)

[![stars](https://img.shields.io/github/stars/YiJieqwq/Android-Native-Overlay?style=flat-square&color=0e75b6)](https://github.com/YiJieqwq/Android-Native-Overlay/stargazers)
[![release](https://img.shields.io/github/v/release/YiJieqwq/Android-Native-Overlay?style=flat-square&label=release)](https://github.com/YiJieqwq/Android-Native-Overlay/releases)
[![license](https://img.shields.io/github/license/YiJieqwq/Android-Native-Overlay?style=flat-square)](https://github.com/YiJieqwq/Android-Native-Overlay/blob/main/LICENSE)

A minimal Android native overlay template built with **SurfaceComposer**, **ANativeWindow/EGL**, **OpenGL ES 3** and **Dear ImGui**, plus a non-exclusive `/dev/input` touch observer. AArch64 native executable with no Activity and no Java UI — a draggable, resizable, foldable glass panel with runtime Surface replacement and EGL context reuse.

`C` · `SurfaceComposer` · `EGL / OpenGL ES 3` · `Dear ImGui` · `CMake / NDK`

### [Inode-Hijacker](https://github.com/YiJieqwq/Inode-Hijacker)

[![stars](https://img.shields.io/github/stars/YiJieqwq/Inode-Hijacker?style=flat-square&color=0e75b6)](https://github.com/YiJieqwq/Inode-Hijacker/stargazers)
[![release](https://img.shields.io/github/v/release/YiJieqwq/Inode-Hijacker?style=flat-square&label=release)](https://github.com/YiJieqwq/Inode-Hijacker/releases)
[![license](https://img.shields.io/github/license/YiJieqwq/Inode-Hijacker?style=flat-square)](https://github.com/YiJieqwq/Inode-Hijacker/blob/main/LICENSE)

Transactional inode lowering for Android — swaps a target directory's inode with a low-inode candidate in seconds, while preserving contents, ownership and SELinux contexts. Smart risk grading and a one-command safe swap.

`Shell` · `SELinux` · `Root filesystem` · `Android`

---

## 🧰 More projects

| Project | What it does |
| --- | --- |
| **[KPMDynaLab](https://github.com/YiJieqwq/KPMDynaLab)** | Kernel Patch Module for **undetectable kernel-level dynamic analysis** of Android bricker malware — hooks the block layer to monitor, simulate or block block-device writes. |
| **[Corax-RAG-Agent](https://github.com/YiJieqwq/Corax-RAG-Agent)** | **Corax-RAG (Strata)** — a lightweight Agentic RAG framework for QQ chats: long-term memory, identity isolation, and a virtual-filesystem shell with snapshot approval. |
| **[Chunqiu-Detector-Problem-solution](https://github.com/mingzun09/Chunqiu-Detector-Problem-solution)** | **I'm the main maintainer** (hosted under [@mingzun09](https://github.com/mingzun09)). A curated documentation of solutions for the common detections used by Chunqiu Detector. |
| **[ADB-Trace-Cleaner](https://github.com/YiJieqwq/ADB-Trace-Cleaner)** | Bilingual shell script that erases USB debugging traces on Android devices — for module developers, reverse engineers and testers. |
| **[android-root-skillkit](https://github.com/YiJieqwq/android-root-skillkit)** | Root / modding security knowledge kit for **AI assistants**: root fundamentals & hiding, bricker threat & defense, and hardening for root-enthusiast software. |
| **[Regent-DREX-QFPlugin](https://github.com/YiJieqwq/Regent-DREX-QFPlugin)** | QQ group administration command system for QFun, built on the DREX command-routing architecture. |
| **[QuoteMemeNext](https://github.com/YiJieqwq/QuoteMemeNext)** · **[QQMsgEditor](https://github.com/YiJieqwq/QQMsgEditor)** | QQ plugins built on QFun — a one-tap quote-image generator and a message editor. |
| **[Folkpatch-theme](https://github.com/YiJieqwq/Folkpatch-theme)** | Theme packages for FolkPatch. |

---

## 🔧 What I work with

- **Languages** — C · Kotlin · Java · Shell · Python · Rust
- **Kernel & security** — Linux kernel · KernelPatch / KPM · block-layer and LSM hooks · eBPF · SELinux · root detection **and** bypass
- **Android native** — NDK / Clang · SurfaceComposer · EGL + OpenGL ES · Dear ImGui · Magisk / KernelSU / APatch module development
- **Reverse engineering** — Frida · ptrace · inline hooking · Ghidra

---

## 📌 Currently

- Extending **Android-Native-Overlay** as a reusable native overlay template.
- Building kernel-level analysis and protection modules on KernelPatch / KPM.
- Working both sides of root detection — writing checks, and defeating them.

---

## 📮 Contact

- **QQ** — `2875395255`
- **Coolapk** — [YiJieqwq](https://www.coolapk.com/u/6095524)

---

⭐ **Stars, issues and PRs are all welcome — let's make these tools better together.**
