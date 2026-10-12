# The Last 5 Days – online (Activity 1 + 1.1)

A single-page web app for **Activity 1 (The Last 5 Days)** and **Activity 1.1 (The Performance Aftermath)**.
One `index.html` file, no build step, no libraries. It runs on **GitHub Pages**.

## Publish it on GitHub (5 minutes)
1. On github.com create a **new public repository**, for example `last5days`.
2. **Add file → Upload files**: drag in **`index.html`** (and `.nojekyll`), then **Commit changes**.
3. **Settings → Pages**: *Deploy from a branch*, branch **main**, folder **/(root)**, **Save**.
4. After 1–2 minutes the site is at `https://YOUR-USERNAME.github.io/last5days/`.
   (Pages on a private repository needs a paid plan, so keep the repository public.)

To change anything later, upload a new `index.html` to the same repository.

## Facilitator access
Open the site → **Facilitator** → enter the code **2026**. The same code opens **Compare (1.1)**.
(To use another code, open `index.html` in a text editor and change `const FAC_PIN = "2026";`.)
This keeps casual visitors out; it is not strong security, because the code is inside the page file.

## Run a session
1. **Setup and group link**: a random **session code** is created for you (press *New session code* for every session). Copy the **group link** and send it to the groups.
2. Groups open the link, pick their **group number** and press **Join**. A green dot appears next to their group in your console.
3. Press **Open 5 Days**. Every group screen unlocks by itself and shows the situation and options A–D. The days are written as a countdown: **5 Days, 4 Days, 3 Days, 2 Days, 1 Day**.
4. A group chooses **one action** and presses **Lock in our choice**. It sees the effect on the **Target only**, and **its choice appears in your table by itself** (the cell flashes). You do not type anything.
5. Press **Open 4 Days** when you are ready. Each group first sees a **"Watch out" warning**: its Day 5 choice also changed **Capacity** and **Trust**, with the exact movement (for example "Capacity decreased by 8 (75% → 67%)", "Trust increased by 3", or "did not change"). From then on **every effect of every choice is shown straight away** (Target, Capacity, Trust, Continuity, with arrows ↑ ↓), and the cards show how each number moved since the last day. (You can move the reveal day in Setup.)
6. Continue with 3 Days, 2 Days, 1 Day, then **Final reveal**: everything is visible and **Real Target** (the average of Target, Capacity and Trust) is shown.
7. **Projector view** shows the room only what groups are allowed to see. Switch back to see every number.
8. **Compare (1.1)** is the debrief screen. Groups continue to **Aftermath (1.1)**: a chart of their decisions, WHAT? SO WHAT? NOW WHAT?, and Keep / Stop / Start (one item each).

You can still **edit any cell** in the table. The change is sent to that group's screen.

## Game feel
- Each stage opens with a full-screen **countdown splash** ("5 DAYS · left · Pressure Arrives"); the screen then slides in. The 4-Days stage has a warmer splash: "the numbers you could not see are about to move".
- A **progress track** (5 → 1, "days left") fills as the group plays.
- Numbers **count up or down** to their new value and flash green or coral. At 4 Days the hidden tiles **flip open** and the "Watch out" card drops in with a pulse.
- After **Lock in** a "Locked in ✓" stamp appears and the effects pop in one by one. The **Final reveal** shows the four scores in sequence and fills the Real Target bar.
- Facilitator console: a **toast** appears when a group joins or locks a choice, and scoreboard numbers move when they change.
- Devices set to "reduce motion" get no animations or splash, only the content.

## Sound effects
Sound uses short synthesized sounds (no files). It is **on by default on group screens** (after the first tap, as browsers require) and **off by default on the facilitator pages**. The **Sound on / Sound off** button in the top bar changes it for that device and is remembered.
- **Taps and choices:** a soft click on every button, a different note for options A, B, C and D, a "lock" thud-and-chime when the choice is locked.
- **Countdown:** a whoosh, a boom and **one tick for every day left** when a stage opens (5 ticks for 5 Days, 1 for 1 Day).
- **Warning (4 Days):** a siren with a low rumble, then a "flip" sparkle for each tile that unlocks.
- **Results:** a rising chime for an increase, a falling buzz for a decrease, a neutral note for no change; a glide up or down while numbers count.
- **Final reveal:** a fanfare, a note for each score and a rising sweep as the Real Target fills.
- **Other:** a welcome jingle when joining, a short error buzz for a wrong code, an "unlock" chime for a right one, and a ping on the facilitator console when a group joins or locks.

## How the live connection works
A website on GitHub has no server, so the app sends tiny messages (group number, day, letter) through the **free public relay ntfy.sh**, on a private topic built from your session code. Because of that:
- Use a **new session code for every session** (anyone who knows the code could read or send messages for that session).
- The relay keeps messages for about 12 hours. Reloading a page rebuilds the session from them.
- If a group (or the venue network) is offline, the screen shows **Live sync: offline**. That group can press **Copy** on its code (like `G3-BCA`) and send it to you; paste it in **Paste group codes**. Each day also has a **backup 4-digit code** on your console.
- Please **rehearse once with two phones** before a live session.
- Advanced: you can point the app to your own ntfy server by opening the site with `?relay=https://your-server/` in the link.

## Good to know
- Everything is saved in the browser of the device in use. *Reset session* clears the facilitator side (and creates a new session code); *Leave* clears a group device.
- The hidden effects are part of the page code, so this is a classroom tool, not a secure exam. Group devices only show the group pages.
- You can test the app offline by double-clicking `index.html` (live sync needs internet).

Built for the Skills Bank "People First Leadership for Sales Leaders" programme.
