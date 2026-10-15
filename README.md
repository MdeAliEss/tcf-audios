# tcf-audios

Recordings for the TCF compréhension orale séries 1–80. The app gets them
from Cloudflare Pages, published from this folder by `tools/audio/publish.sh`
in the tcf repo:
`https://tcf-media.pages.dev/comprehension-orale/<sid>/<qid>.mp3`.
This repo is their source and backup. (jsDelivr, used before, failed on a
repo this size: "Failed to fetch … from GitHub" for about 1 file in 4.)

- séries 1–40 (`co-001` … `co-040`): copied from
  `tcfcanada.github.io/tcf-co`, re-encoded to mono 64 kbit/s (same length, so
  the captions still line up). A question repeated in two séries has a copy in
  each.
- séries 41–80: made by `tools/audio/generate.py` in the tcf repo.

`images/comprehension-orale/<sid>/<qid>.<ext>` holds the 97 pictures of the
picture questions in séries 1–40, copied from the same site.
