# Fernlight Advice — Home loan snapshot (portfolio demo)

A one-page mortgage snapshot for New Zealanders. Visitors pick a path (first home, refinance or investment property) and answer one question per screen, with follow-up questions that only appear when they apply. An indicative snapshot then unlocks behind an opt-in screen: deposit or equity, borrowing, loan-to-value and debt-to-income, repayments at three frequencies, a plain-English position card and a mock booking calendar, followed by a simulated AI-callback notice.

Live demo: https://historfic.github.io/fernlight-advice-home-loans/

## About this project

Fernlight Advice is a fictional brand, and this page is a portfolio piece. It is not a real business and does not give financial advice.

- **No backend.** The site is one static `index.html` with inline CSS and JavaScript. The snapshot is worked out in the browser. The only outside resource it loads is Google Fonts.
- **Nothing is collected or sent.** The form checks what you type, then discards it. No requests are made, nothing is stored, and no cookies are set. A Content-Security-Policy blocks network calls and form submission.
- **The booking calendar is a mock.** It shows sample times, and picking one books nothing.
- **The AI phone call is simulated.** No call is placed.
- **The phone numbers are fictional** and use the 555-01xx range.
- The snapshot uses an illustrative indicative rate and common New Zealand reference points (the 20% owner-occupier deposit benchmark and the Reserve Bank's LVR and DTI settings) and is for illustration only. Lenders appear only as generic labels, and the page is not affiliated with any bank, lender or government agency.

## Run locally

Any static file server works. For example:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.
