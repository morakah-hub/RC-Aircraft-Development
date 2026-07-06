# RC Aircraft Development

**An iterative fixed-wing development program — six scratch-built aircraft, failures documented, leading to the [LWPLA Aircraft](https://github.com/morakah-hub/LWPLA-Aircraft) project.**

Each aircraft was designed and built to answer questions raised by the previous one. All airframes were scratch-built from foamboard, with custom parts (wheels, mounts) designed in CAD and 3D printed — no kits. Photos and flight videos are hosted in Google Drive galleries, linked per aircraft.

---

## Program Overview

| # | Aircraft | Configuration | Outcome |
|---|---|---|---|
| 1 | Delta Canard | Delta wing + canard, rear pusher | ❌ Never airborne |
| 2 | Flying Wing | Lightweight foamboard flying wing | ✅ Flew — later lost in a crash |
| 3 | Flying Wing (V1 & V2) | Hand-launch flying wing, two iterations | ⚠️ V1 stalled at launch; V2 flew ~1 circuit |
| 4 | Conventional T-Tail | Fuselage, T-tail, full 3-axis control | ⚠️ ~30 s sustained flight |
| 5 | Conventional Aircraft | Refined conventional, hand launch | ✅ Successful takeoff and landing |
| 6 | Simple Trainer | *(details to be added)* | *(to be added)* |

---

## ✈️ Plane 1 — Delta Canard

**Objective:** First ground-up build — integrate airframe, propulsion, controls, FPV, and landing gear into one aircraft.

**Outcome:** ❌ Never became airborne. Too heavy, wing loading too high, and the foam landing gear failed repeatedly before takeoff speed.

**Key lessons:**
- Wing loading limits come before features
- Landing gear must survive repeated takeoff attempts
- Electronics packaging and mechanical integration add weight fast

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1VOr5R7L0C-D3P6gKFdMUMwoOVN3ra7kY?usp=sharing)

---

## ✈️ Plane 2 — Flying Wing

**Objective:** Cut the weight and complexity of Plane 1 and achieve flight.

**Outcome:** ✅ First successful flight of the program. Later lost in a crash; flight footage was lost with it.

**Key lessons:**
- Simplicity improves reliability
- Weight reduction matters more than features
- Construction methods validated for later builds

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1v9wBFDzPWr2t_yl_6g1mXgYAeFedf6Hl?usp=sharing)

---

## ✈️ Plane 3 — Flying Wing (Version 1 & Version 2)

**Objective:** Develop the flying-wing configuration through deliberate iteration.

**Outcome:** ⚠️ V1 stalled immediately after launch — CG was set with conventional-aircraft intuition, which does not apply to tailless aircraft. V2 (corrected CG, electronics bay, landing gear) took off and completed about one circuit before crashing.

**Key lessons:**
- Flying-wing CG and stability are a separate discipline — the direct reason the LWPLA project starts with a formal MAC/CG analysis
- Control surface sensitivity needs tuning before flight
- A flyable aircraft can still be lost to pilot experience

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/15bA6EiIgdRn3G_mqOZVnDV85EYeRiox4?usp=sharing)

---

## ✈️ Plane 4 — Conventional T-Tail

**Objective:** Move to a conventional layout with full three-axis control.

**Outcome:** ⚠️ Attempt 1: runway vibration broke the T-tail before takeoff. Attempt 2: a 4S battery on a lower-voltage power system killed the motor. Attempt 3 (SunnySky motors): ~30 seconds of sustained flight, then crashed after flying too far to maintain visual orientation.

**Key lessons:**
- Structural vibration is a real failure mode
- Power systems must be matched as a system, not upgraded one part at a time
- Pilot orientation and confidence are part of the engineering problem

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/16gl0GJUmX5MUpb61wPt7LlrZiTKaj13G?usp=sharing)

---

## ✈️ Plane 5 — Conventional Aircraft

**Objective:** Refine the Plane 4 design with better construction quality and a simpler operating concept.

**Outcome:** ✅ Successful takeoff and landing — the most successful completed aircraft of the program. Built at the university makerspace with another student; hand-launched to remove landing gear from the takeoff problem.

**Key lessons:**
- Better manufacturing improves repeatability
- Simpler designs are easier to validate
- Full flight cycle (takeoff → flight → landing) achieved

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1PiaJzF-f68qz-FpzUVIke0YkvXnuFelq?usp=sharing)

---

## ✈️ Plane 6 — Simple Trainer

**Objective:** *(to be added)*

**Outcome:** *(to be added)*

**Key lessons:**
- *(to be added)*

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1gODa4EXehjri_2UhR_syTH68Lbv6_FR1?usp=sharing)

---

## Engineering Progression

```
Plane 1 — Delta Canard        →  wing loading, landing-gear strength
Plane 2 — Flying Wing         →  lightweight construction, first flight
Plane 3 — Flying Wing V1/V2   →  flying-wing CG & stability
Plane 4 — Conventional T-Tail →  structures, power matching, sustained flight
Plane 5 — Conventional        →  manufacturing quality, full flight cycle
Plane 6 — Simple Trainer      →  (in progress)
LWPLA Aircraft                →  all lessons applied through a formal
                                 engineering workflow
```

Specific carryovers: Plane 3's CG failure became LWPLA's MAC/CG analysis. Plane 4's power-system failure became LWPLA's throttle-limit constraint and planned thrust-stand testing. Plane 5's manufacturing lesson became LWPLA's print-calibration-first approach.

➡️ **Current project: [LWPLA Aircraft](https://github.com/morakah-hub/LWPLA-Aircraft)**
