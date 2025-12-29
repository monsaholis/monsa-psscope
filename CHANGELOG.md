# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] - 2025-12-29

### Added
- Initial release
- Real-time process monitoring with ncurses TUI
- Three-section layout (System/Process List/Detail)
- 9 detail tabs: Overview, Threads, Files, Memory, Libraries, Environment, Signals, Locks, Resources
- Process tree view and list view modes
- Multiple sort options: PID, Name, User, CPU, Memory, Time, Start, Nice, State, OOM, IONice, Context Switch
- Keyboard-driven navigation (j/k, arrows, PgUp/PgDn, Home/End)
- Process dump generation and analysis
- Bookmark functionality for processes
- Dark and Mono themes
- 60-second history tracking
- Color-coded process states (high CPU, high memory, zombie, new process)

### Security
- No network communication
- No telemetry or tracking
- No auto-update mechanism

---

[Unreleased]: https://github.com/monsaholis/monsa-psscope/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/monsaholis/monsa-psscope/releases/tag/v0.1.0
