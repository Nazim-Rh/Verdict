# Verdict — installer

Verdict is a desktop app for quickly classifying astronomical detections
as real, fake, or uncertain by eye, from each source's FITS cutout.

## Install

```bash
./install.sh
```

You'll be asked where to install (defaults to `~/Verdict`) and asked to
confirm before anything is copied. The installer sets up Verdict's
Python environment and installs its requirements right away, so the
first launch afterwards is instant — nothing is set up on first run. A
launcher icon is also added to your Desktop.

To skip the location prompt, pass a path directly:

```bash
./install.sh /path/to/somewhere
```

## After installing

Open the install folder (`~/Verdict` unless you chose another path) and
you'll only see two things:

- `Verdict.sh` — the launcher
- `README.md` — usage instructions

Once installed, just double-click **Verdict** on your Desktop, or run
`./Verdict.sh` from the install folder.

for any queries contact at knnazimrh@gmail.com
