# bzor · MIDI Stepping Stones

Version 1.0.0 · Nintendo 64 homebrew

Four musical parts hop across folded faces in time with a stereo soundtrack. Stones rise into place on each hit, sustained notes extend light trails, and eight palettes recolor the entire scene. The song runs for about 57 seconds, followed by a scrambled restart prompt and social links.

Follow on X: **@bzor** · Instagram: **@bzorsystems**.

## Play on SummerCart64

1. Extract this ZIP.
2. Copy `bzor-midi-stepping-stones-v1.0.0.z64` to your SummerCart64 SD card.
3. Launch the ROM from the cartridge menu with a controller in port 1.

The soundtrack and visuals are included in the ROM. The build targets NTSC timing, uses standard 4 MiB RAM and does not require an Expansion Pak or save storage. This version has been checked in Ares v148; a physical-console check of this exact version is still pending.

## Controls

| Action | N64 controller | Ares keyboard mapping |
| --- | --- | --- |
| Restart / replay | A (B also works) | Space (R also works) |
| Pause / resume | Start | Return |
| Previous / next palette | D-pad left / right | A / D |
| Show / hide tuning | D-pad down | S |
| Show / hide labels | D-pad up | W |
| Select tuning row / change value | Stick up-down / left-right | Arrow keys |
| Full / low bass note display | Z | Z |
| Previous / next song cue | L / R | Q / E |

Keyboard bindings depend on your emulator configuration. “PRESS A TO RESTART” refers to the controller's A button.

The UI starts hidden. Ion Storm is the default palette; the others are Neon, Acid Signal, Cold Front, Hotwire, Ultraviolet, Rust Bloom and Afterglow. A palette name appears briefly when cycling. Restart keeps your current palette and tuning, while reopening the ROM restores defaults.

Default tuning: bounce 50, scroll 72, pitch width 140, trail 10, sync −40 ms and music 90. Full bass and atmosphere are on. Sync adjusts the visuals relative to the soundtrack; negative values delay the visuals. Restart includes a two-second silent lead-in for the first stones.

## Verify

`SHA256SUMS.txt` lists the SHA-256 of the ROM, this guide and the third-party notices. On macOS/Linux, run `shasum -a 256 -c SHA256SUMS.txt` in the extracted folder.

See `THIRD_PARTY_NOTICES.txt` for component credits and notices.
