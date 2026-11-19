# Word Search: the live text

The VRChat world Word Search downloads these files at the addresses they have here, which never change: the text is revised in place.
`index.txt` pairs them: it names the revision of every file (a file's first line ends in `r<N>`), which words each `senses_<slot>.txt`
holds, and the windows' own wording. The world shows a meaning's longer entry only when its English table and the entry's file are the
revisions the index names. Tools/RemoteData/publish.py live (in the world's project) writes all of it; nothing here is edited by hand.

`defs_<word language>_<text language>.txt` are the definition tables and `senses_<slot>.txt` the meanings' entries (written for the game
with Claude, from the sources below). The licence notices are in ../../LICENSE.md.
