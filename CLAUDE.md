# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a GitHub Pages personal professional profile and digital Curriculum Vitae hosted at `www.nickabel.me`. It serves as the home for a resume and personal and professional project portfolio. It contains:
- `index.html` — a bare-bones personal intro page with a link to the resume
- `resume.pdf` — the resume file served directly
- `CNAME` — routes the GitHub Pages site to the custom domain `www.nickabel.me`

## Deployment

Pushes to `main` trigger `.github/workflows/jekyll-gh-pages.yml`, which builds with `actions/jekyll-build-pages` (the `github-pages` gem) and deploys to GitHub Pages. No manual build step required.

## Structure

- `_config.yml` — site settings, Minimal Mistakes theme config, author sidebar
- `index.md` — About/home page
- `_pages/projects.md` — Projects page at `/projects/`
- `_data/navigation.yml` — Top navigation links
- `Gemfile` — Ruby dependencies (mirrors what the Actions workflow builds with)
- `resume.pdf` — Resume served directly at `/resume.pdf`
