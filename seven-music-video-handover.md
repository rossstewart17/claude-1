# "Seven" music video: handover brief

Paste this into a new chat in the correct group/project, and attach or point to the files (the WAV, lyrics, EP artwork, reference photos).

## Goal
Make a mock-up AI music video for my song **"Seven"** (R.A. Stewart, "Seven" CD master, 16-bit/44.1 kHz). It will go to a couple of music video directors to see how they'd approach it, so it needs to be realistic to produce for real, but I'm not limited by what's practical in the mock-up. I want it soon because the CDs are being printed, and one director is getting a CD.

## Files
- **Audio:** `01_Seven.wav`, 47.3 MB, about 4:28. Google Drive, My Drive, Ross Stewart (Music) folder, subfolder "Seven" (file ID `1Q_yEpq9xeP_qRRi7w_-6FEj3qt7etM1e`). It was too big to analyse in the previous chat, which was in the wrong group.
- **Lyrics:** I'll add these.
- **EP artwork:** shows the red mask. Needed to match the mask design.
- **Reference photos of me:** I'll supply a lot. Used for a close-likeness character.

## Tools and approach agreed
- **Kling AI** (I have an account and credits; I can link the API). Good for short cinematic clips, image-to-video, reference-based characters, and audio-driven lip-sync. Clips are roughly 5–10 s each, so the video is a few dozen clips cut together in an editor. Runway, Veo or Luma are fallbacks for individual shots.
- **The song has sung vocals**, so lip-sync is needed on the singing shots. Not constant: only the performance layer and a few key moments. Lip-sync works best on a clear front-facing face and ideally on an isolated vocal stem (I'll check whether I have one).
- **My likeness:** the singer and warrior are a close likeness of me. Build a character sheet first (face from several angles), check it looks like me before spending credits on video.
- **Photo tips:** 10–20 photos, even light, front, three-quarter and profile, neutral and smiling, no sunglasses or hats, a few mid and full-body shots, and the outfit.
- **Audio analysis:** Claude can't listen. Either I give section timestamps from my DAW, or Claude writes a Python script (tempo, beats, section changes) that I run locally and paste the output of.
- **Process:** 1) Brainstorm. 2) Audio analysis and section timestamps. 3) Shot list with timecode, scene, camera, mood, lyric line, and singing versus cutaway flag. 4) Reference images and key frames. 5) Generate in Kling (image-to-video, then lip-sync passes). 6) Edit to the WAV.
- **Rest of the band:** faceless, so no face-consistency problem. Faceless figures and silhouettes also cover the weakness of AI for instrument-playing shots.

## The story (my description)
Two layers cut together:
- **Performance layer** (me singing, lip-sync): the cell, and the band by the water.
- **Story layer** (nobody sings): the desert pursuit.

| Section | Story layer | Performance layer |
|---|---|---|
| Intro | Old stone prison cell, castle-dungeon style, light through the bars or window. A prisoner (me) sits in the corner, light across his face. | |
| Full music intro | A hooded figure in a long battered cloak and the **red mask** (from the EP artwork) walks through desert. A warrior (me) tracks him: Prince of Persia or Viking style, light leather armour, not heavy. | Band playing by the water's edge. Band either masked in red, or hooded so they can't be seen properly. Undecided. |
| Verse 1 (music drops down) | Masked man walks the desert and picks up a couple of followers who are drawn to him. Warrior reads tracks, speaks to villagers, asks if they've seen him. | Flashes of me singing in the cell, light shining on me. |
| Chorus | | Band by the water. |
| Verse 2 (escalation) | Different desert locations. More followers. Warrior gets closer, sees them in the distance, but is alone. | Cell flashes. |
| Chorus | Flashes of lots of followers. As it culminates, the masked man reaches the water's edge (a scene like the band's, but never both in one shot). He stands at the front of hundreds and turns to talk to them. | Band by the water. |
| Acoustic guitar lead-in to interlude | The crowd parts. The warrior has tracked them and walks through to the front. | |
| Interlude (music jumps up) | Warrior grabs the mask and pulls it off with the hood. The face underneath is the same face (me). The masked man grabs the warrior's head and presses his forehead to his: the mirror-image key moment. The masked man sings the first half of the interlude, then both sing at each other for the second half. | |
| Brief silence (only vocals) | The masked man wisps away into dust. The warrior at the front is revealed as the man they were all following all along: the two were the same. | |
| Final chorus | Flash to the crowd, then back to me (the warrior) at the front of the band singing to the crowd. Waves crash behind us and spray our faces. Halfway through I sing a double line of the chorus and hold a big note, which releases a sonic boom into the water. The water sprays out sideways and knocks a few people at the front over. | Band by the water. |
| Outro | Bookend: back to the prisoner in the corner of the cell. | |

## Production flags raised
- **Unmasking and forehead press** is the hardest moment. Build from separate shots: over-the-shoulder each way, a still of the mask lifting as a start or end frame, and composite the forehead contact in the edit.
- **Both of us singing at each other:** separate lip-sync clips, alternating close-ups, not both faces in one frame.
- **Dust vanish and sonic boom:** straightforward in generation, and real VFX in a real shoot. Generate the spray and cut it in on the big note.
- **Crowd of hundreds:** fine in wides. Keep close crowd shots short and dark.
- **Same-man consistency** (cell man, warrior, masked man, singer): the face reference matters a lot.
- **Pitch line for directors:** the hunter and the hunted are the same man, and the cell bookend frames the whole thing as happening in his head.

## Open questions
1. Do the band wear red masks, hoods, or nothing? (Suggestion: hooded, keeping the red mask special to the one figure so the reveal lands.)
2. Where is the EP artwork with the red mask? (Needed in the same folder.)
3. In the final chorus, am I in the warrior outfit with the band, or a separate performance look?
4. Does the cell man's look match the warrior, or is he more worn down?

## What to do first in the new chat
1. Read `01_Seven.wav` from Drive, or use my section timestamps or the analysis script.
2. Read the lyrics and the EP artwork.
3. Draft the full shot list with timecodes from the table above.
4. Then the character sheet from my reference photos, and test shots in Kling.
