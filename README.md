# GitHub Desktop Linux — Releases

Binary release mirror for the **amitwh/GitHubDesktop** fork (the
community-maintained Linux port of GitHub Desktop, upstream
[`desktop/desktop`](https://github.com/desktop/desktop)).

The source repository is kept private. This repo exists solely to
host the public binary artifacts (AppImage, `.deb`, Snap, flatpak)
so that Linux users can download and install them.

## Releases

Each release in this repo corresponds to a tag on the fork. See the
[Releases page](../../releases) for downloads and notes.

The mirror is updated via a `workflow_dispatch` trigger in the
forked repo (workflow file: `.github/workflows/release-mirror.yml`).

## License

GitHub Desktop is released under the MIT license. See
[desktop/desktop](https://github.com/desktop/desktop) for upstream
attribution.
