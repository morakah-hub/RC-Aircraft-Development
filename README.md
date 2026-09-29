# RC Aircraft Development
 
Six planes I built before starting [AWRAS](https://github.com/morakah-hub/AWRAS-1.0). The first five crashed or never got off the ground, and each one showed me what to fix in the next.
 
All six were built from foamboard, with no kits. I designed parts like the wheels and mounts in CAD and 3D printed them.
 
**Each plane has a Google Drive link with photos and flight videos. Click through to see the actual aircraft.**
 
| # | Aircraft | Result |
|---|---|---|
| 1 | Delta canard, rear pusher | Never flew |
| 2 | Tailless, three-fin landing gear | Got airborne, flipped, crashed |
| 3 | Flying wing (V1, V2) | V1 stalled at launch; V2 flew ~3 s |
| 4 | Conventional T-tail | Tail collapsed on takeoff roll |
| 5 | Conventional rebuild | Flew ~30–40 s |
| 6 | Small trainer | Took off, flew, and landed |
 
## Plane 1: Delta Canard
 
My first full build, with the airframe, motor, controls, FPV camera, and landing gear all on one plane. The foam landing gear kept breaking on takeoff. I took it off and hand-launched the plane instead, but it still couldn't fly because the motor didn't give enough thrust for its weight.
 
**Lesson:** Check thrust-to-weight before building. Every system you add makes the plane heavier.
 
[Photos & videos](https://drive.google.com/drive/folders/1VOr5R7L0C-D3P6gKFdMUMwoOVN3ra7kY?usp=sharing)
 
## Plane 2: Simplified Tailless
 
A lighter, tailless version of Plane 1. It got off the ground, then flipped and crashed almost right away. The causes were low thrust-to-weight again, plus the landing gear: three long fins with printed PETG wheels. The video of this one was lost.
 
**Lesson:** Landing gear shape affects how a plane flies, not just how it rolls on the ground. After failing on thrust twice, I made thrust-to-weight a required check.
 
[Photos](https://drive.google.com/drive/folders/1v9wBFDzPWr2t_yl_6g1mXgYAeFedf6Hl?usp=sharing)
 
## Plane 3: Flying Wing (V1 & V2)
 
V1 failed at launch because I placed the center of gravity (CG) where I would on a normal plane, and that's wrong for a flying wing. V2 fixed the CG and added landing gear and an electronics bay. It took off but crashed after about 3 seconds. The controls were too sensitive, and I was still learning to fly.
 
**Lesson:** Flying wings need their own CG and stability math. Control sensitivity needs tuning before the first flight.
 
[Photos & videos](https://drive.google.com/drive/folders/15bA6EiIgdRn3G_mqOZVnDV85EYeRiox4?usp=sharing)
 
## Plane 4: Conventional T-Tail
 
I switched to a normal layout with a fuselage, ailerons, elevator, rudder, a ~1.2 m wingspan, and aluminum landing gear. Vibration from the runway collapsed the T-tail before the plane left the ground.
 
**Lesson:** The tail has to handle vibration and ground loads, not just flight loads.
 
[Photos & videos](https://drive.google.com/drive/folders/16gl0GJUmX5MUpb61wPt7LlrZiTKaj13G?usp=sharing)
 
## Plane 5: Conventional Rebuild
 
The first attempt reused Plane 4's motor and ESC with a 4S battery. The motor wasn't built for that voltage, so it failed. The second attempt used a SunnySky motor with matching electronics. It flew for 30–40 seconds, then crashed after I lost track of which way it was facing.
 
**Lesson:** Motor, ESC, battery, and prop have to be chosen together. This was also the first proof the design could fly.
 
[Photos & videos](https://drive.google.com/drive/folders/1PiaJzF-f68qz-FpzUVIke0YkvXnuFelq?usp=sharing)
 
## Plane 6: Simple Trainer
 
A smaller, cleaner version of Plane 5 that I built with another student at the university makerspace. It was hand-launched, flew, and landed in one piece. That made it the first full flight of the program.
 
**Lesson:** Better build quality and a simpler design made it much easier to get right.
 
[Photos & videos](https://drive.google.com/drive/folders/1gODa4EXehjri_2UhR_syTH68Lbv6_FR1?usp=sharing)
 
## What carried into AWRAS
 
- **Planes 1–2 (thrust):** thrust and thrust-to-weight estimates before building
- **Plane 3 (CG):** a formal MAC/CG analysis
- **Plane 5 (power system):** a throttle limit and planned thrust-stand testing
- **Plane 6 (build quality):** calibrating prints before printing parts
**Current project: [AWRAS](https://github.com/morakah-hub/AWRAS-1.0)**
 
