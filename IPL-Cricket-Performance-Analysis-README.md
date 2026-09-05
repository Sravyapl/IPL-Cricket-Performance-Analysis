# 🏏 IPL Cricket Performance Analysis Dashboard

Player, team, and match performance analysis for the Indian Premier League, built in Power BI.

## 📌 Overview

Analyzes match and delivery-level data to surface player form, team performance trends, and venue-based patterns across IPL seasons.

## 🧹 Data Cleaning

Multiple cleaning passes on raw CSV data, including:
- Standardizing inconsistent team name spellings/abbreviations across seasons
- Normalizing venue names (same ground listed under multiple naming variants)
- Resolving Power Query caching issues that were causing stale results after source refreshes

## 🗂️ Data Model

Star schema relating match, delivery, player, and team dimensions to a central delivery-level fact table.

## 📐 DAX

Measures built at both match level (wins, net run rate, results by venue) and delivery level (strike rate, economy rate, boundary %, powerplay/death-overs splits).

## 🛠️ Tech Stack

Power BI • SQL

