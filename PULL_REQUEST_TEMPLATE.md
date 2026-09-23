## What changed

<!-- One or two sentences. Link the issue: Closes #123 -->

## How it was tested on dev

<!-- Steps you ran on dev.litlittlelab.com or locally, and what you saw. -->

## Screenshots

<!-- UI changes only. Never include customer data. -->

## Checklist

- [ ] Migration included: yes / no. If yes, `MIGRATIONS.md` has its row.
- [ ] Touches customer data or money (quotes, invoices, payments, portal): yes / no
- [ ] Rollback: how to undo this (a revert is fine for most changes; say so)
- [ ] Security: no secrets, keys or customer data in the diff; new collections have rules set in the same migration; no new `dangerouslySetInnerHTML`
- [ ] Copyright: any new images, fonts, icons or copied code are ours or properly licensed (say which license)
- [ ] No em dashes in code, comments or UI text

Production deploys need an approving review from the other person on the final commit. The droplet refuses anything else.
