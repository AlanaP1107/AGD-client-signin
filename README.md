# AGD Client Check In — Version 2.1 FINAL

This package uses the exact AGD logo supplied for the project.

## Upload all seven files

Upload these files to the main/root area of the GitHub Pages repository:

- `index.html`
- `agd-logo.png`
- `favicon.png`
- `apple-touch-icon.png`
- `icon-192.png`
- `icon-512.png`
- `manifest.webmanifest`

Do not upload the ZIP itself. Unzip it first, then upload the files inside.

## GitHub upload steps

1. Open the repository.
2. Select **Add file**.
3. Select **Upload files**.
4. Drag all seven files into the upload area.
5. Choose **Commit changes**.
6. Allow GitHub Pages about one or two minutes to rebuild.
7. Refresh the published site.

## Add it to the iPad Home Screen

1. Open the published GitHub Pages address in Safari.
2. Tap Safari’s **Share** button.
3. Select **Add to Home Screen**.
4. Use the name **AGD Client Check In**.
5. Tap **Add**.

If the iPad still shows an older icon, delete the old Home Screen shortcut and add it again.

## Included behavior

- Exact AGD logo
- AGD Client Check In app name
- Embedded Morning IOP/MHDT Microsoft Form
- Embedded Afternoon Wellness Microsoft Form
- Existing Form URLs preserved
- Existing Power Automate flows unchanged
- Welcome / “Preparing your sign-in…” transition
- Small Home button
- Hidden five-minute reset timer
- Automatic return to the welcome screen
- Form cleared when returning home
- iPad Home Screen icon and browser favicon

## Timer limitation

Microsoft Forms is embedded from another domain. Browser privacy rules prevent the surrounding page from detecting every tap made inside that form. The five-minute reset still operates, and activity visible to the surrounding page resets it, but a very slow form completion could reach five minutes even while the client is interacting inside Microsoft Forms.
