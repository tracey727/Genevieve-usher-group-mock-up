# GENEVIEVE Shared Core Adoption Audit — Usher Group Demo

Date: 2026-10-05

Status: **DEMO / SYNTHETIC — PARTIAL SHARED CORE ADOPTION**

## Current strengths

The existing static demo already demonstrates:
- site status;
- worker break/fatigue support;
- hazards;
- materials;
- defects/rework;
- trade handovers;
- supervisor sign-off concepts;
- manager action board;
- evidence export;
- Cloudflare deployment direction;
- explicit fake-data and WHS/legal boundaries.

## Critical ecosystem mismatch

The demo uses GREEN / AMBER / RED plus **BLACK / URGENT**. The canonical GENEVIEVE operational vocabulary is RED / AMBER / GREEN / HOLD. BLACK must not become a competing state.

Repair rule:
- RED = immediate/action-required condition;
- AMBER = attention/review;
- GREEN = normal/verified;
- HOLD = missing, suspect or insufficient evidence/data, or a controlled gate that prevents progression.
- Safety escalation language such as STOP WORK / URGENT may remain an instruction or pathway, but not a fifth alert state.

## Next implementation requirements

1. Add HOLD to the visible demo vocabulary and styling.
2. Add an accountable action contract: owner + due time + evidence requirement for actionable RED/AMBER items.
3. Keep the demo synthetic/static; do not pretend Neon persistence exists.
4. Preserve human WHS/supervisor authority.
5. Do not implement Stampli/NetSuite as live integrations without explicit credentials/approval; future adapters must be fail-closed and minimum-necessary.
6. Do not merge this demo into Revenue Rescue.
