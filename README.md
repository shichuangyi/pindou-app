# 拼豆助手 · Pindou Studio

A local-first Android app for fuse-bead (拼豆) crafting and studio shops. **No cloud, no account — everything stays on the phone.**

## Features

- 🎨 Image-to-pattern: turn any photo into a bead pattern (16–64 beads wide)
- 🎨 Built-in 46-color coded palette with automatic nearest-color matching
- 🔢 Per-color bead usage counts — know exactly what to prepare
- ✏️ Pattern editor: tap cells to recolor, eraser for blanks, optional color-code overlay
- 🗂️ Pattern library + PNG export
- ⏱️ Shop timing: 10 stations, start / pause / resume / checkout, configurable price, billing blocks (per-minute / 15 min / 30 min / hourly) and free-pause allowance
- 📦 Semi-finished work storage registry with overdue highlighting
- 📈 Today / month revenue stats, 🔒 PIN lock, 💾 JSON backup export & import

## Tech

Single-file offline web app (HTML/CSS/JS, localStorage) inside a thin Android WebView shell. Built automatically by GitHub Actions (Gradle 8.7, AGP 8.5.2, JDK 17).

## Install

Download the APK from the latest successful Actions run's artifact, allow "install unknown apps", and install. Android 7.0+.
