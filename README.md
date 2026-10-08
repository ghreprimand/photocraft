# PhotoCraft Auto scaling PR evidence

These images are solely evidence for the upstream contribution that makes Auto UI scale follow desktop/browser DPI.

- `before-effective-200.png`: the old Auto behavior on 4K displays, reproduced with a 200% effective UI scale in the offscreen harness.
- `after-native-125.png`: Auto using a 125% native scale. Both comparison images render the same 2560 × 1440 physical area with the patched UI harness; the before image simulates the old effective scale rather than claiming to be an unpatched binary.
- `native-167.png`: actual native Wayland window captured on a desktop monitor configured for 166.6667%; the control channel reported 1.6666666 pixels per point.

All images show PhotoCraft's empty home UI, with no personal documents or other applications. ArtCraft marks remain unchanged in this contribution-only fork, as allowed by PhotoCraft's brand license.
