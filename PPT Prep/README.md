# A Transfer Under Clark-Wilson — Interactive Demo

## How to run

Open `index.html` in any modern browser by double-clicking it. No server, build step, or network connection required.

## 8-minute demo order

| Time | What | Key idea |
|------|------|----------|
| 0:00–0:30 | Open the page; point out the three columns, five stages, rule strip. Click **Glossary** briefly. | "Users never touch data directly; they act through certified programs." |
| 0:30–3:30 | **Scenario 1 — Normal transfer.** Walk through all steps for Asha (Part 1) then Ravi (Part 2). Pause on the IVP result. End on the recap frame. | Well-formed transactions, separation of duty, audit trail, validated inputs. |
| 3:30–4:30 | **Scenario 2 — Edit the ledger directly.** Show E1 and E2 both fail. Point out unchanged balances. | "No certified program means no access — period." |
| 4:30–5:30 | **Scenario 3 — Wrong person for the job.** E1 passes but E2 fails. | "A certified program is not enough; the user must be bound to it." |
| 5:30–6:30 | **Scenario 4 — Approve your own transfer.** E2 blocks Asha. Toggle the careless configuration to show C3. | "Separation of duty needs two people to collude." |
| 6:30–7:30 | **Scenario 5 — Bad input.** Click through the four presets. Optionally type a valid amount to show it succeeds. | "C5 is the gatekeeper: every raw input is checked." |
| 7:30–8:00 | Open **Rules** overlay. Scroll through the nine rules. Highlight the rule strip (all nine now coloured). Close. | "The original paper's nine rules work together." |

## What is simulated

- **Authentication** is simulated (no real passwords or tokens).
- **Time** uses a deterministic simulated clock (09:30:00 +3s per event).
- **The bank** is a toy with two accounts and ₹70,000 total.
- No data persists between page reloads.

## Keyboard shortcuts

`→` / `Space` / `Enter` = Next · `←` / `Backspace` = Back · `R` = Reset · `1`–`5` = Scenario · `P` = Presenter · `G` = Glossary · `L` = Rules · `?` = Shortcuts · `Esc` = Close overlay

## Self-test

Open `index.html#selftest` to run engine assertions. Results appear in a banner and in the console.

## Limitations

- Input forms in scenarios 1 and 5 rebuild all frames on change, resetting to step 1 for consistency.
- The presenter pop-out requires popup permissions in the browser.
- The layout is optimised for ≥1280px (projector); smaller screens use a stacked single-column layout that is usable but less visual.
