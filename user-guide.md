---
layout: page
title: User Guide
permalink: /user-guide/
---

## 1. Install

1. **Watch:** install **DOPE Sync** from the Connect IQ Store (Connect IQ app on your phone), then sync your watch.
2. **Phone:** install the **DOPE Sync** app. Android is in beta (testers get a Google Play test link); iPhone is in testing.
3. Make sure your watch is paired with **Garmin Connect** on the phone.

<p class="ds-note">DOPE Sync is in beta. The store listings are coming soon; <a href="mailto:taylor@taylormadetech.io?subject=DopeSync%20beta">ask to join the beta</a>.</p>

Open DOPE Sync on the phone once. The status screen shows Garmin Connect, your watch, and whether the watch app is installed.

<img class="ds-phone" src="{{ site.baseurl }}/images/iphone-status.png" alt="DOPE Sync status screen" width="260">

**iPhone only:** tap **Choose watch in Garmin Connect** once. Garmin Connect opens, you pick your watch, and it comes back to DOPE Sync.

## 2. Send a card

| From | Steps |
|---|---|
| GeoBallistics (stage card) | **Comp** tab > Export > **CSV** > **DopeSync** in the share menu |
| GeoBallistics (full chart) | **Chart** tab > Export > **CSV** > **DopeSync** |
| Applied Ballistics | Export > **CSV** > **DopeSync** |

On Android the share menu shows **DopeSync** with "Send to Garmin" under it. You can leave right away: a short "Sending card to watch" notification shows while it sends.

When the watch confirms, the phone shows **"4 targets sent to fenix 6 Pro"** (your watch's name). If something's wrong with the file, the phone says so and **nothing is sent** to the watch.

## 3. Open it on the watch

- **Start**, then **DopeSync** (tip: move it to the top of the Start list so it's two presses).
- If the app is closed when a card arrives, the watch buzzes and shows **"4 targets ready"** with **Launch / Dismiss**. Press Start on **Launch**.
- If the app is already open, the new card just appears.

## 4. Reading the card

<figure class="ds-fig"><img src="{{ site.baseurl }}/images/watch-gb-card.png" alt="GeoBallistics card" width="260"><figcaption><strong>GeoBallistics</strong> stage card</figcaption></figure>

| Part | Meaning |
|---|---|
| Title | Rifle / profile name from your ballistic app |
| YD / M | Target number or letter (stage order, never sorted) and range. Chart exports have no target column, so only the range shows. |
| ELEV | **U** up / **D** down, in your hold units (MRAD or MOA), to one decimal. Applied Ballistics' two-decimal holds are rounded (1.23 shows as 1.2). |
| WIND | **R** right / **L** left. Two-wind AB cards show a range, e.g. `R 0.2-0.3` under `W10-15` |
| Footer | Wind speed and clock position relative to your shot, e.g. `22 MPH @ 6:00` |
| Dots on the right | Pages: Up/Down to flip |
| `--` | Your ballistic app didn't give a hold for that row. With Applied Ballistics' free version this happens past its range limit; a paid AB plan fills them in. |
| `STALE 14h` | The stage card is older than your stale setting |

## 5. Stage card and pins

- Every new share replaces the **stage card**.
- **Pin** a card to keep it: hold **Up** (Menu) > **Pin this card**. Pinned cards are never overwritten (up to 5).
- Hold **Up** > **Cards** to switch between the stage card and your pins.
- **Clear stage card** and **Delete this card** ask to confirm first.
- Hold **Up** > **About** shows the version.
- **Tactical mode** (black and red only): **hold Start** for about a second on the card, or hold **Up** > **Tactical mode**.

## 6. Watch settings

In Garmin Connect on your phone (your watch > Activities & Apps > DOPE Sync > Settings), or the Connect IQ app:

| Setting | Default |
|---|---|
| Tactical mode (black and red only; also hold Start on the watch) | Off |
| Stale after (hours) | 12 |
| Prompt to open on new card | On |
| On this watch (read-only list of your stage card and pins) | - |
| Paste a card (no phone app needed) | Empty |
| Last pasted card (read-only result of the last paste) | - |

**Paste a card:** open the CSV your ballistic app exported, copy all of its text, and paste it into this box. The next time the watch syncs settings (or you open DOPE Sync), it becomes the stage card and the box empties. One card at a time, up to 4000 characters. If it can't be read, **Last pasted card** says why. Settings may not appear while DOPE Sync is in beta.

## Troubleshooting

| Problem | Fix |
|---|---|
| "No Garmin watch connected" | Open Garmin Connect, make sure the watch is connected, try again. iPhone: tap Choose watch. |
| "Delivered to ... Open DopeSync on your watch" | The card reached the watch; open DOPE Sync to see it. |
| "Watch didn't confirm" | Open DOPE Sync on the watch, make sure Bluetooth is on, and share again. |
| "Not a GeoBallistics or Applied Ballistics range card" | Export as CSV from one of those apps. Other files are ignored on purpose. |
| Card shows `--` on some rows | Your ballistic app gave no hold for those rows (for example past Applied Ballistics' free-version range limit). |
