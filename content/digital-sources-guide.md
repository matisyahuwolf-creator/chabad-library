---
title: "Digital Sources Guide"
tags: [chabad, lubavitch-rebbes]
---

# Digital Sources for the Writings & Talks of the Chabad-Lubavitch Rebbes

A practical map of *where* to find the corpus of the seven Chabad-Lubavitch Rebbes — in the original Hebrew/Yiddish and in English — across the major digital libraries. For each resource: what it is, how it covers the seven Rebbes, free vs. paid, languages, English availability, how to navigate it, and its strengths and limits.

The seven Rebbes whose corpus is in view:

1. **Alter Rebbe** — R. Schneur Zalman of Liadi (Tanya, Shulchan Aruch HaRav, Torah Or, Likutei Torah, Igros)
2. **Mitteler Rebbe** — R. Dovber Schneuri
3. **Tzemach Tzedek** — R. Menachem Mendel Schneersohn (Or HaTorah, Derech Mitzvosecha, responsa)
4. **Rebbe Maharash** — R. Shmuel Schneersohn (Toras Shmuel)
5. **Rebbe Rashab** — R. Sholom DovBer Schneersohn (the "maamarim" continuation series, e.g. Hemshech Ayin Beis)
6. **Frierdiker (Previous) Rebbe** — R. Yosef Yitzchak Schneersohn (Sefer HaMaamarim, Igros Kodesh, Sefer HaSichos, Sefer HaZichronos)
7. **The Rebbe** — R. Menachem Mendel Schneerson (Likutei Sichos, Torat Menachem, Sefer HaMaamarim Melukat, Igros Kodesh, Reshimos)

---

## The digital libraries

### chabadlibrary.org — Otzar Sifrei Lubavitch (official online reader)

- **URL:** https://chabadlibrary.org (book reader at https://chabadlibrary.org/books/)
- **What it is:** The official free online reader of the Library of Agudas Chassidei Chabad — Ohel Yosef Yitzchak (the central Chabad-Lubavitch library at 770 Eastern Parkway). It is run by the movement itself and presents the published Chabad seforim ("Otzar Sifrei Lubavitch") as full, navigable text.
- **Coverage of the seven Rebbes:** This is the single most complete free home for the *primary published corpus* of all seven Rebbes. Confirmed holdings include the Alter Rebbe's Igros Kodesh, the Tzemach Tzedek's Igros Kodesh, the Maharash's Toras Shmuel, and the Rebbe's Likutei Sichos, Torat Menachem and Igros Kodesh — and the breadth extends across maamarim, Torah Or / Likutei Torah, sichos and letters of the line.
- **Free vs. paid:** Free. No subscription or login required (a donation button supports the library).
- **Languages:** Primarily Hebrew (with Yiddish where original). Bilingual Hebrew/English site chrome; separate library *catalogs* exist in English, French, German, Italian and Russian, but the readable full texts are overwhelmingly the Hebrew originals.
- **English availability:** Minimal — this is an original-language resource. For English translations go to Sefaria, Chabad.org or Sichos in English.
- **How to navigate:** Enter the `/books/` reader and drill down by Rebbe/author, then by work and volume. Each work has a stable numeric URL (e.g. a book id like `chabadlibrary.org/books/6502210011`), so you can deep-link to a specific volume. Text is selectable/searchable.
- **Strengths:** Authoritative, official, free, and structured by Rebbe and work; reliable canonical text; deep-linkable. **Limits:** Hebrew only in practice; the catalog/reader split can be confusing; interface is utilitarian and Hebrew-first.

### HebrewBooks.org

- **URL:** https://hebrewbooks.org (English browse at https://hebrewbooks.org/english)
- **What it is:** A free repository of 40,000+ scanned Hebrew seforim in PDF, originally built to preserve out-of-print American Hebrew books and now aiming to hold "all Torah seforim ever printed."
- **Coverage of the seven Rebbes:** Good and growing. Historically held a respectable Chabad collection; has been adding newer Kehot prints and recent typeset editions, including hard-to-find volumes and historical Chabad works. Strongest for older/out-of-print editions of maamarim and classic Chabad seforim; coverage of the most recent copyrighted Kehot series is partial.
- **Free vs. paid:** Free.
- **Languages:** Hebrew (some Yiddish). Page-image scans of the printed originals.
- **English availability:** Essentially none for translations; it is a Hebrew page-scan library.
- **How to navigate:** Search by title, author, or full text; view in-browser as HTML or page-image, or download the PDF. Browse by subject/author. (Note: the site is sometimes behind anti-bot protection for automated access; the human-facing site works normally.)
- **Strengths:** Free PDFs of the actual printed pages; excellent for older editions and bibliographic/historical research; full-text search. **Limits:** Scans, not reflowable text; coverage of current copyrighted Kehot editions is incomplete; no English.

