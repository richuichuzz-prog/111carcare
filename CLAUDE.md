# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single-page static website for **Auto Sports Car Care**, a vehicle detailing and car wash center located in Ajman, UAE. The site is a pure HTML/CSS landing page with no build tools, frameworks, or package managers.

## Structure

The entire site lives in one file: `index.html`. It contains:
- Inline CSS in a `<style>` block in `<head>`
- A hero section with logo, business name, tagline, and location badge
- A 2-column services grid (`.services-grid`) that collapses to 1 column below 380 px
- Two CTA buttons: WhatsApp link (`https://wa.me/971563867796`) and Google Review link
- A footer with copyright

There is no JavaScript, no external CSS files, no assets directory, and no dependencies.

## Development

Open `index.html` directly in a browser — no server or build step needed.

The color scheme is dark (`#0a0a0a` background) with gold (`gold` / `#FFD700`) accents throughout. All layout uses CSS Flexbox and CSS Grid.

## CI / GitHub Actions

`.github/workflows/generator-generic-ossf-slsa3-publish.yml` is the default OSSF SLSA provenance template added by GitHub. It is **not wired to any real build artifacts** for this project (the `Build artifacts` step just creates placeholder files). It triggers on `workflow_dispatch` and new releases.
