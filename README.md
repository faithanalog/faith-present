# Faith's Simple Presentation Generator

This is a simple script to generate slides for a presentation. Each slide is
a self contained HTML file. Use the keyboard to control the presentation.

# Installation

Just copy faith-present wherever you want. It's a self-contained shell script,
so as long as your system has `sh` and `awk` you should be good.

# Usage

`faith-presentation <presentation> [stylesheet]`

`[stylesheet]` may be a path to a CSS file, which is inserted into each slide.

# Keys

  - Next Slide
    - Right Arrow
    - Enter
    - l
  - Prev Slide
    - Left Arrow
    - h

# Syntax

The syntax is simple, but limited. I don't like to go crazy with my
presentations.

`# Title` sets the current slide's title

`- Bullet` adds a bullet to the current slide's list of bullets

An empty line or the end of the file designate the end of the current slide.

## Example Presentation

```
# Slide one
- Bullet one
- Bullet two
- Bullet three

# Slide two
- Bullet one
- Bullet two
```

# TODO

Add image support
