# Slides Generator

A simple CLI tool to initialize HTML slides from a template, and create a GitHub repository for it with automatic deployment to GitHub pages.

## Requirements

* [Bash](https://www.gnu.org/software/bash/) _(Installed by default on UNIX machines)_

## Install

### Manually

First, clone this repo somewhere:

```bash
$ git clone git@github.com:rubensworks/slides-generator.sh.git
```

Then, add the `/bin` folder to your `$PATH`.
For example, by adding the following to your `~/.bashrc`

```bash
export PATH="/path/to/slides-generator.sh/bin:$PATH"
```

## Usage

The `slides-generate` takes 5 required input arguments:

1. The folder/repository name. This folder and repo can not exist yet.
2. The title of the presentation.
3. The venue where the presentation will be given.
4. The venue date.
5. The venue URL.

```bash
$ slides-generate "slides-2020-tmp" "AMF in TPF" "SSWS 2020" "2 November 2020" "http://www.ssws-ws.org/SSWS2020/"
```

## License

This code is copyrighted by [Ruben Taelman](https://www.rubensworks.net/)
and released under the [MIT license](http://opensource.org/licenses/MIT).
