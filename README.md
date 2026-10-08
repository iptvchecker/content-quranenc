# QuranEnc translation mirror

This repository mirrors original QuranEnc.com publisher archives for reliable reuse by iQuran. We do not claim ownership, make the material proprietary, modify its content or replace its original conditions. The ZIP files are downloaded directly from the publisher and remain byte-for-byte unchanged. Their SQLite contents contain all 114 surahs and 6,236 ayah entries per translation.

## Sources, versions and dates

Credit: [QuranEnc.com](https://quranenc.com) and the translators identified in `SOURCE.json`. [Publisher redistribution conditions](https://quranenc.com/en/home/api).

`SOURCE.json` retains each resource's full publisher catalog entry, version, `last_update` timestamp, original download URL, HTTP Last-Modified/ETag when supplied, archive-member modification time, retrieval time, byte count and SHA-256. Publisher update dates, archive modification times, retrieval times and GitHub commit dates are different facts and are never substituted for one another. A missing publisher date remains unknown. `CHECKSUMS.sha256` verifies the unchanged ZIPs. Original publisher filenames inside each ZIP are retained; the outer mirror filename adds its resource/version/snapshot identity.

## Reuse and updates

Preserve content without additions, deletions or modifications. Credit the publisher/source and translator, state the translation version and retain document/transcript information. Notify QuranEnc of translation observations, apply its published updates, and avoid inappropriate advertising when displaying translations. This mirror grants no additional rights.

Fetch updates into a separate review branch or candidate snapshot. Compare publisher versions, available dates/HTTP validators and byte checksums. Review content, attribution and conditions before publishing a new release. Never automatically delete our mirrored files because upstream removes them. Keep historical immutable releases and app-pinned revisions. Any removal requires a deliberate maintainer decision; publisher obligations remain in force.

The six translation archives are kept distinct. No proprietary app source, credentials or user data is included. The app's sources and download formats are unchanged; mirror integration is separate work.

## Original chapter API responses

The `api/RESOURCE/VERSION/2026-10-08/` folders retain all 114 unchanged
chapter responses per selected translation, with individual source URLs and
hashes in each SOURCE.json. These are separate from the original publisher
SQLite ZIPs above. No conversion or content editing was performed.
