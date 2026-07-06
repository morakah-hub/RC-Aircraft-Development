# RC Aircraft Development

**An iterative fixed-wing development program — six aircraft, documented failures included, leading to the [LWPLA Aircraft](https://github.com/morakah-hub/LWPLA-Aircraft) project.**

---

This repository is not a collection of six unrelated airplanes. It is an engineering logbook: each aircraft was designed, built, and flown (or failed to fly) to answer questions raised by the one before it. Every airframe was scratch-built — primarily foamboard, hot glue, and tape — with custom components such as wheels and mounts designed in CAD and 3D printed. No kits.

The failures are documented as thoroughly as the successes, because they carried most of the learning. The lessons accumulated here — wing loading, CG placement on tailless aircraft, structural vibration, power-system matching — are applied directly in the [LWPLA flying-wing UAV](https://github.com/morakah-hub/LWPLA-Aircraft), where this iterative approach was upgraded to a full engineering workflow with published analysis.

📷 Photos and flight videos are hosted in Google Drive galleries (linked per aircraft below) while this repository is being migrated.

---

## Program Overview

| # | Aircraft | Configuration | Outcome |
|---|---|---|---|
| 1 | Delta Canard | Delta wing + canard, rear pusher | ❌ Never airborne — overweight, landing gear failures |
| 2 | Flying Wing | Lightweight foamboard flying wing | ✅ Flew — later crashed and destroyed |
| 3 | Flying Wing (V1 & V2) | Hand-launch flying wing, two iterations | ⚠️ V1 stalled on launch (CG); V2 flew ~1 circuit, then crashed |
| 4 | Conventional T-Tail | Fuselage, T-tail, ailerons, 3 attempts | ⚠️ ~30 s sustained flight, lost to orientation |
| 5 | Conventional Aircraft | Refined smaller conventional, hand launch | ✅ Successful takeoff **and** landing |
| 6 | Simple Trainer | *(details to be added)* | *(to be added)* |

---

## ✈️ Plane 1 — Delta Canard

**Objective:** First ground-up aircraft design — integrate an airframe, propulsion, control surfaces, FPV, and landing gear into one working system.

**Configuration:**
- Delta wing with canard configuration
- Single rear-mounted pusher motor
- Three servos; two linked front fins for pitch control, rear control surfaces, no rudder
- Independent FPV camera with its own battery and video transmitter
- Foamboard airframe with foam landing gear
- Custom CAD-designed landing wheels, printed in PETG with ball bearings

**Outcome:** ❌ Never became airborne. The aircraft was too heavy, wing loading was too high, and the foam landing gear repeatedly failed before takeoff speed could be reached.

**What I learned:** 🔧 Wing loading limits, structural design, landing-gear strength, mechanical integration, and electronics packaging. Ambition has to be paid for in grams.

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1VOr5R7L0C-D3P6gKFdMUMwoOVN3ra7kY?usp=sharing)

---

## ✈️ Plane 2 — Flying Wing

**Objective:** Cut the complexity and weight of Plane 1 and build something that actually flies.

**Configuration:**
- Flying-wing layout
- Lightweight foamboard construction
- Homemade landing gear with CAD-designed printed wheels
- Simplified electronics — FPV camera removed

**Outcome:** ✅ Flew successfully — the program's first flight. The aircraft was later lost in a crash, and the flight footage was unfortunately lost with it.

**What I learned:** 🔧 Simplicity improves reliability, weight reduction matters more than features, and a successful flight validated the construction methods used across the rest of the program.

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1v9wBFDzPWr2t_yl_6g1mXgYAeFedf6Hl?usp=sharing)

---

## ✈️ Plane 3 — Flying Wing (Version 1 & Version 2)

**Objective:** Develop the flying-wing configuration properly across deliberate iterations.

### Version 1

**Configuration:** Minimal hand-launched flying wing — no dedicated electronics bay, no landing gear.

**Outcome:** ❌ Stalled immediately after launch. The CG was placed using conventional-aircraft intuition; a tailless aircraft demands a fundamentally different CG philosophy. The aircraft pitched up, stalled, and impacted the ground.

