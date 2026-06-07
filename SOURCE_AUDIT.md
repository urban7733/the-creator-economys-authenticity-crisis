# Source and Legal Use Audit

Status: working audit, 2026-06-07.

This is not legal advice. It is a practical source review for academic citation, arXiv submission, and GitHub publication.

## Standard Applied

A source is acceptable if it is used for citation, factual support, or critical discussion, with proper attribution and without copying protected expression beyond short, necessary excerpts. The paper should paraphrase findings, cite the source, avoid reproducing figures/tables/images without permission, and avoid implying endorsement by any cited organization.

## Overall Finding

The current bibliography is usable for an academic paper. No source requires removal for obvious illegality or obvious bad provenance. The main caveats are:

- Platform and company sources are primary sources for their own policies and claims, not neutral evidence.
- Market reports from Goldman Sachs, IAB, and YouTube are useful but should be framed as industry estimates or platform reported figures.
- Apex Verify is the author's own product, so the paper now includes an author disclosure.
- arXiv papers are citable, but some are preprints and should not be described as peer reviewed unless a venue is listed.
- Do not copy images, charts, app screenshots, article text, or platform UI from these sources unless permission or a compatible license is confirmed.

## Source Review

| Key | Source | Legal to Cite | Source Quality | Caveat |
| --- | --- | --- | --- | --- |
| `goldman2023creator` | Goldman Sachs Research | Yes | Good industry source | Use as estimate, not independent truth or investment advice. |
| `iab2025creator` | Interactive Advertising Bureau | Yes | Good trade association source | Industry source with market incentive; use as ad market estimate. |
| `youtube2025made` | YouTube Blog | Yes | Primary platform source | Reliable for YouTube's own payout/product claims; not neutral. |
| `youtube2024impact` | YouTube/Oxford Economics impact report | Yes | Primary platform source backed by economics report | Frame as YouTube reported/Oxford supported estimate. |
| `youtube2025brand` | YouTube Blog | Yes | Primary platform source | Only use for YouTube product/creator commerce claims. |
| `pew2025social` | Pew Research Center | Yes | Strong nonpartisan research source | Date and URL corrected to Nov. 20, 2025 report. |
| `pew2025influencers` | Pew Research Center | Yes | Strong nonpartisan research source | Good for news influencer reach/affiliation claims. |
| `youtubeHelpSynthetic` | YouTube Help | Yes | Primary policy documentation | Use only for YouTube disclosure policy. |
| `youtubeLikeness2026` | YouTube Help | Yes | Primary policy/product documentation | Use only for YouTube likeness detection mechanics. |
| `tiktok2023labels` | TikTok Newsroom | Yes | Primary platform source | Use only for TikTok label/disclosure claims. |
| `tiktok2024credentials` | TikTok Newsroom | Yes | Primary platform source | Good for TikTok C2PA/Content Credentials claims; not neutral. |
| `tiktokRewards2024` | TikTok Newsroom | Yes | Primary platform source | Use only for TikTok Creator Rewards mechanics. |
| `meta2024labeling` | Meta Newsroom | Yes | Primary platform source | Use only for Meta's stated labeling approach. |
| `xRules2026` | X Help | Yes | Primary platform policy | Use only for current X rule claims; policies can change. |
| `xRevenue2026` | X Help | Yes | Primary monetization policy | Use only for revenue sharing and AI conflict disclosure policy. |
| `ftc2024reviews` | FTC | Yes | Strong official regulator source | Good for fake reviews/testimonials law and enforcement context. |
| `ftc2024celebrity` | FTC Consumer Advice | Yes | Strong official consumer protection source | Good for fake celebrity/influencer endorsement scams. |
| `ftc2025fraud` | FTC | Yes | Strong official fraud data source | Use as reported losses, not total actual fraud losses. |
| `ftc2019bots` | FTC report to Congress | Yes | Strong official source | Useful for fake followers/views and influencer fraud context. |
| `c2pa2026` | C2PA | Yes | Primary technical standard organization | Use for standard description; avoid overstating adoption. |
| `apexVerifyAppStore` | Apple App Store listing | Yes | Primary product listing | Conflict of interest; author disclosure required and added. |
| `wittenberg2025labeling` | PNAS Nexus | Yes | Strong peer reviewed journal source | Open access; cite findings, do not reproduce figures without checking license. |
| `gamage2025labeling` | CHI 2025 / ACM DOI | Yes | Strong peer reviewed conference source | Citation is fine; do not redistribute ACM PDF unless license permits. |
| `jiang2025misinformation` | arXiv preprint | Yes | Useful empirical preprint | Treat as preprint unless later publication is confirmed. |
| `aiforensics2025virality` | AI Forensics report page | Yes | Useful civil society/report source | Advocacy/research organization; use cautiously and pair with arXiv paper. |
| `aiforensicsArxiv2025` | arXiv preprint | Yes | Useful empirical preprint | Authors corrected from organization to named authors. |
| `chrysidis2026synthetic` | arXiv preprint | Yes | Useful empirical preprint | Recent preprint; avoid overstating as settled literature. |
| `brigham2024violation` | SOUPS 2024 / arXiv | Yes | Strong usable security/privacy research | Sensitive topic; paraphrase carefully and avoid graphic examples. |
| `li2024reporting` | arXiv preprint | Yes | Useful audit study | Under review; state as audit evidence, not final consensus. |
| `fbi2025officials` | FBI PSA | Yes | Strong official source | Use as cyber threat warning; FBI explicitly does not endorse products. |

## Legal Risk Notes

Academic citation is generally lawful when the paper cites sources and paraphrases their findings. The risky actions would be:

- copying large passages from articles or reports;
- using copyrighted figures, charts, screenshots, logos, or app screenshots without permission;
- presenting platform or company claims as independent proof;
- implying that FTC, FBI, YouTube, TikTok, Meta, X, Apple, C2PA, Goldman Sachs, IAB, Pew, ACM, PNAS, or arXiv endorse Apex Verify;
- using Apex Verify claims without disclosing the author's relationship to the product.

## Recommended Cleanup Before Submission

- Keep the Author Disclosure section.
- Add a short "No endorsement" sentence if the final paper heavily discusses Apex Verify.
- Use neutral phrasing for market and platform claims: "reported", "estimated", "states", "according to".
- Do not include third party logos or screenshots in the PDF unless permission/license is clear.
- For arXiv submission, include only source files required to build the paper and do not bundle third party PDFs.

