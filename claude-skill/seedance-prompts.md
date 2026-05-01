# Seedance 2.0 — Prompt Engineering Skill

> Source: `ZeroLu/awesome-seedance` (actively maintained), `donghaozhang/ai-video-prompts` (170+ curated prompts)

## What is Seedance 2.0?

Seedance 2.0 is ByteDance's AI video generation model, known for high-fidelity motion,
character consistency across frames, and strong cinematic output. Particularly strong
for anime, UGC, social media content, and advertising.

## Prompt Formula

```
[Subject + Appearance] + [Action/Motion] + [Scene/Setting] + [Camera Work] + [Lighting] + [Style] + [Pacing/Mood]
```

## Seedance 2.0 Strengths

| Strength | Use Case |
|---------|----------|
| Character consistency | Multi-shot storytelling |
| Smooth motion | Dance, sports, fluid animation |
| Anime fidelity | Japanese animation style |
| Realistic physics | Water, cloth, hair movement |
| Social media formats | Vertical 9:16 shorts |
| Advertising clarity | Product + message delivery |

## Prompt Templates by Category

### Cinematic Film
```
[Character description] [action] in [location], [time of day],
[camera: slow dolly/crane/tracking], [lighting: dramatic/soft/natural],
film noir / epic / thriller style, cinematic color grade, 24fps film look
```

### Anime Style
```
[Anime character] with [distinctive features] [action], [Japanese setting],
sakura petals / rain / snow falling, fluid anime animation,
[studio style: Ghibli / Makoto Shinkai / Trigger], vibrant colors, smooth motion
```

### UGC / Social Media (9:16 Vertical)
```
Vertical format, [relatable everyday situation],
[natural handheld camera feel], authentic lighting, real-person style,
fast cut energy / slow satisfying reveal, trending social media aesthetic
```

### Advertising / Brand
```
[Product/brand element] hero shot, [environment matching brand identity],
smooth camera reveal, professional lighting, [color palette],
clean modern aesthetic, 15-second commercial pacing
```

### Meme / Comedy
```
[Setup scenario], [unexpected twist action], exaggerated reaction,
quick cuts, comedic timing, bright saturated colors,
internet meme visual language, punchy 3–5 second loop
```

## Camera Motion Keywords (Seedance)

```
slow zoom in        | quick cut to close-up
tracking left/right | push-in reveal
static locked shot  | drift/float movement
dutch tilt          | overhead top-down
whip pan            | smooth orbit
```

## Seedance-Specific Tips

1. **Character consistency** — describe character fully on first mention; Seedance maintains it
2. **Motion specificity** — "slowly raises hand" beats "moves"
3. **Pacing words** — "fast-paced", "slow and deliberate", "rhythmic to beat"
4. **Reference real directors/styles** — "Wong Kar-wai color palette", "Miyazaki movement"
5. **Vertical format** — always specify `9:16 vertical` for TikTok/Reels/Shorts
6. **Loop-friendly** — end prompts with "seamless loop" for repeating content

## Example Prompts (Seedance 2.0)

```
1. CINEMATIC:
   A detective in a 1940s fedora and trench coat walks down a rain-soaked alley at night,
   neon signs reflecting in puddles, slow tracking shot from behind, dramatic shadow play,
   film noir black and white with selective red neon color, 24fps cinematic grain

2. ANIME:
   A teenage girl with silver hair and school uniform runs across a rooftop at golden hour,
   city skyline behind her, wind blowing her hair and scarf dramatically, cherry blossoms swirling,
   Makoto Shinkai lighting style, ultra-smooth animation, vibrant warm palette

3. SOCIAL MEDIA (9:16):
   Satisfying close-up of hands kneading bread dough on a wooden table,
   natural window light from left, steam rising gently, cozy kitchen sounds,
   slow rhythmic motion, vertical 9:16, ASMR aesthetic, warm tones

4. ADVERTISING:
   A sleek black electric sports car drives along a coastal highway at sunrise,
   low angle tracking shot, golden light glinting off bodywork, ocean waves below,
   aspirational luxury aesthetic, smooth professional motion, 16:9 widescreen
```

## Comparison: Seedance 2.0 vs Kling 3.0

| Aspect | Seedance 2.0 | Kling 3.0 |
|--------|-------------|-----------|
| Anime quality | Excellent | Good |
| Character consistency | Excellent | Very Good |
| Realism | Very Good | Excellent |
| Social media formats | Native vertical | Manual |
| Motion smoothness | Excellent | Very Good |
| API access | Yes | Yes |
