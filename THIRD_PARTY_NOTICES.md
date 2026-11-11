# Third-party notices

This file is part of every distributable copy of Amudi. Original Amudi
application code is proprietary and all rights are reserved; the materials
below remain under their respective third-party terms.

## Rights-review status for the current online library

The current strict local release manifest contains 23,266 daf/layer
exclusions. Of the current provenance page/layer pairs, 20,863 are excluded
and 20,390 are retained. The retained set contains 6,774,526 provenance word
occurrences, all of which pass the strict source-ID screen; 0 retained
occurrences are unresolved. All 1,134 retained tractate/source-record pairs
have hash-matching bundled evidence. This establishes the documented source-
terms gate for the filtered local inputs, not legal certification or parity
with an already-hosted encrypted package. Sefaria states that copyright and
reuse terms are specific to each text version and language.

The app downloads encrypted packages, decrypts them on-device, and stores the
resulting text for offline reading. CC BY-SA prohibits downstream restrictions
or effective technological measures where they restrict the recipient's
licensed rights. Effective 2026-10-15, each Shas Gemara page/layer whose sole
hold was this encrypted-delivery concern is displayed with a plaintext `.txt`
download of the released Gemara source layer and its source, license,
attribution, change, and ShareAlike notices. Separately sourced Mishnah
passages injected at runtime are excluded from that Gemara download. This
releases 8,515 Gemara daf/layers and provides 8,514 nonempty downloads; Nazir
33b is an intentionally Gemara-empty, commentary-only physical page. The other
14,751 page/layers remain excluded. MAM-based Bible Code data is
separately recorded as CC BY-SA and its access compatibility remains
unresolved. This notice is not a legal clearance for excluded or unrelated
material.

For the current Amudi edition, imported publisher page links are normalized to
internal Amudi routes. Publisher-specific cross-reference sentences were
removed from a small number of imported text files; the original work/version
and license attribution remain recorded in the corresponding book metadata.
These are changes made by Amudi and should be considered when preparing a
release or a share-alike source package.

## Biblical texts

- **JPS 1917 English Tanakh** — Public domain. The digital transcription used
  by Sefaria came through the Open Siddur Project.
- **Modernized Tanakh — HOLD** — *Modernized Tanakh — Based on JPS 1917*, edited
  by Adam Cohn (2013). Source: http://modernizedtanakh.blogspot.com. Digitized
  by Sefaria and identified there as CC BY without a version. The applicable
  license and authority for the exact edition have not been verified; this
  notice is not permission or clearance.
- **Tanach with Ta'amei Hamikra** — Public-domain Westminster Leningrad Codex
  text distributed by Sefaria, with source identified as
  `http://www.tanach.us/Tanach.xml`.
