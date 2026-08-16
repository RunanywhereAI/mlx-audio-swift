# RunAnywhere mlx-audio-swift fork

This fork tracks canonical `Blaizzy/mlx-audio-swift`. RunAnywhere tags exist
only to make the Apple runtime dependency graph deterministic: every MLX audio
target resolves the same RunAnywhere `mlx-swift` and `mlx-swift-lm` releases as
the SDK's LLM path.

Release `0.1.5` is based on canonical commit `cae704f` and pins:

- `RunanywhereAI/mlx-swift` `0.31.8`
- `RunanywhereAI/mlx-swift-lm` `3.31.5`

No audio model implementation is carried only in this fork; upstream audio
changes should continue to be merged from the canonical repository.
