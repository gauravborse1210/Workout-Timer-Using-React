## Workout Timer App

This React app helps users plan workouts by calculating total duration based on sets, speed, and breaks. It shows a live clock and adjusts workout options depending on whether it’s AM or PM. Sound feedback plays when duration updates, and users can toggle it on or off.

The workout list is optimized using useMemo, so it only recalculates when needed. The Calculator component is wrapped in memo to prevent unnecessary re-renders. Together, these optimizations keep the app fast and responsive.
