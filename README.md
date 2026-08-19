<p align="center">
  <h1 align="center">Do Models Quietly Downgrade Users They Judge Immoral</h1>
  <p align="center"><strong>Measure whether models degrade HHH quality when they infer a user has poor moral character.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **Do Models Quietly Downgrade Users They Judge Immoral**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Measure whether models degrade HHH quality when they infer a user has poor moral character.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
