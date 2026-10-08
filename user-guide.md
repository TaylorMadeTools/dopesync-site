---
layout: page
title: User Guide
permalink: /user-guide/
---

## 1. Install

1. **Watch:** install **DOPE Sync** from the Connect IQ Store (Connect IQ app on your phone), then sync your watch.
2. **Phone:** install the **DOPE Sync** app (Android: Google Play; iPhone: in testing).
3. Make sure your watch is paired with **Garmin Connect** on the phone.

Open DOPE Sync on the phone once. The status screen shows Garmin Connect, your watch, and whether the watch app is installed.

<img src="{{ site.baseurl }}/images/iphone-status.png" alt="DOPE Sync status screen" width="260">

**iPhone only:** tap **Choose watch in Garmin Connect** once. Garmin Connect opens, you pick your watch, and it comes back to DOPE Sync.

## 2. Send a card

| From | Steps |
|---|---|
| GeoBallistics (stage card) | Comp tab > Export > CSV > Share > **Send to Garmin** (Android) / **DopeSync** (iPhone) |
| GeoBallistics (full chart) | Chart > Export > CSV > Share > Send to Garmin / DopeSync |
| Applied Ballistics | Export > Share > Send to Garmin / DopeSync |

The phone confirms with "N targets sent to your watch" once the watch has received it. If something's wrong with the file, the phone says so and **nothing is sent** to the watch.

## 3. Open it on the watch

- **Start**, then **DopeSync** (tip: move it to the top of the Start list so it's two presses).
- If the app is closed when a card arrives, the watch buzzes and shows **"4 targets ready"** with **Launch / Dismiss**. Press Start on **Launch**.
- If the app is already open, the new card just appears.

## 4. Reading the card

<figure class="ds-fig"><img src="{{ site.baseurl }}/images/watch-gb-card.png" alt="GeoBallistics card" width="260"><figcaption><strong>GeoBallistics</strong> stage card</figcaption></figure>

| Part | Meaning |
|---|---|
| Title | Rifle / profile name from your ballistic app |
| YD / M | Target number (stage order, never sorted) and range |
| ELEV | **U** up / **D** down, in your hold units (MRAD or MOA) |
| WIND | **R** right / **L** left. Two-wind AB cards show a range, e.g. `R 0.2-0.3` under `W10-15` |
| Footer | Wind speed and clock position relative to your shot, e.g. `22 MPH @ 6:00` |
| Dots on the right | Pages: Up/Down to flip |
| `--` | Your solver had no solution for that row (for example past its range limit) |
| `STALE 14h` | The stage card is older than your stale setting |

## 5. Stage card and pins

- Every new share replaces the **stage card**.
- **Pin** a card to keep it: hold **Up** (Menu) > **Pin this card**. Pinned cards are never overwritten (up to 5).
- Hold **Up** > **Cards** to switch between the stage card and your pins.
- **Clear stage card** and **Delete this card** ask to confirm first.
- Hold **Up** > **About** shows the version.

## 6. Watch settings

In the Connect IQ app on your phone (DOPE Sync > Settings):

| Setting | Default |
|---|---|
| Tactical mode (black and red only) | Off |
| Stale after (hours) | 12 |
| Prompt to open on new card | On |

## Troubleshooting

| Problem | Fix |
|---|---|
| "No Garmin watch connected" | Open Garmin Connect, make sure the watch is connected, try again. iPhone: tap Choose watch. |
| "Watch didn't confirm" | Open DOPE Sync on the watch and share again. |
| "Not a GeoBallistics or Applied Ballistics range card" | Export as CSV from one of those apps. Other files are ignored on purpose. |
| Card shows `--` on some rows | The ballistic app had no solution there (free versions limit range). |
