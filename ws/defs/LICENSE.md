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
