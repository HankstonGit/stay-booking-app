# Stay Booking Screenshot Checklist
- [ ] Completed application
- [ ] Destination TextInput
- [ ] Guest-name TextInput
- [ ] Guest count above 1
- [ ] Room modal open
- [ ] Selected room
- [ ] Validation error
- [ ] Successful confirmation
- [ ] Original room
- [ ] RoomPreferenceModal.js
- [ ] BookingScreen.js
- [ ] Clean git status
- [ ] Git log graph
- [ ] GitHub main
- [ ] APA 7 reflection

## Feature branch verification — September 13, 2026

`npm run web` started successfully and Metro bundled the application. Chromium
interaction checks at a 390 × 844 viewport passed:

- Both inputs accept text and update the booking summary.
- Focus destination focuses its input; Enter moves focus to the guest-name input.
- Guest count starts at 1, increases, decreases, and remains at 1 when decrease is disabled.
- The modal opens and closes; Standard Room, Deluxe Room, City Suite, and Balcony King appear.
- Selecting each room closes the modal and updates the summary name and nightly price.
- Empty or whitespace-only destination and guest name show their exact required errors and focus the relevant input.
- Missing room shows the required room-preference error.
- A valid reservation shows “Reservation ready to submit.” and clears the error.
- A failed review after success clears the confirmation.
- The ScrollView scrolls; no browser runtime or console errors were reported.
- No assignment TODOs remain in src; JavaScript bundled without syntax errors.

Environment issues: the sandbox blocked Git metadata and Expo's home cache;
these operations succeeded with approved permissions. Chromium required system
libraries, which were installed for testing outside the project. npm reported
16 dependency advisories (7 moderate, 9 high); Expo reported version recommendations
for vector icons and React Native. Starter dependency declarations were preserved.

The checklist above tracks submission evidence, not automated test results.
Capture source files and the final Git output for submission. GitHub main evidence
is pending explicit push/merge authorization. The APA 7 reflection remains a
separate submission document; follow the 250–300 word and formatting requirements
in README.md and include your own student/title-page details.
