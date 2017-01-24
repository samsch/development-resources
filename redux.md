# Redux

## Lessons learned

Either:
- Create a standard return value for selectors which can't get their data yet (due to fetchings, permissions, etc.)
 - A potential solution would be a small object with a few standard keys (e.g. `{ loading: true|false, accessAllowed: true|false }`).
- Write application such that a selector which can't retrieve it's data yet will never be called.

## Tools to check out

- [Petux](https://petux-docs.surge.sh/) Another take on dealing with side-effects.
