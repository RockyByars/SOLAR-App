# SOLAR Playback — Download

**[⬇︎ Download the latest version](../../releases/latest)**

SOLAR is a native macOS app for live fill+key playback.

## Install

1. Download `SOLAR.dmg` from the [latest release](../../releases/latest).
2. Open the `.dmg` and drag **SOLAR** into your **Applications** folder.
3. Launch it — see **First launch** below, since macOS will ask you to confirm.

Requires **macOS 13 (Ventura)** or later, Apple Silicon or Intel.

## First launch — allowing the app

SOLAR is a small independent app, so the **first** time you open it macOS asks you
to confirm it's OK. This is normal and only happens once. Pick the steps for your
macOS version (Apple menu  → About This Mac to check):

### macOS Sonoma / Ventura (13–14)

1. In **Applications**, **right-click** (or Control-click) **SOLAR** → **Open**.
2. In the dialog that appears, click **Open** again.
3. It opens — and every launch after that is a normal double-click.

### macOS Sequoia (15) or later

Apple changed this in Sequoia — right-click ▸ Open no longer works, so:

1. Double-click **SOLAR** once. macOS blocks it — click **Done**.
2. Open **System Settings → Privacy & Security**.
3. Scroll down to the **Security** section. You'll see *"SOLAR was blocked…"* with an
   **Open Anyway** button — click it, then confirm with **Open Anyway** / Touch ID.
4. It opens — and future launches are a normal double-click.

### If macOS says SOLAR is "damaged" or "can't be opened"

That message doesn't mean anything is actually wrong — it's macOS being cautious
about an app downloaded from the web. To clear it, open the **Terminal** app
(Applications → Utilities → Terminal), paste this line, and press Return:

```
xattr -dr com.apple.quarantine /Applications/SOLAR.app
```

Then open SOLAR normally. (This just removes the "downloaded from the internet" flag.)

> Prefer not to do any of this? A future signed + notarized release will open with a
> normal double-click, no steps needed.

## Updates

SOLAR checks this page for new versions — **Settings ▸ General ▸ Check for Updates…**
When a newer release is published here, the app offers to download it.

## Support

Questions or issues: rocky@sweeneyandsons.tv
