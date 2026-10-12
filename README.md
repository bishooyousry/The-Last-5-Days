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
3. Press **Open Day 5**. Every group screen unlocks by itself and shows the situation and options A–D.
4. A group chooses **one action** and presses **Lock in our choice**. It sees the effect on the **Target only**, and **its choice appears in your table by itself** (the cell flashes). You do not type anything.
5. Press **Open Day 4** when you are ready. Each group first sees a **"Watch out" warning**: its Day 5 choice also changed **Capacity** and **Trust**, with the exact movement (for example "Capacity decreased by 8 (75% → 67%)", "Trust increased by 3", or "did not change"). From then on **every effect of every choice is shown straight away** (Target, Capacity, Trust, Continuity, with arrows ↑ ↓), and the cards show how each number moved since the last day. (You can move the reveal day in Setup.)
6. Continue to Day 3, Day 2, Day 1, then **Final reveal**: everything is visible and **Real Target** (the average of Target, Capacity and Trust) is shown.
7. **Projector view** shows the room only what groups are allowed to see. Switch back to see every number.
8. **Compare (1.1)** is the debrief screen. Groups continue to **Aftermath (1.1)**: a chart of their decisions, WHAT? SO WHAT? NOW WHAT?, and Keep / Stop / Start (one item each).

You can still **edit any cell** in the table. The change is sent to that group's screen.

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
