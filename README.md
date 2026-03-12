# 🟢 Ben 10 Universe Explorer

A visually rich **Ben 10 fan website** that explores the complete **Ben 10 universe** — from the original **Classic (2005)** series to **Alien Force**, **Ultimate Alien**, **Omniverse**, and the **2016 Reboot**.

This project is a **frontend web experience** designed to feel like a cinematic tour of the Ben 10 world, featuring animated alien galleries, background videos, smooth scrolling effects, and immersive UI interactions.

---

# 🌌 Project Overview

This website works as a **fan encyclopedia and visual exploration hub** for the Ben 10 universe.

Visitors can:

- Explore different **Ben 10 series**
- Discover **aliens, villains, and characters**
- Navigate through sections with **smooth animated transitions**
- Experience **scroll-based animations**

---

# ✨ Features

## 🎬 Immersive Hero Section
- Fullscreen **background video**
- Ambient **background music**
- Animated title introduction
- Smooth entrance animations

## 🧭 Navigation System
- Fixed navigation bar
- Smooth scrolling
- Multiple sections:
  - Home
  - About
  - Ben 10 Universe
  - Gallery
  - Tools & Gadgets
  - Explore

## 👽 Alien Gallery
Large alien showcase grid including characters like:

- Alien X  
- Way Big  
- Swampfire  
- Four Arms  
- Diamondhead  
- Echo Echo  
- Ghostfreak  
- Rath  
- Upgrade  
- Heatblast  

## ⚡ Scroll Animations
The website uses **GSAP + ScrollTrigger** to animate elements during scrolling.

Example:

```javascript
gsap.to(image, {
  scale: 0,
  scrollTrigger: {
    trigger: image,
    start: "top bottom",
    end: "bottom top",
    scrub: true
  }
});
