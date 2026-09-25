# Splash

[Play here](https://mtg9t4.github.io/splash/)

Splash is a fluid playground that runs in your browser, on desktop and mobile. Drag your finger or mouse and paint with liquid light. Leave it alone for a few seconds and it starts painting on its own.

## What Splash adds

- **Palettes.** Seven curated color themes (Rainbow, Pump, Sunset, Neon night, Ocean, Candy, Ghost). Pick one from the panel. Your choice is remembered.
- **Ambient mode.** When nobody touches the screen for five seconds, Splash paints gentle splats by itself. Turn it off in the panel if you want full control.
- **Share links.** Every palette has a link. Hit "Copy share link" in the panel and send someone the exact look you made.
- **Screenshots.** The Capture panel saves what you painted as `splash.png`.
- **No tracking, no ads.** The analytics and mobile-app promos from upstream are gone.

Controls: drag to paint, space for a color burst, P to pause.

## Run it

No build step. Serve the folder and open it:

```bash
npx serve .
```

## Credit

Splash is a fork of [WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) by Pavel Dobryakov, used under the MIT license. The fluid solver, shaders, and simulation code are his work. Palettes, ambient mode, share links, and the rebrand are new.

## License

MIT. See [LICENSE](LICENSE).
