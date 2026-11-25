# SPEC — Launch Poster, 90 s, 9:16

GOAL:   A viewer with a last-minute design to make believes one idea can become a shared Canva design in one place, and taps "Try Canva free".
OUTPUT: HyperFrames, 1080 x 1920, 30 fps.
TIME:   90 s x 30 = 2700 frames. Music 118 BPM -> 15.25 frames/beat, 61 frames/bar. Bar lines at 0, 2.03, 4.07 ... s.

LOOK:
  Ground A (desk world): #14121A with one #FFB35C light panel at 12% opacity, sharp edge, no glow or gradient.
  Ground B (product world): #FFFFFF with #F5F3F7 plates; 1 px #E6E3EA hairlines.
  Ink #111018 on light, #F6F4F8 on dark. One accent #7D2AE8 (Canva), max 8% of any frame, on one word, the share button, and the end card only.
  Display: Outfit 800, 132 px (6.9% of height), tracking -2%; body Outfit 500, 42 px; all-caps meta Outfit 600, 30 px, tracking +4%.
  Medium: real captured Canva UI plates, shown flat and sharp (never tilted in 3D), crops at 1.6-2x on the action; physical phone with 10 px bezel and 44 px corner radius.
  Depth: one 0 / 18 px / 34 px shadow at 0.18 alpha on the hero card only. No grain, no bloom, no vignette.

OBJECTS: phone with 9:41 status bar; message bubble "launch is tomorrow"; blank poster; Canva homepage plate; template gallery plate; editor plate with layers strip; 64 px cursor; share panel with copyable link; finished poster (MIDNIGHT MARKET / LAUNCH TOMORROW); Canva favicon mark; "Canva" wordmark.

MOTION:
  enter expo.out 0.22 s; camera power2.inOut 0.5 s; exit power3.in 0.18 s; click rebound back.out(1.4) 0.12 s.
  Cursor 64 px (5.9% of width), enters from off-screen in 0.4 s; its click causes the next thing on the same frame.
  One hero move per shot; secondary moves travel 60% as far and start 0.12 s later. Titles land then hold dead still.
  Readable text holds 0.5 s + 0.3 s/word; the last line holds at least 2 s.

SHOTS:
  1. f0-225    (0-7.5 s)   hook: phone + "launch is tomorrow"; phone lifts 40 px, message pops; tick. Hand-off: message -> notification chip.
  2. f225-510  (7.5-17 s)  tension: file chips multiply, spinner freezes, poster stays blank; near silence. Hand-off: chip -> Canva tile.
  3. f510-750  (17-25 s)   reveal: amber-to-white colour flood on the real Canva homepage plate, cursor clicks; title "One idea. One place."; music opens. Hand-off: click -> template grid.
  4. f750-1140 (25-38 s)   proof/pick: real template gallery, cursor scrolls and picks; chosen template lands in the editor; "Pick a starting point"; clicks. Hand-off: template -> editor.
  5. f1140-1530 (38-51 s)  proof/edit: photo swap and headline retype on the real editor plate; "Make it yours", one accent word; key ticks. Hand-off: headline -> share button.
  6. f1530-1860 (51-62 s)  proof/share: share panel opens, link copies, finished poster appears on a phone; "Share it anywhere"; pop. Hand-off: phone -> poster.
  7. f1860-2310 (62-77 s)  payoff: finished poster fills frame, 1.0 -> 1.08 push, details reveal, pull back to workspace; riser + impact, music peak.
  8. f2310-2520 (77-84 s)  claim: "From idea to shared, in one place."; one accent word; hold >= 2 s; music settles.
  9. f2520-2700 (84-90 s)  end card: Canva mark carried in, wordmark wipes beside it, CTA "Try Canva free" held 2.5 s; final chord, 1.5 s fade.

BANNED: dark void with small floating UI; glow, bloom, particles; purple/blue mesh gradients; cream paper + serif + mono labels; everything centred or fading in at once; three cards in a row; docked logo; titles that drift after landing; invented Canva buttons or a made-up dashboard (unverified UI must be labelled as a placeholder); voiceover.

QA: frames 0, 90, 270, 510, 660, 780, 1020, 1200, 1440, 1590, 1800, 1980, 2250, 2400, 2550, 2670. Check each: hero fills >= 40% of frame; readable text >= 42 px inside 80% title-safe; accent used once; cursor click causes the next state; no UI tilted; end-card mark is the real Canva favicon mark.
