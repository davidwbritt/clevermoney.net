# CleverMoney.net - Claude Session Context

## Project Overview
A personal finance blog at **clevermoney.net** targeting young professionals (25-40) with practical, evidence-based financial advice. The goal is to build a sustainable content business generating $3,000-6,000/month through ads, affiliates, and digital products.

## Key Documents
- **Implementation Plan**: `CLEVERMONEY_IMPLEMENTATION_PLAN.md` - Full strategy, progress tracking, monetization roadmap, and next steps
- **Content Files**: `/content/*.md` - All blog posts with WordPress block formatting
- **Custom CSS**: `/content/custom-css.css` - Site styling
- **Images**: `/content/images/` - Logo and featured images

## Current Status (January 2026)

### Completed
- Kadence theme configured with custom branding
- 5 categories created (Budgeting & Saving, Investing Basics, Debt Management, Income Growth, Financial Independence)
- 5 pillar pages populated (Start Here, Budgeting, Debt, Saving, About)
- 10 blog posts published with featured images and media-text block layouts
- Logo and color palette established
- Custom CSS implemented

### In Progress
- SEO plugin setup
- Analytics configuration
- Email list infrastructure

### Next Priorities
1. Google Search Console submission
2. AdSense application
3. Affiliate account setup (Credit Karma, NerdWallet, etc.)
4. Email service provider (ConvertKit)

## Design System

### Colors
- Primary: `#008254` (teal)
- Hover: `#005f3f` (dark teal)
- Accent: `#c9a24d` (gold)
- Background: `#eef5f2` (light mint)

### Typography
- Body: Inter
- Headings: IBM Plex Sans

### Logo
- Teal lightbulb with $ sign
- Files: `clevermoney_logo.png`, `clevermoney_icon.png`

## WordPress Access
Use the `wordpress-clevermoney` MCP server tools for:
- Creating/updating posts and pages
- Managing media uploads
- Checking site settings and categories

## Content Guidelines
- Tone: Conversational, practical, evidence-based, non-judgmental
- Format: WordPress blocks with media-text layouts for featured images
- SEO: Include focus keyword, meta description, proper heading hierarchy
- All posts backed up locally in `/content/` with WordPress block formatting

## Git Workflow
- Repository: `clevermoney.net`
- Branch: `develop`
- Content and images are version-controlled
- Related project: `wordpress-mcp-server` (MCP server for WordPress API)

## Monetization Timeline
- Months 1-6: AdSense + affiliate marketing setup
- Months 6-12: Launch digital products (budget templates, calculators)
- Months 12+: Email newsletter monetization, sponsored content

## Quick Reference
```
# Check WordPress posts
mcp__wordpress-clevermoney__wp_get_posts

# Get site info
mcp__wordpress-clevermoney__wp_get_site_info

# View categories
mcp__wordpress-clevermoney__wp_get_categories
```
