# v1.8.62 wheel_delta_notch_fix

Release date: 2026-06-10

## Summary

This build improves mouse wheel rollback detection.

## Changes

- Convert Windows wheel Delta values into standard wheel notches.
- Accumulate small Delta values until they reach one standard notch.
- Count wheel up/down by notches instead of raw event count.
- Detect rollback by stable scroll intent, opposite notches, and quick return to original direction.
- Keep version number at `1.8.62` for internal build continuity.

## Installer

File:

`AKLPeripheralDiagnosticPlatform_Setup_v1.8.62_wheel_delta_notch_fix.exe`

SHA256:

`AD2FFD55E3D5C38F7D7D4F651BE18D7367BAD73F185E0AEA196D952D6E9B9389`

Size:

`99707430`

