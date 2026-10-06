# LT Training

Independent clean-slate copy of the PPLUL workout app. Starts at Week 1 with no logged weights, reps, effort, completion or history. No original workout files or Git history are included.

Workouts save locally on each browser/device. Use Backup & settings to export JSON backups. Optional GitHub sync is restricted in code to this repository; it requires a separately supplied token with access to LT-PPLUL only. Never share a token for the original repository.

Browser database, authentication keys and service-worker caches use the lt-pplul namespace. The original app is unchanged.

Spotify requires a separately configured Spotify application: set CLIENT_ID in spotify.js and register this copy's exact HTTPS URL as its redirect URI. No Spotify login or token is copied.

This repository serves its static app files directly from the main branch root using GitHub Pages.

