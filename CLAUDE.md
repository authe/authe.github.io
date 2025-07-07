# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based personal research website for Andreas Uthemann, hosted on GitHub Pages. The site showcases academic publications, working papers, CV, and contact information.

## Development Commands

### Local Development
```bash
bundle exec jekyll serve
```
Starts the Jekyll development server. The site will be available at http://localhost:4000.

### Bundle Management
```bash
bundle install
```
Install or update Ruby gem dependencies defined in the Gemfile.

```bash
bundle update
```
Update all gems to their latest compatible versions.

## Project Structure

- `_config.yml` - Main Jekyll configuration file containing site settings, theme, and plugins
- `index.md` - Homepage with personal introduction and photo
- `research.md` - Research publications, working papers, and policy briefs
- `cv.md` - Curriculum vitae page with employment and education history
- `contact.md` - Contact information and institutional affiliation
- `assets/` - Static files including PDFs of papers, CV, and profile images
- `_includes/` - Jekyll partial templates (currently contains footer.html)
- `Gemfile` - Ruby gem dependencies for Jekyll 3.5.1 and minima theme

## Site Configuration

The site uses:
- Jekyll 3.5.1 static site generator
- Minima theme (~> 2.0)
- Kramdown markdown processor
- Jekyll Feed plugin for RSS generation

Navigation pages are defined in `_config.yml` under `header_pages` and include research, CV, and contact sections.

## Content Management

Academic content is organized into:
- **Publications**: Peer-reviewed journal articles
- **Working Papers**: Papers under review or in preparation
- **Policy Briefs**: Central bank and policy institution publications
- **Permanent Working Papers**: Long-term working papers

All paper PDFs are stored in the `assets/` directory and linked directly from the markdown pages.