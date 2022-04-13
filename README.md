**Voron Stealthburner Beta**
----------------------------

---

- [Introduction](#introduction)
- [Filename Nomenclature](#filename-nomenclature)
- [CHANGE LOG: *(Detailing significant changes)*](#change-log-detailing-significant-changes)
  - [2022-04-09 - Stealthburner Toolhead updates and CW2 Bells and Whistles #112](#2022-04-09---stealthburner-toolhead-updates-and-cw2-bells-and-whistles-112)
  - [2022-04-01 - Stealthburner Upgrades and Toolhead Changes #109](#2022-04-01---stealthburner-upgrades-and-toolhead-changes-109)
  - [2022-03-28 - CW2 Holes Patched and Other Body Tweaks #106](#2022-03-28---cw2-holes-patched-and-other-body-tweaks-106)
  - [2022-03-14 - Guidler Pivot Relocation #104](#2022-03-14---guidler-pivot-relocation-104)
  - [2022-03-04 - Added cable-management to ADXL sensor mounts #103](#2022-03-04---added-cable-management-to-adxl-sensor-mounts-103)
  - [2022-02-24 - CW2 Extruder Gear Mesh Adjustment Screw #100](#2022-02-24---cw2-extruder-gear-mesh-adjustment-screw-100)
  - [2022-02-18 - Clockwork 2 body and latch updates #93](#2022-02-18---clockwork-2-body-and-latch-updates-93)
  - [2022-02-14 - BMO and BMS toolhead patch #89](#2022-02-14---bmo-and-bms-toolhead-patch-89)
  - [2022-02-14 - Minor adjustments to ADXL mounts #88](#2022-02-14---minor-adjustments-to-adxl-mounts-88)
  - [2022-02-14 - Stealthburner ADXL Support and toolhead updates #86](#2022-02-14---stealthburner-adxl-support-and-toolhead-updates-86)
  - [2022-02-01 - Revised stealthburner_leds.cfg #80](#2022-02-01---revised-stealthburner_ledscfg-80)
  - [2022-02-01 - Stealthburner diffuser and mask updates #79](#2022-02-01---stealthburner-diffuser-and-mask-updates-79)
  - [2022-01-27 - Major updates for Stealthburner #76](#2022-01-27---major-updates-for-stealthburner-76)
  - [2022-01-27 - Corrected missing hole-bridge feature on main_body #75](#2022-01-27---corrected-missing-hole-bridge-feature-on-main_body-75)
  - [2022-01-27 - Corrected tiny unwanted artifact on motor plate #74](#2022-01-27---corrected-tiny-unwanted-artifact-on-motor-plate-74)
  - [2022-01-27 - Clockwork2 Updates focusing on filament tension and design finesse #73](#2022-01-27---clockwork2-updates-focusing-on-filament-tension-and-design-finesse-73)
  - [2022-01-20  - Set initial_RED to 1 #70](#2022-01-20----set-initial_red-to-1-70)
  - [2022-01-16 - Clockwork2 updates #67](#2022-01-16---clockwork2-updates-67)
  - [2022-01-14 - Small fixes for Dragon and Rapido TH #63](#2022-01-14---small-fixes-for-dragon-and-rapido-th-63)
  - [2022-01-14 - Toolhead updates #61](#2022-01-14---toolhead-updates-61)
  - [2022-01-06 - Stealthburner fan cutout updates and toolhead changes #53](#2022-01-06---stealthburner-fan-cutout-updates-and-toolhead-changes-53)
  - [2021-12-29 - Repaired missing features in Guidler and Motor Plate #41](#2021-12-29---repaired-missing-features-in-guidler-and-motor-plate-41)
  - [2021-12-29 - Made adjustments to V6/R6 Toolhead #39](#2021-12-29---made-adjustments-to-v6r6-toolhead-39)
  - [2021-12-29 - Stealthburner updates, CW2 adjustments, chain anchors, Phaetus fixes #38](#2021-12-29---stealthburner-updates-cw2-adjustments-chain-anchors-phaetus-fixes-38)
  - [2021-12-27 - Corrected CW2 filament path #23](#2021-12-27---corrected-cw2-filament-path-23)
  - [2021-12-24 - Sb betaupdate1 #21](#2021-12-24---sb-betaupdate1-21)
    <br>

# Introduction

This marks the beta release of the next generation of the Voron Afterburner: Stealthburner

As with any beta release, the provided STLs and manuals are not final, and we ask the community to provide feedback in the `#stealthburner_beta`  channel on our discord server.

![image](https://user-images.githubusercontent.com/4352664/147270796-57a92610-b85f-49b1-8e2a-21ffb9f59b06.png)
<br>
![Voron Logo](http://vorondesign.com/images/voron_design_logo.png)

<br>

# Filename Nomenclature

`_____.stl` -> Base color<br>
`[a]-*.stl` ->  Accent color<br>
`[o]-*.stl` ->  Opaque (light doesn't penetrate)<br>
`[c]-*.stl` ->  Clear/Translucent (light can penetrate)<br>
`*-cw1.stl` ->  Clockwork1 Version<br>
`*-cw2.stl` ->  Clockwork2 Version<br>

# CHANGE LOG: *(Detailing significant changes)*

<br>

## 2022-04-09 - Stealthburner Toolhead updates and CW2 Bells and Whistles [#112](https://github.com/VoronDesign/Voron-Afterburner/pull/112)

**Affected Files:**<br>

\+`Clockwork2/cable_door-beta2.stl`<br>
\+`Clockwork2/chain_anchor_2hole-beta2.stl`<br>
\+`Clockwork2/chain_anchor_2hole-SW-beta1.stl`<br>
\+`Clockwork2/chain_anchor_3hole-beta2.stl`<br>
\+`Clockwork2/chain_anchor_3hole-SW-beta1.stl`<br>
\+`Clockwork2/main_body-beta11.stl`<br>
\+`Clockwork2/motor_plate-beta10.stl`<br>
\+`Stealthburner/[a]_stealthburner_main_body_beta7.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta4.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta4.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta6.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta6.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta6.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta6.stl`<br>
\+`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta5.stl`<br>
\+`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta4.stl`<br>
\+`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta4.stl`<br>
\+`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta5.stl`<br>
\+`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta5.stl`<br>
\+`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta3.stl`<br>
\+`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta3.stl`<br>
\+`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw1-beta6.stl`<br>
\+`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw2-beta6.stl`<br>
\+`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-front-beta2.stl`<br>
\+`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw1-beta2.stl`<br>
\+`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw2-beta2.stl`<br>


\-`Clockwork2/cable_door-beta1.stl`<br>
\-`Clockwork2/chain_anchor_2hole-beta1.stl`<br>
\-`Clockwork2/chain_anchor_2hole-SW-beta0.stl`<br>
\-`Clockwork2/chain_anchor_3hole-beta1.stl`<br>
\-`Clockwork2/chain_anchor_3hole-SW-beta0.stl`<br>
\-`Clockwork2/main_body-beta10.stl`<br>
\-`Clockwork2/motor_plate-beta9.stl`<br>
\-`Stealthburner/[a]_stealthburner_main_body_beta6.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta3.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta3.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta5.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta5.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta5.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta5.stl`<br>
\-`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta4.stl`<br>
\-`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta3.stl`<br>
\-`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta3.stl`<br>
\-`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta4.stl`<br>
\-`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta4.stl`<br>
\-`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta2.stl`<br>
\-`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta2.stl`<br>
\-`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw1-beta5.stl`<br>
\-`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw2-beta5.stl`<br>
\-`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-front-beta1.stl`<br>
\-`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw1-beta1.stl`<br>
\-`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw2-beta1.stl`<br>


> **Major Changes**
>
> * Fixed thin-wall issue on Stealthburner 'Main Body' lower mounting holes (Thanks str1pes!)
> * Added a straight bridging feature to the 5015 fan retainer spring on `Main Body` to improve printability
> * Revised `Cable Cover` to have more material around the pivot bolt to prevent cracking
> * Made `Cable Cover` pivot bolt hole 1mm deeper to give more clearance for pivot bolt
> * Added additional material to mounting bolt location of `Cable Cover` to reduce cracking
> * Removed material on `Motor Plate` to accomodate for `Cable Cover` additional thickness
> * Added zip-tie slots to all `Cable Chain Anchor` parts
> * Slightly revised the shape of 50mm bolt extraction feature on all `Toohead Rear`
> * Fixed hole size for 2 heatsets in `Dragon Toolhead Front`


![image1](https://user-images.githubusercontent.com/34219833/162587749-2e3d525c-64d0-4e06-9c35-b74813c168c5.png)

![image2](https://user-images.githubusercontent.com/34219833/162587750-4d22b514-9211-4a3a-be4e-86990780bb2d.png)

![image3](https://user-images.githubusercontent.com/34219833/162587754-4a28b10b-25d2-429c-908a-8d10f8db2fd2.png)

![image4](https://user-images.githubusercontent.com/34219833/162587756-af11ec2e-5a64-4a1d-bbe0-8581b3ccd3a4.png)

![image5](https://user-images.githubusercontent.com/34219833/162587763-eedce323-635d-41aa-8fc5-bf288725c29a.png)


<br>


## 2022-04-01 - Stealthburner Upgrades and Toolhead Changes [#109](https://github.com/VoronDesign/Voron-Afterburner/pull/109)

**Affected Files:**<br>

\+`Clockwork2/motor_plate-beta9.stl`<br>
\+`Stealthburner/[a]_stealthburner_main_body_beta6.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta4.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta3.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta3.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-front-beta4.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta5.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta5.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-front-beta4.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta5.stl`<br>
\+`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta5.stl`<br>
\+`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta4.stl`<br>
\+`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta3.stl`<br>
\+`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta3.stl`<br>
\+`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta6.stl`<br>
\+`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta4.stl`<br>
\+`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta4.stl`<br>
\+`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-front-beta3.stl`<br>
\+`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta2.stl`<br>
\+`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta2.stl`<br>
\+`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-front-beta4.stl`<br>
\+`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw1-beta5.stl`<br>
\+`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw2-beta5.stl`<br>
\+`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-front-beta1.stl`<br>
\+`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw1-beta1.stl`<br>
\+`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw2-beta1.stl`<br>

\-`Clockwork2/motor_plate-beta8.stl`<br>
\-`Stealthburner/[a]_stealthburner_main_body_beta5.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta3.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta2.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta2.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-front-beta3.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta4.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta4.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-front-beta3.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta4.stl`<br>
\-`Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta4.stl`<br>
\-`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta3.stl`<br>
\-`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta2.stl`<br>
\-`Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta2.stl`<br>
\-`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta5.stl`<br>
\-`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta3.stl`<br>
\-`Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta3.stl`<br>
\-`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-front-beta2.stl`<br>
\-`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta1.stl`<br>
\-`Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta1.stl`<br>
\-`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-front-beta3.stl`<br>
\-`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw1-beta4.stl`<br>
\-`Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw2-beta4.stl`<br>
\-`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-front-beta0.stl`<br>
\-`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw1-beta0.stl`<br>
\-`Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw2-beta0.stl`<br>


> This update is a lot of little QOL changes for Stealthburner and its toolheads.
>
> **Major Changes**
>
> * Beefed up the lower nozzle LED wiring retainers on `Main Body` and added a larger gap.
> * Removed intermediate wiring retainer beside 4010 fan which was too tricky to use well.
> * Increased the spacing between tabs on the nozzle LED wiring retainers at the top of the 4010 fan to make getting the wires in easier.
> * Repositioned the nozzle LEDs slightly to give more clearance to toolheads.
> * Tweaked the nozzle LED retainers slightly.
> * Repaired issues on `Main Body` when "Thin Wall Detection" is not used.
> * Revised 50mm bolt-extractor feature on ALL toolheads (why are there so many hotends???)
> * Added anti-rattle feature to upper wire retainer on `Main Body`
> * Added missing hole-bridge feature in `Motor Plate`
> * Reworked area around heatset for revised guidler pivot on `Motor Plate` to eliminate hot-goo squish-out that could catch on 50T gear.

![image](https://user-images.githubusercontent.com/34219833/161367510-a0a7d586-3043-4627-8e6d-776e81126402.png)

![image](https://user-images.githubusercontent.com/34219833/161367520-ebb43b14-09e5-4b88-81b7-5f60c807ef09.png)

![image](https://user-images.githubusercontent.com/34219833/161367523-c52c27a1-bf11-4761-bad7-c2bb99645816.png)

<br>

## 2022-03-28 - CW2 Holes Patched and Other Body Tweaks [#106](https://github.com/VoronDesign/Voron-Afterburner/pull/106)

**Affected Files:**<br>

\+ `/Clockwork2/main_body-beta10.stl`<br>
\+ `/Clockwork2/motor_plate_beta8.stl`<br>
\+ `/Clockwork2/[a]_guidler_a-beta7.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta7.stl`<br>
\+ `/Clockwork2/[a]_latch-beta4.stl`<br>

\- `/Clockwork2/main_body-beta9.stl`<br>
\- `/Clockwork2/motor_plate_beta7.stl`<br>
\- `/Clockwork2/[a]_guidler_a-beta6.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta6.stl`<br>
\- `/Clockwork2/[a]_latch-beta3.stl`<br>

> Repaired some issues that were brought up when "Thin Wall Detection" settings aren't used.  Ended up having to move the `latch` pivot position 0.4mm to the right in order to fix the issue.  I've also reprofiled the lower portion of CW2 to better match the toolhead portion.
>
> ![image](https://user-images.githubusercontent.com/34219833/160529037-04c07e1b-447e-4a95-a466-712386b71fb1.png)
>
> ![image](https://user-images.githubusercontent.com/34219833/160529048-75799658-b0ee-4371-bdc2-63b48ed2fb88.png)
> ?
> ![image](https://user-images.githubusercontent.com/34219833/160529053-d75a1951-ae04-4387-9e61-75dd48bc77d4.png)
>
> **Major Changes**
>
> * `main body` `motor plate` `guidler a` `guidler b` and `latch` have all had work done to them.  They are *NOT* compatible with previous revisions.

<br>

## 2022-03-14 - Guidler Pivot Relocation [#104](https://github.com/VoronDesign/Voron-Afterburner/pull/104)

**Affected Files:**<br>

\+ `/Clockwork2/main_body-beta9.stl`<br>
\+ `/Clockwork2/motor_plate_beta7.stl`<br>
\+ `/Clockwork2/[a]_guidler_a-beta6.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta6.stl`<br>
\+ `/Clockwork2/[a]_latch_shuttle-beta2.stl`<br>
\+ `/Clockwork2/[a]_latch-beta3.stl`<br>

\- `/Clockwork2/main_body-beta8.stl`<br>
\- `/Clockwork2/motor_plate_beta6.stl`<br>
\- `/Clockwork2/[a]_guidler_a-beta5.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta5.stl`<br>
\- `/Clockwork2/[a]_latch_shuttle-beta1.stl`<br>
\- `/Clockwork2/[a]_latch-beta2.stl`<br>
\- `/Clockwork2/[a]_latch(long)-beta0.stl`<br>

> In an attempt to increase tension adjustment linearity and improve the ability to print flexible materials, the guidler pivot location has been re-vised.
>
> The relocation allows for the driven filament gear to travel in a large arc which reduces the amount of clearance required around the gear (less place for sneaky squishy filament to buckle and work it's way out of the filament path.
>
> The pivot has also been moved to be closer to vertical with the axis of the driven gear which means that movement of the driven gear in and out (from adapting to gears of different specs) results in less vertical misalignment of the two gears which forces the filament of axis from the filament path.
>
> ![image](https://user-images.githubusercontent.com/34219833/158295200-b345e836-578f-48de-b517-3bfa9b67ab46.png)
>
> ![image](https://user-images.githubusercontent.com/34219833/158295254-d0bd4bdd-bfa6-4e9e-8050-3375508961e5.png)
>
> **Major Changes**
>
> * `main body` `motor plate` `guidler a` `guidler b` and `latch shuttle` have all been extensively reworked to relocate the pivot point
> * redesigned `latch shuttle` from scratch
> * adjusted `main body` and `motor plate` geometry for new shuttle swing-arc
> * revised latch shuttle orientation tab/slot on `guidler a` and `guidler b`
> * removed original `latch` design in favor of "long" version that has been in testing for a few weeks.

<br>

## 2022-03-04 - Added cable-management to ADXL sensor mounts [#103](https://github.com/VoronDesign/Voron-Afterburner/pull/103)

**Affected Files:**<br>

\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta5.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw1-beta4.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw2-beta4.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit_19mm_c-c-beta2.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit-LIS3DH-beta1.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_generic_15.5mm_c-c-beta2.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_ldo_15mm_c-c-beta2.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_sparkfun-LIS3DH-beta1.stl`<br>

\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta4.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw1-beta3.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw2-beta3.stl`<br>
\- `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit_19mm_c-c-beta1.stl`<br>
\- `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit-LIS3DH-beta0.stl`<br>
\- `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_generic_15.5mm_c-c-beta1.stl`<br>
\- `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_ldo_15mm_c-c-beta1.stl`<br>
\- `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_sparkfun-LIS3DH-beta0.stl`<br>

> **Minor Changes**
>
> * Added zip-tie slot to `adxl_mount_generic`
> * Added zip-tie slot to `adxl_mount_adafruit`
> * Added zip-tie slot to `adxl_mount_ldo`
> * Added zip-tie slot to `adxl_mount_sparkfun_lis3dh`
> * Added zip-tie slot to `adxl_mount_adafruit_lis3dh`
> * Corrected model issue on toolhead rear for `r6/v6_mount_cw1` and `r6/v6_mount_cw2` (thanks Geeter)
> * Corrected air bleed ports on `rapido_front` toolhead (thanks FlyEspresso)

<br>

## 2022-02-24 - CW2 Extruder Gear Mesh Adjustment Screw [#100](https://github.com/VoronDesign/Voron-Afterburner/pull/100)

**Affected Files:**<br>

\+ `/Clockwork2/main_body-beta8.stl`<br>
\+ `/Clockwork2/motor_plate_beta6.stl`<br>
\+ `/Clockwork2/[a]_guidler_a-beta5.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta5.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit-LIS3DH-beta0.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_sparkfun-LIS3DH-beta0.stl`<br>

\- `/Clockwork2/main_body-beta7.stl`<br>
\- `/Clockwork2/motor_plate_beta5.stl`<br>
\- `/Clockwork2/[a]_guidler_a-beta4.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta4.stl`<br>

> **CW2 - Added Adjustment screw for extruder gear minimum C - C distance**
> Due to the wide variances we're seeing in manufacturing tolerances and specs on the extruder gears, tension screws, and tension springs, changes that were made some time ago to allow for greater tension were causing some users on the other end of the spectrum issues with gear-binding, etc.  So I dreamed up a way to try and kill a few birds with 1 stone.
> **Major Changes**
>
> - Added adjustment screw to `main_body` under the `shuttle` that allows for adjustment of the extruder gear minimum center to center distance.  M3x6 BHCS must be use here.  Do not substitute with SHCS.
> - Shuffled a few things around on `guidler_a` and `guidler_b` to accomodate a slot to adjust the min. c-c screw.
> - Revised dovetail interface on `guidler_a` and `guidler_b` to make tab less delicate.
> - Revised interlock profile under latch on `main_body` and `motor_plate` to give more material and prevent that little thing from snapping off too easily.
> - Added a clearance cutout for 50T gear on `motor_plate`
>
> **Other Updates**
>
> - Added ADXL mount for Adafruit LIS3DH sensor
> - Added ADXL mount for Sparkfun LIS3DH sensor

![image](https://user-images.githubusercontent.com/34219833/155484746-fd3ebe8b-fb63-4732-93e6-a2b54ff8adbc.png)

![image](https://user-images.githubusercontent.com/34219833/155485317-0c7b112d-fd0b-4305-9aef-470b9f6821fe.png)

![image](https://user-images.githubusercontent.com/34219833/155485575-1dac2de1-e8ad-499a-9e59-d133a7b06a4b.png)

<br>

## 2022-02-18 - Clockwork 2 body and latch updates [#93](https://github.com/VoronDesign/Voron-Afterburner/pull/93)

**Affected Files:**<br>

\+ `/Clockwork2/[a]_latch-beta2.stl`<br>
\+ `/Clockwork2/[a]_latch(long)-beta0.stl`<br>
\+ `/Clockwork2/main_body-beta7.stl`<br>
\+ `/Clockwork2/motor_plate_beta5.stl`<br>

\- `/Clockwork2/[a]_latch-beta1.stl`<br>
\- `/Clockwork2/main_body-beta6.stl`<br>
\- `/Clockwork2/motor_plate_beta4.stl`

> **Major Changes:**
>
> - Beefed the `main_body` around the driveshaft bearing to better support the bearing.
> - Reduced size of bearing bore diameter on `main_body` to improve bearing fitment.
> - Added mounting holes for toolhead PCB locations based on Hartk's revised PCB design on `main_body` and `motor_plate`
> - Revised `latch` profile to give some addtional flex to the latch to make locking it easier.
> - Added an additional "extended" version of the `latch` to make it easier to unlatch.  Please try out both and provide feedback in Discord.
>
> **Minor Changes:**
>
> - Adjusted counter bore depths on `main_body` to make bolt head depth more consistent.

<br>

## 2022-02-14 - BMO and BMS toolhead patch [#89](https://github.com/VoronDesign/Voron-Afterburner/pull/89)

**Affected Files:**<br>

\+ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta4.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta4.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta4.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta4.stl`<br>

\- `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta3.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta3.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta3.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta3.stl`<br>

> **Minor Changes:**
>
> - Corrected a missing through-hole in the `BMO toolhead front`
> - Corrected thin features on toolhead rear sections of `BMS6` & `BMS7`

<br>

## 2022-02-14 - Minor adjustments to ADXL mounts [#88](https://github.com/VoronDesign/Voron-Afterburner/pull/88)

**Affected Files:**<br>

\~ `/Stealthburner/ADXL345_Mounts/sb_adxl_washer-beta0.stl`<br>

\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit_19mm_c-c.stl-beta1`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_generic_15.5mm_c-c.stl-beta1`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_ldo_15mm_c-c.stl-beta1`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_washer-beta1.stl`<br>

\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit_19mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_generic_15.5mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_ldo_15mm_c-c.stl`<br>

> **Minor Changes:**
>
> - Shortened ADXL mounting area height to allow for more thread engagement.  (Thanks HackerJack42)
> - Slightly adjusted profile of ADXL mounts to make the design flow better.
> - Renamed ADXL mounts to match the rest of the Beta components.

<br>

## 2022-02-14 - Stealthburner ADXL Support and toolhead updates [#86](https://github.com/VoronDesign/Voron-Afterburner/pull/86)

**Affected Files:**<br>
\~ `/Stealthburner/Toolheads/README.md`<br>

\+ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-front-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-front-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta4.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-front-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw1-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw2-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-front-beta0.stl`<br>
\+ `/Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw1-beta0.stl`<br>
\+ `/Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw2-beta0.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit_19mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_generic_15.5mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_ldo_15mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_washer.stl`<br>

\- `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-front-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-front-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta3.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta2.stl`<br>
\- `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-front-beta2.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw1-beta2.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw2-beta2.stl`<br>

> **Major Changes:**
> Added `revo_voron` toolhead in preperation for upcoming release!
> `dragon_front` hotend duct has been revised to alleviate heatcreep issues in certain situations while printing PLA.
> All toolhead front sections now come with integrated mounting points for ADXL345 sensors for Input Shaping.  Choose mount you need from the new `ADXL345_Mounts` folder.
> ADXL345 mounts have been added. Mounts for LDO, Adafruit, and most generic sensors included.
> All toolheads now include revised M3x50mm screw extraction feature which should eliminate an gaps between the toolhead and the carriage when installing a toolhead for the first time. (Thank you to everyone who printed any of the 19 test pieces and offered feedback!)
>
> **Minor Changes:**
> `rapido_rear` rear has been revised to allevaite fastener interference with Omron probes.
> Toolhead STL Readme updated to include E3D Revo Voron.

<br>

## 2022-02-01 - Revised stealthburner_leds.cfg [#80](https://github.com/VoronDesign/Voron-Afterburner/pull/80)

**Affected Files:**<br>
~ `Klipper_Macros/stealthburner_leds.cfg`

> Restructured the config a little and added step-by-step instructions on how to set up and  use this new-found goodness.
>
> Hopefully the quells a lot of the questions and confusion from people new to Klipper and macros.

<br>

## 2022-02-01 - Stealthburner diffuser and mask updates [#79](https://github.com/VoronDesign/Voron-Afterburner/pull/79)

**Affected Files:**<br>
\+ `/Stealthburner/[a]_stealthburner_main_body_beta5.stl`<br>
\+ `/Stealthburner/[c]_stealthburner_LED_diffuser-beta3.stl`<br>
\+ `/Stealthburner/[o]_stealthburner_LED_diffuser-mask-beta1.stl`<br>

\- `/Stealthburner/[c]_stealthburner_LED_diffuser-beta2.stl`<br>
\- `/Stealthburner/[o]_stealthburner_LED_diffuser-mask-beta0.stl`<br>

> **Major Changes:**<br>
>
> - added chamfers (a) to `main_body` diffuser cavity entrance to make getting that little >guy in there much easier.
> - created slightly more clearance to `diffuser`/`mask` mating surfaces.
> - added chamfer to print surface (b) of `diffuser_mask` to battle elephants foot.
> - added chamfers (c) to `diffuser` to help with printing and assembling.
>
> **Minor Changes:**<br>
>
> - removed a strange little polygon artifact from the bottom of `main_body` (d).

<br>

## 2022-01-27 - Major updates for Stealthburner [#76](https://github.com/VoronDesign/Voron-Afterburner/pull/76)

**Affected Files:**<br>
\+ `/Clockwork2/main_body-beta6.stl`<br>
\+ `/Stealthburner/[a]_stealthburner_main_body_beta4.stl`<br>
\+ `/Stealthburner/[c]_stealthburner_LED_diffuser-beta2.stl`<br>
\+ `/Stealthburner/[o]_stealthburner_LED_carrier-beta2.stl`<br>
\+ `/Stealthburner/[o]_stealthburner_LED_diffuser-mask-beta0.stl`<br>

\- `/Clockwork2/main_body-beta5.stl`<br>
\- `/Stealthburner/[a]_stealthburner_main_body_beta3.stl`<br>
\- `/Stealthburner/[c]_stealthburner_LED_diffuser-beta1.stl`<br>
\- `/Stealthburner/[c]_stealthburner_LED_carrier-beta1.stl`<br>

> Changes in this PR will mean that ALL diffusers and LED carriers from previous versions will **no longer be compatible**.  Please print the latest and greatest.
>
> `[a]` ->  Accent color <br>
> `[o]` ->  Opaque (light doesn't penetrate)<br>
> `[c]` ->  Clear/Translucent (light can penetrate)<br>
>
> - `main_body` has had nozzle LED retainer mechanism completely reworked.  The 17th version was the winner.  Thank you to all who printed the test pieces and reported back with feedback.
> - `main_body` has had some work done under the hood to try and help reduce light bleed from the Logo LED through somewhat translucent main body colors.
> - `main_body` nozzle led wiring channel slightly reworked to accommodate revised LED retainer springs.
> - `led_carrier` has been revised to accommodate thicker PCBs, but most importantly has had the bottom cut out.  **the LED carrier should now be printed out of an opaque filament**
> - `led_diffuser` has been redesigned (may still get some more massaging depending on feedback.
> - `led_diffuser_mask`  ......that's a new one.  The diffuser now fits inside of this impenetrable fortress for light. The diffuser mask should be printed out of an opaque material as well to keep the light contained and only spill it where we want.
>
> ![image](https://user-images.githubusercontent.com/34219833/151489492-828ae1f5-051d-45f8-bebe-7ae1532a2b76.png)
>
> Repaired missing counterbore on CW2 Main Body.
> ![image](https://user-images.githubusercontent.com/34219833/151511988-8ff86ecb-ecb7-46ec-818a-5d780dca8bf8.png)

<br>

## 2022-01-27 - Corrected missing hole-bridge feature on main_body [#75](https://github.com/VoronDesign/Voron-Afterburner/pull/75)

**Affected Files:**<br>
~ `/Clockwork2/main_body-beta5.stl`

<br>

## 2022-01-27 - Corrected tiny unwanted artifact on motor plate [#74](https://github.com/VoronDesign/Voron-Afterburner/pull/74)

**Affected Files:**<br>
~ `/Clockwork2/motor_plate-beta4.stl`

<br>

## 2022-01-27 - Clockwork2 Updates focusing on filament tension and design finesse [#73](https://github.com/VoronDesign/Voron-Afterburner/pull/73)

**Affected Files:**<br>
\+ `/Clockwork2/[a]_guidler_a-beta4.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta4.stl`<br>
\+ `/Clockwork2/[a]_latch-beta1.stl`<br>
\+ `/Clockwork2/[a]_latch_shuttle-beta1.stl`<br>
\+ `/Clockwork2/main_body-beta5.stl`<br>
\+ `/Clockwork2/motor_plate-beta4.stl`<br>

\- `/Clockwork2/[a]_guidler_a-beta3.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta3.stl`<br>
\- `/Clockwork2/[a]_latch-beta0.stl`<br>
\- `/Clockwork2/[a]_latch_shuttle-beta0.stl`<br>
\- `/Clockwork2/main_body-beta4.stl`<br>
\- `/Clockwork2/motor_plate-beta3.stl`<br>

> **Clockwork2 Updates:**
>
> - Revised `main_body` to allow more travel of guidler...further increasing maximum allowable tension on filament (she won't go any more, Captain).
> - Reworked `main_body` and `motor_plate` in preparation of mounting locations for toolhead PCB designed by Hartk.
> - Adjusted depth of counter-bore on latch-locking bolt (M3x25) in `main_body` to give better thread-engagement.
> - Revised diameter of motor mount/adjustment slot on `motor_plate` to allow larger diameter washers to be used.
> - Reworked `guidler_a` to create more initial tension on filament.
> - Reworked `guidler_a` to reduce some unnecessary fore/aft clearance on driven gear.
> - Reworked `guidler_a` filament tensioner hole to be slotted rather than just a clearance hole to allow unrestricted movement of guidler.
> - Reworked orientation slot/tab on `guidler_a`. `guidler_b`, and `latch_shuttle` from a straight tab to an arc to prevent binding. (since it travels in an arc...).
> - Adjusted profile of `latch_shuttle` to accommodate additional travel of guidler or greater.
> - Adjusted `latch` to require slighty more force to lock the shuttle and to make the latch a little more "grabby" around it's locking bolt.

<br>

## 2022-01-20  - Set initial_RED to 1 [#70](https://github.com/VoronDesign/Voron-Afterburner/pull/70)

**Affected Files:**<br>
\~ `Klipper_Macros/stealthburner_leds.cfg`<br>

<br>

## 2022-01-16 - Clockwork2 updates [#67](https://github.com/VoronDesign/Voron-Afterburner/pull/67)

**Affected Files:**<br>
\+ `/Clockwork2/[a]_guidler_a-beta3.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta3.stl`<br>
\+ `/Clockwork2/main_body-beta4.stl`<br>
\+ `/X_Carriage/[a]_x_bearing_block_SW_beta0.stl`<br>
\+ `/X_Carriage/x_frame_SW_left-beta1.stl`<br>
\+ `/X_Carriage/x_frame_SW_right-beta1.stl`<br>

\- `/Clockwork2/[a]_guidler_a-beta2.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta2.stl`<br>

> Some changes have been made to the guidler and main body to help improve filament engagement/tension over a wider variety of BMG gears.
>
> **Changes:**
>
> - Guidler A and B update to allow for more travel (more filament engagement/tension).
> - Idler shaft area has additional support material added to deflection when pushing extruder to more extreme extrusion levels.
> - Main Body was updated to accommodate additional travel.
> - Switchwire X Frame update to allow more clearance for probe. (Thanks Steve)

<br>

## 2022-01-14 - Small fixes for Dragon and Rapido TH [#63](https://github.com/VoronDesign/Voron-Afterburner/pull/63)

**Affected Files:**<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta3.stl`<br>

\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta2.stl`<br

> **Fixes:**
>
> - Added missing air-bleed ports for Dragon toolhead front.
> - Fixed hotend fan flow-straightener vane on Rapido toolhead front.

<br>

## 2022-01-14 - Toolhead updates [#61](https://github.com/VoronDesign/Voron-Afterburner/pull/61)

**Affected Files:**<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-front-beta2-.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw2-beta2.stl`<br>

\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta1.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw2-beta1.stl`<br>

> Some toolhead updates to correct some shortcomings on the previous revisions.
>
> **Changes:**
>
> - V6/R6 toolhead cutout has been revised to optimize airflow across lower portion of heatsink and no long forces heat higher up the heatsink.
> - Dragon toolhead has had the nozzle height corrected.  It was roughly 1.4mm too high.
> - Rapido toolhead mounting bolt pattern has been rotated 12° to orient the metal strain-relief tab better.  Also added a tiny bit more clearance for strain-relief zip-tie.

<br>

## 2022-01-06 - Stealthburner fan cutout updates and toolhead changes [#53](https://github.com/VoronDesign/Voron-Afterburner/pull/53)

**Affected Files:**<br>

\~ `README.md` <br>
\~ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-front-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-front-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw1-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw2-beta1.stl`<br>

\+ `/Clockwork2/motor_plate-beta3.stl`<br>
\+ `/Stealthburner/[a]_stealthburner_main_body_beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta2.stl`<br>

\- `/Clockwork2/motor_plate-beta2.stl`<br>
\- `/Stealthburner/[a]_stealthburner_main_body_beta2.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw2-beta1.stl`<br>

> **Stealthburner Updates:**
>
> - Re-centered 5015 inlet to undo previous bad decision :)   (Delta and GDSTIME fans are perfectly centered)
> - Added a tiny bit of additional wiring clearance for 4014 fan wiring
> - Completely redesigned nozzle-nozzle LED wiring channel to give added strength to main body mounting screw locations
> - Made a couple of changes to 4010 fan area to ease fan installation
> - Tweaked bridging for upper wire retainer
>
> **Toolhead Changes:**
>
> - Added Phaetus Rapido toolhead
> - Fixed type on BMS toolhead
> - Split BMS toolhead up into 6 and 7 fin designs which should now support Zodiac version as well
> - Re-organized toolheads into sub-folders to make selecting the correct files easier
> - Updated Readme.md to be more helpful and supportive (thanks for the help Timmit!)
>
> **Clockwork 2 Changes:**
>
> - fixed a missing print-hack thingy for a chain anchor mount threaded insert

<br>

## 2021-12-29 - Repaired missing features in Guidler and Motor Plate [#41](https://github.com/VoronDesign/Voron-Afterburner/pull/41)

**Affected Files:**<br>
\+ `/Clockwork2/[a]_guidler_a-beta2.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta2.stl`<br>
\+ `/Clockwork2/main_body-beta3.stl`<br>
\+ `/Clockwork2/motor_plate-beta2.stl`<br>

\- `/Clockwork2/[a]_guidler_a-beta1.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta1.stl`<br>
\- `/Clockwork2/main_body-beta2.stl`<br>
\- `/Clockwork2/motor_plate-beta1.stl`<br>

> A CAD error caused some features to go boom from the previous commit. These have been corrected. My apologies for not catching this. Thanks to Steve for notifying me as soon as you did.
>
> Reprint:
>
> - [a]_guidler_a-beta2.stl
> - [a]_guidler_b-beta2.stl
>
> Don't necessarily need to reprint:
>
> - main_body-beta3.stl
> - motor_plate-beta2.stl

## 2021-12-29 - Made adjustments to V6/R6 Toolhead [#39](https://github.com/VoronDesign/Voron-Afterburner/pull/39)

**Affected Files:**<br>
\~ `/Stealthburner/Toolheads/README.txt`<br>

\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw2-beta1.stl`<br>

\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw2-beta0.stl`<br>

## 2021-12-29 - Stealthburner updates, CW2 adjustments, chain anchors, Phaetus fixes #38

**Affected Files:**<br>
\+ `/Clockwork2/[a]_guidler_a-beta1.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta1.stl`<br>
\+ `/Clockwork2/cable_door-beta1.stl`<br>
\+ `/Clockwork2/chain_anchor_2hole-beta1.stl`<br>
\+ `/Clockwork2/chain_anchor_2hole-SW-beta0.stl`<br>
\+ `/Clockwork2/chain_anchor_3hole-beta1.stl`<br>
\+ `/Clockwork2/chain_anchor_3hole-SW-beta0.stl`<br>
\+ `/Clockwork2/main_body-beta2.stl`<br>
\+ `/Clockwork2/motor_plate-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/[a]_stealthburner_main_body_beta2.stl`<br>
\+ `/Stealthburner/[c]_stealthburner_LED_carrier-beta1.stl`<br>
\+ `/Stealthburner/[c]_stealthburner_LED_diffuser-beta1.stl`<br>

\- `/Clockwork2/[a]_guidler_a-beta0.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta0.stl`<br>
\- `/Clockwork2/cable_door-beta0.stl`<br>
\- `/Clockwork2/chain anchor_2hole-beta0.stl`<br>
\- `/Clockwork2/chain anchor_3hole-beta0.stl`<br>
\- `/Clockwork2/main_body-beta1.stl`<br>
\- `/Clockwork2/motor_plate-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/a_stealthburner_main_body_beta1.stl`<br>
\- `/Stealthburner/c_stealthburner_LED_carrier-beta1.stl`<br>
\- `/Stealthburner/c_stealthburner_LED_diffuser-beta1.stl`<br>

> **Corrected CW2 filament path**
>
> - Corrected 0.6mm misalignment for filament path with Clockwork2 Main Body.  Corrected small cutout issue on Revo Micro Toolhead Front that should not require a reprint.
>
> **Replace RevoMicro toolhead**
>
> - Replaced original Beta1 STL with version with repaired geometry
>
> **Revised filename on RevoMicro**
>
> **Added Switchwire cable chain anchors**
>
> **...and corrected SB file names**
>
> **Stealthburner Changes:**
>
> - Offset 5015 fan inlet slightly to align center of impeller better due to wide variances between fans from different manufacturers.
> - Reduced size of inlet loft at impeller to increase fan efficiency and greatly improve performance.
> - Added some additional clearance for Sanace B52 fans. (Hopefully they fit now)
> - Removed small amount of material on bottom of 5015 fan cutout that was causing some impellers to rub the Main Body.
> - Reduced mounting screw depth by 1mm on Phaetus-BMO Toolhead.
> - Revised corner radius on toolhead cutout for Phaetus-BMS to match actual parts vs. Phaetus CAD.
> - Fixed naming on several files.
> - Started to replace toolhead identification mark on Toolhead Rear.
>
> **Clockwork2 Changes:**
>
> - Added chain anchors for Voron Switchwire.
> - Adjusted all chain anchors to have better thread-engagement on M3x20 mounting bolt. (Does not require reprint if yours work ok)
> - Added some additional clearances to Main Body, Guidler, and Motor Plate to accommodate large variances in drive shafts and gears.  (Does not require reprint if yours work ok)
> - Added small alignment features to Motor Plate and Cable Cover to help aligned screw hole easier.
> - Revised hole size on cable door for better thread engagement.
>
> **Remove old stls**

<br>

## 2021-12-27 - Corrected CW2 filament path [#23](https://github.com/VoronDesign/Voron-Afterburner/pull/23)

**Affected Files:**<br>
\+ `/Clockwork2/main_body-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(revo_micro)-front-beta1.stl`<br>
\+ `/Clockwork2/main_body-beta0.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(revo_micro)-front-beta0.stl`<br>

> Corrected 0.6mm misalignment for filament path with Clockwork2 Main Body. Corrected small cutout issue on Revo Micro Toolhead Front that should not require a reprint.

<br>

## 2021-12-24 - Sb betaupdate1 [#21](https://github.com/VoronDesign/Voron-Afterburner/pull/21)

**Affected Files:**<br>
\+ `/Stealthburner/a_stealthburner_main_body_beta1.stl`<br>
\+ `/Stealthburner/c_stealthburner_LED_carrier-beta1.stl`<br>
\+ `/Stealthburner/c_stealthburner_LED_diffuser-beta1.stl`<br>

\- `/Stealthburner/[a]_stealthburner_main_body_beta0.stl`<br>
\- `/Stealthburner/[c]_stealthburner_LED_carrier-beta0.stl`<br>
\- `/Stealthburner/[c]_stealthburner_LED_diffuser-beta0.stl`<br>

> Fixed a missing fillet on Stealthburner main_body which was causing slicing and print issues for some users.
>
> Revised LED carrier to accommodate some PCBs that have SMD components soldered wider than usual.
>
> Revised LED diffuser to add more clearance on top and re-designed internal structure of printed part for easier printing.
