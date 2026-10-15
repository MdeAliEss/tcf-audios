# tcf-audios

Recordings for the TCF compréhension orale séries 1–80, served to the app by
the jsDelivr CDN straight from this repo:
`https://cdn.jsdelivr.net/gh/MdeAliEss/tcf-audios@main/comprehension-orale/<sid>/<qid>.mp3`.

jsDelivr caches `@main` for up to 12 hours: a recording replaced under the
same name can take that long to reach the app.

- séries 1–40 (`co-001` … `co-040`): copied from
  `tcfcanada.github.io/tcf-co`, re-encoded to mono 64 kbit/s (same length, so
  the captions still line up). A question repeated in two séries has a copy in
  each.
- séries 41–80: made by `tools/audio/generate.py` in the tcf repo.

`images/comprehension-orale/<sid>/<qid>.<ext>` holds the 97 pictures of the
picture questions in séries 1–40, copied from the same site.
