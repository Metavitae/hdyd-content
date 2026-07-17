# hdyd-content

Public, auto-updated content for [HDYD](https://github.com/Metavitae/libre-group-backup) (private repo — this exists so the app can fetch fresh content without exposing that repo).

`playerNames.json` is regenerated daily by a GitHub Action running in the private HDYD repo, which calls an AI model to write a fresh batch of funny solo/group dancer names, then pushes the result here. The app fetches this file at runtime via jsDelivr's GitHub CDN.

Do not edit `playerNames.json` by hand — it gets overwritten daily. If it goes stale or missing, the app falls back to a hardcoded name list built in.
