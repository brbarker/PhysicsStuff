# Yo-Yo Exploration
This is an exploration of the physics at work for a simple model of a yo-yo.

## Simple Model (SM)
The Simple Model (SM) is meant to be a starting point. As much as possible is set to a constant value and/or approximated.

  ### SM Definitions
  - $r_1$ is the radius of the cylinder used to represent the "finger" around which the top loop of the yo-yo string is wrapped
  - $r_2$ is the radius of the central shaft of the yo-yo around which the bottom loop of the yo-yo string is wrapped
  - $r_3$ is the total radius of the yo-yo, from the center of the central axis, to the outer edge of the yo-yo
  - $y=0$ is the bottom of the cylinder ("finger")
  - $y_{max}$ is the position of the center of the yo-yo at the top of its path. This is where the yo-yo starts at $t=0$
  - $y_{min}$ is the position of the center of the yo-yo at the bottom of its path. This is where the yo-yo sits as it "sleeps"
  - $g$ is the acceleration due to gravity
  - $l$ is the total length of the yo-yo string, including the wraps around the "finger" and the central axis of the yo-yo. That is, $l=(2 \pi r_{1})+\frac{1}{2}(2 \pi r_{1})+(2 \pi r_{2})+d$
    - $(2 \pi r_{1})$ is the circumference of the "finger" cylinder
    - $frac{1}{2}(2 \pi r_{1})$ is used to account for the half wrap around the finger that arises from the slip knot style of the top of the yo-yo string
    - $(2 \pi r_{2})$ is the circumference of the central shaft of the yo-yo
    - $d$ is the length of yo-yo string between $y=0$ and the top of the central shaft of the yo-yo
