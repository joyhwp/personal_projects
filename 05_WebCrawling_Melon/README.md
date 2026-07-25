# Melon Music Chart Crawling

## Overview
Built a web crawling pipeline to automatically collect the Top 100 chart data from Melon (멜론), one of Korea's largest music streaming platforms.

## Approach
- Accessed the Melon homepage and navigated to the "멜론차트" (Melon Chart) → Top 100 section
- Used Selenium to automate browser navigation and handle dynamically rendered page elements
- Extracted key fields for each track: **rank, song info (title/artist), album, and like count**
- Structured and saved the collected data as a CSV file for further analysis

## Tech Stack
`Python` `Selenium` `Web Crawling` `pandas`

