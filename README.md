# Bright Mind Academy

Bright Mind Academy is a single-page self-check for leaders. It asks 12 questions across four areas, scores the answers in the browser, and suggests three one-minute practices. There is no server, account, or build step.

Open `index.html` in a browser to use it.

## What it includes

- **Stress reactivity** — impatience, rushed decisions, and defensiveness
- **Recovery** — weekends, sleep, and time off
- **Relationship clarity** — distance, priorities, and listening
- **Embodiment** — jaw, breath, and shoulders

Each statement is scored from 0 (does not apply) to 4 (fully applies). The total runs from 0 to 48:

| Score | Zone | Meaning |
| --- | --- | --- |
| 0–16 | In flow | Mostly regulated. Keep the routines that already help. |
| 17–32 | Tense but functional | Activation is rising. A short daily practice is useful now. |
| 33–48 | Past the pain threshold | Chronic activation. Talk with a coach, doctor, or therapist. |

The check is in English. It is a reflection tool, not a medical diagnosis.

## Run it locally

1. Clone this repository.
2. Open `index.html` in a browser.
3. Answer all 12 statements and choose **Show results**.

To embed the page:

```html
<iframe src="index.html" width="100%" height="900" style="border:0;border-radius:8px" title="Bright Mind Academy self-check"></iframe>
```

## Customize

Everything lives in `index.html`:

- Colors are the CSS variables `--cream`, `--ink`, `--terra`, and `--gold`.
- Statements are the `QUESTIONS` array.
- Zone cutoffs are in the form submit handler (`score <= 16` and `score <= 32`).

## Contact

Bright Mind Academy

- Email: [admissions@brightmindacademy.com](mailto:admissions@brightmindacademy.com)
- Phone: [+1 (555) 014-3920](tel:+15550143920)

## License

MIT. See [LICENSE](LICENSE).