### Version 2

**Configuration changes:** Corrected CG, added an electronics compartment, landing gear, and improved structure.

**Outcome:** ⚠️ Took off successfully and completed roughly one circuit before crashing — attributed to a combination of pilot experience, remaining CG imperfection, and overly sensitive control surfaces.

**What I learned:** 🔧 Flying-wing stability is its own discipline — this failure is the direct reason the LWPLA project begins with a formal MAC/CG analysis before anything is printed. Also: a flyable aircraft can still be lost to control tuning and pilot limitations.

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/15bA6EiIgdRn3G_mqOZVnDV85EYeRiox4?usp=sharing)

---

## ✈️ Plane 4 — Conventional T-Tail

**Objective:** Move to a conventional layout with full three-axis control.

**Configuration:**
- Conventional fuselage with T-tail
- Rudder, elevator, and ailerons
- Larger wingspan
- Proper landing gear

**Outcome — three attempts:**

| Attempt | Result |
|---|---|
| 1 | ❌ Runway vibration broke the T-tail structure before takeoff |
| 2 | ❌ Switched to a 4S battery on a power system designed for lower voltage — motor failed |
| 3 | ⚠️ Installed SunnySky motors — sustained powered flight for ~30 seconds, then crashed after flying too far to maintain visual orientation |

**What I learned:** 🔧 Structural vibration is a real failure mode, power systems must be matched as a system (not upgraded one component at a time), and pilot factors — confidence and orientation — are part of the engineering problem.

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/16gl0GJUmX5MUpb61wPt7LlrZiTKaj13G?usp=sharing)

---

## ✈️ Plane 5 — Conventional Aircraft

**Objective:** Refine the Plane 4 design with better tools, better construction quality, and a simpler operating concept.

**Configuration:**
- Smaller, refined version of the Plane 4 conventional layout
- Built at the university makerspace, in collaboration with another student
- Hand-launched — landing gear complexity removed from the takeoff problem

**Outcome:** ✅ Successful takeoff **and** successful landing — the most successful completed aircraft of the program.

**What I learned:** 🔧 Better manufacturing improves repeatability, and simpler designs are easier to validate. This aircraft closed the loop: the program could now reliably produce an aircraft that flies and comes back.

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1PiaJzF-f68qz-FpzUVIke0YkvXnuFelq?usp=sharing)

---

## ✈️ Plane 6 — Simple Trainer

**Objective:** *(to be added)*

**Configuration:** *(to be added)*

**Outcome:** *(to be added)*

**What I learned:** *(to be added)*

[![Photos & Flight Videos](https://img.shields.io/badge/📁_Photos_&_Flight_Videos-Google_Drive-4285F4?logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1gODa4EXehjri_2UhR_syTH68Lbv6_FR1?usp=sharing)

---

## Engineering Progression

Each aircraft existed to answer the question raised by the previous one:

```
Plane 1 — Delta Canard
   ↓  wing loading, landing-gear strength, integration
Plane 2 — Flying Wing
   ↓  lightweight construction, first successful flight
Plane 3 — Flying Wing V1 & V2
   ↓  flying-wing CG & stability, control tuning
Plane 4 — Conventional T-Tail
   ↓  structures, power-system matching, sustained flight
Plane 5 — Conventional Aircraft
   ↓  manufacturing quality, full flight cycle validated
Plane 6 — Simple Trainer
   ↓  (in progress)
LWPLA Aircraft
   →  all of the above, applied through a formal engineering
      workflow: published aerodynamic analysis, CG derivation,
      performance prediction, and structured flight testing
```

The through-line: every hard lesson here became a design requirement there. The CG failure of Plane 3 became LWPLA's MAC analysis. The power-system failure of Plane 4 became LWPLA's throttle-limit constraint and planned thrust-stand testing. The manufacturing lesson of Plane 5 became LWPLA's print-calibration-first approach.

➡️ **Continue to the current project: [LWPLA Aircraft](https://github.com/morakah-hub/LWPLA-Aircraft)**
