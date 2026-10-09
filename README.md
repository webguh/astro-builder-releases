# Astro Builder

A desktop app for building [Astro](https://astro.build) websites visually. Open a site, click anything on the page, and edit its text, attributes and styles. Every change is written straight back into your source files, so the project stays a normal Astro codebase you can open in any editor.

## Download

**[Get the latest version](https://github.com/webguh/astro-builder-releases/releases/latest)**. Under **Assets**, pick the file for your computer:

| Computer | File |
| --- | --- |
| Windows (regular and Arm PCs) | `astro-builder-<version>-setup.exe` |
| Mac (Apple Silicon and Intel) | `astro-builder-<version>-universal.dmg` |

Every computer also needs [Node.js](https://nodejs.org) 22.12 or newer. The app tells you if it can't find it.

## Install on Windows

1. Run the `.exe`.
2. Windows says it "protected your PC" because the installer isn't signed yet. Click **More info → Run anyway**.

## Install on Mac

1. Open the `.dmg` and drag **Astro Builder** into **Applications**.
2. The first time you open the app, macOS blocks it because it isn't signed yet. Go to **System Settings → Privacy & Security** and click **Open Anyway**.
3. If macOS says the app is "damaged", run this in Terminal instead:
   ```
   xattr -cr "/Applications/Astro Builder.app"
   ```

## Problems or ideas

[Open an issue](https://github.com/webguh/astro-builder-releases/issues) on this repository.

## License

Astro Builder is released under the MIT license. The license, and those of the open-source software built into the app, ship inside it: in `Resources/licenses` on Mac, and in the install folder's `resources\licenses` on Windows.
