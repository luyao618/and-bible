# AndBible issue #3880 — browser component evidence

These images are produced by mounting the actual baseline and modified `WordType.vue` side by side in a browser. Both panels receive the same first-letter-mode input `F`. The baseline rejects it for `“For` and `¶For`; the fixed component advances to `God`, preserves the marker, and records no error.

- Baseline: upstream `current-stable` commit `7e73c11508f32e4f531d531f6d5b110dd2a1f204`.
- The modified component is identified by its SHA-256 in `source-manifest.json`.
- Light, night, monochrome, and no-animation host configurations were checked, with zero browser exceptions.
- Settings and strings are mocked, matching the component-test boundary. Text is a literal fixture, **not a loaded NASB/KJV module**.
- These are **not Android application/device screenshots**.
- This evidence-only branch is not part of the pull request's source diff.
