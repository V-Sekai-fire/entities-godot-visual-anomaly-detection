# entities-godot-visual-anomaly-detection

A one-class visual anomaly detector, trained on images of normal avatar poses, for spotting rendering bugs.

## What it is for

It trains a one-class anomaly model on a folder of normal images and scores new images against it, so a render that departs from the normal set stands out.

## Build and run

```sh
just train
just predict
```

Both need a Python environment with the `anomalib` package installed.

## Licence

MIT; see `LICENSE`.
