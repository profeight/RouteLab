# RouteLab

RouteLab is a Windows desktop trainer for recognizing a precise solution route before doing calculations. It includes 500 adapted AMC 10 A/B recognition prompts, local diagrams, question-specific rubric feedback, and spaced review.

## Download

The application ZIP is in `releases/RouteLab-Windows.zip`. Download the full ZIP, then extract it. This repository distributes binaries and user documentation only; source code is not published.

## Start

Extract the full ZIP into a writable folder. Open **RouteLab-Desktop.exe**, keeping `deck.json` and `assets` beside it. The app uses the Windows .NET Framework 4.x Windows Forms runtime. No account, API key, subscription, or payment is required.

Type a plan naming the quantities, the specific operation, its next use, and any restriction. For example: “Define row r and column c starting at zero. Equate the two label formulas, parameterize the resulting integer solutions, and apply the grid bounds.” Stop before lengthy arithmetic.

- **Check route / Ctrl+Enter:** compare rubric ingredients and the model route.
- **Reveal route / Ctrl+R:** flashcard study.
- **Again / Hard / Got it:** save a review and schedule it.
- **Alt+Right:** skip without saving.
- **Question library:** search years, prompts, and techniques; double-click a result to practice it.
- Click a diagram to enlarge it.

The default 110+ focus selects middle-contest questions. Mix topics, then fully solve a few weak questions to check execution. Difficulty labels and review schedules are study aids, not score guarantees.

## Optional support

All features are available without paying. The **Donate** button opens the [Stripe support page](https://buy.stripe.com/6oUdR11MlaGb2YsfZLcV200). **Ko-fi** opens [Ko-fi support](https://ko-fi.com/prof8). The app does not process payments, collect card details, or send your practice history to these sites.

## Feedback and local history

This is an offline keyword/phrase coverage checker, not a semantic or mathematical proof checker. It can miss a valid alternative route or recognize terms in an incorrect argument. Read the model, check how the steps connect, and self-rate. Later edits do not replace the first attempt's recorded coverage.

After self-rating, progress and your typed route save to `progress.json` beside the app; `.bak` stores the previous save. Unsaved text is not restored after closing. Keep these files private and preserve them when installing an update. The public package excludes saved progress, logs, screenshots, source code, and development files.

## Study content

The deck covers A/B from 2025,2024,2023,2022, fall and spring 2021,2020,2019,2018,2017. It contains concise adapted prompts and method notes, not full worked solutions. AoPS source links and the public source-revision manifest remain for attribution and traceability. See ATTRIBUTION.md.

Practice itself makes no automatic network requests. Source links and support buttons open the default browser only when selected. See PRIVACY.md.

## Distribution

This is a **closed-source binary release**, not an open-source project. Source code and build tools are not included. Read LICENSE.txt for the software license and content notices. See CHANGELOG.md for release changes.
