# Public Platform Export Presets

> File: BIMG_KB_02_Public_Platform_Export_Presets.md  
> Project: BIMG — Website & Social Photo Prep  
> File role: Public runtime platform knowledge  
> Status: Active  
> Version: v1.2  
> Last updated: 2026-07-15  
> Authority level: Supporting public platform guidance  
> Refresh priority: High  

## Preset labels

Every platform recommendation must use one label:

- Verified platform preset.
- Generic aspect-ratio recommendation.
- Unverified or unavailable.

Do not describe a generic recommendation as an official platform requirement.

## Website image preparation

Preset ID: WEB_PHOTO_JPEG_SRGB

Default recommendation:

- Use JPEG for ordinary photographic content.
- Use PNG for transparency, graphics, or lossless requirements.
- Normalize to sRGB.
- Preserve aspect ratio.
- Remove GPS and unnecessary sensitive metadata from public derivatives.
- Use a measured derivative sized for the actual page placement when the user provides that placement.
- If no placement is supplied, provide a practical recommendation without claiming a universal website dimension.

Google Search supports common image formats including JPEG, PNG, WebP, SVG, and AVIF. Image filenames should be descriptive, and page implementations should balance quality, speed, and responsive handling.

Source: https://developers.google.com/search/docs/appearance/google-images

## Google Business Profile

Preset ID: GBP_PHOTO_JPG_PNG

Label: Verified platform preset.

Use these requirements for a Google Business Profile photo:

- Format: JPG or PNG.
- File size: 10 KB to 5 MB.
- Recommended resolution: 720 by 720 pixels.
- Minimum resolution: 250 by 250 pixels.
- Quality: focused and well lit.
- Authenticity: represent reality without significant alteration or excessive filters.

Only crop to a square when the crop remains fair and does not hide material context. If a square crop would mislead, recommend the original aspect ratio or ask for user direction.

Source: https://support.google.com/business/answer/6103862

## Accessibility

Preset ID: ACCESSIBILITY_ALT_CLASS

Label: Verified guidance.

Classify image use as:

- Informative.
- Functional.
- Decorative.
- Image of text.
- Complex.

Use concise, purpose-based alt text. Decorative images generally use an empty alt value. Complex images need a longer text equivalent outside the alt attribute.

Sources:

- https://www.w3.org/WAI/tutorials/images/decision-tree/
- https://www.w3.org/WAI/tutorials/images/

## Facebook feed

Preset IDs:

- SOCIAL_SQUARE_GENERIC
- SOCIAL_LANDSCAPE_GENERIC
- SOCIAL_PORTRAIT_GENERIC

Label: Generic aspect-ratio recommendation.

Use a square, landscape, or portrait crop based on the requested composition and subject protection. Do not claim that the chosen ratio is an official current Facebook specification unless separately verified.

## Instagram feed

Preset IDs:

- SOCIAL_SQUARE_GENERIC
- SOCIAL_PORTRAIT_GENERIC

Label: Generic aspect-ratio recommendation.

Use square or portrait framing based on the image subject and requested placement. Keep important subjects away from crop edges. Do not claim official current Instagram pixel dimensions from this source.

## Instagram Stories

Preset ID: STORY_VERTICAL_GENERIC

Label: Generic aspect-ratio recommendation.

Use a vertical 9:16 crop when the user requests a Story-style output. Protect the primary subject from top and bottom interface areas. Do not claim official current Story dimensions from this source.

## LinkedIn

Preset ID: LINKEDIN_UNVERIFIED

Label: Unverified or unavailable.

When LinkedIn is requested, provide a generic advisory recommendation only and state that no verified LinkedIn preset is active. Do not create a LinkedIn-specific derivative or claim a verified LinkedIn preset until a current verified specification has been added through the maintenance process.

## Preset selection rules

Choose the smallest useful set of outputs:

1. The user’s named destination.
2. A verified preset when available.
3. A generic ratio only when no verified preset is available.
4. No output when the crop would materially mislead or damage the image’s meaning.

Do not generate every platform derivative automatically.

## Change Log

| Date | Version | Change |
|---|---|---|
| 2026-07-15 | v1.2 | Renamed the public product to Website & Social Photo Prep; BIMG code and stable filenames retained. |
| 2026-07-15 | v1.1 | Unified LinkedIn advisory-only handling pending a verified preset. |
| 2026-07-15 | v1.0 | Initial public platform and export presets. |
