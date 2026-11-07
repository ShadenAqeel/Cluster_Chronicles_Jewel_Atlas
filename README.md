# Cluster Chronicles · حكايات العناقيد — "The Shattered Crown / التاج المتصدّع"

Educational adventure about **K-Means**, **DBSCAN** and **PCA**, played on the real diamonds dataset.

## Play
Open **`index.html`** in Chrome or Edge (works offline).
Pick **العربية / English** on the title screen or in the header at any time, choose your Keeper, and begin.

Controls: `WASD` / arrows move · `E` interact · `Space` dash (brief invulnerability) · `1 / 2 / 3` abilities in the final duel. Touch controls appear on touch devices.

## What's new in this version
- **Fully bilingual (Arabic RTL / English LTR)** – every screen, dialogue, quiz, tooltip and canvas label; switch live, even mid-dialogue.
- **One coherent visual system** – deep midnight base, brass-gold UI, and one jewel colour per guardian (amber K-Means, emerald DBSCAN, violet PCA, crimson king). All text is light-on-dark; no more clashing panels.
- **New, more mature characters** – cloaked, faceted figures with walk cycles, blinking, capes/scarves and role props (orbiting centroids, eps pulse ring, floating prism).
- **Five redesigned environments** – Royal Vault, Centroid Court (animated scales), Density Cavern, Prism Observatory (rainbow prism), Fractured Throne – with light shafts, parallax, torches and drifting motes.
- **More gameplay** – patrolling sentinels in the Vault, a sweeping sentinel in the Court, bouncing "outlier wisps" in the Cavern, dash with i-frames, collect combos, carry-and-deposit diamonds with live measurements, a live eps neighbourhood ring in the Cavern, a live variance scree + 85% line in the Observatory, and a boss duel with varied shot patterns and a randomised sequence of demands.
- Generative ambient music plus small synthesized sound effects (no external audio files).
- The word "curse" / «لعنة» is gone: the story is now about the **Shattered Crown**.

## Data
`diamonds 2.csv` and `project_PCA_notebook.ipynb` are the team's reference materials. All figures shown in the game (53,893 rows, 88.12% variance with 2 PCs, silhouette 0.429 → 0.487, DBSCAN 804 / 311 noise points, etc.) are unchanged from the original.
