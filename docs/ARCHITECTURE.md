# Lab 3 architecture — decision record (unselected)

**Product not defined.** No code stack, Android API floor, persistence layer or module framework has been selected.

## Non-negotiable boundaries
- Independent Android app shell and future ZIMT host integration must be possible.
- Product-specific state and logic should not depend on app package identity or Activity lifecycle.
- UI/rendering technology is chosen after interaction and performance needs are known.
- Persisted data, if introduced, needs stable IDs, explicit schema/version and safe export/import; no destructive migration.
- Haptics express semantic intentions with device-specific fallback; no universal rendering/haptic abstraction before real need.
- One authoritative state machine per critical gesture; visual effects cannot own data commits.
- Moto G6 and Nothing Phone 3a are test targets where relevant, but no invented FPS pass results.

## Decision trigger
Replace this placeholder with a short ADR once the product brief and first vertical slice are approved. Keep evidence and unknowns explicit.
