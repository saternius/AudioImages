# Word Search: definition data

These files are downloaded by the VRChat world Word Search (its definition windows). Each name carries its content hash and never changes.
defs_<word language>_<text language>.*.txt are the definition tables; defs_kanji_<n>.*.txt are 2048x2048 Alpha8 atlas pages of the
definitions' kanji, rendered from M PLUS Rounded 1c (SIL Open Font License 1.1, OFL-MPLUSRounded1c.txt).

## LICENSES

The four tables are adaptations of the sources below. Because `defs_ja_en`, `defs_ja_ja` and part of `defs_en_ja`
contain JMdict material and `defs_ja_ja` contains Wiktionary text, those tables are licensed **CC BY-SA 4.0**
(share-alike); `defs_en_en` is under **CC BY 4.0** (OEWN) with the WordNet notice. The notices below must travel
with the data (the WordNet and Japanese WordNet licences ask for their notice on all copies, including modified ones).

| Source | Used for | Licence |
|---|---|---|
| Open English WordNet 2025, https://en-word.net/ (McCrae et al., Global WordNet Association) | English definitions, senses, exception lists | CC BY 4.0 |
| Princeton WordNet 3.0, https://wordnet.princeton.edu/ | tag counts (sense order) and sense-key → synset links only; no PWN text is copied (OEWN is itself derived from PWN) | WordNet 3.0 licence (below) |
| AGID rev 4 (2016.01.19), Kevin Atkinson, http://wordlist.aspell.net/ | inflected form → lemma | permissive notice (below) |
| Japanese WordNet 2.1 and 1.1 definitions, https://bond-lab.github.io/wnja/ | Japanese lemmas and definitions for English senses; fallback Japanese glosses for katakana words | Japanese WordNet licence (BSD-like, below) |
| JMdict (JMdict_e), EDRDG, https://www.edrdg.org/wiki/index.php/JMdict-EDICT_Dictionary_Project | katakana entries, spellings, POS, English glosses; en_ja fallback | CC BY-SA 4.0 (EDRDG licence) |
| Japanese Wiktionary, https://ja.wiktionary.org/ (dump 20261101) | Japanese definitions of katakana words | CC BY-SA 4.0 (and GFDL) |
| Unicode Unihan (kJoyoKanji), https://www.unicode.org/ | report only (jōyō count); not in the tables | Unicode licence |

EDRDG terms to note: an on-screen word display must acknowledge JMdict where it is shown (when mixed with other
sources a general acknowledgement is enough, for example on the popup or a credits panel reachable from it), and
"there must be a procedure for regular updating of the data from the most recent versions available": re-run the
build when the world is updated.

### Attribution text for the world's credits

> Word definitions: Open English WordNet 2025 (en-word.net, CC BY 4.0), based on Princeton WordNet (WordNet 3.0
> © 2006 Princeton University); Japanese WordNet (© 2009-2011 NICT, 2012-2026 Francis Bond, Takayuki Kuribayashi);
> AGID inflection database © 2000-2014 Kevin Atkinson. This world uses the JMdict dictionary files, the property
> of the Electronic Dictionary Research and Development Group, used in conformance with the Group's licence
> (CC BY-SA 4.0, www.edrdg.org). Japanese definitions include text adapted from Japanese Wiktionary
> (ja.wiktionary.org) by Wiktionary contributors, CC BY-SA 4.0. The definition tables are shared under CC BY-SA 4.0.

### Notices

