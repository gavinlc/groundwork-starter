# Engineering definition of done template

This is a definition of done template for a software team. It is the merge contract. It is intentionally short.

If an item is not on this list, it is not required. Do not add items because they sound professional. Add them because skipping them has hurt you.

## Before you open a pull request

- The change solves the stated problem - not a neighbouring problem that was more interesting.
- You can explain the change in two or three sentences. If you can't, the work is probably too big to review.
- Existing automated tests pass locally, or you have a documented reason they don't.
- You have scanned the diff for secrets, tokens, and real customer data.

## Before you merge

- At least one other person has reviewed the pull request and approved it.
- The preview deploy (or staging) has been clicked through for the path you changed.

## Before you call it shipped

- It is deployed, not merely merged.
- You know how to undo this: revert, flag off, or migrate back. "We'll figure it out" is not a rollback plan.

## Explicitly not required yet

- A coverage number as a merge gate.
- A full accessibility audit on every PR. Do add labels and keyboard access on new UI.
- Feature flags on ordinary work. Flags are for risk, not tickets.
- A documentation task on every change. Write things down when the next person would otherwise have to ask you.

## How this document is allowed to change

- If something not on this list causes a real problem twice, add a line.
- If an item has been ticked for a month and has never caught anything, propose removing it.
- Anyone can propose a change in a pull request.

Need this fitted to your team (stack, review rules, release cadence)? Use the [free definition of done generator](https://getgroundwork.dev/tools/definition-of-done).
