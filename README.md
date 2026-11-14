# Senko

**Senko** (閃光, "flash") is a free After Effects panel made for anime and AMV editors.
Works in After Effects 2020 to 2026, on Windows and Mac, on any hardware: a gaming
graphics card, integrated graphics, or just the processor.

## Download

👉 **[Get the latest version](https://github.com/yur0fx/senko/releases/latest)**

- **Windows:** download `Senko-Setup-x.x.x-exe.zip`, unzip it, close After Effects and run
  `Senko-Setup-x.x.x.exe`. If Windows shows "Windows protected your PC", click
  **More info → Run anyway**.
- **Mac:** download `Senko_vx.x.x.zip`, unzip it, close After Effects, then right-click
  `Install-Mac.command` → **Open**.

Then start After Effects and open **Window → Extensions → Senko**.

Senko updates itself: when a new version is out, the panel offers it with one click.

## What's in it

- **Upscale & interpolate**: one card to upscale (Real-CUGAN / Real-ESRGAN) and add in-between
  frames (RIFE, or **GMFSS Anime** for much less warping on big moves). Interpolation keeps the
  clip length and skips held frames. Options live in their own **Settings** window.
- **Content fill**: remove things from video, like Content-Aware Fill but faster: the real background comes from
  other frames, and AI fills only what no frame shows, without flicker. Own panel: **Senko Content Fill**.
- **Object mask**: click or paint (like Roto Brush) on a character to mask it through the whole clip, in its own floating
  window. Green dots add, red dots cut out gaps (between arms, legs, hair). Pick **Fast**,
  **Standard** or **Best** model, and **AI fine** edges for hair and fur.
- **Duplicate Frame Remover**: finds and removes repeated frames in anime footage
- **Scene cut finder / Sequence**: finds every cut in a clip and splits it into layers
- **Graph**: a value graph for easing keyframes, with an eyedropper and custom handles
- **Presets**: quick-apply effects, presets and curves (double-click to apply), FX Console style
- **Senko Bar**: your own buttons for menu commands, scripts, effects and code
- **Device choice**: every AI tool can run on Auto, your dedicated card, integrated graphics or
  the processor, so it works on low-end PCs too
- **Look**: Glass or Flat theme, with optional glow

AI models download the first time you use them, so the installer stays small.

## What's new

- **4.54.4**: Object mask and Content fill work on the whole clip when the work area misses it.
- **4.54.3**: Content fill no longer tears the background on still shots.
- **4.54.2**: Content fill no longer leaves an outline round glowing characters.
- **4.54.1**: Content fill no longer leaves a thin outline round the fill.
- **4.54.0**: Object mask brush like Roto Brush, unlimited strokes, AI fine edges.
- **4.53.0**: new **Content fill** tool.
- **4.52.4**: curves now work on Mask Path and shape Path keyframes.
- **4.52.3**: GMFSS Anime is offered only with a dedicated graphics card, and always runs on it.
- **4.52.2**: GMFSS Anime runs fully on the graphics card, with a faster motion search and less memory.
- **4.52.1**: GMFSS Anime interpolation model.
- **4.52.0**: compact Upscale & interpolate card, Settings window, Less warp option.
- **4.51**: Interpolate skips held frames; fix for "Couldn't write the matte".
- **4.50**: new Glass look, eyedropper picks from the comp, Object mask reaches the frame edges.
- **4.49**: Object mask in its own window; fixed update check.
- **4.47 – 4.48**: much faster interpolation.
- **4.44 – 4.46**: automatic error reports, smoother mask preview, red dots cut out small gaps.
- **4.37 – 4.43**: device choice per tool, interpolation keeps clip length, no more grey or
  see-through clips, native timeline label colours, Sequence trims each cut.
- **4.34 – 4.36**: Upscaler works without a Vulkan card, one Upscale & interpolate card,
  double-click presets, Fast / Standard / Best mask models.

## Feedback

Found a bug or have an idea? Use the **speech-bubble button** at the top of the panel
to send it straight to me.

Made by **yuro.m4a** · [TikTok](https://www.tiktok.com/@yuro.m4a)
