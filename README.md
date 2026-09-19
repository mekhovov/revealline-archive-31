# RevealLine Archive31: original v0.63.0 and v0.64.0

This proposed append retains accepted archive `f476c311e0050b47d7408db51d57239fba7bece6` (tree `d144cc112088882211bb1b5e04df298f4f4a78be`) and adds the exact original v0.64.0 release. The archive successor is not yet deployed or accepted. Main v0.64.0 is independently accepted; future Replay v0.64.1, archive admission and selector changes remain separate.

Original v0.64.0 source `7c9d34f7011a904b9c100f66884a19808666315a`, tree `db0b7014be960b5e04e41234a802fac9d5930d6d`, annotated tag `30f93a1d5c072fbd58769dc533ba64217e293374`, Release 392031774. Nine published asset descriptors, four byte-identical metadata originals and main/public acceptance evidence are pinned in `append-v0640-input-authority.json`. Existing `input-authority.json` remains historical and unchanged. Local donor checkout `bef984c3b7863b6801f75a3070955e23c8f1c6fe` has the accepted tree exactly; no fetch was performed merely to obtain the absent merge commit object.

Expected inventory: **1,420 rows / 627,122,610 bytes**. All 711 earlier paths remain: 710 rows unchanged, including all 708 original v0.63.0 release rows / 313,556,519 bytes. Only the archive root index changes (+79 bytes) to list both versions. New v0.64.0 cohort: 709 rows / 313,564,618 bytes. The 800,000,000-byte budget retains 172,877,390 bytes of headroom.

The main-only workflow explicitly fetches both immutable v0.63.0 and v0.64.0 tags. Production prepare/verify helpers, explorer bridge, extractor tooling `a13ab970222498d7c5fa7f62f9fc04fe436979d5` and its SHA remain unchanged. Extraction uses original released ZIPs, verifies source/tag identities and every byte including hidden files, and never builds historical source. The 3 GiB hosted free-space guard, 20,000-row limit and non-cancelling concurrency remain.

Preparation does not download game payloads or source TARs. Root must review the patch, obtain fresh authorities, run finite fixture checks, merge an infrastructure PR, retain actual workflow/deployment/small receipts, verify the complete public inventory and scoped native v0.64.0 archive keyboard journey, and check retained v0.63.0 routing. Source qualification and main acceptance do not establish archive acceptance.

Only after this archive successor and the next current release are independently accepted may a publisher move canonical v0.64.0 allocation here. Preserve existing v0.63.0 ownership and all 99 current catalog authorities until that separate admission. Physical devices, audio/offline, Team win/Next and broader phase limitations remain separate.
