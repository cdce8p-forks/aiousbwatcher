# Changelog

## v1.0.0 (2026-04-03)

### Bug fixes

- Fix stop watcher callback ([`a0eaa5c`](https://github.com/cdce8p-forks/aiousbwatcher/commit/a0eaa5c8d31c2660c37d3c24c4f25799ba989a23))
- Import asyncinotify sooner to avoid blocking i/o in the event loop (#12) ([`c57d32e`](https://github.com/cdce8p-forks/aiousbwatcher/commit/c57d32ed170b00d3222ad4093920b20698413cb0))

### Features

- Use `path.walk` instead of recursive `path.iterdir` (#7) ([`122afa6`](https://github.com/cdce8p-forks/aiousbwatcher/commit/122afa6d61df188bf4bee6a964c08c050f797218))
- Drop python older than 3.12 (#9) ([`1a30665`](https://github.com/cdce8p-forks/aiousbwatcher/commit/1a30665a82a41f1b3c9922637faef32611bd6162))
- Improve example to show how to stop the watcher (#6) ([`27a9a14`](https://github.com/cdce8p-forks/aiousbwatcher/commit/27a9a142589444f167ab5d576975fa3409c40776))
- Add example watcher (#5) ([`02d9afd`](https://github.com/cdce8p-forks/aiousbwatcher/commit/02d9afdd7a8158561ed4c3d7d7550fc53bfdc948))
- Add initial implementation (#1) ([`1d44d56`](https://github.com/cdce8p-forks/aiousbwatcher/commit/1d44d5609ad69084b99f640e044a3291ff9f4f58))
