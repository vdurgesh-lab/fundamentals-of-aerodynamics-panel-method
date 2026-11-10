# The Panel Method: Interactive Class Lecture

**Fundamentals of Aerodynamics · Class lecture material · For classroom teaching only**

> This repository hosts an interactive, step-by-step animation used in class to teach the
> source and vortex panel methods. It is provided for classroom teaching only. It is not a
> design tool and has not been validated for engineering use.

**Open the lecture:** https://vdurgesh-lab.github.io/fundamentals-of-aerodynamics-panel-method/

---

## What the lecture covers

The page walks through the panel method in ten steps. Each step has an animation, short
narration, the governing equation, and a "pause and think" question for discussion.

| Step | Topic | What students see |
|---|---|---|
| 1 | The problem | A uniform flow passes through a body; the no-penetration condition **V · n = 0** |
| 2 | Source sheet | Building a source sheet of strength λ(s) from individual line sources |
| 3 | Panels | Replacing the surface with straight panels and control points |
| 4 | Boundary condition | Splitting V∞ at control point 4 of the cylinder; V∞,n + Vn = 0 (Eq. 3.151) |
| 5 | Influence | Influence coefficients I₄,ⱼ and the row equation for panel 4 (Eq. 3.164) |
| 6 | Equations | The 8 × 8 matrix, and all **8 equations written out and solved simultaneously** |
| 7 | Solve | Raising λ to the solution, the flow closing around the body, and Σλⱼ Sⱼ = 0 |
| 8 | Pressure | Surface velocity and Cp compared with the exact cylinder result |
| 9 | Lift | Vortex panels, the Kutta condition, circulation and lift on an airfoil |
| 10 | Try it | Choose a shape, panel type, number of panels and angle of attack |

All numbers and curves are computed by a panel solver that runs in the page. Its 8-panel
cylinder results reproduce Anderson's Example 3.19, including the influence coefficients
and the table of source strengths.

## Using it in class

- Space plays or pauses; the left and right arrow keys change step.
- Link directly to a step by adding `#step-N` to the address, for example
  `.../#step-6` opens the 8 simultaneous equations.
- The page works in any modern browser, on a projector, laptop or phone, in light or dark mode.
- To run it offline, download `index.html` and open it in a browser.

## Source

- J. D. Anderson, Jr., *Fundamentals of Aerodynamics*, McGraw-Hill, Section 3.17 and Example 3.19.

No text or figures are reproduced from this source. Equation numbers refer to Anderson so
students can follow along in the textbook.

## Terms of use

This material was prepared by Vibhav Durgesh for teaching the Fundamentals of Aerodynamics
course. It is shared for classroom teaching and personal study only. Please contact the author
before reusing or redistributing it for any other purpose.
