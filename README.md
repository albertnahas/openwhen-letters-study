# Open When Letters: aggregate statistics from 56,670 digital letters

How people write, lock and open "Open When" letters: short letters a recipient is told to open at a particular moment ("open when you miss me", "open on your birthday"). The data comes from OpenWhen (https://www.openwhen.cards), a website for writing and sending these letters, and covers every letter sealed from 2026-02-04 to 2026-11-03.

Author: Albert Nahas, OpenWhen. Licence: CC BY 4.0. DOI: [10.5281/zenodo.24085754](https://doi.org/10.5281/zenodo.24085754). A written summary with charts is at https://www.openwhen.cards/open-when-letters-study.

## Files

- `open-when-letters-study.csv`: every figure in one tidy table (section, metric, label, country, value, unit).
- `letters-study.json`: the same figures as published on the website.

## What is in it

- Totals: 56,670 letters by 33,686 senders.
- Titles: the share of letters using a ready-made title, and which ones.
- Opening: how many letters get opened and how soon, with and without a question lock.
- Locks: letters locked behind a question only the recipient can answer, or behind a date.
- Countries, weekdays and occasion spikes (days with far more letters than the days around them).
- Optional extras: songs, stickers, photos, voice notes, replies.

## Method

- Metadata only. No letter text and no lock question was read or categorised. A title is counted only when it matches one of OpenWhen's own ready-made titles; any other title counts as custom and nothing else about it is recorded.
- Every published figure covers at least 50 letters.
- Our own test letters are excluded. Days are in UTC.
- Opening figures cover the 27,361 letters sealed 2026-09-05 to 2026-10-26, when every first open was recorded the same way, each given at least a week. An open is the first reveal in a browser other than the one the letter was written in.
- Country is where a sender first arrived from, known for 66.2% of letters. The sample leans towards the Philippines, India and Indonesia, so do not read it as a global picture.
- A spike compares a day with the median of the seven days either side, so growth alone does not count as a spike.
- The OpenWhen privacy policy allows publishing aggregate statistics like these, never text from any letter.

## Limitations

These are letters written on one website, not open when letters in general: who finds the site shapes the mix of countries and occasions. Percentages are rounded to one decimal place.

## Cite

Nahas, A. (2026). Open When Letters: aggregate statistics from 56,670 digital letters [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24085754
