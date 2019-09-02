# Change Log

All notable changes to this project will be documented in this file.
This change log follows the conventions of
[keepachangelog.com](http://keepachangelog.com/).

## [Unreleased][unreleased]

Nothing so far.


## [0.1.1] - 2019-08-25

### Added

- Ability to parse `PCO2` tags, which hold cues and loops along with
  DJ-assigned comment labels and colors, displayable on nxs2 players.
- Ability to parse `PSSI` tags, which hold phrase structure analysis
  performed by rekord box with a Performance license. (As this is not
  currently included when tracks are exported to removable media,
  nor available through a `dbserver` query, it cannot be used by
  Beat Link.) Many thanks to [@mganss](https://github.com/mganss) for
  this contribution!
- More explanation of the interpretation of waveform color preview
  tags.


## 0.1.0 - 2019-02-23

### Added

- Initial release.


[unreleased]: https://github.com/Deep-Symmetry/crate-digger/compare/v0.1.1...HEAD
[0.1.1]: https://github.com/Deep-Symmetry/crate-digger/compare/v0.1.0...v0.1.1