**Princeton WordNet 3.0** (also covers OEWN's WordNet-derived content):

```
WordNet Release 3.0
This software and database is being provided to you, the LICENSEE, by Princeton University under the following
license. By obtaining, using and/or copying this software and database, you agree that you have read, understood,
and will comply with these terms and conditions.:
Permission to use, copy, modify and distribute this software and database and its documentation for any purpose and
without fee or royalty is hereby granted, provided that you agree to comply with the following copyright notice and
statements, including the disclaimer, and that the same appear on ALL copies of the software, database and
documentation, including modifications that you make for internal use or for distribution.
WordNet 3.0 Copyright 2006 by Princeton University. All rights reserved.
THIS SOFTWARE AND DATABASE IS PROVIDED "AS IS" AND PRINCETON UNIVERSITY MAKES NO REPRESENTATIONS OR WARRANTIES,
EXPRESS OR IMPLIED. BY WAY OF EXAMPLE, BUT NOT LIMITATION, PRINCETON UNIVERSITY MAKES NO REPRESENTATIONS OR
WARRANTIES OF MERCHANT- ABILITY OR FITNESS FOR ANY PARTICULAR PURPOSE OR THAT THE USE OF THE LICENSED SOFTWARE,
DATABASE OR DOCUMENTATION WILL NOT INFRINGE ANY THIRD PARTY PATENTS, COPYRIGHTS, TRADEMARKS OR OTHER RIGHTS.
The name of Princeton University or Princeton may not be used in advertising or publicity pertaining to
distribution of the software and/or database. Title to copyright in this software, database and any associated
documentation shall at all times remain with Princeton University and LICENSEE agrees to preserve same.
```

**Japanese WordNet** (`downloads/wnja11/license.txt`, same text as `wnja21_x/wnja/LICENSE`):

```
Copyright: 2021-2026 Francis Bond, Takayuki Kuribayashi
Copyright: 2018-2020 Francis Bond
Copyright: 2016-2017 Francis Bond, Takayuki Kuribayashi
Copyright: 2012-2015 Francis Bond
Copyright: 2009-2011 NICT

Japanese WordNet
This software and database is being provided to you, the LICENSEE, by the National Institute of Information and
Communications Technology under the following license. By obtaining, using and/or copying this software and
database, you agree that you have read, understood, and will comply with these terms and conditions:
  Permission to use, copy, modify and distribute this software and database and its documentation for any purpose
  and without fee or royalty is hereby granted, provided that you agree to comply with the following copyright
  notice and statements, including the disclaimer, and that the same appear on ALL copies of the software, database
  and documentation, including modifications that you make for internal use or for distribution.
THIS SOFTWARE AND DATABASE IS PROVIDED "AS IS" AND NICT MAKES NO REPRESENTATIONS OR WARRANTIES, EXPRESS OR IMPLIED.
BY WAY OF EXAMPLE, BUT NOT LIMITATION, NICT MAKES NO REPRESENTATIONS OR WARRANTIES OF MERCHANTABILITY OR FITNESS FOR
ANY PARTICULAR PURPOSE OR THAT THE USE OF THE LICENSED SOFTWARE, DATABASE OR DOCUMENTATION WILL NOT INFRINGE ANY
THIRD PARTY PATENTS, COPYRIGHTS, TRADEMARKS OR OTHER RIGHTS.
The name of the National Institute of Information and Communications Technology may not be used in advertising or
publicity pertaining to distribution of the software and/or database. Title to copyright in this software, database
and any associated documentation shall at all times remain with National Institute of Information and
Communications Technology and LICENSEE agrees to preserve same.
```

Citation asked for by the Japanese WordNet authors: Hitoshi Isahara, Francis Bond, Kiyotaka Uchimoto, Masao Utiyama
and Kyoko Kanzaki. Development of Japanese WordNet. LREC 2008, Marrakech.

**AGID** (`downloads/agid_x/agid-2016.01.19/README`):

```
Copyright 2000-2014 by Kevin Atkinson
Permission to use, copy, modify, distribute and sell this database, the associated scripts, the output created
form the scripts and its documentation for any purpose is hereby granted without fee, provided that the above
copyright notice appears in all copies and that both that copyright notice and this permission notice appear in
supporting documentation. Kevin Atkinson makes no representations about the suitability of this array for any
purpose. It is provided "as is" without express or implied warranty.
```
(AGID's part-of-speech data comes from Alan Beale's 2of12id and WordNet, whose notice is above.)

**JMdict**: © James William Breen and the Electronic Dictionary Research and Development Group, CC BY-SA 4.0,
https://www.edrdg.org/edrdg/licence.html.

**Wiktionary**: text by Wiktionary contributors, CC BY-SA 4.0, https://ja.wiktionary.org/ ; changes: definitions
cut out of their pages, wiki markup removed, shortened.

**Open English WordNet**: © the English WordNet contributors, CC BY 4.0,
https://github.com/globalwordnet/english-wordnet (changes: definitions selected, shortened and combined).

## Casual definitions (`casual.py`, M50.17)

User (2026-11-11): the definitions should be casual, explain all the meanings a word has, and still fit the window at a legible size. The window now
shows text written by Claude Opus 5.5 (Message Batches API) wherever `casual/` has a line for the word; everything above remains the fallback and the
checklist of meanings the model is given.

- **Files (committed):** `casual/en.jsonl` and `casual/ja.jsonl`, one word a line, `{"w": WORD, "s": [sense, ...]}`; an English sense is
  `{"p": n|v|adj|adv|other, "en", "ja", "es", "fr", "de"}`, a Japanese one `{"k": spelling, "en", "ja", "es", "fr", "de"}`. An empty `s` means the model
  did not know the word. `casual/forms.tsv`: the English word forms (`WORD<TAB>i|o<TAB>tag:lemma:P[,...]`, i = the form's reading goes first), from
  build_defs' rules. `casual/meta.json`: model, effort, prompt hashes.
- **Rebuilding:** `python -I casual.py prepare --dl downloads` (a minute; writes `work/casual_items.json` and `casual/forms.tsv`), then
  `python -I casual.py run --yes` sends only the words with no line in `casual/` (new words after a word-list change), waits, checks, asks again and saves.
  `--sample N` sends a few; `--cap` (dollars, default 180) stops before the money spent would pass it; `status` shows the batches and the spend. The key
  is `ANTHROPIC_API_KEY`, or the file `~/.anthropic-key`. Then `python -I compact.py`, and the M57 flow (Build Scene, `publish.py`, Build Scene).
- **Checks** (`window_fit.py`, also used by compact.py): every text must show at the window's full 27 mm (5 lines of the 516 x 220 mm box, the font's
  own advance widths and line height), use only characters M+ Rounded 1c has, and a Japanese spelling must be one of the word's JMdict spellings.
  A text that fails is asked again with the reason, twice; after that compact.py keeps the lines that fit.
- **Table text:** one meaning a line, `|` between lines (the window turns it into a line break), a bullet on each line when there are several.
  Word forms: a label ("past tense of run", "runの過去形", "pasado de run") and the lemma's lines for that part of speech, fitted by compact.py.
- **Needs:** `pip install anthropic fonttools`.

## Every meaning of every word (`allsenses.py`, M50.23)

casual.py wrote at most five senses a word and never held a reply against the dictionary; allsenses.py adds what is missing and keeps what is
written. It is the step to run after a word-list change now (casual.py still writes the Japanese words).

- **What it sends:** every English word a stroke can find (`valid_words.txt`), the planted words, the words the world's table holds, and every
  lemma a word form is built from: each with the senses it has (they stay, in their places) and ALL of its WordNet senses as numbered notes. A
  word that has a sense and at most one note is settled without asking.
- **What comes back:** the senses to add, English only (`{"p", "en"}`), and `cover`: for each note the number of the sense that covers it. The
  check wants a number for every note, each naming a sense of the note's part of speech, and an added sense in at most two lines of the window;
  a reply that fails is asked again with what was wrong (three rounds).
- **Kept in** `casual/en.jsonl` (the added senses after the ones a word had) and `casual/cover.jsonl` (`{"w", "ss": [the synsets it was held
  against], "c": [the sense covering each]}`): a word is asked again only when its WordNet senses change.
- **Rebuilding:** `python -I allsenses.py prepare --dl downloads` (ten seconds; writes `work/allsenses_items.json` and `casual/forms.tsv` for
  the whole valid list), `python -I allsenses.py run --yes` (resumable: `work/allsenses_state.json`; `--cap` dollars; `--sample N` for a trial
  that also measures the cost), `status`. Then `compact.py`, `senses.py prepare` and `run` (the new senses' entries), `senses.py files`, and
  `publish.py live`. Needs `downloads/oewn`, `oewn_wndb_x`, `pwn30_x`, `agid_x` (the curls above; the WNDB zip is on the project's GitHub
  releases when en-word.net is down).
- **The window** shows what fits above a MORE row and lengthens for the rest, so `compact.py` drops no line (a record holds up to
  `MAX_MEANINGS` = 50). `window_fit.word_size` is the window's rule, ported.

## Meaning entries (`senses.py`, M74)

User (2026-11-18): each meaning of a word should open a window of its own with a longer explanation and example sentences
(`Docs/spec/M74-meaning-windows.md`). An entry is written for every casual sense that some English record shows; a word form's lines are its lemma's,
so one entry serves every record that shows the line. English words and English text only, for now.

- **Files (committed):** `senses/en.jsonl`, one word a line, `{"w": WORD, "s": {"<sense index in casual/en.jsonl>": {"x": explanation,
  "e": [examples, the word between asterisks]}}}`; `senses/meta.json`: model, effort, prompt hash.
- **Rebuilding:** `python -I senses.py prepare` (seconds; matches every record line of `out/world/defs_en_en.txt` to its casual sense and writes
  `work/senses_items.json`), then `python -I senses.py run --yes` sends only the senses with no entry yet, waits, checks, asks again and saves.
  `--sample N` sends a few (a pilot list first); `--cap` (dollars, default 20: raise it for the whole run) stops before the money spent would pass
  it; `status` shows the batches and the spend. The key is casual.py's. Then `python -I senses.py files`, and the M57 flow (Build Scene, `publish.py`,
  Build Scene).
- **Checks:** `window_fit.sense_size` is the window's own layout, ported (`DefinitionWindow.Wrap`; the meaning's 516 x 278 mm box; the number and the
  one-line meaning hung beside a 34 mm column, the explanation, each example in quotes). An entry that would show under 21 mm loses a third example
  or is asked again with that said; every character must be in the font.
- **The world's files:** `files` writes `out/world/senses_en_en_NN.txt` (WSEN1, about 256 KB each, records in key order, a record's map from its
  meaning lines to entries) and `senses_en_en.idx` (each file's first key), and only when every meaning line has its entry: a part-written set would
  show buttons that open nothing (`--partial --out DIR` writes what there is, for looking, never to the world's folder). `export FILE.json` is the
  review page's data.
