# Naruto Gesture Battle

An interactive browser-based project where hand gestures control anime-style powers in real time.

Built using MediaPipe, this project turns your webcam into a motion-controlled system where you can charge, lock, and launch abilities inspired by Naruto and Sasuke.

---

## Features

* Real-time hand tracking using MediaPipe
* Gesture-based power system
* Charging mechanics with visual feedback
* Lock-on system for abilities
* Projectile throwing using motion velocity
* Clash detection with cinematic explosion effects
* Particle system and screen flash effects
* Dual-hand interaction (left vs right mechanics)

---

## Controls

Left Hand (Naruto):

* Open hand: Charge ability
* Hold for 4 seconds: Lock ability
* Close fist and release: Throw projectile

Right Hand (Sasuke):

* Open hand: Charge ability
* Full charge: Lock ability

Interaction:

* Bring both abilities close to trigger a clash event

---

## Tech Stack

* HTML, CSS, JavaScript
* MediaPipe Hands
* Canvas API
* Web Video Processing

---

## How It Works

The system tracks hand landmarks using MediaPipe and interprets gestures such as open palm and fist. Based on these gestures:

* Energy is accumulated over time
* Abilities get locked after reaching thresholds
* Motion is tracked to simulate velocity-based throws
* Collision detection triggers visual effects and particle systems

---

## Future Improvements

* Sound effects for charging and clashes
* Mobile support
* Performance optimizations
* Modular code structure
* More abilities and gesture combinations

---

## Creator

Amogh Poonakar
