# Audio clips for UC4 (Call on my behalf)

Both prototypes (`call-on-behalf-call.html` and `call-on-behalf-rcs.html`)
gracefully no-op if a clip is missing — they fall back to the `ms` timing
declared in the script — so the demo runs end-to-end without audio. Drop
WAVs in here when ready.

Sarvam: use `model: 'bulbul:v2'`. For "AI" pronunciation, write `ए, आई,`
(Devanagari) and set `target_language_code: 'hi-IN'`.

## Shared between both prototypes
| Filename | Voice | Text |
|---|---|---|
| `cob_jia_to_mom.wav`  | Anushka (Jia) | `Hi Auntie, this is Jia, Shreya's ए, आई, assistant. Just a quick reminder to take your BP medicines now — Shreya wanted me to check in. Have a wonderful day!` |
| `cob_mom_reply.wav`   | Vidya (or any older female voice) | `Oh, thank you beta — I'll take them right now.` |

## Only used by `call-on-behalf-call.html` (Shreya↔Jia phone call)
| Filename | Voice | Text |
|---|---|---|
| `cob_jia_hello.wav`     | Anushka | `Hi Shreya — how can I help?` |
| `cob_shreya_ask.wav`    | Manisha (Shreya) | `Hey Jia, can you call my mum and remind her to take her BP medicines at 9 AM?` |
| `cob_jia_confirm.wav`   | Anushka | `Of course — I'll call her at 9 AM and confirm with you here. Anything else?` |
| `cob_shreya_thanks.wav` | Manisha | `No, that's it. Thanks!` |
| `cob_jia_bye.wav`       | Anushka | `You're welcome — talk soon.` |
