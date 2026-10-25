# Depth of Field & Exposure Simulator

**Live:** https://ado-prog.github.io/depth-of-field/

> **Credit:** This is a fork of [jherr/depth-of-field](https://github.com/jherr/depth-of-field) by [Jack Herrington](https://github.com/jherr). The original depth-of-field simulator, its calculations and graphics are his work; this fork only adds features on top. All credit for the original project goes to him. Original live demo: https://jherr.github.io/depth-of-field/
>
> Dies ist ein Fork von [jherr/depth-of-field](https://github.com/jherr/depth-of-field). Das Original stammt von Jack Herrington; dieser Fork ergänzt nur zusätzliche Funktionen.

A web app to figure out the depth of field of a camera and lens: adjust aperture, focal length and subject distance to see the near and far limits and the hyperfocal distance.

## What this fork adds

Changes by [Mustafi Studio](https://github.com/Ado-prog):

- **12 languages:** German, Bosnian, Serbian, Albanian, English, Turkish, Spanish, French, Russian, Japanese, Chinese (Mandarin), Korean
- **Camera & lens picker:** Panasonic, Sony, Canon, Nikon (with Sigma and Tamron lenses), plus DJI (Osmo, action cams, drones) and Insta360. Selecting a lens limits focal length and aperture to what it can do.
- **Camera monitor preview:** shows background blur and bokeh as the photographer would see it
- **Light scenes:** summer, spring, autumn, winter, overcast, golden hour, blue hour, night, wedding hall, party/disco, with adjustable light intensity and colour temperature
- **Exposure:** shutter speed, ISO, white balance, M and A modes, exposure meter
- **Video mode:** PAL/NTSC, frame rates, 180° shutter rule, Auto ISO, flicker warning
- **Filters:** ND (ND2–ND64000), variable ND, CPL, UV
- **Log profiles:** V-Log, S-Log2/3, C-Log2/3, N-Log, D-Log / D-Log M, I-Log, with LUT preview

Camera and lens specs are approximate and for illustration only.

## Getting Started

```bash
npm install
npm run dev
```

## License

The original project does not include a license, so its code remains © Jack Herrington. This fork is shared on GitHub for viewing and learning, not for commercial use.
