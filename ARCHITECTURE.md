# Public site architecture

`index.html` embeds the page's structure, styles, charts, status and research summaries. GitHub Pages serves static bytes to a browser; links lead to external organization/research/contact destinations. There is no JavaScript execution, API, form backend or database in this checkout. README identifies the actual research repository as private.

```text
committed index.html -> static hosting -> visitor reads dated status/evidence/roadmap
private research evidence -> editorial verification -> future page update (separate action)
```

The embedded page describes identity/memory/consolidation/growth/swap components, but those are subjects of its prose, not deployed parts of this repository. Numeric chart labels and the honesty ladder explain the claimed scope; they do not supply raw private receipts.

## Risk / failure boundaries

- A stale “running/live” label can be mistaken for current operational status. Preserve snapshot date and canonical revision; revalidate evidence before updating public claims.
- Research summaries can overstate private/isolated evidence if copied without honesty classes. A page screenshot does not independently verify model identity persistence, clinical/personhood claims, quantization results or a security gate.
- Publishing may disclose private research/identity details. Changes reach public hosting through its deployment process; opening this docs PR is not permission to update research claims or publish private artifacts.
- Static hosting failure leaves an unavailable page; broken external links do not imply the private runtime is down.

## Docs proof

README and actual status/evidence/roadmap read. Local Chromium rendered the real file, including “Nothing in this program is production-accepted yet”; screenshot/receipt retained. No private runtime, model, service, telemetry or publication touched. Static rendering only, not current research acceptance. Revert docs for rollback.
