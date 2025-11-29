# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a marketing website for Busy BJJ (Brazilian Jiu-Jitsu academy) owned by Mario "Busy" Correa in Centennial, Colorado. The site's primary goal is to convert visitors into trial signups for their "Zero Payment - 7 Days Unlimited Access" offer.

## Design Philosophy

**Brand Positioning:** "Sophisticated beautiful BJJ" rather than ultra-masculine MMA aesthetics. The owner prefers:
- Light theme (not dark/aggressive)
- Elegant, refined martial arts presentation
- Combat sport aesthetic without "meathead MMA" vibes
- Professional but welcoming

**Key Differentiators:**
- Direct Gracie lineage (Carlos Gracie Jr. → Mario Correa)
- 33+ years of BJJ experience
- Pan-American Champion credentials
- 15+ years serving Denver community
- Beginner-friendly, safety-first approach

## Color Palette

Located in `busybjjLanding.html` CSS variables:

**Brand Colors (from logo):**
- `--yellow: #EAFE1A` (accent, CTAs)
- `--navy: #25477E` (primary brand color)
- `--forest: #0F5A2C` (secondary brand color)
- `--sage: #DDE8D7` (soft backgrounds)

**Neutrals:**
- `--white: #FFFFFF`
- `--off-white: #FAFBF9`
- Gray scale from `--gray-100` to `--gray-800`
- `--black: #1A1C1A`

## Typography

- **Display font:** 'Playfair Display' (serif) - for headings
- **Body font:** 'DM Sans' (sans-serif) - for body text

The current font styling may be "too soft" per owner feedback—future iterations should explore fonts with more combat/martial arts character while maintaining sophistication.

## File Structure

```
/Users/jameseschduran/BusyBJJ_Website/
├── busybjjLanding.html          # Current production landing page
├── busybjjLanding1.html         # Alternative version
├── busybjjresearchandstrategy.txt  # Comprehensive research on Mario Correa, gym history, BJJ benefits
├── colortheme.txt               # (appears empty - colors are in HTML)
├── social_links.txt             # Social media URLs
├── SampleLandingPage[1-3].md   # Design/copy references
└── public/
    └── images/
        ├── logo/
        │   └── BusyBJJLogoText.avif
        └── teacher_photos/
            ├── MarioCorrea.avif
            ├── Professor Mario "Busy" Correa.avif
            └── [8 other instructor photos]
```

## Key Content Sources

**Research file (`busybjjresearchandstrategy.txt`) contains:**
- Mario Correa's BJJ lineage (Mitsuyo Maeda → Carlos Gracie Sr. → Carlos Gracie Jr. → Mario Correa)
- Competition achievements (1993 Brazilian National Champion, 2008 Pan-Am Champion)
- Gym history and philosophy
- Evidence-based BJJ benefits (with citations)
- Student testimonials
- Instructor team details

This file should be referenced when updating copy to ensure accuracy and authenticity.

## Social Media Links

- Facebook: https://www.facebook.com/BusyBJJ/
- Instagram: https://www.instagram.com/busybjj/
- Twitter/X: https://x.com/busybjj
- YouTube: https://www.youtube.com/channel/UC6nUAFDi4CQ6lNNJHBe6oiA

## Local Development

This is a static HTML site. To run locally:

```bash
# Simple Python HTTP server
python3 -m http.server 8000

# Or use any static file server
# Then navigate to: http://localhost:8000/busybjjLanding.html
```

## Key Messaging

**Primary CTA:** 7 Days Unlimited Access - Zero Payment Required

**Target Audience:**
- Adults: busy professionals seeking stress relief, fitness, self-defense, community
- Kids: parents looking for confidence-building, anti-bullying skills, discipline

**SEO Focus:** Local SEO for Denver metro area (Centennial, Greenwood Village, Englewood, Littleton, Aurora, Highlands Ranch)

## Content Guidelines

1. **Authenticity:** All claims about Mario's lineage and achievements are well-documented in research file
2. **Evidence-based benefits:** BJJ benefits are backed by peer-reviewed research (citations in research file)
3. **Testimonials:** Use verbatim quotes from research file - they're real student reviews
4. **Tone:** Professional, welcoming, confidence-inspiring (not aggressive or intimidating)
5. **Avoid:** MMA branding, overly masculine imagery, dark/aggressive aesthetics

## Current Issues

Per owner feedback (from /init command):
- Font may be "too soft" - needs more combat character while staying sophisticated
- Site is functional but typography could better balance elegance with martial arts aesthetic

## Image Assets

Teacher photos are stored as `.avif` format for optimal web performance. Note there are two files for Mario:
- `MarioCorrea.avif`
- `Professor Mario "Busy" Correa.avif`

Logo available at: `public/images/logo/BusyBJJLogoText.avif`