### Sefaria.org (and its open API)

- **URL:** https://www.sefaria.org — Tanya at https://www.sefaria.org/Tanya — developer portal at https://developers.sefaria.org
- **What it is:** The largest free, open digital library of Jewish texts, with aligned Hebrew + English and a structured, interlinked database. Committed to open-source/open-data.
- **Coverage of the seven Rebbes:** Selective rather than comprehensive. Strong on the Alter Rebbe's **Tanya** (full, structured, with commentary links) and other foundational/anthologized Chabad material; Likutei Sichos and other Rebbe-era works appear via topics and source sheets rather than as complete authoritative editions. Use it for the canonical foundational texts, not as a complete Chabad shelf.
- **Free vs. paid:** Free.
- **Languages:** Hebrew and English aligned side-by-side (plus other translations where available).
- **English availability:** Strong for what it carries — Tanya and core texts have English; quality and completeness vary by work.
- **How to navigate:** Browse the table of contents or search; click any segment to see translations, commentaries and cross-links. **API:** the public API needs no key or auth and returns JSON. Base under `https://www.sefaria.org/api/` with the live reference endpoints documented at the developer portal — e.g. `/api/v3/texts/{ref}` (current text retrieval with language control), `/api/v1/texts/{ref}` (legacy), `/api/index/{title}` (metadata/structure) and `/api/links/{ref}` (connections). An AI/agent index is published at https://developers.sefaria.org/llms.txt.
- **Strengths:** Free, open, structured, machine-readable; the best programmatic source; bilingual alignment. **Limits:** Chabad coverage is partial — fine for Tanya and core texts, not for the full maamarim/sichos/igros corpus.

### Chabad.org Library

