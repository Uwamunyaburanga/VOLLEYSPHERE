# VolleySphere — director discussion demo

This is an independent, self-contained front-end prototype to explain a possible volleyball club management and performance platform.

## Open it
Open `index.html` in a modern browser. It does not require installation or an internet connection.

## What the demo shows
- Overview for a club director or coach
- Teams and a small fictional player directory
- Director workspace for club-wide team, staff and registration oversight
- Global scouting workspace with fictional international player profiles, review statuses and scout notes
- Attendance register with editable statuses
- Training drill entry with automatic success-rate calculation
- Match action log
- Physical test entry
- A simple reports snapshot

## Important limitations — please be transparent
- All names, teams, match results and measurements are fictional sample data.
- The demo is front-end only. Entries are held in the browser page's memory and disappear on refresh.
- It is not connected to a database, club management software, player accounts, or live devices.
- No data is transmitted to Cesena Volley or any other organisation.
- It does not perform AI video analysis, automatic scoring, or official match scoring.
- Global talent detection is represented as a manual scouting pipeline, not an automated worldwide player discovery engine.
- Club management is a concept-level director dashboard; it does not yet manage payments, federation registrations, contracts, facilities or real user permissions.
- The sample team names are generic and there is no Cesena branding, logo, or claim of endorsement.

## Suggested way to present it
1. Start on Overview: "This is the idea, not a finished product."
2. Open Attendance: show how a coach can verify a simple register.
3. Open Training Centre: add one drill record and show the calculated percentage.
4. Open Match Centre: add one action to demonstrate match data capture.
5. Open Physical Assessment: show how test results can be followed over time.
6. Ask the director which one of these workflows would actually save staff time, and what should be removed or changed.

## Proposed build sequence
1. Validate workflows and definitions with coaches.
2. Build secure sign-in, roles and a database.
3. Pilot one team and a small number of indicators.
4. Add reports only after data quality is reliable.
5. Explore AI-assisted video analysis as a later research/development phase, with human review.

## Privacy and safeguarding
Before using real player data, especially for minors, define lawful basis, consent/parental information where required, role-based access, retention, security, and GDPR-compliant handling. Avoid continuous location tracking. Keep wellness information access restricted.
