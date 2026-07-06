# RC Aircraft Development

**An iterative fixed-wing development program — six scratch-built aircraft, failures documented, leading to the [LWPLA Aircraft](https://github.com/morakah-hub/LWPLA-Aircraft) project.**

Each aircraft was designed and built to answer questions raised by the previous one. All airframes were scratch-built from foamboard, with custom parts (wheels, mounts) designed in CAD and 3D printed — no kits. Photos and flight videos are hosted in Google Drive galleries, linked per aircraft.

---

## Program Overview

| # | Aircraft | Configuration | Outcome |
|---|---|---|---|
| 1 | Delta Canard | Delta wing + canard, rear pusher | ❌ Never airborne |
| 2 | Simplified Tailless | Tailless, three-fin landing gear | ❌ Briefly airborne, flipped and crashed |
| 3 | Flying Wing (V1 & V2) | Hand-launch flying wing, two iterations | ⚠️ V1 stalled at launch; V2 flew ~3 s |
| 4 | Conventional T-Tail | Fuselage, T-tail, full 3-axis control | ❌ Never flew — T-tail collapsed on takeoff roll |
| 5 | Conventional Aircraft | Rebuilt conventional, two attempts | ⚠️ ~30–40 s sustained flight |
| 6 | Simple Trainer | Smaller version of Plane 5, hand launch | ✅ Successful takeoff, flight, and landing |

---

## ✈️ Plane 1 — Delta Canard

**Objective:** First ground-up build — integrate airframe, propulsion, controls, FPV, and landing gear into one aircraft.

**Outcome:** ❌ Never became airborne. The foam landing gear repeatedly broke during takeoff attempts; the gear was then removed and the aircraft hand-launched, but it still failed to fly due to a poor thrust-to-weight ratio.

**Key lessons:**
- Wing loading limits come before features
- Thrust-to-weight ratio must be checked before building, not after
- Landing gear must survive repeated takeoff attempts
- Systems integration adds weight fast

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1VOr5R7L0C-D3P6gKFdMUMwoOVN3ra7kY?usp=sharing)

---

## ✈️ Plane 2 — Simplified Tailless

**Objective:** Simplify Plane 1 into a lighter tailless aircraft that can get airborne.

**Outcome:** ❌ Briefly became airborne, then flipped and crashed almost immediately — a combination of poor thrust-to-weight ratio and the unusual landing gear geometry (three long downward fins with custom PETG wheels). Phone footage of the attempt was later lost.

**Key lessons:**
- Landing gear geometry affects flight, not just ground handling
- Thrust-to-weight ratio again — the same failure mode twice made it a permanent design check
- Simplifying a design is not enough on its own

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1v9wBFDzPWr2t_yl_6g1mXgYAeFedf6Hl?usp=sharing)

---

## ✈️ Plane 3 — Flying Wing (Version 1 & Version 2)

**Objective:** Develop the flying-wing configuration through deliberate iteration.

**Outcome:** ⚠️ V1, a minimal hand-launched flying wing, failed immediately — the CG was placed using conventional-aircraft intuition, which does not apply to tailless aircraft. V2 (corrected CG, landing gear, electronics compartment) took off but flew only about three seconds before crashing, primarily due to pilot experience and overly sensitive controls.

**Key lessons:**
- Flying-wing CG and stability are a separate discipline — the direct reason the LWPLA project starts with a formal MAC/CG analysis
- Control surface sensitivity needs tuning before flight
- A flyable aircraft can still be lost to pilot experience

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/15bA6EiIgdRn3G_mqOZVnDV85EYeRiox4?usp=sharing)

---

## ✈️ Plane 4 — Conventional T-Tail

**Objective:** Move to a conventional layout with full three-axis control.

**Outcome:** ❌ Never flew. Runway vibration caused the T-tail to collapse during the takeoff roll. Configuration: conventional fuselage with rudder, elevator, and ailerons, ~1.2 m wingspan, aluminum landing gear, and a camera installed but never used.

**Key lessons:**
- Structural vibration is a real failure mode
- Tail structures need reinforcement for ground loads, not just flight loads

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/16gl0GJUmX5MUpb61wPt7LlrZiTKaj13G?usp=sharing)

---

## ✈️ Plane 5 — Conventional Aircraft

**Objective:** Rebuild the conventional design and achieve sustained flight.

**Outcome:** ⚠️ Attempt 1 reused the Plane 4 motor and ESC with a 4S battery — the motor failed because the power system was not designed for that voltage. Attempt 2, with SunnySky motors and appropriate electronics, flew successfully for about 30–40 seconds before crashing after visual orientation was lost.

**Key lessons:**
- Power systems must be matched as a system, not upgraded one part at a time
- Pilot orientation is part of the engineering problem
- The overall aircraft design was validated in sustained flight

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1PiaJzF-f68qz-FpzUVIke0YkvXnuFelq?usp=sharing)

---

## ✈️ Plane 6 — Simple Trainer

**Objective:** Refine the Plane 5 design into a smaller, higher-quality build and complete a full flight cycle.

**Outcome:** ✅ Successful takeoff, flight, and landing — the most successful completed aircraft of the program. Built at the university makerspace with another student; hand-launched.

**Key lessons:**
- Better manufacturing improves repeatability
- Simpler designs are easier to validate
- Full flight cycle (takeoff → flight → landing) achieved

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1gODa4EXehjri_2UhR_syTH68Lbv6_FR1?usp=sharing)

---

## Engineering Progression

```
Plane 1 — Delta Canard        →  wing loading, thrust-to-weight, landing gear
Plane 2 — Simplified Tailless →  landing gear geometry, T/W confirmed as a design check
Plane 3 — Flying Wing V1/V2   →  flying-wing CG & stability
Plane 4 — Conventional T-Tail →  structural vibration, tail reinforcement
Plane 5 — Conventional        →  power-system matching, sustained flight
Plane 6 — Simple Trainer      →  manufacturing quality, full flight cycle
LWPLA Aircraft                →  all lessons applied through a formal
                                 engineering workflow
```

Specific carryovers: the thrust-to-weight failures of Planes 1–2 became LWPLA's published thrust and T/W estimation. Plane 3's CG failure became LWPLA's MAC/CG analysis. Plane 5's power-system failure became LWPLA's throttle-limit constraint and planned thrust-stand testing. Plane 6's manufacturing lesson became LWPLA's print-calibration-first approach.

➡️ **Current project: [LWPLA Aircraft](https://github.com/morakah-hub/LWPLA-Aircraft)**
Specific carryovers: Plane 3's CG failure became LWPLA's MAC/CG analysis. Plane 4's power-system failure became LWPLA's throttle-limit constraint and planned thrust-stand testing. Plane 5's manufacturing lesson became LWPLA's print-calibration-first approach.

