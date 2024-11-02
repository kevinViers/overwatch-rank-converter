# Overwatch 2 Rank Converter

A simple tool to convert Overwatch 2 ranks between pre-Season 9 and post-Season 9 distributions.

## Live Tool

**Access the converter here:** https://kevinviers.github.io/overwatch-rank-converter/

## Local Usage

You can use this tool in two ways:

1. **Visit the live website** (link above)
2. **Run locally**:
   - Clone this repository: `git clone https://github.com/kevinviers/overwatch-rank-converter.git`
   - Open `index.html` in any web browser

## Overview

This tool helps players understand how their previous ranks (before Season 9) compare to the new ranking system implemented in Overwatch 2 Season 9. It uses the official rank distribution data to calculate equivalent ranks based on percentile rankings.

## Technical Details

The converter uses the following rank distribution data:

Pre-Season 9:
- Bronze: 10.2%
- Silver: 19.1%
- Gold: 26.8%
- Platinum: 26.2%
- Diamond: 12.3%
- Master: 3.9%
- Grandmaster: 1.5%

Post-Season 9:
- Bronze: 4.73%
- Silver: 20.2%
- Gold: 36.67%
- Platinum: 26.93%
- Diamond: 9.4%
- Master: 1.93%
- Grandmaster: 0.27%
- Champion: 0.1%

## Disclaimers

- This tool provides **approximate** conversions based on percentile rankings
- Individual placements may vary based on multiple factors including:
  - MMR changes
  - Performance in placement matches
  - Changes to the ranking algorithm
  - Account activity/inactivity
- The Champion rank was introduced in Season 9 and has no direct equivalent in the old system
- Blizzard's internal MMR system and placement algorithms may produce different results
- This tool is unofficial and not affiliated with Blizzard Entertainment

## GitHub Pages Deployment

If you want to fork this repository and host your own version:

1. Fork this repository
2. Go to repository Settings
3. Navigate to Pages section
4. Under "Source", select "main" branch
5. Save the changes
6. Your site will be available at `https://kevinviers.github.io/overwatch-rank-converter/`

## Credits

Distribution data source: [Overwatch rank DEFLATION: Explained](https://youtu.be/0vArSaM9EQA?si=kAinEmK3m20l1iU9&t=217)

## License

Free to use and modify. Created for the Overwatch community.
