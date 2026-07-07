# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the repository for **Auto Sports Car Care**, a vehicle detailing and car wash center located in Ajman, UAE. The project has no active source files at the moment — `index.html` was removed and the repository is effectively empty aside from this file and the GitHub Actions workflow.

## CI / GitHub Actions

`.github/workflows/generator-generic-ossf-slsa3-publish.yml` is the default OSSF SLSA provenance template added by GitHub. It is **not wired to any real build artifacts** (the `Build artifacts` step creates placeholder files only). It triggers on `workflow_dispatch` and new releases.
