# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.7.0] - 2025-10-25

### Added

- PREMIS_IE_events - repeating event_detail columns (also applies to PREMIS_Rep_events and PREMIS_Files_events)

### Changed

- PREMIS_IE_events - renamed event_detail to event_detail1 (also applies to PREMIS_Rep_events and PREMIS_Files_events)
- Rewrote filename standardisation information and moved it into the supplement.

### Removed

- PREMIS_Files_original_name - reserved by DP systems

## [0.6.0] - 2024-10-01

### Removed

- PREMIS_Rep_creating_app - invalid in PREMIS on Rep level
- PREMIS_Rep_inhibitors - invalid in PREMIS on Rep level

### Fixed

- Broken PREMIS Link
- Underline text removed
- Wording for inhibitor_key
- Wording for bitstream_preservation_level
- Multiple instances of the wording 'will be' changed to 'should be'
- Missing links to supplement.md
- Reference to combined metadata
- Remove quasi regex from supplement.md
- Update bitstream preservation definition
- Update METS definition