- **Miqra According to the Masorah (MAM)** — Prepared by Seth (Avi) Kadish
  from Hebrew Wikisource materials, with major technical assistance from Erel
  Segal-Halevi and Benjamin Denckla. Licensed under CC BY-SA 4.0. Attribution:
  [Hebrew Wikisource](https://he.wikisource.org/wiki/%D7%9E%D7%A7%D7%A8%D7%90_%D7%A2%D7%9C_%D7%A4%D7%99_%D7%94%D7%9E%D7%A1%D7%95%D7%A8%D7%94).
  The consonantal Bible-code datasets remove qere, vowels, cantillation,
  spacing, punctuation, and section markers while retaining ketiv.
- **Bible Code Masoretic text** — The source is *Miqra According to the
  Masorah* (MAM), prepared by Seth (Avi) Kadish with technical assistance from
  Erel Segal-Halevi and Benjamin Denckla, from Hebrew Wikisource; recorded as
  CC BY-SA 4.0. Amudi's consonantal dataset removes qere, vowels, cantillation,
  spaces, punctuation, and section markers while retaining ketiv; Sephardi
  and Baladi views are generated from this base. Attribution and change notes
  are recorded in `Library/Torah/BibleCode/ATTRIBUTION.md`. **The current
  encrypted-only library does not provide a plaintext copy; compatibility
  with CC BY-SA's no-downstream-restrictions condition remains unresolved.**

Further details are in `TEXT_SOURCES.md` and
`Library/Torah/BibleCode/ATTRIBUTION.md`.

## Additional Talmud commentary editions

Amudi includes additional Hebrew Bavli and Yerushalmi commentary segments from
specific Sefaria Export editions that Sefaria labels Public Domain, PD, or CC0.
Each imported commentary file includes its edition title, source edition,
provider license label, source URL, live version-record URL, and content hash
in `rightsSources`. The full source register is
`Library/Shas/Semantic/data/sefaria-public-domain-commentary-source-register.json`.
The selected Public Domain/CC0 labels do not require attribution under those
recorded terms; Amudi retains the source records for transparency. Versions
labeled CC-BY or CC-BY-SA were not imported into the encrypted paid-library
path. These additions are organized by daf and individual provider segment;
they do not claim sentence-level alignment against AlHaTorah.

### Additional Torah commentary source editions (2026-10-30)

- **Siftei Chakhamim on the Torah** — Shabbetai ben Joseph Bass, Torah
  supercommentary on Rashi. The exact Hebrew *Siftei Hakhamim* edition from
  Torat Emet, distributed by Sefaria Export, is recorded as Public Domain.
  The included *Sefaria Community Translation* is CC0 1.0 and is only a
  small fragment. [Exact version records](https://www.sefaria.org/api/texts/versions/Siftei%20Chakhamim).
- **Torah Temimah on the Torah** — Barukh HaLevi Epstein. The exact Hebrew
  Vilna 1904 edition distributed by Sefaria Export is recorded as Public
  Domain; the included *Sefaria Community Translation* is CC0 1.0 and is
  partial. [Exact version records](https://www.sefaria.org/api/texts/versions/Torah%20Temimah%20on%20Torah).

Attribution, exact edition URLs, current version-license evidence, source
hashes, and chapter/verse coverage are stored in each volume under
`Library/Tanakh/Commentaries/{siftei-chakhamim,torah-temimah}/`. Amudi converts
the existing source JSON into its reader format. Placeholder strings are
excluded, and reference corrections are documented with their original
source coordinates. No OCR or newly generated translation was used. These
records do not represent the partial English text as a complete translation.

### Restored Kabbalah source sections (2026-10-30)

- **Sha'ar HaKavanot** — Chaim Vital; the existing *Sefaria Community
  Translation* is CC0 1.0. Amudi restored missing source paragraphs and
  aligned the available English to the corresponding Hebrew source nodes.
  The English remains partial.
- **Sha'ar Ruach HaKodesh** — Chaim Vital; Jerusalem 1863 Hebrew edition,
  distributed by Sefaria Export as Public Domain. Source introductions and
  supplementary prayer were retained as named appended reader chapters.
- **Ohr HaChammah on Zohar** — Abraham Azulai; Peremyshl 1896–1898 Hebrew
  edition, distributed by Sefaria Export as Public Domain. The author's
  introduction and preface were retained as named appended reader chapters.

Each book's `source-manifest-bibliography-repair-20261030.json` records its
exact source and license, source hash, retained section coordinates, output
hashes, and changes. Existing Hebrew main-text chapter numbers are preserved.
No OCR or new translation was performed.

### Further bibliography editions (2026-10-30)

- **Riva on Torah / Minchat Yehudah** — source attribution: Yehudah ben Eliezer. The exact Hebrew *Rabotenu Ba'ale ha-Tosafot, Warsaw, 1876* edition distributed by Sefaria Export is Public Domain. Five Torah volumes are retained. No English edition was found in the inspected exact version records.
- **Bartenura on Torah / Amar Naka** — the source index records attribution to Ovadiah of Bartenura, with an alternative attribution to Ovadiah ben Zechariah Hamon of Bartenura; Amudi preserves that dispute. The exact Warsaw 1876 Hebrew edition is Public Domain. The separate CC0 Sefaria Community Translation is partial and has retained entries in Numbers only. Exact source/version/license, index attribution evidence, source hashes and entry coverage are recorded in the collection's index and volume files.
- **Pri Chadash on Shulchan Arukh, Orach Chayim and Yoreh De'ah (partial)** — Hezekiah da Silva; Hebrew Wikisource contributors, typed transcription, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Orach Chayim contains only source simanim 67, 418, 671; Yoreh De'ah only 1, 69, 89, 240, 242, 245, 246. Source pages and exact revisions, licenses, hashes, formatting conversion, and coverage gaps are recorded in each book's source-manifest.json. Amudi distributes these adaptations under CC BY-SA 4.0, free and plaintext, without encryption or DRM. No English translation was imported. [Orach Chayim source](https://he.wikisource.org/wiki/פרי_חדש_על_אורח_חיים); [Yoreh De'ah source](https://he.wikisource.org/wiki/פרי_חדש_על_יורה_דעה).
- **Sefer HaRiqma / Kitab al-Luma’** — Jonah ibn Janah, author; Judah ibn Tibbon, Hebrew translator; Hebrew Wikisource contributors. The typed Hebrew transcription, based on the Frankfurt 1856 edition with documented contributor corrections, is CC BY-SA 4.0. Amudi retains all 48 source content pages (two introductions and gates 1–46), source revision IDs, hashes, and conversion/repair notices in source-manifest.json. This establishes coverage of that source’s contents, not the 54-chapter count stated in the attachment. The adaptation is distributed free and plaintext under CC BY-SA 4.0 without DRM; no English edition was imported. [Source](https://he.wikisource.org/wiki/ספר_הרקמה); [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
- **Midrash Tehillim source coverage** — Hebrew On Your Way edition, Public Domain; Sefaria Community Translation, CC0 as explicitly declared by the exact exported English version. Amudi restored empty canonical Hebrew chapter slots, added 18 English source entries in chapters 144–150, and retained the historical English wording at chapter20 with the version difference recorded. Source/license snapshots and all 300 chapter-file hashes are recorded in the source-coverage repair manifest; no OCR or new translation was performed.
- **Pirkei DeRabbi Eliezer, annotated English edition** — Gerald Friedlander, translator and annotator, London 1916; exact source version distributed by Sefaria Export as Public Domain and identified to NLI item 001020236. All 54 source chapter arrays, including inline footnotes, are retained as a separate edition. The earlier translation remains available. [Exact version/license records](https://www.sefaria.org/api/texts/versions/Pirkei%20DeRabbi%20Eliezer).
- **Meshekh Chokhmah / Mishnah Berurah restored source sections** — the Public Domain Riga 1927 Meshekh Chokhmah export supplies the omitted Bechukotai section and supplementary Haftorah/Megillah/essay sections; the CC0 Mishnah Berurah community edition supplies two introduction paragraphs. Exact source and output hashes, source-node mapping, and source-order metadata are recorded per book. The selected Mishnah Berurah Hebrew export has no text for simanim 1–186; Amudi records that gap explicitly. English coverage remains partial.

All additions in this section use existing typed source data. No OCR or newly generated translation was performed by Amudi.

- **Sefer HaTishbi (partial)** — Elijah Levita; Hebrew Wikisource contributors, typed and pointed transcription, [source](https://he.wikisource.org/wiki/ספר_התשבי), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Five available source pages are retained: introductions and Aleph through Dalet. Nine unfinished lexical entries are marked explicitly. Amudi's conversion removes formatting/navigation, retains notes and variants, and interleaves the introductory poem's line pairs; no OCR or new translation. Adaptation distributed free/plaintext under the same license, without DRM.
- **Sefer HaHasaga** — Jonah ibn Janah; medieval Hebrew translator Obadiah HaSefaradi; Hebrew Wikisource contributors, manuscript-based typed transcription, [source](https://he.wikisource.org/wiki/ספר_ההשגה), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). All eight source content pages retained. Source revisions, editorial changes, transcription corrections, and Amudi formatting conversion are recorded in source-manifest.json; no OCR/new translation. Adaptation distributed free/plaintext under the same license without DRM.
- **Ralbag Torah commentary, Ralbag Beur HaMilot, and Ralbag on Ruth** — Levi ben Gershon. Exact Venice1547 Torah and Königsberg1860 Ruth Hebrew exports are Public Domain; separate partial Sefaria Community English editions are [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). All eleven biblical volumes retain exact source strings, positions, source URLs, attribution and hashes. Introductions and Benefits remain separate source sections, accessible in the reader. No OCR/new translation.
- **Additional English editions** — Ovadiah of Bartenura, original Mishnah commentary; Sefaria Community contributors, partial CC0 English translation,301 exact source-entry mappings across14 books. Additional Tanakh English editions retain J.W.Etheridge's1862 Onkelos, M.Friedländer's1873 IbnEzraIsaiah, R.G.Finch's1919 RadakPsalms and A.McCaul's RadakZechariah editions labeled Public Domain; separate CC0 community additions remain partial. Exact edition/API license records, source/output hashes, attribution, formatting changes and any rejected positions are recorded per volume. Source wording preserved; no OCR/new translation.

- **Ba’alei Brit Avram** — Abraham Azulai; exact Vilna1873 disambiguated Sefaria Export Hebrew edition labeled Public Domain,52 source sections. Four existing Sefaria Community English paragraphs are CC0 1.0 and remain partial. Converted source sections into reader chapters, removed formatting wrappers while retaining displayed words, and preserved blank English alignment positions; no OCR/new translation. Exact source/API/hash and chapter correspondence records are in source-manifest.json.
- **Alshich on Lamentations, Song of Songs and Daniel** — Moshe Alshich; exact named Warsaw1862 Five Megillot and Warsaw1876 Daniel Sefaria Export editions, declared Public Domain and corroborated against current exact version records. All five Lamentations and eight Song chapters are present in these sources; Daniel includes only chapters1–6 and9. Four partial CC0 English Lamentations source paragraphs are retained, including introductory material. Formatting conversion preserves source paragraphs, supplemental sections and verse positions; no OCR/new translation. These named sources replace the earlier initial-revision import.

## Talmud

- **Current Semantic Shas (Bavli and Yerushalmi)** — Current content is
  distributed in per-tractate encrypted packages. Edition, provider, license
  claim, and source-evidence pointers are recorded per tractate in
  `data/tractates/<work>/sources.json`; the source manifest alone is not proof
  that an upstream contributor had authority to license the exact text. The
  v7 release applies a fail-closed page/layer filter. Do not infer that every
  Vilna text, transcription, or edition is public domain merely from its age
  or label. Gemara page/layers released by the 2026-10-15 open-license rule
  include a per-daf plaintext download; a page/layer with any additional hold
  reason remains hidden.

- **Sefaria exact Public Domain editions** — Retained Sefaria records are
  limited to exact version-title, source-URL, language, and license metadata
  matches. Byte-for-byte evidence files and SHA-256 values are bundled under
  `Shas/Semantic/data/source-evidence/sources/sefaria/`. This includes the
  Piotrków 1898–1900 *Chiddushei Ridbaz on Jerusalem Talmud* editions sourced
  to the National Library of Israel. Public Domain attribution is not legally
  required, but work, edition, Sefaria export URL, and NLI source are retained.
- **Open Scriptorium Tosafot** — Exact retained excerpts use Open
  Scriptorium's official `tosafot-bavli.csv` text. Open Scriptorium identifies
  Tosafot as Public Domain and says each work's reuse terms are supplied by
  its work metadata. The downloaded CSV, source URL, Public Domain record,
  and SHA-256 are retained under
  `Shas/Semantic/data/source-evidence/sources/openscriptorium/`. No
  attribution is required by the recorded work metadata; this notice is kept
  for provenance.

- **Bavli page scans** — Romm Vilna edition (1882–1887), digitized by Duke
  University Libraries and distributed by Internet Archive under Public
  Domain Mark 1.0. Source:
  https://archive.org/details/Talmud_Bavli_Vilna_images
- **Legacy Bavli V2 English translations** — The superseded
  `Library/Shas/Vilna/BavliV2/` dataset records the selected version and
  license on each daf under `source.canonicalEnglish`. It includes the William
  Davidson Edition – English (CC BY-NC 4.0), Sefaria Community Translation
  (CC0), and Wikisource Talmud (CC BY-SA 4.0). This legacy data is distinct
  from the current Semantic Shas source/provenance records; do not package or
  serve it to new releases unless legacy-client support is intentionally
  retained. No endorsement by any source, translator, or publisher is implied.
- **Current Semantic Shas** — Bavli and Yerushalmi files under
  `Library/Shas/Semantic/data/tractates/` have their own source manifests and
  per-daf provenance. Verify the exact edition, license, attribution, and
  changes in those current records rather than relying on the legacy V2 notice.
  Sources: https://www.sefaria.org, https://en.wikisource.org, and
  https://www.nli.org.il/he/books/NNL_ALEPH001901012/NLI
- **Legacy Dicta pointed Hebrew** — The older `Library/Shas/Vilna/BavliV2/`
  dataset used `Talmud-Bavli-with-Nikud`, `combinedfullmaleh`, by Dicta: The
  Israel Center for Text Analysis, under CC BY-SA 4.0. That dataset is not the
  current Semantic Shas v7 release and must not be included in a new release
  without an explicit decision to support legacy clients and a separate
  review of downstream access restrictions. No endorsement by Dicta is
  implied.
- **Yerushalmi scan source selected for integration** — the standard
  Vilna/Romm tzurat hadaf represented by HebrewBooks item 40733. The historic
  edition is public domain. Amudi preserves the source identifier and credits
  HebrewBooks for the scan. Source: https://www.hebrewbooks.org/40733
- **Yerushalmi structured editions** — Imported from Sefaria only on a
  per-version basis when Sefaria metadata records Public Domain, CC0, CC BY,
  or another compatible reuse license. Version title, source, license, and
  attribution are retained with every imported dataset.

### Public-domain rabbinic translations

Editions for Mishnah, Tosefta, Minor Tractates, Midrash, Halakhah, Responsa,
Kabbalah, Chasidut, Musar, liturgy, commentary, and other Jewish works are
imported from Sefaria Export only when their individual version metadata
explicitly records `Public Domain`, `PD`, `CC0`, `CC-BY`, or `CC-BY-SA`. Amudi
selects the most complete eligible English edition for each work and retains
its version title, source URL, version source, and license in `book.json`.
Some eligible community translations are partial.

The development-only junction `Library/Shas/Vilna/Bavli/debug_original_pages`
points to a local test source and must not be included in distributable builds.

## Fonts

All bundled Hebrew and English fonts are distributed under the freely
redistributable licenses listed below. No font extracted from a scanned or
source PDF is included in the distributable library.

### Google Fonts (SIL OFL 1.1)

Montserrat, Noto Serif, Noto Serif Hebrew, Noto Rashi Hebrew, Miriam Libre, Open Sans, Roboto, Rubik, and David Libre are
distributed under the SIL Open Font License 1.1 from Google Fonts. Copyright notices and complete 
OFL texts are kept in each font family's directory.
`fonts/English/English.woff2` is an unaltered Roboto binary covered by `fonts/English/Roboto/OFL.txt`.

- **Noto Rashi Hebrew** — Copyright 2022 The Noto Project Authors. Source:
  https://github.com/google/fonts/tree/main/ofl/notorashihebrew
- **Miriam Libre** — Copyright 2023 The Miriam Libre Project Authors. Source:
  https://github.com/google/fonts/tree/main/ofl/miriamlibre

### SIL International Fonts (SIL OFL 1.1)

Ezra SIL is distributed under the SIL Open Font License 1.1 by SIL International.
License details: `fonts/Hebrew/Ezra_SIL/` and available at https://www.sil.org/resources/software_fonts/

### OpenSiddur.org Community Fonts (SIL OFL 1.1 / GPL+FE)

The following fonts are freely licensed under SIL Open Font License 1.1 or GNU Public License 
with Font Exception (GPL+FE) by the OpenSiddur.org community project, a volunteer-driven, 
non-profit, libre Open Access archive of Jewish prayer and liturgical resources.

- ShlomoStam — Elegant Hebrew calligraphic/manuscript style
- Mekorot-Rashi — GPL-licensed body-text face used for ordinary Gemara commentary; Noto Rashi remains the dibbur-hamatchil face
- Nachlaot — Modern Israeli community typography
- Stam Ashkenaz CLM — Ashkenazi religious/ceremonial script
- Stam Sefarad CLM — Sephardi religious/ceremonial script  
- Paleo Siloam — Ancient Hebrew script (8th century BCE)
- Proto-Canaanite — Proto-Canaanite ancient script (pre-Hebrew ancestor)
- Mekorot-Vilna — based with minor changes on Drugulin CLM from the Culmus
  Font Project; GPL version 2 or later. Source and license:
  https://github.com/aharonium/fonts/tree/master/Fonts/Hebrew%20Letters%20with%20Vowels%20(no%20cantillation)/Mekorot%20(LPPL)/Vilna

License details, copyright notices, and complete license texts are available in each 
font directory within `fonts/Hebrew/`. Additional information: https://opensiddur.org/help/fonts/

OpenSiddur Project attribution: https://opensiddur.org (Copyleft © 2002-Present, Contributors)

## Icons

The interface contains icons from the Lucide/Feather and Google Material
Symbols collections.

- Lucide is licensed under ISC; icons inherited from Feather are MIT licensed.
  See `LICENSES/Lucide-ISC-MIT.txt`.
- Google Material Symbols are licensed under Apache License 2.0. See
  `LICENSES/Apache-2.0.txt`.

## JavaScript attribution

- The Talmud page layout is based on and adapted from
  [TalmudLab/daf-renderer](https://github.com/TalmudLab/daf-renderer), licensed
  under the MIT License. Copyright (c) 2020 Dan Jutan Shaun Regenbaum. See
  `LICENSES/daf-renderer-MIT.txt`.
ImageMagick and Tesseract OCR are used as external build-time tools and are not
bundled as browser assets.

## Native Android dependencies

- Capacitor and the Capacitor Local Notifications and Share plugins — MIT.
- AndroidX libraries — Apache License 2.0.
- Firebase and Google Play services — distributed under the applicable Google
  SDK and service terms.
- Bouncy Castle Java provider — MIT-style Bouncy Castle license.
- Apache Commons Compress — Apache License 2.0.

Corresponding license texts and source links are included in `LICENSES/`.

## Original Amudi artwork

The Amudi logo, launcher and splash-screen variants, and bookmark image were
created by the Amudi project owner and are covered by the Amudi proprietary
license. No third-party logo artwork is claimed.

<!-- bibliography-final-additions:start -->
### Additional typed bibliography editions and source repairs (2026-10-30)

- Tanya: Shneur Zalman of Liadi; Hebrew Wikisource contributors. All120 selected chapter/preface pages across five parts retained; exact source revisions and contributor histories are in its source-manifest.json. [Source](https://he.wikisource.org/wiki/ספר_התניא), [CC BY-SA4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi removed site/navigation formatting and converted the source into reading chapters, retaining text and notes. The adaptation remains CC BY-SA4.0, free/plaintext with unrestricted export. No new translation or OCR.
- Zohar: traditional attribution to Shimon bar Yochai and his circle; Hebrew Wikisource contributors. All29 distinct selected typed chunks are retained;54 source omission/redirect notices remain explicit. [Source](https://he.wikisource.org/wiki/ספר_הזהר), [CC BY-SA4.0](https://creativecommons.org/licenses/by-sa/4.0/). Converted to321 reading sections without changing selected-source words; source revisions, contributor histories and notices are in source-manifest.json. Adaptation remains CC BY-SA4.0, free/plaintext with unrestricted export. No new translation or OCR; no claim to cover every historical word or separate ZoharChadash/TikkuneiZohar.
- Other additional English editions: exact creator/translator, publisher, source, provider grant, versioned license, prior notices and Amudi conversion changes are recorded per edition in data/library-attributions.json and each source-manifest.json. Community CC0 and named CC BY editions remain individually distinguishable. A complete selected source can be a partial translation of the underlying work; that limitation is retained.
- Additional Hebrew source introductions, appendices and missing continuations were restored from the exact recorded licensed editions. Existing historic readings remain, with current alternative readings/supplements explicitly labeled. Source locations, hashes, current grant evidence and conversion changes are in each book’s source manifest.
- Seder Tannaim ve-Amoraim: anonymous Geonic work, Hida/Krengel recension and source annotations; Hebrew Wikisource contributors, CC BY-SA4.0. Five source sections and84 rules retained. Source revision2936985 and contributor history are recorded; Amudi converted HTML sections to chapters without OCR/new translation. Adaptation free/plaintext under the same license; the separate chronology/Kahana1935 edition is not claimed.

Exact source/grant evidence controls each component. Unverified legacy Greenman empty-source association and Sefat Emet differing English paragraphs are on HOLD; verified replacement source editions are linked. No unavailable or unverified material is represented as newly cleared merely by its title.
<!-- bibliography-final-additions:end -->

### Fragment Targum — Wikisource edition (2026-10-30)

The fragment Targum text was typed and vocalized by David Wiscot according to the Hebrew Wikisource source index, and includes contributions from Hebrew Wikisource editors. The version used here was extracted directly from the recorded chapter revisions. Source pages, immutable revision links and contributor histories are in the edition’s source-manifest.json. Amudi removed passage markers and navigation, normalized whitespace, reconciled source marker errors using visible labels and a separately indexed edition, and placed the text into verse arrays; no OCR or translation was performed. The resulting adaptation is provided free and without encryption or restrictions on reuse under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Source: [Hebrew Wikisource](https://he.wikisource.org/wiki/תרגום_ירושלמי_(קטעים)_לתורה).

### Targum to Chronicles — Wikisource edition (2026-10-30)

The source page credits David Wiscot for its typed, vocalized text and includes contributions by Hebrew Wikisource editors. Amudi extracted the passages into verse arrays, removed numbering and category links, normalized whitespace, and aligned a run of inconsistent source labels with the source headings and a separately indexed edition. No OCR or translation was performed. The exact source revision, history link, wording differences, and alignment notes are in source-manifest.json. The adaptation is provided free and without encryption or reuse restrictions under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). [Source revision](https://he.wikisource.org/w/index.php?oldid=728465). A separate partial English Sefaria Community Translation of I Chronicles (50 verses) is [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/); it comes from a different edition and does not translate every wording of the Wikisource text. [English source](https://storage.googleapis.com/sefaria-export/json/Tanakh/Targum/Targum%20Jerusalem/Targum%20of%20I%20Chronicles/English/Sefaria%20Community%20Translation.json).

- **Haggahot Maimuniyyot — Hebrew Wikisource (partial)** — Rabbi Meir HaKohen and Hebrew Wikisource contributors; [source](https://he.wikisource.org/wiki/הגהות_מיימוניות), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Four partial source chapters; revision and contributor-history links are in the book’s source manifest. Source markup was converted to reader paragraphs; the adapted text is freely available without encryption under the same license.

- **Shulchan Arukh — Lemberg source editions** — Joseph Karo; embedded glosses by Moses Isserles. Hebrew editions: Maginei Eretz, Lemberg 1893, and Ashlei Ravrevei, Lemberg 1888; Sefaria Export labels both Public Domain. Partial English: Sefaria Community Translation contributors, [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Exact source and version links, source hashes, missing source positions and Amudi formatting changes are recorded in each edition’s source-manifest.json.

- **Shulchan Arukh commentary passage links** — Sefaria links dataset, [source file 0](https://storage.googleapis.com/sefaria-export/links/links0.csv), [source file 1](https://storage.googleapis.com/sefaria-export/links/links1.csv), [source file 3](https://storage.googleapis.com/sefaria-export/links/links3.csv), [source file 4](https://storage.googleapis.com/sefaria-export/links/links4.csv), [source file 5](https://storage.googleapis.com/sefaria-export/links/links5.csv), [source file 9](https://storage.googleapis.com/sefaria-export/links/links9.csv), [source file 10](https://storage.googleapis.com/sefaria-export/links/links10.csv), [source file 11](https://storage.googleapis.com/sefaria-export/links/links11.csv), [source file 12](https://storage.googleapis.com/sefaria-export/links/links12.csv), [source file 13](https://storage.googleapis.com/sefaria-export/links/links13.csv), [source file 14](https://storage.googleapis.com/sefaria-export/links/links14.csv), [source file 15](https://storage.googleapis.com/sefaria-export/links/links15.csv), [source file 16](https://storage.googleapis.com/sefaria-export/links/links16.csv), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Filtered to checked source references, matched to exact locally retained source chapters and converted to Amudi paragraph positions. Text editions have their own separate licenses.

- **Additional passage links** — Sefaria links dataset, [source file 2](https://storage.googleapis.com/sefaria-export/links/links2.csv), [source file 6](https://storage.googleapis.com/sefaria-export/links/links6.csv), [source file 7](https://storage.googleapis.com/sefaria-export/links/links7.csv), and [source file 8](https://storage.googleapis.com/sefaria-export/links/links8.csv), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). References were filtered and converted to local positions after matching source chapters. The underlying text editions have separate licenses.

- **Kaf HaChayim, Orach Chayim, 1924–1928 volumes** — R. Yaakov Chaim Sofer; Sefaria Export labels the selected named edition Public Domain. Simanim 319–494 were retained in source order with source and historical publication evidence in the book’s source-manifest.json. Partial Sefaria Community English is [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Later 1931 and 1933 volumes remain held pending separate rights review.

### Targum Neofiti on Genesis — English excerpts (2026-10-30)

Sefaria community contributors, Targum Neofiti, Sefaria Community Translation, Genesis 1:1–8, [source](https://storage.googleapis.com/sefaria-export/json/Tanakh/Targum/Targum%20Neofiti/Targum%20Neofiti/English/Sefaria%20Community%20Translation.json), [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Passage alignment uses [Sefaria links](https://www.sefaria.org/api/links/Targum%20Neofiti%201?with_text=0), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); filtered to exact corresponding verse references. The English text is unchanged. No Aramaic source text is included.

### Ralbag on Song of Songs — English introduction (2026-10-30)

Sefaria community contributors, Ralbag on Song of Songs, Introduction, [source](https://storage.googleapis.com/sefaria-export/json/Tanakh/Rishonim%20on%20Tanakh/Ralbag/Writings/Ralbag%20on%20Song%20of%20Songs/English/Sefaria%20Community%20Translation.json), [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). The 13 paragraphs are preserved as an introduction, without assigning them to verses. No OCR or new translation.

### Reviewed Sefaria community Tanakh excerpts (2026-10-30)

Sefaria community contributors; reviewed excerpts in Daniel, Esther, Isaiah, Job, Nehemiah and Proverbs; [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Each exact source and reviewed passage is listed in the respective book’s translation metadata. Unreviewed or misnumbered passages are omitted; no source wording was changed.

### Chomat Anakh on I Samuel — Wikisource passages (2026-11-05)

Seven passages of Chomat Anakh by Chaim Yosef David Azulai are adapted from Hebrew Wikisource contributors, under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The exact source revisions and contributor histories are in the edition source manifest. Amudi extracted verse commentary, retained its footnote, removed navigation and an alternate-page notice, and normalized whitespace. This partial adaptation is offered free without technical restrictions on reuse. No OCR or translation was performed by Amudi.

### Yosef Kara on Lamentations — Wikisource passages (2026-11-05)

Fifteen passages of Rabbi Yosef Kara’s commentary are adapted from Hebrew Wikisource contributors under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Each source revision and contributor history is in the edition source manifest, and editable source wikitext is provided. Amudi normalized markup, removed navigation and footnotes, and assigned verse coordinates. This partial adaptation is free and distributed without technical restrictions on reuse. The original digitization method is unspecified; no OCR or translation was performed by Amudi.

### Onkelos — Yemenite Taj (Wikisource edition) (2026-11-05)

Aramaic passages of Targum Onkelos, in Hebrew Wikisource contributors’ Yemenite Taj edition, are adapted from Sefaria Export and direct Wikisource readings under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Chapter source revisions and contributor histories are listed in the source manifest; editable source wikitext is included. Amudi retained export verses corroborated by Hebrew letters, substituted nine direct Wikisource readings, and documented alternate verse divisions. Provider vocalization was not independently collated. No OCR or new translation was performed by Amudi. This adaptation is offered free without technical restrictions on reuse.

### Onkelos community English excerpts (2026-11-05)

Partial English translations of Onkelos from Sefaria Community Translation contributors are provided under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Source URLs, hashes and verse-level coverage appear in the relevant edition records. Amudi retained the source wording and positions, without translating or using OCR. Literal equivalence with the separate Yemenite Taj reading is not asserted.

### Onkelos: Etheridge English excerpts (2026-11-05)

English excerpts translated by J. W. Etheridge (first published 1862–1865) are from the [eBible.org digital edition](https://ebible.org/find/show.php?id=engoke), which marks the text public domain. Amudi extracted a partial set of verse passages from its [USFM source](https://ebible.org/Scriptures/engoke_usfm.zip), removed formatting and notes, and checked the wording against a second transcription. No OCR or new translation was performed by Amudi; the historical digitization method is not specified. The excerpts are associated by verse number and are not asserted to translate the specific Yemenite Taj reading literally.

### Yosef Kara on Torah — excerpts collected by Abraham Geiger (2026-11-05)

Selected paragraphs attributed to Yosef Kara are from Abraham Geiger’s [Sefer Parshandatha](https://benyehuda.org/read/29158), in the Project Ben-Yehuda edition marked public domain. The provider [permits commercial use](https://benyehuda.org/page/about) of works so marked. Amudi retained Geiger’s paragraphs and qualifications, normalized whitespace, and placed them at the biblical verse references stated in the source. This is a partial collection, not the full commentary. No OCR or new translation was performed by Amudi.

### Menachem ben Helbo through Yosef Kara — excerpts collected by Abraham Geiger (2026-11-05)

Selected passages attributed to Menachem ben Helbo through Yosef Kara come from Abraham Geiger’s [Sefer Parshandatha](https://benyehuda.org/read/29158), in Project Ben-Yehuda’s public-domain-labeled edition. Its [terms](https://benyehuda.org/page/about) allow commercial use of works so marked. Amudi preserved Geiger’s full source paragraphs and editorial notes, normalized whitespace and aligned each passage to its stated biblical verse. This is a partial collection, not a complete commentary. No OCR or translation was performed by Amudi.

### Bartenura on Mishnah — English by Rabbi Robert Alpert (2026-11-05)

English translation by Rabbi Robert Alpert, supplied by Sefaria Export, is provided under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Each book’s source manifest identifies the exact work, source, author and changes. Amudi retained the source wording and joined source coordinates to documented Sefaria passage links. These translations are available in plaintext without technical restrictions. No OCR or new translation was performed by Amudi.

### Bartenura on Mishnah — community English excerpts (2026-11-05)

Partial English translations from Sefaria Community Translation contributors are provided under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Each edition records its source and attribution. Amudi retained the source wording and joined source coordinates to documented Sefaria passage links; no OCR or new translation was performed by Amudi.

### Siftei Chakhamim, Chizkuni and Rabbeinu Bahya — English source editions (2026-11-05)

English commentary editions supplied by Sefaria Export are available under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Siftei Chakhamim is from the Metsudah Publications edition; Chizkuni and Rabbeinu Bahya are translated by Eliyahu Munk. The exact source, publisher, attribution, provider’s prior modification notice, and Amudi’s changes are recorded in each edition’s source manifest. Amudi preserved the existing English wording and source verse coordinates and excluded standalone ellipsis placeholders; no OCR or new translation was performed by Amudi.


### Or HaChaim and Tur HaArokh — English translated by Eliyahu Munk (2026-11-05)

English translations by Eliyahu Munk, provided by Sefaria Export, are available under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Each edition’s source manifest identifies the exact source, publisher, attribution, provider’s prior corrections and Amudi’s changes. Amudi retained source wording and verse positions and excluded one out-of-range duplicate. No OCR or new translation was performed by Amudi.

### Rashi — English editions (2026-11-05)

Selected English Rashi translations supplied by Sefaria Export are available under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Each volume identifies its own translator where named, publisher, source, license evidence and provider’s prior changes. Amudi retained source wording, formatting and verse coordinates; no OCR or new translation was performed by Amudi. The source collection may be partial.

### Mishnah Berurah: Hebrew Wikisource (2026-11-06)

Selected Hebrew Mishnah Berurah passages by Rabbi Israel Meir HaKohen of Radin are based on [Hebrew Wikisource](https://he.wikisource.org/wiki/קטגוריה:משנה_ברורה_על_אורח_חיים), under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Page-level source revisions, contributor histories and editable original wikitext accompany this partial edition. Six heading corrections in simanim 49, 91 and 128 use [Sefaria passage links](https://storage.googleapis.com/sefaria-export/links/links12.csv) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Extracted text from revision-specific rendered Wikisource pages, grouped commentary by its labelled Shulchan Arukh seif or the only seif of an unheaded siman, and removed page navigation and headings. Six misdirected heading links in simanim 49, 91 and 128 were checked against Sefaria passage links (CC BY 4.0). Siman 509 text embedded on the siman 508 page is kept only under its matching 509 source. Copyrightable adaptations are offered under CC BY-SA 4.0. No OCR or new translation was performed by Amudi; the historical digitization method is not established.

### Mishnah Berurah: community English excerpts (2026-11-06)

Selected English comments are from the [Sefaria Community Translation](https://www.sefaria.org/Mishnah_Berurah?tab=versions), marked [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). The selection uses [Sefaria passage links](https://storage.googleapis.com/sefaria-export/links/links12.csv), licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), and Wikisource comment numbers to associate comments with the same seif. Selected original CC0 English comments and grouped them by the matching Wikisource seif after reviewing the comment numbers and Sefaria passage links. Offset source indices and conflicting links were individually checked against the English heading, Wikisource and the base passage. One comment on 8:13 is linked directly to the base although its numbered Hebrew counterpart is absent from the selected Wikisource group. Source wording and comment order are retained. This is not a sentence-by-sentence equivalence claim for the Wikisource Hebrew edition.

### Mishnat Sofrim: Hebrew Wikisource appendix (2026-11-06)

Selected Mishnat Sofrim passages by Rabbi Israel Meir HaKohen of Radin are from [Hebrew Wikisource](https://he.wikisource.org/wiki/משנה_ברורה_על_אורח_חיים_לו), under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The source page is marked incomplete. The revision, contributor history, changes and editable source accompany this partial edition.


### Simchat HaRegel: partial Hebrew Wikisource introductory studies (2026-11-06)

The partial introductory studies of Simchat HaRegel are by Chaim Yosef David Azulai, with Wikisource transcription and notes credited to Ido Avraham and contributors. [Source revision](https://he.wikisource.org/w/index.php?title=%D7%A9%D7%9E%D7%97%D7%AA%20%D7%94%D7%A8%D7%92%D7%9C&oldid=2875815), [contributor history](https://he.wikisource.org/w/index.php?title=%D7%A9%D7%9E%D7%97%D7%AA%20%D7%94%D7%A8%D7%92%D7%9C&action=history), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi labels the source’s added explanations, restructures the text into reading sections and offers the adapted text and original source without access restrictions. Study C and the Haggadah commentary are not present in this source.

### Vayikra Rabbah — Sefaria 2022 English (2026-11-06)

Vayikra Rabbah; The Sefaria Midrash Rabbah, 2022. Managing editor: Jason Rappoport; translator: Joshua Schreier; editors: Michael Siev and Yaacov Francus; copy editors: Deborah Meghnagi Bailey and Ilana Sobel. Source: Sefaria. [Source](https://storage.googleapis.com/sefaria-export/json/Midrash/Aggadah/Midrash%20Rabbah/Vayikra%20Rabbah/English/The%20Sefaria%20Midrash%20Rabbah,%202022.json); [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Converted the selected existing source edition into Amudi chapter JSON without changing source wording or ordering. Each English chapter is readable independently; no alignment to the differently segmented Wikisource Hebrew edition is asserted. No OCR or new translation was performed by Amudi.

### Sifrei Bamidbar — Silverstein English (2026-11-06)

Sifrei Bamidbar; English translation by Rabbi Shraga Silverstein, provided by Sefaria. The translator’s edition incorporates alternative readings, based in part on the Vilna Gaon’s glosses. [Source](https://storage.googleapis.com/sefaria-export/json/Midrash/Halakhah/Sifrei%20Bamidbar/English/Sifrei%20by%20Rabbi%20Shraga%20Silverstein.json); [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Amudi converted the existing source translation into chapter JSON, preserving source wording and order. No OCR or new translation was performed by Amudi. The source has different readings and some different segment counts from the Hebrew; no sentence-level correspondence with a separate Hebrew edition is asserted.

### Sifrei Bamidbar — Wikisource Hebrew (2026-11-06)

Sifrei Bamidbar, Wikisource edition; Hebrew Wikisource contributors, supplied by Sefaria Export. The source index and linked page histories are recorded in the accompanying manifest. [Source export](https://storage.googleapis.com/sefaria-export/json/Midrash/Halakhah/Sifrei%20Bamidbar/Hebrew/Wikisource.json); [Wikisource index](https://he.wikisource.org/wiki/%D7%A1%D7%A4%D7%A8%D7%99); [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). Amudi split the existing typed provider edition into chapter JSON while preserving every source segment and its order. This selected source is separate from the older local edition and the Silverstein translation; no cross-edition passage alignment is asserted. No OCR or translation was performed by Amudi. The provider source text and linked page histories accompany the open edition.

### Bamidbar Rabbah: partial Hebrew Wikisource edition (2026-11-06)

Bamidbar Rabbah, Hebrew Wikisource edition, by Wikisource contributors. Individual passage revisions and contributor histories are linked in the source manifest. [Source index](https://he.wikisource.org/wiki/%D7%91%D7%9E%D7%93%D7%91%D7%A8_%D7%A8%D7%91%D7%94); [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi converted the selected rendered Hebrew Wikisource passages and list items into plain reading text, labeled source footnotes, removed navigation, formatting and explanatory tooltip expansions, and retained blank positions for unavailable or unreviewed passages. The adapted edition is shared under CC BY-SA 4.0. No OCR or new translation was performed by Amudi. Source revisions, contributor histories, editable wikitext and template-history links accompany the edition.

### Pesikta Rabbati: partial community English (2026-11-06)

Pesikta Rabbati, Sefaria Community Translation; translated by Sefaria community contributors and provided by Sefaria. [Source](https://storage.googleapis.com/sefaria-export/json/Midrash/Aggadah/Pesikta%20Rabbati/English/Sefaria%20Community%20Translation.json); [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Amudi divided the existing source into numbered reading sections and flattened nested source arrays; source paths and blank entries are preserved in the manifest. No OCR or new translation was performed. Source coordinates have not been matched to the separate Hebrew edition.

### Sifra: Rabbi Shraga Silverstein English edition (2026-11-06)

Sifra, translated by Rabbi Shraga Silverstein, provided by Sefaria; source: http://www.sefaria.org/shraga-silverstein. [Source](https://storage.googleapis.com/sefaria-export/json/Midrash/Halakhah/Sifra/English/Sifra%20by%20Rabbi%20Shraga%20Silverstein.json); [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Amudi divided the typed source into numbered reading sections while preserving the source section names, source order, wording and empty entries. The provider notes that the translation incorporates alternative readings based in part on the Vilna Gaon’s glosses and can differ from its Hebrew edition. No OCR or new translation was performed by Amudi; no cross-edition sentence alignment is asserted.

### Devarim Rabbah: partial Hebrew Wikisource edition (2026-11-06)

Devarim Rabbah, Hebrew Wikisource edition, by Wikisource contributors. Individual passage revisions and contributor histories are linked in the source manifest. [Source index](https://he.wikisource.org/wiki/%D7%93%D7%91%D7%A8%D7%99%D7%9D_%D7%A8%D7%91%D7%94); [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi converted the selected rendered Hebrew Wikisource passages and list items into plain reading text, labeled source footnotes, removed navigation, formatting and explanatory tooltip expansions, and retained blank positions for unavailable or unreviewed passages. The adapted edition is shared under CC BY-SA 4.0. No OCR or new translation was performed by Amudi. Source revisions, contributor histories, editable wikitext and template-history links accompany the edition.


### Esther Rabbah: partial Hebrew Wikisource edition (2026-11-06)

Esther Rabbah, Hebrew Wikisource edition, by Wikisource contributors. Individual passage revisions and contributor histories are linked in the source manifest. [Source index](https://he.wikisource.org/wiki/%D7%90%D7%A1%D7%AA%D7%A8_%D7%A8%D7%91%D7%94); [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi converted the selected rendered Hebrew Wikisource passages and list items into plain reading text, labeled source footnotes, removed navigation, formatting and explanatory tooltip expansions, and retained blank positions for unavailable or unreviewed passages. The adapted edition is shared under CC BY-SA 4.0. No OCR or new translation was performed by Amudi. Source revisions, contributor histories, editable wikitext and template-history links accompany the edition.


### Ohr HaSekhel: community English source edition (2026-11-06)

Ohr HaSekhel by Abraham Abulafia; Sefaria Community Translation by Sefaria community contributors, provided by Sefaria. [Source](https://storage.googleapis.com/sefaria-export/json/Kabbalah/Ohr%20HaSekhel/English/Sefaria%20Community%20Translation.json); [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Amudi presents the existing source introduction and ten source parts as eleven numbered reading sections, preserving source text and blank slots. No OCR or new translation was performed, and alignment with a separate Hebrew edition is not asserted.

### Nefesh David on Zohar: Wikisource-derived Hebrew edition (2026-11-06)

Nefesh David on Zohar by Rabbi David Luria; Hebrew Wikisource contributors. Sefaria Export identifies the linked Wikisource work as the source. [Provider export](https://storage.googleapis.com/sefaria-export/json/Kabbalah/Zohar/Nefesh%20David%20on%20Zohar/Hebrew/Nefesh%20David.json); [Wikisource source](https://he.wikisource.org/wiki/%D7%A0%D7%A4%D7%A9_%D7%93%D7%95%D7%93_(%D7%A8%D7%93%22%D7%9C)); [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi preserves the provider text in three volume arrays and provides its source in reusable form. The source states that this transcription has not been proofread. The exact upstream Wikisource revisions used by Sefaria are not identified. Current linked page histories and editable source files accompany the edition; exact upstream revisions are not established.

### Nefesh David on Zohar: direct Wikisource edition (2026-11-06)

Nefesh David on Zohar by Rabbi David Luria; Hebrew Wikisource contributors. The source index and individual page histories are included. [Source index](https://he.wikisource.org/wiki/%D7%A0%D7%A4%D7%A9_%D7%93%D7%95%D7%93_(%D7%A8%D7%93%22%D7%9C)); [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi converted the seven selected Wikisource pages into named reading sections, preserved source order and labeled source footnotes. Formatting, links and tooltip expansions were removed. The source says its transcription has not been proofread. The adapted edition is shared under CC BY-SA 4.0. No OCR or new translation was performed by Amudi. Editable Wikisource source and page histories accompany the edition.

### Shemot Rabbah — Sefaria English (2026-11-06)

Shemot Rabbah, The Sefaria Midrash Rabbah, 2022; translator Joshua Schreier; managing editor Jason Rappoport; editors Michael Siev and Yaacov Francus; copy editors Deborah Meghnagi Bailey and Ilana Sobel; Sefaria. [Source](https://storage.googleapis.com/sefaria-export/json/Midrash/Aggadah/Midrash%20Rabbah/Shemot%20Rabbah/English/The%20Sefaria%20Midrash%20Rabbah,%202022.json); [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Amudi retained the source text in chapter JSON without changing wording or order. No OCR or new translation was performed. Source edition is separately readable and English/Hebrew segment counts differ in some chapters.

### Kohelet Rabbah — Sefaria English (2026-11-06)

Kohelet Rabbah, The Sefaria Midrash Rabbah, 2022; translator Joshua Schreier; managing editor Jason Rappoport; editors Michael Siev and Yaacov Francus; copy editors Deborah Meghnagi Bailey and Ilana Sobel; Sefaria. [Source](https://storage.googleapis.com/sefaria-export/json/Midrash/Aggadah/Midrash%20Rabbah/Kohelet%20Rabbah/English/The%20Sefaria%20Midrash%20Rabbah,%202022.json); [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Amudi retained source text in chapter JSON without changing wording or order, flattening source sections while recording their coordinates. No OCR or new translation was performed. The source edition is separately readable.

### Shir HaShirim Rabbah — Sefaria English (2026-11-06)

Shir HaShirim Rabbah, The Sefaria Midrash Rabbah, 2022; translator Joshua Schreier; managing editor Jason Rappoport; editors Michael Siev and Yaacov Francus; copy editors Deborah Meghnagi Bailey and Ilana Sobel; Sefaria. [Source](https://storage.googleapis.com/sefaria-export/json/Midrash/Aggadah/Midrash%20Rabbah/Shir%20HaShirim%20Rabbah/English/The%20Sefaria%20Midrash%20Rabbah,%202022.json); [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Amudi retained source text in chapter JSON without changing wording or order, flattening source sections while recording their coordinates. No OCR or new translation was performed. The source edition is separately readable.

### Devarim Rabbah — Sefaria English (2026-11-06)

Devarim Rabbah, The Sefaria Midrash Rabbah, 2022; translator Joshua Schreier; managing editor Jason Rappoport; editors Michael Siev and Yaacov Francus; copy editors Deborah Meghnagi Bailey and Ilana Sobel; Sefaria. [Source](https://storage.googleapis.com/sefaria-export/json/Midrash/Aggadah/Midrash%20Rabbah/Devarim%20Rabbah/English/The%20Sefaria%20Midrash%20Rabbah,%202022.json); [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Amudi retained the source text in chapter JSON without changing wording or order. No OCR or new translation was performed. Source edition is separately readable and English/Hebrew segment counts differ in some chapters.

### Ohr Sameach on Prayer — community English excerpt (2026-11-06)

Sefaria Community Translation contributors; Sefaria Export. [Source](https://storage.googleapis.com/sefaria-export/json/Halakhah/Mishneh%20Torah/Commentary/Ohr%20Sameach/Sefer%20Ahavah/Ohr%20Sameach%20on%20Mishneh%20Torah%2C%20Prayer%20and%20the%20Priestly%20Blessing/English/Sefaria%20Community%20Translation.json); [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/); [provider community-translation policy](https://developers.sefaria.org/docs/general-faq). The exact export and version record leave the license field blank. One existing English passage retained with source position 10:16:1; no OCR or new translation. The separate edition has its own chapter numbering.


### Tosafot Yeshanim on Yoma — Vilna and community translation (2026-11-06)

Tosafot Yeshanim on Yoma, Vilna Edition, supplied by Sefaria Export and declared Public Domain by the provider. One source-coordinate-matched English passage is from Sefaria Community Translation contributors and declared CC0. [Hebrew source](https://storage.googleapis.com/sefaria-export/json/Talmud/Bavli/Rishonim%20on%20Talmud/Tosafot%20Yeshanim/Seder%20Moed/Tosafot%20Yeshanim%20on%20Yoma/Hebrew/Vilna%20Edition.json); [English source](https://storage.googleapis.com/sefaria-export/json/Talmud/Bavli/Rishonim%20on%20Talmud/Tosafot%20Yeshanim/Seder%20Moed/Tosafot%20Yeshanim%20on%20Yoma/English/Sefaria%20Community%20Translation.json); [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Amudi retained the original typed wording and placed passages by source daf and comment order.

### Yoma Tosafot Yeshanim source-reference links (2026-11-06)

Passage links by Sefaria, [source](https://storage.googleapis.com/sefaria-export/links/links16.csv), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected Yoma links and matched the cited source segments to local daf word ranges.

### Yoma Tosafot Yeshanim partial source-reference links (2026-11-06)

Passage links by Sefaria, [source](https://storage.googleapis.com/sefaria-export/links/links16.csv), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected Yoma links and matched the cited source segments to local daf word ranges.

### Yevamot Tosafot Yeshanim source-reference links (2026-11-06)

Passage links by Sefaria, [source](https://storage.googleapis.com/sefaria-export/links/links16.csv), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected Yevamot links and matched the cited source segments to local daf word ranges.

### Yevamot Tosafot Yeshanim partial source-reference links (2026-11-06)

Passage links by Sefaria, [source](https://storage.googleapis.com/sefaria-export/links/links16.csv), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected Yevamot links and matched the cited source segments to local daf word ranges.

### Tosafot Yeshanim on Keritot — Vilna source (2026-11-06)

Tosafot Yeshanim on Keritot, Vilna Edition, supplied by Sefaria Export and declared Public Domain by the provider. [Source](https://storage.googleapis.com/sefaria-export/json/Talmud/Bavli/Rishonim%20on%20Talmud/Tosafot%20Yeshanim/Seder%20Kodashim/Tosafot%20Yeshanim%20on%20Keritot/Hebrew/Vilna%20Edition.json). Amudi selected and placed existing source text by daf, line and comment coordinates.

### Keritot Tosafot Yeshanim source-reference links (2026-11-06)

Passage links by Sefaria, [source](https://storage.googleapis.com/sefaria-export/links/links9.csv), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected Keritot links and matched the cited source segments to local daf word ranges.

### Keritot Tosafot Yeshanim partial source-reference links (2026-11-06)

Passage links by Sefaria, [source](https://storage.googleapis.com/sefaria-export/links/links9.csv), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected Keritot links and matched the cited source segments to local daf word ranges.

### Four Tosafot tractate editions — Vilna sources (2026-11-06)

Sefaria Export supplies these selected Vilna editions and labels them Public Domain: [Tosafot HaRosh on Horayot](https://storage.googleapis.com/sefaria-export/json/Talmud/Bavli/Rishonim%20on%20Talmud/Tosafot%20HaRosh/Seder%20Nezikin/Tosafot%20HaRosh%20on%20Horayot/Hebrew/Talmud%20Bavli%2C%20Vilna%201883%20ed..json); [Tosafot HaRosh on Niddah](https://storage.googleapis.com/sefaria-export/json/Talmud/Bavli/Rishonim%20on%20Talmud/Tosafot%20HaRosh/Seder%20Tahorot/Tosafot%20HaRosh%20on%20Niddah/Hebrew/Talmud%20Bavli%2C%20Vilna%201883%20ed..json); [Tosafot Shantz on Sotah](https://storage.googleapis.com/sefaria-export/json/Talmud/Bavli/Rishonim%20on%20Talmud/Tosafot%20Shantz/Seder%20Nashim/Tosafot%20Shantz%20on%20Sotah/Hebrew/Vilna%20Edition.json); [Tosafot Ri HaZaken on Kiddushin](https://storage.googleapis.com/sefaria-export/json/Talmud/Bavli/Rishonim%20on%20Talmud/Tosafot%20Ri%20HaZaken/Seder%20Nashim/Tosafot%20Ri%20HaZaken%20on%20Kiddushin/Hebrew/Vilna%20Edition.json). Amudi retained the source text and positioned passages by daf and source comment order.

### Four Tosafot editions: source-reference links (2026-11-06)

Commentary links by Sefaria; [source 1](https://storage.googleapis.com/sefaria-export/links/links7.csv), [source 2](https://storage.googleapis.com/sefaria-export/links/links13.csv), [source 3](https://storage.googleapis.com/sefaria-export/links/links16.csv), [source 4](https://storage.googleapis.com/sefaria-export/links/links10.csv); [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected references and matched complete source Gemara segments to local daf positions.

### Four Tosafot editions: partial source-reference links (2026-11-06)

Commentary links by Sefaria; [source 1](https://storage.googleapis.com/sefaria-export/links/links7.csv), [source 2](https://storage.googleapis.com/sefaria-export/links/links13.csv), [source 3](https://storage.googleapis.com/sefaria-export/links/links16.csv), [source 4](https://storage.googleapis.com/sefaria-export/links/links10.csv); [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected references and matched distinctive portions of source Gemara segments to local daf positions.


### Tosafot Rid on Gittin — Vilna source (2026-11-06)

Sefaria Export supplies this selected Vilna edition and labels them Public Domain: [Tosafot Rid on Gittin](https://storage.googleapis.com/sefaria-export/json/Talmud/Bavli/Rishonim%20on%20Talmud/Tosafot%20Rid/Tosafot%20Rid%20on%20Gittin/Hebrew/Vilna%20Edition.json). Amudi retained the source text and positioned passages by daf and source comment order.

### Tosafot Rid on Gittin: source-reference links (2026-11-06)

Commentary links by Sefaria; [source 1](https://storage.googleapis.com/sefaria-export/links/links6.csv); [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected references and matched complete source Gemara segments to local daf positions.

### Tosafot Rid on Gittin: partial source-reference links (2026-11-06)

Commentary links by Sefaria; [source 1](https://storage.googleapis.com/sefaria-export/links/links6.csv); [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected references and matched distinctive portions of source Gemara segments to local daf positions.

### Tosafot Rid on Ketubot — Vilna source (2026-11-06)

Sefaria Export supplies the selected [Vilna edition of Tosafot Rid on Ketubot](https://storage.googleapis.com/sefaria-export/json/Talmud/Bavli/Rishonim%20on%20Talmud/Tosafot%20Rid/Tosafot%20Rid%20on%20Ketubot/Hebrew/Vilna%20Edition.json) and labels it Public Domain. Source passages were retained with their original text and placed on their recorded daf. Some are additionally aligned using a unique opening phrase or a provider link matched to a complete local Gemara segment; remaining passages have daf-level placement only.

### Midrash Tehillim passage references (2026-11-06)

Sefaria link data, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), was filtered to same-psalm midrash references and quotation-corroborated unclassified related references, and converted to Amudi chapter and passage coordinates. Source shard links appear in the commentary drawer and the associated evidence report. The selected Sefaria Psalms and Midrash Tehillim Hebrew versions are labeled Public Domain by their provider.

### Yalkut Shimoni related passage references (2026-11-06)

Reference data from Sefaria, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), was filtered and mapped to Bible and existing Feuer English source coordinates. Some unclassified references were retained only after corroborating a unique quotation. Hebrew Wikisource passages are matched within source units and include their page revisions and contributor histories in the reader. The related Feuer excerpts are credited to Rabbi Mike Feuer and are recorded by their provider as [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/); the related Sefaria Community Translation passages are recorded as [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Source links, changes, and alignment limitations are shown in the commentary drawer.


### Noda BiYehudah and Shoel uMeshiv source corrections (2026-11-06)

Fourteen short local text differences were corrected to match the selected Hebrew editions supplied by Sefaria Export. The provider labels these selected editions Public Domain. Source versions and URLs:

- Noda BiYehudah I: [Noda BeYehuda Warsaw 1880](https://storage.googleapis.com/sefaria-export/json/Responsa/Acharonim/Noda%20BiYehudah%20I/Hebrew/Noda%20BeYehuda%20Warsaw%201880.json).
- Noda BiYehudah II: [Noda Bi-Yehudah Part II; Warsaw, 1880](https://storage.googleapis.com/sefaria-export/json/Responsa/Acharonim/Noda%20BiYehudah%20II/Hebrew/Noda%20Bi-Yehudah%20Part%20II%3B%20Warsaw%2C%201880.json).
- Shoel uMeshiv Mahadura I: [Lemberg, 1865-1890](https://storage.googleapis.com/sefaria-export/json/Responsa/Acharonim/Shoel%20uMeshiv/Shoel%20uMeshiv%20Mahadura%20I/Hebrew/Lemberg%2C%201865-1890.json).
- Shoel uMeshiv Mahadura II: [Lemberg, 1865-1890](https://storage.googleapis.com/sefaria-export/json/Responsa/Acharonim/Shoel%20uMeshiv/Shoel%20uMeshiv%20Mahadura%20II/Hebrew/Lemberg%2C%201865-1890.json).
- Shoel uMeshiv Mahadura III: [Lemberg, 1865-1890](https://storage.googleapis.com/sefaria-export/json/Responsa/Acharonim/Shoel%20uMeshiv/Shoel%20uMeshiv%20Mahadura%20III/Hebrew/Lemberg%2C%201865-1890.json).
- Shoel uMeshiv Mahadura IV: [Lemberg, 1865-1890](https://storage.googleapis.com/sefaria-export/json/Responsa/Acharonim/Shoel%20uMeshiv/Shoel%20uMeshiv%20Mahadura%20IV/Hebrew/Lemberg%2C%201865-1890.json).
- Shoel uMeshiv Mahadura V: [Lemberg, 1865-1890](https://storage.googleapis.com/sefaria-export/json/Responsa/Acharonim/Shoel%20uMeshiv/Shoel%20uMeshiv%20Mahadura%20V/Hebrew/Lemberg%2C%201865-1890.json).
### Noda BiYehudah II — English responsa

Sefaria Responsa Anthology, Sefaria Export, is available under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Amudi moved two existing translated responsa to match their Hebrew source coordinates; the translation wording was not changed.


### Responsa community translation coordinate corrections (2026-11-06)

Sefaria Community Translation contributors, Sefaria Export: selected CC0 1.0 passages were moved to the matching local Hebrew source coordinates without changing translation wording. The affected books and source URLs are recorded in the translation metadata and alignment evidence.

### Epistle of Rav Sherira Gaon coordinate correction (2026-11-06)

One Hebrew character was restored to the selected Sefaria Export version, which the provider labels Public Domain. Existing Sefaria Community Translation passages, marked CC0 1.0 by the provider, were moved to their matched Hebrew source coordinates without changing the English wording.
### Havot Yair — English responsa

Sefaria Responsa Anthology, Sefaria Export, is recorded under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Amudi moved existing translated passages to match their Hebrew source coordinates; the translation wording was not changed.

### B'Mareh HaBazak, volumes I and VII

The Hebrew editions are attributed to Machon Eretz Hemdah and supplied by Sefaria Export under the provider-recorded [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) terms. English excerpts are Sefaria Community Translation, recorded as CC0. Amudi moved four English excerpts to their matching Hebrew source coordinates without changing their wording; edition source links appear in the book metadata.

### Responsa English source passages

Selected passages from Sefaria Community Translation are recorded by the provider as [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Selected passages from Sefaria Responsa Anthology are recorded as [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Amudi added existing source passages at their matched Hebrew source coordinates without changing the translation wording. Book metadata contains the edition-specific source links and credits.

### Responsa Chatam Sofer — Pressburg 1855–1864

The selected Hebrew edition is supplied by Sefaria Export and labeled Public Domain by the provider. The accompanying Sefaria Community Translation excerpts are recorded as [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Amudi converted source units into reading chapters and preserved the translated passages at their source coordinates; edition-specific source links and the chapter mapping are in the book's source manifest.

### Rashba and Rosh — English excerpts

The Rashba excerpts are from Sefaria Responsa Anthology, Sefaria Export, under the provider-recorded [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) terms. The Rosh excerpts are from Sefaria Community Translation, recorded as [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Amudi retained the source passages as separately numbered excerpts; source coordinates and version details appear in each book's source manifest.


### Arukh HaShulchan: Roman English translation (partial)

Arukh HaShulchan, Hupah veKiddushin, English translation by Norman T. Roman, via Sefaria. [Source](https://storage.googleapis.com/sefaria-export/json/Halakhah/Arukh%20HaShulchan/English/Hupah%20veKiddushin%2C%20trans.%20by%20Norman%20T.%20Roman.%20HUC%2C%201975.json); [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Selected nonempty source segments and stored them in source order in a separate reading section, preserving exact displayed wording and the source coordinates in the manifest. No OCR or new translation. Hebrew alignment has not been established.

### Arukh HaShulchan, Choshen Mishpat: community English excerpts

Arukh HaShulchan, Choshen Mishpat, Sefaria Community Translation by Sefaria community contributors. [Source](https://storage.googleapis.com/sefaria-export/json/Halakhah/Arukh%20HaShulchan/English/Sefaria%20Community%20Translation.json); [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Selected existing typed source segments and preserved source order and paragraph positions; no new OCR or translation.

### Arukh HaShulchan, Yoreh De'ah: community English excerpts

Arukh HaShulchan, Yoreh De'ah, Sefaria Community Translation by Sefaria community contributors. [Source](https://storage.googleapis.com/sefaria-export/json/Halakhah/Arukh%20HaShulchan/English/Sefaria%20Community%20Translation.json); [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Selected existing typed source segments and preserved source order and paragraph positions; no new OCR or translation.

### Arukh HaShulchan, Yoreh De’ah: selected Wikisource sections

Arukh HaShulchan, Yoreh De’ah: Wikisource contributors, via Sefaria; contributor histories are linked per section in source-manifest.json. [Source](https://storage.googleapis.com/sefaria-export/json/Halakhah/Arukh%20HaShulchan/Hebrew/Arukh%20HaShulchan%2C%20Yoreh%20De%27ah%20--%20Wikisource.json); [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); [provider CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/). Selected six existing source sections, retained source wording and order, added section labels and source-coordinate links. No OCR or translation performed by Amudi. Adapted material is shared under CC BY-SA 4.0.

### Malbim on Leviticus — open source-matched excerpts

Commentary by Malbim; digitization and editorial contributions by Hebrew Wikisource contributors, with the Sefaria export as the source text. The edition selects 733 partial passages and reorganizes them by verse; the matching Wikisource page revisions and contributor histories are listed in its source-manifest.json. The export is labelled Public Domain by its provider; the selected adaptation is conservatively shared under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) without encryption or reuse restrictions. [Source export](https://storage.googleapis.com/sefaria-export/json/Tanakh/Acharonim%20on%20Tanakh/Malbim/Torah/Malbim%20on%20Leviticus/Hebrew/Malbim%20on%20Vayikra%20%E2%80%93%20Wikisource.json). Verse references use the Sefaria links dataset under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). No OCR or translation was performed by Amudi.

### Meshekh Chokhmah on Torah — selected passages

Hebrew commentary by Meir Simcha of Dvinsk, Riga 1927 edition, labelled Public Domain by Sefaria; [source](https://storage.googleapis.com/sefaria-export/json/Tanakh/Acharonim%20on%20Tanakh/Meshech%20Hochma/Meshekh%20Chokhmah/Hebrew/Riga%2C%201927.json). Nine partial English excerpts by Sefaria Community Translation contributors are [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/); [source](https://storage.googleapis.com/sefaria-export/json/Tanakh/Acharonim%20on%20Tanakh/Meshech%20Hochma/Meshekh%20Chokhmah/English/Sefaria%20Community%20Translation.json). Verse references use the Sefaria links dataset under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected source-coordinate excerpts using matching Hebrew openings, including common vav/yod spelling variations, or independently reviewed edition headings, and rearranged them by verse; no OCR or new translation was performed. Source references and changes are in the edition’s source manifest.

### Kiddushin Tosafot HaRosh source-reference links (2026-11-06)

Passage links by Sefaria, [source](https://storage.googleapis.com/sefaria-export/links/links10.csv), [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Amudi selected Kiddushin commentary links and matched their cited segments to local daf word ranges.

### Standalone semantic viewer renderer

The local semantic viewer bundles the MIT-licensed [TalmudLab daf-renderer](https://github.com/TalmudLab/daf-renderer). Its license is included at `Shas/Semantic/vendor/daf-renderer-MIT.txt`.


- **Pardes Rimmonim** — Moses Cordovero; Sefaria export: main Hebrew version marked Public Domain by the provider (upstream transcription rights remain unconfirmed), supplemental Koretz 1780 edition marked Public Domain, and partial [Sefaria Community Translation under CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Source URLs, hashes, chapters, and limitations are documented in the book source manifest. No OCR or new translation performed.

### Rashi on Song of Songs — Ginsburg excerpt

Selected English specimen paragraphs translated by Christian David Ginsburg, The Song of Songs (London, 1857). The source edition is [recorded as public domain in the USA](https://www.gutenberg.org/ebooks/69329); rights outside the USA require separate review. Digitization credited to Jeroen Hellingman, the Online Distributed Proofreading Team, and Project Ben-Yehuda volunteers. Amudi selected five verse-labelled paragraphs, removed digitization page markers and normalized whitespace; the source itself presents an excerpt. [Source and license information](https://www.gutenberg.org/policy/license.html).

### Ibn Ezra on Song of Songs — Ginsburg excerpt

Selected allegorical gloss translated by Christian David Ginsburg, The Song of Songs (London, 1857), recorded as [public domain in the USA](https://www.gutenberg.org/ebooks/69329); rights outside the USA require review. Digitization credited to Jeroen Hellingman, the Online Distributed Proofreading Team, and Project Ben-Yehuda volunteers. Amudi selected four verse-labelled paragraphs and normalized whitespace; the source is an excerpt.

### Shulchan Arukh Orach Chayim — Brahms Yom Kippur English

Translation by Jan M. Brahms, Hebrew Union College, 1976, digitized by Sefaria and supplied under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). [Source edition](https://storage.googleapis.com/sefaria-export/json/Halakhah/Shulchan%20Arukh/Shulchan%20Arukh%2C%20Orach%20Chayim/English/Hilkhot%20Yom%20ha-Kippurim%2C%20trans.%20by%20Jan%20M.%20Brahms.%20HUC%2C%201976.json). Amudi preserved the English wording and source positions, selecting exact normalized Hebrew matches and individually reviewed heading, spelling, or abbreviation variants for the Lemberg edition; the edition and links are partial. No OCR or new translation was performed by Amudi.


### Vilna Gaon on Joshua (selected passages)

Vilna Gaon, as attributed by Hebrew Wikisource; Hebrew Wikisource contributors. Source revision and contributor history for each passage are in source-manifest.json. CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/). Extracted typed commentary paragraphs from the cited verse pages, removed navigation and styles, and normalized whitespace; mapped to the verses named by the source. No OCR or translation.

- [הגאון מווילנה על יהושע ב יב](https://he.wikisource.org/w/index.php?title=%D7%94%D7%92%D7%90%D7%95%D7%9F%20%D7%9E%D7%95%D7%95%D7%99%D7%9C%D7%A0%D7%94%20%D7%A2%D7%9C%20%D7%99%D7%94%D7%95%D7%A9%D7%A2%20%D7%91%20%D7%99%D7%91&oldid=1312139) · [Contributor history](https://he.wikisource.org/w/index.php?title=%D7%94%D7%92%D7%90%D7%95%D7%9F%20%D7%9E%D7%95%D7%95%D7%99%D7%9C%D7%A0%D7%94%20%D7%A2%D7%9C%20%D7%99%D7%94%D7%95%D7%A9%D7%A2%20%D7%91%20%D7%99%D7%91&action=history)
- [הגאון מווילנה על יהושע ב יד](https://he.wikisource.org/w/index.php?title=%D7%94%D7%92%D7%90%D7%95%D7%9F%20%D7%9E%D7%95%D7%95%D7%99%D7%9C%D7%A0%D7%94%20%D7%A2%D7%9C%20%D7%99%D7%94%D7%95%D7%A9%D7%A2%20%D7%91%20%D7%99%D7%93&oldid=1312138) · [Contributor history](https://he.wikisource.org/w/index.php?title=%D7%94%D7%92%D7%90%D7%95%D7%9F%20%D7%9E%D7%95%D7%95%D7%99%D7%9C%D7%A0%D7%94%20%D7%A2%D7%9C%20%D7%99%D7%94%D7%95%D7%A9%D7%A2%20%D7%91%20%D7%99%D7%93&action=history)

### Isaiah di Trani on Torah — quotation in Uvacharta Bachaim

A single attributed quotation at Exodus 7:22 is from Chaim Palache, Uvacharta Bachaim, edited by Netanel Haba and [Hebrew Wikisource contributors](https://he.wikisource.org/w/index.php?title=%D7%95%D7%91%D7%97%D7%A8%D7%AA_%D7%91%D7%97%D7%99%D7%99%D7%9D/%D7%95%D7%90%D7%A8%D7%90&oldid=2716311), licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi extracted the paragraph, normalized whitespace, and placed it at its cited verse. The rest of the work and an English translation are not included in this edition.

### Uvacharta Bachaim — Exodus 14:7 source excerpts

One quotation attributed to Isaiah di Trani and one editor summary attributed to Moshav Zekenim come from [Uvacharta Bachaim, Beshalach](https://he.wikisource.org/w/index.php?title=%D7%95%D7%91%D7%97%D7%A8%D7%AA_%D7%91%D7%97%D7%99%D7%99%D7%9D/%D7%91%D7%A9%D7%9C%D7%97&oldid=2716315), Chaim Palache, edition editor Netanel Haba and Hebrew Wikisource contributors, under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi extracted the paragraphs, normalized whitespace, and linked them to the source’s verse. They are partial; the latter is a summary, not a verbatim original.

Moshav Zekenim: an additional editor summary on Deuteronomy 1:3 is taken from [Uvacharta Bachaim, Devarim](https://he.wikisource.org/w/index.php?title=%D7%95%D7%91%D7%97%D7%A8%D7%AA_%D7%91%D7%97%D7%99%D7%99%D7%9D/%D7%93%D7%91%D7%A8%D7%99%D7%9D&oldid=2716374), by Chaim Palache, edition editor Netanel Haba and Hebrew Wikisource contributors, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The paragraph was extracted, whitespace normalized, and linked to the footnote’s biblical verse. It discusses multiple authors and preserves the editor’s disagreement.

### Yosef Da’at — discussion in Uvacharta Bachaim

One discussion citing Yosef Da’at at Numbers 23:24 is from [Uvacharta Bachaim, Balak](https://he.wikisource.org/w/index.php?title=%D7%95%D7%91%D7%97%D7%A8%D7%AA_%D7%91%D7%97%D7%99%D7%99%D7%9D/%D7%91%D7%9C%D7%A7&oldid=2716366), Chaim Palache, edited by Netanel Haba and Hebrew Wikisource contributors, under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Amudi extracted the paragraph, normalized whitespace, and corrected the verse reference using the biblical quotation. This is not a verbatim version of Yosef Da’at.

### Bava Kamma Rabbeinu Chananel passage links (2026-11-10)

Passage links by [Sefaria](https://developers.sefaria.org/docs/usage-of-our-name-and-logo), CC BY (provider does not specify a version; [license information](https://creativecommons.org/licenses/by/)). Amudi selected and mapped links to local daf word offsets. Source datasets: [links1.csv](https://storage.googleapis.com/sefaria-export/links/links1.csv), [links2.csv](https://storage.googleapis.com/sefaria-export/links/links2.csv).
