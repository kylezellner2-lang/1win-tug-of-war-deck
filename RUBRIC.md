# Image Generation Rubric — 1win Deck

## Canonical scene (every render must match this world)
- **Setting:** thousands of feet up, over a vast sea of clouds and distant mountains, clear sky, **golden-hour** warm light.
- **The rig:** a **thin, flat platform on a light steel truss**, **suspended from the hot air balloon's BASKET on long thin cables**, floating well below the balloon. Minimal and realistic — NOT a thick industrial box, NO light bars.
- **Balloon branding:** a **1win flag / logo panel on the balloon** (Stake-style), NOT a banner wrapping the whole balloon.
- **Other branding:** 1win logo on the platform surface/sides; every creator in 1win merch.
- **Style:** cinematic, photorealistic, natural grade, no text/watermarks.

## HARD FAILS (reject + re-prompt if any hit)
- [ ] Platform floating BESIDE the balloon instead of hanging BENEATH it on cables.
- [ ] Full-wrap balloon banner instead of a flag/logo panel.
- [ ] Thick / industrial platform, or light bars on the platform.
- [ ] Wrong head-count — **count every time** (tug of war = 6: three per team). GPT overshoots on wide shots.
- [ ] Anyone off the platform edge / floating in air, UNLESS it's an intended freefall/swing shot.
- [ ] Invented elements not in the scene (crowds, stands, jumbotrons, second balloon, gibberish text, wrong logos).
- [ ] Distorted / melted 1win logo, extra limbs, melted faces, other AI artifacts.
- [ ] Lighting that doesn't match golden hour.
- [ ] Harsh, over-contrasty grade.
- [ ] Wrong aspect ratio.
- [ ] (Quarter pipe only) money/coins in the air — there should be NONE.

## Shot list
| # | Name | File | Spec |
|---|------|------|------|
| 01 | Tug of War (hero) | `photos/concept.png` | Corrected: thin platform, basket-suspended, flag branding, 2 teams of 3, one rope over open center |
| 02 | Monkey Bars | `photos/monkey-bars.png` | Real monkey-bar ladder below the balloon; a person hanging + swinging; 1win flag; minimal rig |
| 03 | Quarter Pipe | `photos/quarter-pipe.png` | Long rectangular runway platform + small launch ramp at the far end; skater launches off into freefall; NO money |
| 04 | Branding close-ups | `photos/brand-*.png` | Optional — tight crops of the mains (flag, ramp side, platform base, creator merch) rather than new gens |

## Status log (APPROVED / REJECTED + why)
_(to be filled during the generation run)_
- 01 Tug of War — pending (current file is uncorrected IMG_1300)
- 02 Monkey Bars — pending (no clean render yet; IMG_1055 is a text-baked ad, reference only)
- 03 Quarter Pipe — stand-in in place (IMG_0882, has halfpipe + money; needs correction)

## To resume
Blocked: the Claude-in-Chrome browser tools are not connected to this Claude Code session, so ChatGPT
cannot be driven from here. To run: connect the Claude for Chrome extension as an MCP server, seed one
ChatGPT chat with the hero image, paste the chat URL, then generate 02 and 03 (and correct 01) in that
single continuous chat, grading each against the HARD FAILS above.
