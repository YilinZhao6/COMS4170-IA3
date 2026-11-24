# Individual Assignment 3 - Local React Project

This is the final React project of COMS W4170 Individual Assignment 3. The project accumulates Parts 1–12 in the same application.

## How to run

Install the dependency first:

```Bash
Npm install
```

Start the local server:

```Bash
npm run dev
```

The terminal will display the local URL, and it can be tested by opening it in the browser.

If you need to check the production construction:

```Bash
npm run build
```
File location

- src/App.jsx: share activity status, loading status, navigation and routing.

- src/components/: activity card, activity list, view switching and RSVP form.

- src/pages/: Events, Event Details, My Events and Not Found pages.

- src/data/: active data and simulation loading function.

- src/styles.css: page style.

Correspondence of homework part

This is the final cumulative version, and there is no separate folder for each Part.

- Parts 1–3: Components, props, active data and list rendering.

- Parts 4–6: Upcoming/Past switching, sharing RSVP status and controlled forms.

- Part 7: Events, Event Details, My Events routing and Not Found page.

- Part 8: My Events is grouped by Going, Invited and Declined.

- Parts 9–11: Verification, RSVP status, live region, focus management, loading, empty data, error and retry.

- Part 12: Going number of people changes, title search and no result prompts.

Quick check

1. Switch the status on the Events page. The number of people is increased by 1 when entering Going, and the number of people is reduced by 1 when leaving Going.

Two. If you search for friday, only Friday Night Social should be displayed; if you search for zzz, you should show no matching prompts.

3. Open the activity details page, and the name and email errors should be displayed after the empty form is submitted.

4. Use the mailbox ending with fail.test to test the failure status; after changing to a normal mailbox, click Try again to test the success status.

5. Temporarily change SIMULATE_FAILURE or SIMULATE_EMPTY to true in src/data/loadEvents.js to test the error and empty data status; change back to false after testing.