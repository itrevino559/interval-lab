# Interval Lab (published copy)

PUBLIC repo itrevino559/interval-lab → https://itrevino559.github.io/interval-lab/ (GitHub Pages from main, root).
Everything here is public. Credit is "Made by Ivan · © 2026" only — no last name, school, or contact info without asking.

Interval Lab is a classroom spin-off of Tone Studio (~/Desktop/Claude/Tone Studio) for grades 6–12 music students.
The app has four tabs (Tuning, Harmonics, Intervals, Temperament), each with Simple/Advanced modes. Tones are sine waves,
except Tuning and Temperament, which use a harmonic-rich tone so beats are audible. The current draft is built in
~/Desktop/Claude/Misc Claude/interval-lab-v2.html and copied over index.html to publish.
index.html is the whole app: one self-contained file with no outside requests (no CDNs, fonts or analytics); keep it that way
so it works offline on school Chromebooks and iPads. Keep the doctype, `lang`, charset, viewport and description meta,
and keep the credit footer ("Interval Lab · Made by Ivan · © 2026") at the end of `.wrap`.

To publish an update: edit index.html, check it in a browser, then commit and push to main; Pages redeploys in a minute
or two. Commits are signed through 1Password (app must be open; approve Touch ID in Ivan's terminal) and use GitHub's
noreply email. Ivan is new to git: explain changes in plain English.
