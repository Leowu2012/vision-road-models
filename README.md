# Vision Road models

Model files the Vision Road app downloads (it cannot download from its private repository).

- `ufldv2-<sha12>/part-NN`: Ultra-Fast-Lane-Detection v2, ResNet18, CULane
  ([cfzd/Ultra-Fast-Lane-Detection-v2](https://github.com/cfzd/Ultra-Fast-Lane-Detection-v2),
  MIT license), converted to LiteRT (FP16) by `scripts/convert_ufldv2.py` in the app's repository.
  The pieces are 45 MB each (git keeps files under 100 MB); joined in order they give the
  `.tflite` file whose SHA-256 begins with `<sha12>`.
