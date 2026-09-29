# Implementation Plan - betBot

## Project Overview
WhatsApp bot for collecting sports betting spreads, with a GitHub Pages dashboard showing weekly bets, season standings, and global rankings.

## Phase 1: Setup
1. Initialize project structure
2. Set up Meta WhatsApp Cloud API integration
3. Configure GitHub Pages repository
4. Set up basic Astro + Tailwind frontend
5. Create data storage strategy (JSON files in repo)

## Phase 2: WhatsApp Bot
1. Implement bot to send weekly spreads from CBS Sports
2. Create bet collection flow (user menu system)
3. Add admin commands (edit bets, start/end betting)
4. Implement configurable betting window
5. Add error handling and validation

## Phase 3: Backend Logic
1. Parse CBS Sports data for spreads
2. Calculate weekly results
3. Generate standings (weekly, season, global)
4. Create data export for frontend

## Phase 4: GitHub Pages Dashboard
1. Build weekly bets table (tabbed interface)
2. Create season standings chart
3. Build global user rankings
4. Add winner history tracker
5. Implement responsive design

## Phase 5: Testing & Deployment
1. Test bot with sample users
2. Verify standings calculations
3. Deploy GitHub Pages site
4. Document admin commands
5. Create user guide

## Configuration Items
- Betting window timing
- CBS Sports data source URL
- Admin phone numbers
- GitHub Pages deployment workflow
