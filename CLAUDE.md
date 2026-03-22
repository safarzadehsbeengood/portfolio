# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a single-file static personal portfolio website (`index.html`). There is no build system, package manager, framework, or dependencies — just plain HTML and CSS.

## Development

Open `index.html` directly in a browser. No server or build step required.

## Structure

Everything lives in `index.html`:
- Inline `<style>` block for all CSS
- A full-viewport landing section with name, title, bio, and nav links
- A projects table listing work with optional hyperlinks
- A footer links bar

The `.separator` class uses `letter-spacing: -9px` to visually collapse the `|` characters between links into a compact separator effect.
