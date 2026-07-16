# Image Generation Rubric — 1win Deck

## OUTPUT (read first)
- **Do NOT put images into the deck.** Save everything to a Desktop folder for review:
  `~/Desktop/1win-deck-images/` with a subfolder per scene:
  `monkey-bars/`, `quarter-pipe/`, `tug-of-war/`.
- **Target ~20 total options** to choose from — roughly **6–7 per scene**: one HERO shot of the
  scene, then several variations of the **same scene** from **different camera angles/aspects**.
- Save at native resolution. Name files `hero.png`, `angle-01.png`, `angle-02.png`, etc.

## THE #1 RULE — LOGIC & CONSISTENCY (this is what usually breaks)
Within each scene, the variations are just a **camera moving around the same frozen scene**. NEVER change what's in the scene:
- **Same number of people** in every shot of a scene (count them every time — GPT adds/drops people).
- **Same faces / same people** — do not swap or regenerate different-looking people.
- **Same structure** — the rig, platform, bars, ramp, balloon, cables stay identical shot to shot.
- **Everything must be physically logical.** It is thousands of feet up. Every person must be
  clearly **supported** — standing/bracing on the platform, gripping the monkey bars, or on the ramp.
  **NOBODY floating in mid-air beside the rig, half-off the edge, or hanging with no support.**
  If a shot doesn't make physical sense, REJECT it. This is the most important check.

Per-scene head-counts to hold constant:
- **Monkey Bars:** 1 creator on the bars (plus anyone the hero establishes — then keep it fixed).
- **Quarter Pipe:** 2 creators.
- **Tug of War:** 6 creators — two teams of three.

## Canonical scene rules (all concepts)
- Setting: thousands of feet up, sea of clouds + distant mountains, clear sky, **golden hour**.
- Rig: **thin, flat platform / minimal light truss**, **suspended from the balloon's BASKET on long
  thin cables**, hanging well below the balloon. No thick industrial boxes, no light bars.
- Balloon branding: a **1win flag / logo panel on the balloon** (Stake-style), NOT a full wrap.
- 1win logo on the rig surface; all creators in 1win merch. Cinematic, photorealistic, natural grade, no text.

## HARD FAILS (reject + re-prompt if any hit)
1. **Anyone floating / hanging off the platform with no support** (unless it's an intended, clearly-
   supported action like gripping the monkey bars). ← most important
2. Wrong head-count vs. the scene's locked number. Count every time.
3. A different face / different person swapped in across variations.
4. The structure changed between shots (rig, ramp, bars, platform, cables, balloon differ).
5. Platform floating BESIDE the balloon instead of hanging BENEATH it on cables.
6. Full-wrap balloon banner instead of a flag/logo panel.
7. Thick / industrial platform, or light bars.
8. Invented elements (crowds, stands, jumbotrons, second balloon, gibberish text, wrong logos).
9. Distorted/melted 1win logo, extra limbs, melted faces, AI artifacts.
10. Lighting not matching golden hour; harsh over-contrast; wrong aspect ratio.
11. (Quarter pipe) any money/coins in the air — there should be NONE.

## The three scenes
**Monkey Bars** (`~/Desktop/1win-deck-images/monkey-bars/`) — a real monkey-bar ladder suspended
below the balloon; a creator hanging + swinging bar to bar; 1win flag; minimal rig. Angles: wide
establishing, drone/aerial, low angle looking up, POV of the swinger, side profile, close on the hands/bars.

**Quarter Pipe** (`~/Desktop/1win-deck-images/quarter-pipe/`) — a LONG rectangular runway platform
with a SMALL launch ramp at the far end; 2 creators; one skating the deck / firing off the end ramp
into freefall; NO money. Angles: wide, drone, down-the-deck POV, side profile of the ramp launch, low angle.

**Tug of War** (`~/Desktop/1win-deck-images/tug-of-war/`) — thin platform, basket-suspended, 6 people
(two teams of three) on one rope over an open center gap; flag branding. Angles: wide establishing,
drone top-down, on-platform POV, low angle, side profile, close on the center gap.

## Status log (APPROVED / REJECTED + why) — fill during the run
- Monkey Bars — pending
- Quarter Pipe — pending
- Tug of War — pending

## Generation mechanism
Drive ChatGPT in the browser (Claude-in-Chrome / Co-work). One continuous chat per scene so it holds
that scene in context. Grade every image against the HARD FAILS above before saving.
