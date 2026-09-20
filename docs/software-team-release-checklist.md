# Software team release checklist

A software team release checklist. A release should be boring. If it is a personality test, the steps are wrong.

## Before

- [ ] Definition of Done is met. If it isn't, this is not a release.
- [ ] CI is green on the revision you are releasing.
- [ ] You know the rollback: revert, flag off, or migrate back.
- [ ] One person drives. Everyone else is available, not hovering.

## After

- [ ] Confirm the thing you meant to change is actually live.
- [ ] Watch errors / logs for ten minutes, then stop staring.
- [ ] Note what went out (changelog, GitHub release, or ticket statuses).

## Who can release

Anyone who can follow this checklist. If only one person can release, that is a bus-factor incident you are scheduling in advance.

Want this fitted to your deploy setup (Vercel, AWS, ad hoc, weekly train)? That's in the [Starter Kit](https://groundwork-one-tau.vercel.app/starter-kit).
