# PaydayMap: Paycheck Budget

**In production · October 23, 2026.** Signed version1.0(1) uploaded and processing. Final device, Files, genuine Apple Sandbox and privacy publication checks remain open. No App Review submission, approval or release is claimed. TestFlight is skipped by publisher instruction.

[Product tour](https://sepidehdalir.github.io/paydaymap/) · [Public showcase](https://github.com/sepidehdalir/paydaymap) · [Workflow guide](https://sepidehdalir.github.io/paydaymap/support.html) · [Privacy](https://sepidehdalir.github.io/paydaymap/privacy.html)

## A clearer path between paydays

Record cash, income dates, bills, savings contributions and spending. PaydayMap reserves commitments and a buffer, then shows the remainder and daily estimate. Expected income stays separate until recorded as received. Overdue bills remain reserved; a shortfall stays visible. Each currency has its own ledger, without exchange-rate conversion.

The first three campaign frames show the daily estimate, correction of a scheduled bill, and the app's generated current-window PDF. Records are fictional. Screens are captured from the native app.

![Daily estimate and reserved cash](https://sepidehdalir.github.io/paydaymap/assets/iphone-01.png)
![Correct a scheduled bill](https://sepidehdalir.github.io/paydaymap/assets/iphone-02.png)
![Native PDF result](https://sepidehdalir.github.io/paydaymap/assets/iphone-03.png)

## Native engineering

Swift and SwiftUI, Foundation, StoreKit2, PDFKit/UIKit, UserNotifications, LocalAuthentication and WidgetKit. Universal iPhone/iPad, minimum15 with SDK26.5. The iPad landscape layout places cash and commitments side by side.

Integer minor-unit currency arithmetic, calendar dates with stored time zones, anchored recurrence revisions, serial atomic persistence and explicit archived-copy imports preserve manual records. CSV neutralizes spreadsheet formulas. PDF pagination checks preserve all100 distinct long-report records, including the final page. Failed writes preserve the prior durable state; unreadable originals require preservation before recovery.

Dated iOS17 native regression:50 passed, including37 core/storage,7 native and6 local StoreKit cases. Separate UI checks cover corrections, Trash/restore/relaunch, local Annual Pro/forecast/Restore and widget opt-in. Current iPhone and landscape iPad captures and dark largest-text checks passed. The actual iOS15 runtime, spoken VoiceOver, physical printing and final owner device checks are unverified. Local StoreKit is distinct from genuine Apple Sandbox.

![Dedicated iPad campaign](https://sepidehdalir.github.io/paydaymap/assets/ipad-01.png)

## Privacy and paid boundaries

No developer backend, tracking, analytics, advertising, bank connection or app account. Records stay local. Optional reminders use generic text. The opt-in widget receives only a minimal expiring estimate; financial values hide for the entire time app lock is enabled. Apple manages purchases; users choose export destinations.

Free includes one income source, five active bills, two savings buckets, current-window planning, corrections, PDFs and safety backups. Optional Annual or Lifetime Pro adds more plans, calendar-year forecasts, independent scenarios, widgets and CSV. Consumer prices come from Apple. Existing records remain readable and correctable after Pro expires.

PaydayMap is a manual planner. It does not verify bank balances, move money or provide financial advice. Research found strong category overlap; no novelty, demand, ranking or revenue claim is made.

Commercial source, signing material and private evidence remain in a separate private repository.

Sepideh Javanbakht Dalir · [Arvinify](https://www.arvinify.com) · hello@arvinify.com
