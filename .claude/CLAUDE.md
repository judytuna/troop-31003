# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll website for Girl Scout Troop 31003 in Alameda, California. The site celebrates the troop's location along the SF Bay with an empowering, flower-filled theme.

## Development Commands

### Initial Setup
```bash
bundle install
```

### Development Server
```bash
bundle exec jekyll serve
```
Site will be available at http://localhost:4000

### Build Site
```bash
bundle exec jekyll build
```
Generated site will be in `_site/` directory

## Project Structure

- `index.md` - Homepage with Girl Scout theme and Alameda references
- `_config.yml` - Jekyll configuration
- `Gemfile` - Ruby dependencies
- `.claude/CLAUDE.md` - This file (excluded from Jekyll processing)

## Notes

- Uses Jekyll's default minima theme
- Site features empowering Girl Scout messaging with local Alameda/SF Bay references
- Includes custom CSS styling with pink/coral gradients and flower emojis