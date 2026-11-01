# Krit Two-Set v2.2 — Keyman source

This ZIP contains Keyman **source**, NOT an installable .kmp package.

Files:
- krit.kmn — Keyman keyboard source
- krit.keyman-touch-layout — iPhone touch layout (default and shift layers)

## Build
1. Open krit.kmn in Keyman Developer (Windows), or a compatible Keyman build environment.
2. Compile the keyboard for mobile; inspect any compiler errors and confirm the touch layout in the simulator.
3. Create a Keyman package (.kps) containing the compiled mobile .js and metadata, then build a .kmp.
4. Transfer the .kmp to the iPhone and install it through Keyman.

## Important
- The keyboard was not compiled or tested in Keyman Developer here. It is NOT yet an iPhone-installable package.
- Layout matches the previously approved v2.2 draft including comma and period in row 3. The Shift counterpart of Δ is now ∇ (U+2207), replacing Λ.
- The draft has duplicate З output on shift, and the role of е versus æ remains unresolved.
- `a` and Cyrillic `а` are equivalent in the constructed language but the main key currently outputs Latin `a`.
- Shift is a toggled layer; automatic one-character shift reset is not implemented.
- Keyman may adjust sizing or system keys on actual iOS devices.
