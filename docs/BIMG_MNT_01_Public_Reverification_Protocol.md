# Public Reverification Protocol

> File: BIMG_MNT_01_Public_Reverification_Protocol.md  
> Project: BIMG — Website & Social Photo Prep  
> File role: Conditional maintenance and reverification protocol  
> Status: Drive-only, conditional  
> Version: v1.1  
> Last updated: 2026-07-15  
> Authority level: Maintenance support  

## Purpose

Use this protocol to reverify public platform guidance, file-processing behavior, and public GPT claims without expanding scope.

## Reverification triggers

Run a review when:

- Google Business Profile requirements change.
- Google Search image guidance changes.
- Accessibility guidance changes materially.
- HEIC or HEIF conversion behavior changes.
- Code Interpreter & Data Analysis behavior changes.
- Download failures recur.
- A public user reports a false claim or privacy issue.
- A source file changes processing, privacy, or platform behavior.
- A new platform lane is proposed.

## Platform reverification

Verify each platform source from an authoritative public page.

Record:

- Platform.
- Source URL.
- Date verified.
- Requirements changed.
- Preset affected.
- File requiring update.
- Test case required.

Do not add Facebook, Instagram, or LinkedIn official dimensions until an authoritative source has been verified.

## HEIC and HEIF reverification

Use clean, non-sensitive fixtures for:

- HEIC conversion.
- HEIF conversion.
- Visual-only fallback.
- Pre-conversion fallback.
- Corrupt file handling.
- Unsupported variant handling.
- Orientation.
- ICC and sRGB.
- GPS and metadata handling.
- Source preservation.

Record actual output existence, measured dimensions, bytes, format, color space, metadata state, hash, and transformation history.

## Runtime reverification

Run the actual configured GPT in Preview after changes to:

- Instruction field.
- Public knowledge sources.
- Code capability.
- File-processing behavior.
- Platform preset source.
- Public scope.
- Privacy or prompt-injection rules.

Do not infer live behavior from source text alone.

## Change control

Routine wording and metadata changes:

- Preserve active filenames.
- Update internal version.
- Update last-updated date.
- Add a change-log entry.
- Run a narrow retest.

Mission, scope, authority, privacy boundary, processing model, or public/private changes:

- Return to Project Architect.
- Rebuild the affected architecture surface.
- Run full Test Lab regression.

## Source promotion rule

Raw research, screenshots, test reports, user images, and administrative evidence remain Drive-only unless converted into a concise public-safe source and approved through the architecture workflow.

## New platform lane rule

Before adding a new platform:

1. Define the user need.
2. Identify an authoritative current specification.
3. Define the smallest useful preset.
4. Define privacy and authenticity risks.
5. Add QA cases.
6. Obtain owner approval.
7. Patch only the affected source files.

Do not add TikTok, Pinterest, YouTube thumbnails, ecommerce feeds, publishing, or integrations automatically.

## Reverification report

Return:

1. Date and scope.
2. Sources checked.
3. Facts that changed.
4. Files affected.
5. Runtime behavior affected.
6. Test cases run.
7. Blockers.
8. Recommended patch.
9. Owner approval needed.

## Change Log

| Date | Version | Change |
|---|---|---|
| 2026-07-15 | v1.1 | Renamed the public product to Website & Social Photo Prep; BIMG code and stable filenames retained. |
| 2026-07-15 | v1.0 | Initial public reverification protocol. |
