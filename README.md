# Harada OS

A free, single-file goal tracker built on the **Harada method**: the system used by Japanese teacher Takashi Harada, and made famous by baseball player Shohei Ohtani's goal chart.

It runs in your browser. There is no account, no server and no tracking. Your entries stay on your own device.

**Live page:** `https://YOUR-USERNAME.github.io/harada-os/`

---

## What it does

Harada OS turns two big goals into a daily routine you can actually follow.

| Tab | What it is for |
| --- | --- |
| **Today** | The daily checklist, a "minimum day" box, your numbers for the day, energy score and a 5-question diary. |
| **Charts** | The 64-square Open Window chart for each goal: 1 goal, 8 pillars, 8 actions per pillar. |
| **Plan** | Your two goal sheets, your daily routine, and a timeline of checkpoints. |
| **Progress** | Charts and bars for each goal, your streak, and a 20-week consistency grid. |
| **Review** | A weekly review (Sunday) and a monthly review, with the numbers filled in for you. |
| **Rules** | If-then rules that decide in advance what you do when your usual trap shows up. |

## The idea in one minute

1. Write one clear goal with a number and a date.
2. Break it into 8 pillars, then 8 actions under each pillar. That is the 64-square chart.
3. Turn the actions into a short daily routine.
4. Choose 2 or 3 **minimum items** you will do even on a terrible day. When they are ticked, the day counts and your streak continues.
5. Write a short diary each night. Review every week and every month, then change what is not working.

The system is built to keep you going on bad days, not to make you feel bad about them.

## Getting started

1. Open the page.
2. Go to **Plan** and read "How this works".
3. Rewrite the two example goals. Choose how each is measured:
   - **Count things done** (lessons, pages, sessions)
   - **Reach a number** (weight, savings, running time)
4. Set your deadline, then edit your **Daily routine**. Tick **Minimum** on the 2 or 3 items that matter most.
5. Fill in the 64-square chart for each goal on the **Charts** tab.
6. Use **Today** every day. Do a review on **Review** every Sunday.

If you want a blank page, press **Clear the example text** at the bottom of the Plan tab.

## Everything is editable

- Goal names, units, targets and deadlines
- The whole daily routine (groups, items, which ones are minimum)
- All 64 squares of both charts
- Checkpoints, parts of a goal (for example the courses you are taking) and your rules

## Where your data lives

Your entries are saved in your **browser's local storage** on the device you use. They are not sent anywhere and they are not stored in this repository.

That has a few consequences:

- A different phone, computer or browser starts empty.
- Clearing site data, or using a private window, removes or skips your entries.
- Nobody else, including the owner of this page, can see what you write.

**Back up regularly.** Open the **Rules** tab, scroll to **Backup**, and press **Export backup**. It saves everything to a `.json` file. Use **Import backup** to load it on another device or after a reset.

## Run it on your own computer

You do not need to install anything.

1. Download `index.html`.
2. Put it in a folder that you will not move.
3. Open it in a browser.

Keep the file in the same place and use the same browser each time, because the browser ties your saved data to that file location. On some privacy-focused setups, check that your browser is not set to delete site data on close.

## Host your own copy

This is a single static HTML file, so any static host works. On GitHub Pages:

1. Fork this repository, or create a new one and upload `index.html`.
2. Go to **Settings, Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. Your page appears at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/` after about a minute.

## Technical notes

- One HTML file with inline CSS and JavaScript. No build step and no dependencies.
- Text uses Google Fonts when online and falls back to system fonts when offline.
- Works in current versions of Firefox, Chrome, Edge and Safari, on desktop and phone.
- Light and dark mode follow your system setting.

## License

Choose a license for your repository, for example MIT, and add a `LICENSE` file.

---

*Harada OS is an independent tool. It is not affiliated with Takashi Harada or any athlete mentioned above.*
