# Project Structure Guide

## Overview

This repository has been cleaned and reorganized to serve as a legacy archive while the active website development happens in the new Next.js repository.

## Directory Structure

```
phenomsec-blogs/                    # This repository (archive)
├── .git/                          # Git history (preserved)
├── .github/                       # GitHub workflows
├── .gitignore                     # Git ignore rules
├── archive/                       # Legacy content archive
│   ├── blog-posts/               # Original markdown blog posts
│   │   ├── 2023-03-21-factorial-separation-appsec-compliance.md
│   │   └── 2023-04-03-calculus-crossroads-of-policy-pyramid.md
│   ├── documentation/            # Legacy Jekyll docs
│   │   ├── 2024-08-26-LLM-graph-threat-modeling.md
│   │   ├── CONTRIBUTING.md
│   │   ├── CODE_OF_CONDUCT.md
│   │   └── SUPPORT.md
│   └── images/                   # Historical images and assets
│       └── fact-separation-moutain-image-DALL.webp
├── phenomsec-website/            # Next.js website source (local copy)
│   ├── src/                      # Next.js app source
│   ├── public/                   # Static assets
│   ├── package.json              # Node.js dependencies
│   └── vercel.json              # Deployment configuration
├── LICENSE                       # MIT License
├── README.md                     # Main documentation
└── PROJECT_STRUCTURE.md         # This file
```

## What Was Removed

### Jekyll Files (No Longer Needed)
- `_config.yml` - Jekyll configuration
- `_includes/` - Jekyll partials
- `_layouts/` - Jekyll templates
- `_sass/` - Jekyll styling
- `assets/` - Jekyll assets
- `script/` - Jekyll build scripts
- `Gemfile` - Ruby dependencies
- `jekyll-theme-cayman.gemspec` - Theme specification
- `index.md`, `index_original.md` - Jekyll pages

### Development Artifacts
- `.DS_Store` - macOS system files
- `.claude/` - Claude Code workspace files
- `CODEOWNERS` - GitHub code owners
- `.vercel/` - Old Vercel configuration (wrong project)

## Active Development

**For new website development, use:**
- **Repository:** https://github.com/microbrewerGM/phenomsec-website
- **Live Site:** https://phenomsec.com
- **Local Development:** See the `phenomsec-website/` directory

## Git Workflow

This repository maintains git history for archival purposes. All new commits should go to the active website repository.

## Deployment Status

- **Legacy Site:** Disabled (GitHub Pages removed)
- **New Site:** Live at https://phenomsec.com (Vercel)
- **DNS:** Configured for Vercel hosting
- **SSL:** Managed by Vercel

## Archive Purpose

This repository now serves to:
1. Preserve original blog content
2. Maintain git history
3. Document the migration process
4. Provide legacy reference materials

All active development should use the new Next.js repository.