# IPL Analytics Power BI Dashboard

A visually rich, interactive Power BI dashboard for deep-dive IPL (Indian Premier League) cricket analytics—showcasing player performance, match outcomes, and franchise rivalries using actual IPL match data.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Data Sources](#data-sources)
- [Project Structure](#project-structure)
- [How to Use the Report](#how-to-use-the-report)
- [Page-by-Page Guide](#page-by-page-guide)
- [Key Insights & Visualizations](#key-insights--visualizations)
- [Sample Screenshots](#sample-screenshots)
- [How to Run Locally](#how-to-run-locally)
- [Credits](#credits)
- [License](#license)

---

## Project Overview

This Power BI dashboard offers end-to-end IPL insights for both fans and data professionals. Built from official match data, it explores batting partnerships, bowling performance, head-to-head team rivalries, and match-level thrillers, all in a modern, magazine-inspired style.

---

## Features

- **Batting Analytics**
    - Top partnerships and highest run-scoring duos
    - Most frequent batting pairs and explosive “impact” combinations
    - Team, position, and season-wise breakdown of partnerships

- **Bowling Analytics**
    - All-time wicket-takers and economy masters
    - Leaders in four/five wicket hauls (“fifer” heroes)
    - Franchise bowling dominance and match-turning spells

- **Rivalry & Match Insights**
    - Interactive head-to-head matrix—track every franchise rivalry
    - Epic matches: high scores, close shaves, biggest upsets
    - Narrowest margins for “IPL thrillers” and memorable comebacks

- **Interactive Filtering**
    - Slicers for team, player, season, or matchup
    - Drilldowns for stats on demand

---

## Data Sources

- **fact_batting_summary.csv** – All player batting records and partnership stats (runs, 4s, 6s, SR, not outs, batting position)
- **fact_bowling_summary.csv** – All bowler records (overs, wickets, economy, 4w/5w hauls)
- **dim_match_summary.csv** – Match-level stats (teams, winner, margin, result)
- **dim_players.csv** (optional) – Player name enrichment

---

## Project Structure

