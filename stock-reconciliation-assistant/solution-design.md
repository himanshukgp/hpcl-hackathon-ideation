# Solution Design

## Workflow

1. UiPath imports stock, receipt, and dispatch files.
2. Power Apps shows opening stock, receipts, dispatches, closing stock, and variance.
3. Fluid AI summarizes abnormal variance.
4. UiPath sends variance report to responsible team.

## Controls

- Highlight variance above threshold.
- Keep imported source files linked.
- Require remarks before closing high variance cases.

