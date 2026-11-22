# Dotflight award zones

**Independent; not affiliated with or endorsed by SAS. SAS and EuroBonus are trademarks of their owner.**

Which countries are in each SAS EuroBonus award zone, which partner airlines can be booked with points, and the
partner-award rules - as Dotflight reads SAS's public pages. No guarantee: SAS's own pages and booking always have
the final word. Read the readable version, in English, Swedish, Norwegian and Danish: https://dotflight.se/award-flights/eurobonus-award-zones

- Zones read on 2026-11-03 from https://www.flysas.com/en/eurobonus/award-flights and https://www.flysas.com/en/eurobonus/points/use/partner-award-flights/.
- Partner statuses checked on 2026-11-03; each row names its public source. A travel blog is not SAS.
- Built on 2026-11-22 from Dotflight's release data.

## Files

- `data/zones.csv`, `data/zones.json` - every zone and its countries.
- `data/airports.csv` - airports and the zone their country is in.
- `data/partners.csv`, `data/partners.json` - partner airlines and how they can be booked.
- `data/rules.json` - the partner-award rules in plain words.
- `data/schema.json` - what each column means.

## Corrections

Spotted something wrong, or a new partner or rule SAS has announced? Open an issue with a public link and the date
you read it - see `CONTRIBUTING.md`. Public facts only: never seats or prices from your own account, screenshots,
booking details or data from paid tools.

## Licence

CC BY 4.0 covers Dotflight's own work: the mapping of countries and airports to zones, the notes and the structure.
Facts from SAS's pages are SAS's;
others are reported, each with its source and how sure it is (`evidence`, `verification`). Airports and country codes come from the airportsdata package (MIT licence); country
names from the Unicode CLDR (notices in `NOTICE`). Please credit: **Source: Dotflight (dotflight.se)**.

Dotflight is a Chrome extension that finds the dates with award seats in your own SAS search: https://chromewebstore.google.com/detail/dotflight/caelmnlbhppcidjkhnamalebdjcidlhl?utm_source=github&utm_medium=readme&utm_campaign=award-zones
