# Biol 312 Parasitoid Dashboard (v2 Results)

A results dashboard for the Biol 312 parasitoid contest labs with *Trissolcus japonicus*. Pairs of females, infected (WI) or uninfected (U) with a bacterial symbiont, compete for a host egg mass in three dyad types: U x U, U x WI and WI x WI. The dashboard shows contests, behaviour and behavioural sequences, female identity, competition within dyads, offspring sex ratio, and the behaviours added to the ethogram based on student observations, using mixed models with dyad as a random effect.

**Open the dashboard:** https://drlyndonduff.github.io/parasitoid-dashboard/

The dashboard opens on a **simulated class**, generated from summary parameters only (no real records). Students upload their class workbook to see their own results and download a figure set. The workbook is read inside the browser tab; it is never sent anywhere or saved, and it disappears when the page is closed or reloaded.

The app is written in R (Shiny) and runs entirely in the web browser with [Shinylive](https://posit-dev.github.io/r-shinylive/) and webR, so nothing needs to be installed and no server is needed. The first load downloads R into the browser and can take one to three minutes while R is loading.

## Credits

- Photo: Warren Wong, Simon Fraser University (CC BY 4.0; cropped).

This repository contains only the exported website. The app's source code is included in `app.json`.
