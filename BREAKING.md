# Pending breaking changes

This page lists deprecations on the Apideck Unify API that have a **future removal date and have
not happened yet**. Each entry tells you what is changing, what to use instead, and the date the
old behavior is removed.

It is a living list, not a changelog: an entry appears here while its removal is pending and is
deleted once the removal actually ships. For a history of changes that have already shipped, see
`CHANGELOG.md`. Every entry here corresponds to a machine-readable `x-apideck-sunsetting` block on
the affected operation, property, or parameter in the OpenAPI specs, so you can detect the same
deprecations programmatically.

**There are currently no pending breaking changes.**

<!--
  ── Entry format (authoring) ─────────────────────────────────────────────────
  Reconciled by `/sunset --write`; see `.claude/rules/sunsetting.md` for the full
  process, and `.claude/commands/sunset.md` for the command. Do not hand-edit
  entries that carry an anchor — the next reconcile will overwrite them.

  Replace the "no pending breaking changes" line above when the first entry lands.

  Group by unified API; within a group, sort by sunset date ascending (soonest
  removal first). Each entry is one bullet block, keyed by its per-entry anchor:

    ### {Unified API} API

    <!- - apideck:sunset-entry #{issue-number} - ->
    - **{What is being sunset}**
      - **What changes:** {concise description of the deprecation / removal}
      - **Replacement / migration path:** {what to use instead, or "none"}
      - **Sunset date:** {YYYY-MM-DD}
      - **Affected surfaces:** {unified API} — {resource(s) / operation(s)}

  (The anchor above is spaced out only to keep this example inside this comment;
  write it without the spaces.)

  The anchor is BOTH the idempotency key and the removal key for this file. It
  ties the entry to board issue #{issue-number} and to the matching `issue:`
  field inside that node's `x-apideck-sunsetting` block in the source spec.
-->
