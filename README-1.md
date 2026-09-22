# Blobbish Crush — Android downloads

The APK for **Blobbish Crush**, a match-3 game, while it is being tested.

### [⬇ Download the latest version](https://github.com/blobbishfun/blobbishfunapk/releases/latest)

It is not on the Play Store yet, so this is where the builds live. Every
release here is signed with the same key, so once you have one installed the
next one updates it in place and keeps your progress.

---

## Installing it

Android will not install an app from outside the Play Store without being
told to, and it will warn you when you do. That is expected here and not
something a test build can turn off.

1. Open the link above on your phone and download the `.apk`.
2. Open it. Android will say something like *"For your security, your phone
   isn't allowed to install unknown apps from this source."*
3. Tap **Settings** on that prompt and allow it for your browser.
4. Go back and open the file again.
5. Play Protect may add *"Unsafe app blocked"* or *"Scan app?"*. Choose
   **Install anyway** / **Don't send**.

**Android 8.0 or newer.** Around 23 MB. It does not replace anything else on
your phone.

## Checking what you downloaded

Every release has a `.sha256` file beside the APK. If you want to be sure the
file arrived intact:

```bash
sha256sum blobbish-crush-1.57.1.apk
```

The output should match the contents of `blobbish-crush-1.57.1.apk.sha256`.

## If you were testing an earlier build

The builds handed round before this repository existed were **debug** builds,
which Android treats as a different app entirely — a different package name
and a different signing key. So:

- Installing a release build **will not** replace the old one. Both will sit
  on your phone until you remove the old one yourself.
- Your progress **does not** carry across. Levels, stars and boosters are kept
  on the phone, under the app that earned them.

Nothing is wrong when that happens; it is how Android tells a test build apart
from a real one. From this repository onwards, updates behave normally.

## A note on what a test build is

It is finished enough to play and not finished enough to be on a store. Levels,
scoring and the economy are still being tuned, and a later build can change
what a level asks for or what something is worth. If something is broken or
unfair, that is worth saying — it is the reason these builds exist.

## Where the game is

**[blobbish.fun](https://blobbish.fun)**

The source lives in a private repository; this one holds the downloads so that
getting the game needs no GitHub account.
