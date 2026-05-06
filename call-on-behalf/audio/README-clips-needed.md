# Audio clips for UC4 (Call on my behalf)

Both prototypes gracefully no-op if a clip is missing — they fall back to
the per-turn `ms` timing — so demos run end-to-end without audio.

Sarvam: use `model: 'bulbul:v2'`. For "AI" pronunciation, write `ए, आई,`
(Devanagari) and set `target_language_code: 'hi-IN'`.

## Used by `call-on-behalf-call.html` (the Shreya↔Jia phone call)
| Filename | Voice | Text |
|---|---|---|
| `cob_jia_hello.wav`     | Anushka (Jia) | `Hi Shreya — how can I help?` |
| `cob_shreya_ask.wav`    | Manisha (Shreya) | `Hey Jia, can you call my mum and remind her to take her BP medicines at 9 AM?` |
| `cob_jia_confirm.wav`   | Anushka | `Of course — I'll call her at 9 AM and confirm with you here. Anything else?` |
| `cob_shreya_thanks.wav` | Manisha | `No, that's it. Thanks!` |
| `cob_jia_bye.wav`       | Anushka | `You're welcome — talk soon.` |

## `call-on-behalf-rcs.html`
No audio needed — Messages-only flow. The confirmation arrives as a
text bubble + receipt card; we don't render or play the Jia↔Mum call.
