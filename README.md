# Decimal Dash

Randomized multiplying-and-dividing-decimals practice for Ava, covering all
eight sections of her 5th-grade study guide: multiplying by whole numbers and
by decimals (ignore-count-place), multiplying and dividing by powers of 10
(point right/left), multiplying by 0.1/0.01/0.001 (the trap - point LEFT),
dividing by whole numbers (decimal straight up) and by decimals (make the
divisor whole), and word problems. 14 freshly generated problems per quiz,
exact-arithmetic generators with every problem independently re-verified,
typed decimal answers, rule questions mixed in, instant grading with the
steps, cheat sheet, and cross-device history via /api/scores (Cloudflare
Pages Function + Workers KV bound as SCORES).

Deploy: `npx wrangler pages deploy . --project-name decimal-dash --branch main`
