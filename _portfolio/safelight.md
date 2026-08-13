---
title: "SafeLight"
excerpt: "A reinforcement learning method toward collision-free traffic signal control<br/><img src='/images/safelight.svg'>"
collection: portfolio
---

Traffic signal control is safety-critical for our daily life. Roughly one-quarter of road accidents in the U.S. happen at intersections due to problematic signal timing, urging the development of safety-oriented intersection control. Existing adaptive traffic signal control research using reinforcement learning has focused mainly on minimizing traffic delay while neglecting potential exposure to unsafe conditions.

We, for the first time, incorporate road safety standards as enforcement to ensure the safety of existing reinforcement learning methods, aiming toward operating intersections with zero collisions. We propose a safety-enhanced residual reinforcement learning method (**SafeLight**, [AAAI 2023](/publication/2023-06-01-safelight)) and employ multiple optimization techniques, such as a multi-objective loss function and reward shaping, for better knowledge integration. Extensive experiments using synthetic and real-world benchmark datasets show our method can significantly reduce collisions while increasing traffic mobility.

Code: [gitlab.com/wenlu057/traffic-safety](https://gitlab.com/wenlu057/traffic-safety)
