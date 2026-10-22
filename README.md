# Physika[^1] (Currently Under Development)

**Learn physics by making things move.**

Physika is a free physics course that runs entirely in your web browser. You read a short lesson, write a few lines of Python, press Run, and watch your own numbers come to life in a simulation: a ball thrown across a field, a planet sweeping around the Sun, a current flowing through a circuit you built yourself.

**Try it: https://minuii.github.io/physika/**

Open the link and start.

---

## Why Physika exists

Physics is usually taught as formulas on a page. You learn that the period of a planet goes as the semi-major axis to the power 3/2, write it down, and move on. It rarely feels like something you can *touch*.

Physika takes a different route. Every idea comes with something to do:

- **You calculate it.** You write the Python that works the answer out, the same way a physicist or engineer would.
- **You see it.** The Lab animates *your* result, not a prepared video. Change a number in your code, run it again, and the picture changes.
- **You build it.** In the Circuit Lab you place batteries, resistors and transistors on a breadboard and measure what happens, instead of only reading about it.

The aim is to make physics feel like a game you play, while still teaching it properly: real equations, real units, and answers that have been checked.

---

## What you can learn

Twelve courses are open now, with **217 exercises** in total:

| Course | Exercises | What it covers |
|---|---|---|
| **Mechanics I** | 12 | Motion, projectiles, forces, energy and your first orbit, all written in Python |
| **Mechanics II** | 12 | Momentum, collisions and rockets, torque, rolling and spin, gravitation and fluids |
| **Electricity** | 34 | Charge and fields, Gauss's law, voltage, capacitors, current and DC circuits |
| **Magnetism** | 42 | Magnetic forces and fields, induction, inductors, AC circuits and electromagnetic waves |
| **Circuits & Electronics** | 37 | Circuit laws, logic gates, diodes, transistors, filters and op-amps, built in the Circuit Lab |
| **Waves & Oscillations** | 12 | Pendulums, springs, resonance, beats and standing waves |
| **Thermal Physics** | 10 | Heat, gases, molecular speeds, engines and entropy |
| **Modern Physics** | 12 | Special relativity, photons, the hydrogen atom, quantum tunnelling and nuclear energy |
| **Astrophysics** | 11 | Orbits, escape speed, starlight, a trip to Mars and dark matter |
| **Computational Physics** | 12 | Numerical methods: stepping equations forward, randomness, chaos, roots and integrals |
| **Optics & Light** | 12 | Mirrors, refraction and optical fibres, lenses and images, two-slit fringes, coatings and gratings |
| **Machine Learning for Physics** | 11 | Gradient descent, fitting laws to data, a perceptron, a small neural network trained by hand, overfitting and clustering stars |

The courses suit anyone from a curious high-school student to a first- or second-year university student. They're also a gentle way into Python, because every program is short and about something real. The later courses assume you're comfortable with basic Python, so start with Mechanics I if you're new to it.

---

## How a lesson works

Every exercise follows the same four steps:

1. **Read.** A short lesson explains one idea in plain language, gives the one equation you need, and works through an example with real numbers.
2. **Code.** You write Python in the editor next to the lesson. It runs right in your browser.
3. **Run.** The Terminal shows what your program prints, and the Lab animates the physics using your values.
4. **Submit.** The checker reads your answers and tells you what to fix if something is off. It even spots common slips, such as a missing factor of 2 or a units mix-up of 1000.

If you get stuck there's a hint first, then a full worked solution. Problem sets lay it out step by step, one numbered step per question, so you can follow the reasoning, not just copy the answer.

### Three kinds of exercises

- **Python exercises** (95): you write a program that calculates something, often with loops, lists and small simulations.
- **Problem sets** (76): you work out several answers, with a Python scratchpad alongside if you want it.
- **Circuit builds** (46): you build or adjust a circuit in the Circuit Lab and measure it.

---

## The Lab

Next to every Python exercise sits the Lab, a small animated simulation that responds to *your* code. A few examples:

