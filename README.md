Gameplay screenshots for hair rendering parity.

aramid-hair-fix-comparison.png: initial material-field comparison; camera projection differs.

aramid-temple-fix-comparison.png: final Metal depth/discard fix, native-exported appearance, matched camera, 1280×800, 1× rendering. Left: native Kenshi 1.0.68 D3D11; middle: Meitou material fix only; right: final fix. Lossless 1:1 crops, no colour edits. Hair coverage intersection-over-union: 63.5% before the depth fix, 98.94% after; this does not measure overall image similarity. Exact compiler/driver cause and performance impact remain unverified.

Screenshots only; no original game source assets, saves, DLLs or GPU dumps. This evidence branch is separate from the code PR.
