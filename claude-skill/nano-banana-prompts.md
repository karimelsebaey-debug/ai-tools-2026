# Nano Banana Pro — Prompt Engineering Skill

> Source: `YouMind-OpenLab/awesome-nano-banana-pro-prompts` (10,000+ prompts), `jau123/nanobanana-trending-prompts` (⭐426), `rockbenben/img-prompt` (⭐312)

## What is Nano Banana Pro?

Nano Banana Pro is a Google Gemini-powered AI image generator. It uses Imagen 3 under the hood,
making it excellent for photorealistic images, portraits, and stylized art — free tier available.

## Prompt Formula

```
[Subject + Detail] + [Action/Pose] + [Environment] + [Lighting] + [Style/Medium] + [Quality Tags]
```

## Core Style Categories (from 10,000+ prompt library)

| Category | Best For |
|----------|----------|
| Photorealistic | Portraits, products, architecture |
| Anime / Manga | Character art, scenes |
| Digital Art | Concept art, fantasy |
| Oil Painting | Fine art, landscapes |
| Watercolor | Soft illustrations |
| 3D Render | Objects, characters, sci-fi |
| Pixel Art | Retro, game assets |
| Cinematic | Movie stills, dramatic scenes |

## Prompt Templates

### Portrait / Person
```
[Gender/age] [ethnicity optional] [expression], wearing [outfit],
[hair description], [background setting], [lighting: soft/dramatic/natural],
photorealistic, 8K, sharp focus, professional photography
```

### Fantasy / Character
```
[Character type: warrior/wizard/elf], [distinctive features],
[environment: enchanted forest/castle/dungeon], [dramatic lighting],
detailed fantasy art, digital painting, trending on ArtStation
```

### Product / Commercial
```
[Product] on [surface/background], [lighting: studio/natural/neon],
[perspective: top-down/45 degree/front], photorealistic render,
commercial photography quality, clean minimal aesthetic
```

### Landscape / Environment
```
[Location: mountain/city/ocean/forest], [time of day], [weather/season],
[mood: peaceful/dramatic/mysterious], wide angle, golden hour lighting,
hyperrealistic, 8K, National Geographic style
```

### Trending Styles (from jau123 engagement data)

```
Ghibli-inspired landscape       → "in the style of Studio Ghibli, soft watercolor..."
Neon cyberpunk city             → "neon lights, rain-wet streets, cyberpunk aesthetic..."
Cozy cottagecore                → "warm interior, natural materials, soft window light..."
Dark academia                   → "vintage library, candlelight, moody atmosphere..."
Retro vaporwave                 → "pastel purple/pink palette, 80s retro, grid floor..."
```

## Quality Booster Tags

Add at the end of any prompt:
```
8K resolution, ultra detailed, sharp focus, professional, award-winning,
trending on ArtStation, masterpiece, cinematic lighting, volumetric fog
```

## Negative Prompt Tags

```
blurry, low quality, deformed, extra fingers, watermark, text, 
ugly, bad anatomy, duplicate, poorly drawn, amateur
```

## Nano Banana–Specific Tips

1. **Be specific with lighting** — "soft diffused window light from the left" beats "good lighting"
2. **Name art styles** — "Rembrandt lighting", "Monet impressionism", "Ansel Adams photography"
3. **Add medium** — "oil on canvas", "digital illustration", "film photography"
4. **Resolution tags work** — always append `8K`, `ultra detailed`, `sharp focus`
5. **Avoid overloading** — max 3–4 strong style references per prompt

## Example Prompts (Nano Banana Pro)

```
1. A young woman with long auburn hair sitting by a cafe window on a rainy day,
   warm golden interior light contrasting with grey wet street outside, contemplative mood,
   photorealistic, shot on 85mm lens, shallow depth of field, film grain, 8K

2. A majestic white wolf standing on a cliff at dawn, misty mountain valleys below,
   rays of sunlight breaking through clouds, epic fantasy digital painting,
   ultra detailed fur, dramatic atmosphere, ArtStation trending, 4K

3. Isometric 3D render of a cozy bookshop at night, warm orange light from windows,
   tiny details: stacked books, cats sleeping, potted plants, cobblestone street,
   pixel-perfect clean render, game asset style, pastel color palette
```
