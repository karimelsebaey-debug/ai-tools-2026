# Universal Prompt Framework — Cross-Platform Skill

> Works with: Kling AI, Veo 3, Nano Banana Pro, Seedance 2.0, Midjourney, DALL-E, Stable Diffusion, Sora
> Source: `Hunyuan-PromptEnhancer/PromptEnhancer` (CVPR 2026, ⭐3,671), `promptslab/Awesome-Prompt-Engineering` (⭐5,845)

## The 7-Component Formula

Based on `Hainrixz/claude-banana` — AI agent with 70+ creative techniques:

```
[1. SUBJECT] + [2. ACTION] + [3. ENVIRONMENT] + [4. CAMERA/COMPOSITION] + [5. LIGHTING] + [6. STYLE] + [7. QUALITY]
```

### Component Guide

| # | Component | Image Example | Video Example |
|---|-----------|---------------|---------------|
| 1 | Subject | "a woman in red dress" | "a samurai warrior" |
| 2 | Action | "sitting, reading" | "charging forward, sword raised" |
| 3 | Environment | "in a sunlit library" | "on a misty battlefield at dawn" |
| 4 | Camera | "portrait, f/1.8 bokeh" | "low-angle tracking shot" |
| 5 | Lighting | "soft window light" | "dramatic backlight, fog" |
| 6 | Style | "oil painting, Renaissance" | "cinematic, slow motion" |
| 7 | Quality | "8K, ultra detailed" | "4K, film grain, 24fps" |

## Tool Selection Guide

```
Need photorealistic IMAGE?     → Nano Banana Pro (Gemini/Imagen 3)
Need stylized/anime IMAGE?     → Nano Banana Pro or Midjourney
Need cinematic VIDEO?          → Kling 3.0 or Seedance 2.0
Need video WITH AUDIO?         → Veo 3 (only tool with native audio)
Need anime VIDEO?              → Seedance 2.0
Need social media vertical?    → Seedance 2.0 (native 9:16)
Need long video (60s+)?        → Veo 3
Need free option?              → Nano Banana Pro (free tier)
```

## Prompt Upgrade Technique (from Hunyuan PromptEnhancer)

Take a weak prompt → apply this upgrade process:

**Weak:** `a cat in a garden`

**Step 1 — Add subject detail:**
`a fluffy orange tabby cat with green eyes`

**Step 2 — Add action:**
`sitting still, watching a butterfly`

**Step 3 — Add environment:**
`in an English cottage garden full of lavender and roses`

**Step 4 — Add camera:**
`medium close-up, shallow depth of field`

**Step 5 — Add lighting:**
`soft afternoon sunlight, golden hour, warm dappled shadows`

**Step 6 — Add style:**
`photorealistic photography, National Geographic style`

**Step 7 — Add quality:**
`shot on Canon 5D, 85mm lens, 8K, ultra sharp`

**Result:**
```
A fluffy orange tabby cat with bright green eyes sitting still watching a butterfly
in an English cottage garden full of lavender and roses, medium close-up,
shallow depth of field, soft golden hour afternoon light with warm dappled shadows,
photorealistic photography, National Geographic style, Canon 5D 85mm, 8K ultra sharp
```

## Cross-Platform Style Dictionary

### Photography Styles
```
golden hour | blue hour | high key | low key | Rembrandt lighting
flat lay | rule of thirds | leading lines | negative space | bokeh
```

### Art Movement Styles
```
impressionism | surrealism | art nouveau | bauhaus | pop art
baroque | minimalism | brutalism | vaporwave | cottagecore
```

### Film/Cinema Styles
```
film noir | neo-noir | French New Wave | Spaghetti Western
Kubrick symmetry | Wong Kar-wai blur | Wes Anderson flat
Nolan practical effects | A24 indie aesthetic
```

### Animation Styles
```
Studio Ghibli | Disney Renaissance | Pixar 3D | Makoto Shinkai
90s anime | webtoon | stop motion | claymation | rotoscope
```

## Quick Cheat Sheet

### For ANY image prompt — always include:
```
✓ Specific subject description
✓ Named lighting type
✓ Art style reference
✓ Resolution tag (8K / ultra detailed)
✓ Medium (photography / painting / 3D render)
```

### For ANY video prompt — always include:
```
✓ Clear subject + motion
✓ Camera movement type
✓ Duration feel (slow / fast / rhythmic)
✓ Lighting atmosphere
✓ Style reference
✓ (Veo 3 only) Sound description
```

## Prompt Length Guidelines

| Tool | Ideal Length | Max |
|------|-------------|-----|
| Nano Banana Pro | 50–150 words | 300 words |
| Kling AI | 50–120 words | 200 words |
| Veo 3 | 60–150 words | 250 words |
| Seedance 2.0 | 50–130 words | 200 words |
