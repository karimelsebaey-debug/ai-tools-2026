# Kling AI — Prompt Engineering Skill

> Source: `DareDev256/Ultimate-Image-Video-Prompt-Generator`, `donghaozhang/ai-video-prompts`, `danvufs/Runway-Kling-prompt-generator`

## Prompt Formula

```
[Subject] + [Action/Motion] + [Scene/Environment] + [Camera Movement] + [Lighting] + [Style] + [Duration/Mood]
```

## Core Parameters

| Parameter | Values |
|-----------|--------|
| Model | Kling 1.0 / Kling 1.5 / Kling 2.0 / Kling 3.0 |
| Duration | 5s / 10s |
| Aspect Ratio | 16:9 / 9:16 / 1:1 |
| Mode | Standard / Pro / Master |
| Camera | Static / Pan / Zoom / Orbit / Tracking |

## Prompt Templates

### Cinematic Scene
```
A [character description] walking through [location], [time of day], [weather condition],
slow tracking shot, cinematic lighting, [film style] style, high detail, 4K quality
```

### Product Showcase
```
[Product name] rotating on [surface], studio lighting, clean white background,
subtle reflections, professional product photography style, slow 360 zoom
```

### Nature / Landscape
```
[Scene: forest/ocean/mountain], [time: golden hour/night/dawn], [weather],
wide establishing shot slowly zooming in, volumetric lighting, photorealistic, epic scale
```

### Portrait / Character
```
Close-up of [character], [emotion], [environment], soft bokeh background,
natural light, slight camera drift, film grain, [era] style
```

## Camera Movement Keywords

- `slow push in` — gradual zoom towards subject
- `pull back reveal` — starts close, pulls back to reveal scene
- `orbit shot` — 360° around subject
- `crane up` — camera rises from ground level
- `handheld` — natural, slightly shaky movement
- `dolly zoom` — Hitchcock/Vertigo effect

## Style Modifiers

```
cinematic | hyperrealistic | anime | 3D rendered | vintage film
stop motion | watercolor | neon noir | documentary | dreamlike
```

## Negative Prompt Tips

Kling supports negative prompts — use to avoid:
```
blurry, distorted faces, extra limbs, watermark, text overlay, low quality, artifacts
```

## Do's and Don'ts

| Do | Don't |
|----|-------|
| Specify camera movement explicitly | Leave motion vague |
| Include lighting direction | Use only generic "good lighting" |
| Set scene context clearly | Overload with conflicting styles |
| Use cinematic language | Use abstract/poetic only descriptions |
| Specify aspect ratio for social | Ignore platform format |

## Example Prompts (Kling 3.0)

```
1. A lone astronaut walks across a red Martian desert at sunset, slow tracking shot,
   dust particles floating, dramatic orange sky, cinematic widescreen, photorealistic

2. Cherry blossom petals falling in slow motion over a traditional Japanese garden,
   koi pond reflecting pink light, gentle breeze, overhead drift shot, 4K, peaceful

3. Futuristic city skyline at night with flying cars, neon reflections on rain-wet streets,
   slow crane reveal upward, cyberpunk style, ultra detailed, Blade Runner aesthetic
```
