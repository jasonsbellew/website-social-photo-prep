# Public Metadata and Delivery Templates

> File: BIMG_OUT_01_Public_Metadata_and_Delivery_Templates.md  
> Project: BIMG — Website & Social Photo Prep  
> File role: Public runtime output templates  
> Status: Active  
> Version: v1.6  
> Last updated: 2026-07-15  
> Authority level: Runtime output support  

## Default response template

## Status

Use one:

- Processing completed.
- Partially completed.
- Metadata and review only.
- Blocked pending user input.
- Blocked pending pre-conversion.

State whether file processing actually occurred.

## What the image visibly shows

Describe only observable content.

For two images, use separate subsections:

### Image 1

### Image 2

Do not merge visual facts across images.

## Confirmed context

List user-confirmed context separately from visible evidence.

If no context was supplied:

None supplied. The description below is based on visible evidence only.

## Privacy and authenticity review

Use this format:

| Finding | Status |
|---|---|
| Visible privacy risks | None identified / list findings |
| Metadata risks | Not inspected / found / removed / not removed |
| Authenticity concerns | None identified / list concern |
| User confirmation needed | Yes / No |
| Publication classification | One required classification |

Required classification:

- Ready to publish.
- Publish after technical optimization.
- Publish after crop or redaction.
- Requires user confirmation.
- Internal only.
- Do not use.

## Recommended metadata

### Filename

Use a lowercase, hyphenated, factual filename based on confirmed details only.

### Alt text

Write purpose-based alt text appropriate to the image’s use.

### Image title

Use a concise, factual title.

### Extended description

Describe useful visible context without inventing location, service, species, product, outcome, or identity.

### Caption

Provide only when a caption improves the requested platform use. Separate user-confirmed context from visual description.

### Media-library description

Include practical asset context, file role, and confirmed use.

### Subject tags

Use only visible or user-confirmed subjects.

### Content-purpose tags

Examples:

- informative.
- service-photo.
- product-photo.
- crew-photo.
- equipment-photo.
- before-after-pair.
- privacy-review-required.

Do not use a tag that makes an unsupported claim.

Do not use before, after, treatment, canker, disease, diagnosis, service, outcome, or similar claim language in a filename, title, caption, tag, or derivative name unless user-confirmed.

### Confirmed location

Include only when supplied or confirmed by the user.

## Recommended platform use

Use a table:

| Destination | Recommendation | Preset status | Action |
|---|---|---|---|
| Website | Use / avoid / use after crop | Verified / generic / unavailable | File or recommendation |
| Google Business Profile | Use / avoid / use after crop | Verified / generic / unavailable | File or recommendation |
| Facebook feed | Use / avoid / use after crop | Verified / generic / unavailable | File or recommendation |
| Instagram feed | Use / avoid / use after crop | Verified / generic / unavailable | File or recommendation |
| Instagram Story | Use / avoid / use after crop | Verified / generic / unavailable | File or recommendation |
| LinkedIn | Generic advisory only when requested; no LinkedIn-specific derivative pending a verified preset | Generic / unavailable | Recommendation only |

When the publication classification is **Requires user confirmation**, set the Action cell for every affected destination to exactly `Requires user confirmation before public use` with no period or other trailing punctuation. Do not use “publication rights,” “use after confirmation,” or similar wording.

## Files generated

Use a delivery table:

| Item | Status | Role | Format | Dimensions | Bytes | Color space | Metadata state | SHA-256 | Notes |
|---|---|---|---|---:|---:|---|---|---|---|
| Original | Reused | Untouched source | Measured format | Measured | Measured | Measured | Measured | Measured when available | Never overwritten |
| Working master | Generated / not produced | Approved master | Measured | Measured | Measured | Measured | Measured | Measured | Source for derivatives |
| Derivative | Generated / reused / omitted / failed | Destination role | Measured | Measured | Measured | Measured | Measured | Measured | Transformation history |

Do not fill a field with an estimate. Use “Not measured” when necessary.

Final-delivery measurement rule: Populate bytes, SHA-256, ICC/profile state, dimensions, format, color space, and metadata state only from the exact user-downloadable file after every write, re-encode, package, or delivery transformation. If the delivery layer can alter a file after measurement, use `Not measured / not final` for affected fields; do not label them final-delivery facts.

For every generated derivative, list the measured working-master filename as its source. Do not generate a derivative if no measured working master exists.

## Transformation history

List operations in order:

1. Source inspection.
2. Orientation normalization.
3. HEIC/HEIF conversion, if applicable.
4. Color-space or ICC handling.
5. Crop.
6. Resize.
7. Compression.
8. Metadata handling.
9. Hash and measurement.

State when an operation was not performed.

## Two-image set template

Use only when two images are supplied.

### Set relationship

- Independent images.
- Possible relationship requiring confirmation.
- Confirmed before-and-after pair.

### Relationship evidence

State the user confirmation and visible basis separately.

### Recommended order

State the recommended display order only when supported.

### Matched crop plan

State whether matched dimensions and aspect ratios are truthful and practical.

### Shared copy

Provide shared caption or campaign language only when the relationship and context are confirmed.

## Limitations or warnings

State:

- Unconfirmed facts.
- Missing user context.
- Visible privacy concerns.
- Metadata limitations.
- HEIC/HEIF conversion limitations.
- Unverified platform specifications.
- Files not generated.
- Measurements not available.

## Next action

Give one clear action, such as:

- Upload a JPG copy.
- Confirm the before-and-after relationship.
- Provide the destination platform.
- Crop or redact the visible address.
- Download the generated files.

## Change Log

| Date | Version | Change |
|---|---|---|
| 2026-07-15 | v1.6 | Renamed the public product to Website & Social Photo Prep; BIMG code and stable filenames retained. |
| 2026-07-15 | v1.5 | Added final-downloadable-artifact measurement and safe withholding rules for delivery-layer transformations. |
| 2026-07-15 | v1.4 | Added claim-term metadata and working-master derivative-source rules. |
| 2026-07-15 | v1.3 | Required punctuation-free exact platform Action text for the recognizable-people gate. |
| 2026-07-15 | v1.2 | Added exact platform-action wording for images requiring user confirmation. |
| 2026-07-15 | v1.1 | Unified LinkedIn advisory-only delivery template pending a verified preset. |
| 2026-07-15 | v1.0 | Initial public metadata and delivery templates. |
