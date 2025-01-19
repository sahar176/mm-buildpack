# mm-buildpack

A Heroku buildpack that installs Git, Unzip, and FFmpeg.

## Components

- **Git** (default v2.42.0)
- **Unzip** (default v6.0)
- **FFmpeg** (default v7.0)

## Configuration

Environment variables:
- `GIT_VERSION`
- `UNZIP_VERSION`
- `FFMPEG_VERSION`

## Installation

```bash
heroku buildpacks:add https://github.com/sahar176/mm-buildpack
```