- **URL:** https://www.chabad.org/library (Texts & Writings: https://www.chabad.org/library/article_cdo/aid/76131/jewish/Texts-Writings.htm)
- **What it is:** The large, free, consumer-facing library of Chabad.org (Merkos L'Inyonei Chinuch), mixing classic Jewish texts with Chabad chassidic works and study aids.
- **Coverage of the seven Rebbes:** Curated rather than exhaustive. Houses **Tanya** (including "Lessons in Tanya"), selections from Torah Or / Likutei Torah, daily Chitas study, and a substantial set of the Rebbe's material via TheRebbe.org (essays, letters, Likkutei Sichot renderings). Tens of thousands of items overall.
- **Free vs. paid:** Free.
- **Languages:** Primarily English, with Hebrew originals and bilingual editions for key works.
- **English availability:** Excellent — this is the best free *English* gateway to Chabad teaching, especially Tanya with running explanation, holiday discourses and the Rebbe's material.
- **How to navigate:** Browse by category (Classic Texts, Chassidic Texts, Chassidic Works) or topic filter; strong internal search; companion study tools (audio classes, Chitas).
- **Strengths:** Best free English entry point; beginner-friendly; pedagogically framed (Lessons in Tanya). **Limits:** Curated/anthologized, not a complete original-language corpus; not designed for scholarly citation of full critical texts.

### Sichos in English / sie.org

- **URL:** https://www.sie.org — store at https://shop.sie.org
- **What it is:** Since 1977/1978, the premier publisher of Chabad chassidic teachings in English, founded to translate the Rebbe's talks for those facing the language barrier. Hundreds of volumes published.
- **Coverage of the seven Rebbes:** Strongest on **the Rebbe** (Likkutei Sichos selections, translated sichos and maamarim, holiday discourses) and the preceding Rebbeim's discourses rendered into English. The explicit mission is to present the Rebbe and earlier Chabad Rebbeim to English readers in their own voice.
- **Free vs. paid:** Hybrid. A large body of translated text is readable free on sie.org; printed and premium editions (e.g. the multi-volume "Selections from Likkutei Sichos" set) are sold via the shop.
- **Languages:** English (translating Hebrew/Yiddish originals).
- **English availability:** This is one of the central English-translation resources for the Rebbe's talks and Chabad discourses.
- **How to navigate:** Read translated works online via the article templates on sie.org; buy print/e-books at shop.sie.org. Browse by work (e.g. Likkutei Sichos) or topic.
- **Strengths:** Authoritative, faithful English translations of the Rebbe's talks; long track record; much available free online. **Limits:** Translations are selective, not a complete rendering of the entire corpus; site organization is dated.

### Otzar HaChochma (Otzar HaHochma)

- **URL:** https://www.otzar.org (English: https://www.otzar.org/otzaren/indexeng.asp)
- **What it is:** The world's largest digital library of Judaica — ~156,000 books scanned page-by-page in their original format, with high-precision OCR full-text search. Includes thousands of current copyrighted titles licensed from major publishers, including **Kehot (Kehat) Publication Society**.
- **Coverage of the seven Rebbes:** The most comprehensive *paid* shelf of the Chabad corpus in original-language scans — because it carries the licensed Kehot catalog alongside historical Chabad printings. If a Chabad sefer exists in print, it is most likely here.
- **Free vs. paid:** Paid/subscription (online plans, and hard-drive editions). Institutional IP-based access is common at yeshivos and university libraries; some institutions offer free patron access.
- **Languages:** Hebrew (and Yiddish where original); page-image scans.
- **English availability:** None to speak of — original-language scans.
- **How to navigate:** Subscribe (individual, family, or institutional) or use it through a library; then search by title/author or full text and read page-images. Catalog/booklists are browsable publicly even where reading requires a subscription.
- **Strengths:** Unmatched breadth, including current copyrighted Kehot editions; powerful OCR search; faithful page-images for citation. **Limits:** Paywalled; scans only; no English; best accessed via an institution.

### Kehot Publication Society — kehot.com / KehotOnline (store.kehotonline.com)

- **URL:** https://www.kehot.org — store at https://store.kehotonline.com
- **What it is:** The official publishing arm of Chabad-Lubavitch, established 1941 by the sixth Rebbe; the world's largest publisher of Jewish literature, with the seventh Rebbe as its founding editor-in-chief. **Kehot is the copyright holder for most of the Rebbes' published works.**
- **Coverage of the seven Rebbes:** Definitive — Kehot is the source of record. It publishes/distributes the authoritative print editions of essentially the entire corpus (Tanya, Likutei Sichos, Torat Menachem, Sefer HaMaamarim, Igros Kodesh, etc.) across many languages.
- **Free vs. paid:** Paid. This is a commercial publisher/bookstore selling print books, e-books, audiobooks and multimedia. Not a free reading library.
- **Languages:** Hebrew, Yiddish, English, Russian, Spanish, French, Italian, Portuguese, Dutch, German, Farsi and Arabic.
- **English availability:** Yes — Kehot publishes authoritative English editions (e.g. bilingual Tanya, translated discourses) for purchase.
- **How to navigate:** Browse/buy at store.kehotonline.com by author/Rebbe, series, or language; some titles in e-book format.
- **Strengths:** The authoritative, complete, official editions; the canonical text and translation; broad language range. **Limits:** Commercial — you buy, you don't browse free full texts; e-book availability varies by title.

### Daat — daat.ac.il

- **URL:** https://www.daat.ac.il (and the related Chassidut-focused project at https://daat.org.il)
- **What it is:** A long-running free Hebrew digital library of Jewish studies affiliated with Herzog College — Bible, Halacha, prayer, philosophy, history, Holocaust studies, and a dedicated Chassidut (חסידות) section, plus courses, an encyclopedia and study sheets.
- **Coverage of the seven Rebbes:** Secondary/supplementary. Useful for chassidic texts, context and academic framing rather than as a complete Chabad primary-source archive; its strength is breadth across Jewish studies, not depth in the Chabad corpus.
- **Free vs. paid:** Free.
- **Languages:** Primarily Hebrew, with a smaller English section.
- **English availability:** Limited.
- **How to navigate:** Browse the subject sections (including Chassidut) or search; also offers distance-learning courses and an online encyclopedia.
- **Strengths:** Free, academically oriented, broad Jewish-studies context. **Limits:** Not Chabad-specialized; Hebrew-first; coverage of the full Rebbe corpus is thin compared with chabadlibrary.org or Otzar.

### Hebrew Wikisource — he.wikisource.org

- **URL:** https://he.wikisource.org (e.g. Tanya: https://he.wikisource.org/wiki/תניא)
- **What it is:** The Hebrew-language free, community-edited library of source texts — reflowable digital text (not scans) under open licenses.
- **Coverage of the seven Rebbes:** Focused on public-domain / openly-licensed foundational works. The complete **Tanya** is hosted as a finished project (based on the Otzar HaChassidim — Lubavitch edition, re-punctuated), in five sections, downloadable as EPUB/MOBI/PDF. Newer copyrighted works (most Rebbe-era material) are not here for copyright reasons.
- **Free vs. paid:** Free.
- **Languages:** Hebrew original.
- **English availability:** No (English source texts live on the separate English Wikisource and are sparse for Chabad).
- **How to navigate:** Search the title; read as structured web text or download EPUB/MOBI/PDF; CC BY-SA 4.0 licensing.
- **Strengths:** Free, reflowable, downloadable, openly licensed; excellent clean text of Tanya. **Limits:** Narrow Chabad coverage (essentially foundational/public-domain texts); community-edited so verify against an authoritative edition.

### Chabadpedia — chabadpedia.co.il / chabadpedia.com

- **URL:** https://chabadpedia.co.il (Hebrew) — https://chabadpedia.com (English)
- **What it is:** A volunteer-run wiki encyclopedia of Chabad (started in the early 2000s by Tomchei Temimim 770 students), with thousands of articles on the Rebbes, their works, history and teachings.
- **Coverage of the seven Rebbes:** Reference/index, not primary text. The best free place to *understand* the corpus — what a given maamar, sichah, or sefer is, when it was said/published, how works relate — and to find pointers to where the texts live.
- **Free vs. paid:** Free.
- **Languages:** Mainly Hebrew; a smaller English edition.
- **English availability:** Partial (English wiki is much smaller than the Hebrew).
- **How to navigate:** Search or browse articles by Rebbe, work, date, or topic; follow article references.
- **Strengths:** Excellent orientation and metadata; helps you identify the right work before hunting the text. **Limits:** Encyclopedia, not a text archive; volunteer-edited with a movement perspective (notable emphasis on Moshiach/Geulah themes) — verify facts and citations.

### TheRebbe.org

- **URL:** https://www.therebbe.org (hosted within Chabad.org; default at https://www.chabad.org/therebbe)
- **What it is:** A joint project of Chabad.org and Jewish Educational Media (JEM) dedicated to the seventh Rebbe — biography, essays, insights, letters, first-person stories, and English renderings of his teachings.
- **Coverage of the seven Rebbes:** The Rebbe only (R. Menachem Mendel Schneerson), whose published teachings fill 400+ volumes. Strong for accessible English on the Rebbe's letters and talks; pairs naturally with Chabad.org's library.
- **Free vs. paid:** Free.
- **Languages:** Primarily English.
- **English availability:** Strong — a leading free English gateway specifically for the Rebbe.
- **How to navigate:** Browse the biography and the essays/letters/stories sections; integrated with Chabad.org search and the Likkutei Sichot English renderings.
- **Strengths:** Accessible, free, well-produced English on the Rebbe; good for letters and applied teachings. **Limits:** Scope limited to the seventh Rebbe; curated/anthologized rather than a complete text edition.

### Other genuinely useful sources

- **Iggud HaShluchim / Igros Kodesh portals** (e.g. https://www.iggudhashluchim.com) — focused online access to the Rebbe's Igros Kodesh (letters), useful for letter-by-letter lookup; free.
- **Sefaria HuggingFace datasets** (https://huggingface.co/Sefaria) — bulk downloads of Sefaria's open text data for offline/programmatic use, including Tanya; free.
- **Library institutional access to Otzar HaChochma** — many university Judaica libraries and yeshivos provide free patron access to the full Otzar (the practical way to read the licensed Kehot corpus without a personal subscription).

---

## Which source for what

| Material | Best **free** source | Best **paid / comprehensive** source |
|---|---|---|
| **Tanya & halacha** (Tanya, Shulchan Aruch HaRav) | Sefaria (Tanya, bilingual, structured) / chabadlibrary.org (Hebrew); he.wikisource for downloadable Tanya | Kehot (authoritative print/e-book editions); Otzar HaChochma (scans) |
| **Maamarim** (chassidic discourses, all Rebbes) | chabadlibrary.org (Hebrew full text) | Otzar HaChochma (full licensed Kehot scans); Kehot for print |
| **Sichos / farbrengens** (talks) | chabadlibrary.org (Hebrew, e.g. Likutei Sichos, Torat Menachem); Sichos in English (English) | Kehot / Sichos in English print sets; Otzar HaChochma |
| **Letters / Igros (Igros Kodesh)** | chabadlibrary.org; Iggud HaShluchim Igros portal | Otzar HaChochma; Kehot print editions |
| **English translations** | Chabad.org Library + TheRebbe.org; Sichos in English (free online); Sefaria (Tanya) | Kehot (bilingual editions); Sichos in English print sets |

---

## Copyright note

Most of this corpus is **under copyright**, held primarily by **Kehot Publication Society**, the official publishing arm of Chabad-Lubavitch and the source of record for the authoritative editions and translations of the Rebbes' works. That copyright is why the most comprehensive *original-language* digital access (the full, current Kehot catalog) sits on a **paid** platform — **Otzar HaChochma** — under license, and why Kehot's own editions are sold rather than given away.

Within that landscape, **chabadlibrary.org is the movement's official free online reader** for the published Chabad seforim — the legitimate way to read the primary corpus at no cost, operated by the central Chabad library itself. Truly open, freely licensed text is limited to genuinely public-domain or openly-licensed works: foundational texts like the **Tanya** on Sefaria (and on Hebrew Wikisource under CC BY-SA), and Sefaria's openly-licensed data via its API.

This guide is a **catalog of where texts live** — it points to the official and licensed homes of each work. It does not host or redistribute copyrighted texts. When you need to copy, republish, or reuse Chabad material beyond personal study, obtain it from the authorized source (chabadlibrary.org for free reading, Kehot/Otzar for licensed editions) and respect Kehot's rights.