- Change the launch angle and the projectile flies a different arc.
- Change a planet's speed and its orbit stretches into an ellipse.
- Change the number of gas molecules and watch them spread through a box.
- Change a galaxy's visible mass and see how far its predicted rotation falls below what is measured, which is the evidence for dark matter.

Before you run anything the Lab shows an example, clearly labelled, so you know what to expect.

## The Circuit Lab

The Circuit Lab is a full circuit simulator on a virtual breadboard. You can:

- place 28 kinds of parts: batteries, AC and square-wave sources, resistors, capacitors, inductors, transformers, bulbs, switches, relays, diodes, LEDs, transistors, op-amps, fuses and sensors;
- watch current flow as moving dots, with probes and meters to measure voltage and current anywhere;
- use an oscilloscope and a frequency-response (Bode) plot for circuits that change over time;
- undo, redo, rotate, duplicate and delete freely;
- open any of **33 ready-made examples**, from a simple voltage divider to amplifiers and filters.

It works as part of the Circuits course, and also as a free sandbox from the **Circuit Lab** link in the header.

## SimLab

SimLab is the free-play side of Physika: physics benches with no exercise attached. Pick a setup, drag the sliders, press play and watch the motion and its graphs build up live. Open it from **SimLab** in the header.

- **Cannon:** launch speed, angle (drag the barrel), cliff height, gravity on Earth, the Moon or Mars, and air drag. Finish its challenges to unlock a predicted path.
- **Collision track:** two carts with any masses and speeds, from sticky to fully elastic, with momentum and energy shown and slow motion around the impact.
- **Springs and pendulums:** damping and a driving force, swings up to 170°, a phase-space picture, energy bars, and a frequency sweep that draws the resonance curve.
- **Orbit sandbox:** click to place a planet and drag to aim it. See the predicted orbit before you press play, plus the eccentricity, the measured period and equal areas in equal times.
- **Wave on a string:** pluck a pulse or shake one end, with each end fixed or free. Watch pulses flip (or not) as they reflect, and find the harmonics of a standing wave.

Every bench has a live graph and readout and ready-made examples. Across the five benches there are **14 challenges worth 245 XP**. 
**Copy link** gives you a link that opens the bench with your settings, so you can share a setup. Benches for optics, heat and fields are coming.

---

## Progress and rewards

- Earn **XP** for every exercise you finish and every SimLab challenge you complete, and level up as it adds up.
- Earn a **badge** for each of the 50 chapters you complete.
- Your progress is saved automatically **in your browser**. There's no sign-up, and nothing about you is sent anywhere. Because of that, it stays on the device and browser you used.

## Made to be comfortable

The **Settings** page lets you set Physika up the way you like:

- light or dark theme, or match your device;
- larger text, and thicker graph lines if you prefer them;
- a larger code editor font, and labelled program output (`Period in years = 1.88` instead of a bare number);
- faster or switched-off animations;
- how the Circuit Lab looks and shows current.

Physika works on phones and tablets as well as laptops, and follows accessibility basics such as readable contrast, keyboard use and reduced-motion support.

---

## Accurate by design

A physics course is only useful if its answers are right. So:

- **Every expected answer is calculated by the site's own code**, never typed in by hand, so a typo can't creep in.
- **Answers are locked.** Any change to an expected answer is flagged and has to be confirmed on purpose.
- **Every model solution is run** in the same Python the site uses, to prove it passes.
- **Answers are currently being independently checked.**
- Every update goes through **automatic and manual checks** before it goes live.

---

## For developers (All source files & documents are in the private repo.)

The whole site is one self-contained web page, built from the `src/` folder and published to GitHub Pages whenever `main` changes.

- **[HANDOFF.md](HANDOFF.md)**: start here. The current state, how the project works and what's left to do.
- **[docs/DEVELOPMENT.md](docs/DEVELOPMENT.md)**: how to build, test and publish, and what each folder contains.
- **[docs/](docs/README.md)**: the roadmap, testing guide, plans and past reviews.

[^1]: Physika is a placeholder name. The source code is private for now, but the site itself is free to use at the link above.
