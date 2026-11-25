# SPEC — Launch Poster, 90 s, 9:16

GOAL:   A viewer with a last-minute design to make believes one idea can become a shared Canva design in one place, and taps "Try Canva free".
OUTPUT: HyperFrames, 1080 x 1920, 30 fps.
TIME:   90 s x 30 = 2700 frames. Bed measured at 135 BPM (0.444 s/beat, 1.778 s/bar); every scene cut lands on a bar line. Scene starts: 0, 7.111, 17.778, 24.889, 37.333, 49.778, 62.222, 76.444, 83.556 s.

LOOK:
  Ground A (desk world): #14121A with one #FFB35C light panel at 12% opacity, sharp edge, no glow or gradient.
  Ground B (product world): #FFFFFF with #F5F3F7 plates; 1 px #E6E3EA hairlines.
  Ink #111018 on light, #F6F4F8 on dark. One accent #7D2AE8 (Canva), max 8% of any frame, on one word, the share button, and the end card only.
  Display: Outfit 800, 132 px (6.9% of height), tracking -2%; body Outfit 500, 42 px; all-caps meta Outfit 600, 30 px, tracking +4%.
  Medium: real captured Canva UI plates, shown flat and sharp (never tilted in 3D), crops at 1.6-2x on the action; physical phone with 10 px bezel and 44 px corner radius.
  Depth: one 0 / 18 px / 34 px shadow at 0.18 alpha on the hero card only. No grain, no bloom, no vignette.

OBJECTS: phone with 9:41 status bar; message bubble "launch is tomorrow"; blank poster; Canva homepage plate; template gallery plate + template detail sheet; poster close-up with floating text toolbar; 64 px cursor; share dialog with copyable link; finished poster (MIDNIGHT MARKET / LAUNCH TOMORROW); Canva favicon mark; "Canva" wordmark.

MOTION:
  enter expo.out 0.22 s; camera power2.inOut 0.5 s; exit power3.in 0.18 s; click rebound back.out(1.4) 0.12 s.
  Cursor 64 px (5.9% of width), enters from off-screen in 0.4 s; its click causes the next thing on the same frame.
  One hero move per shot; secondary moves travel 60% as far and start 0.12 s later. Titles land then hold dead still.
  Readable text holds 0.5 s + 0.3 s/word; the last line holds at least 2 s.

SHOTS (final cut, bar-aligned):
  1. 0-7.111 s     hook: large phone, "launch is tomorrow" visible on frame one, slow settle; chime.
  2. 7.111-17.778 s tension: file chips multiply around a blank poster, spinner turns, three titles.
  3. 17.778-24.889 s reveal: amber flood to the real Canva homepage, cursor clicks "Start designing"; title "One idea. One place."
  4. 24.889-37.333 s proof/pick: real template gallery scrolls, a photo post is selected, Canva-style template sheet opens on the Midnight Market design; title "Then make it yours."
  5. 37.333-49.778 s proof/edit: poster close-up, headline and subline type on, lavender swatch recolours one word via a floating toolbar; title "Make it yours."
  6. 49.778-62.222 s proof/share: share dialog copies the link, then the finished poster rises on a phone with a check badge; title "Share it anywhere."
  7. 62.222-76.444 s payoff: full poster, slow 1.0 -> 1.04 photo push, export chip "PNG · 1080 × 1350"; riser + impact, music peak.
  8. 76.444-83.556 s claim: "From idea to shared, in one place."; one accent word; hold >= 2 s; music settles.
  9. 83.556-90 s   end card: centred Canva mark, wordmark wipes beside it, CTA "Try Canva free" held 2.5 s; final chime.

BANNED: dark void with small floating UI; glow, bloom, particles; purple/blue mesh gradients; cream paper + serif + mono labels; everything centred or fading in at once; three cards in a row; docked logo; titles that drift after landing; invented Canva buttons or a made-up dashboard (unverified UI must be labelled as a placeholder); voiceover.

QA: decoded frames at 0, 2, 5, 8, 12, 16, 19, 22, 26, 31, 36, 39, 43, 47, 51, 54, 58, 61, 64, 69, 73, 78, 81, 85, 89 s (workflow uploads them). Check each: hero fills >= 40% of frame; readable text >= 42 px inside title-safe; accent used once; cursor click causes the next state; no UI tilted; end-card mark is the real Canva favicon mark.
