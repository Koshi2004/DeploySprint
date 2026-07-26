# Deploy Sprint Finale Submission

Complete this file on `main` as tasks are completed. Do not paste secrets, private keys, token values, or screenshots that reveal credentials.

## Team

- Team name: blackops
- Team members:
- Live IP URL:
- Assigned domain URL:
- Repository URL: https://github.com/knurdz/deploy-sprint-finale-team-blackops

## Release Evidence

- Current production commit:
- Current artifact/image identifier:
- Current deployment workflow run:
- Current release manifest path or URL:
- Notes on live evidence or fallback evidence: T01 adds a build-time generator (`team-site/scripts/generate-status.mjs`) that writes `dist/health` (`ok`) and `dist/status` (JSON with team, commit SHA, release ID, deploy time, `T01` marker) on every `npm run build`, so the values reflect the commit actually being deployed instead of being hardcoded. Live `IP_PUBLIC_URL`/`/health`/`/status` verification is pending the first organizer deploy run after merge.

## Score Summary

- Automated / organizer-confirmed points out of 800:
- Judge-awarded points out of 200:
- Final total points out of 1000:

## Completed Tasks

### Release 00:00

- [ ] T01 - Launch Provided Website (75 pts, 65 auto, 10 judge)
- [ ] T02 - Connect Custom Domain (35 pts, 29 auto, 6 judge)
- [ ] T03 - Build Once Deploy Same Artifact (30 pts, 25 auto, 5 judge)

### Release 00:30

- [ ] T04 - Rollback To Known-Good Release (30 pts, 25 auto, 5 judge)
- [ ] T05 - Secret And Config Separation (20 pts, 17 auto, 3 judge)
- [ ] T06 - CI Gate Before Deployment (20 pts, 17 auto, 3 judge)
- [ ] T07 - OpenWeather API Widget (40 pts, 32 auto, 8 judge)

### Release 01:00

- [ ] T08 - Rebase Organizer Feature (20 pts, 17 auto, 3 judge)
- [ ] T09 - Conflict Merge With Both Outcomes (20 pts, 17 auto, 3 judge)
- [ ] T10 - Web3Forms Contact Service (40 pts, 32 auto, 8 judge)

### Release 01:30

- [ ] T11 - Pull Request Preview Deployment (30 pts, 25 auto, 5 judge)
- [ ] T12 - Fast Dependency Pipeline (30 pts, 25 auto, 5 judge)
- [ ] T13 - Feature Bundle With Tests (30 pts, 25 auto, 5 judge)

### Release 02:00

- [ ] T14 - Production Docker Image (20 pts, 17 auto, 3 judge)
- [ ] T15 - Runtime Feature Flag (30 pts, 25 auto, 5 judge)
- [ ] T16 - Resend Email Alerts (40 pts, 30 auto, 10 judge)
- [ ] T17 - Low-Downtime Release Strategy (40 pts, 30 auto, 10 judge)

### Release 02:30

- [ ] T18 - Containerized VPS Deploy (20 pts, 17 auto, 3 judge)
- [ ] T19 - Post-Deploy Smoke Tests (30 pts, 25 auto, 5 judge)
- [ ] T20 - Google OAuth Login (40 pts, 28 auto, 12 judge)

### Release 03:00

- [ ] T21 - Least-Privilege And Concurrency (20 pts, 17 auto, 3 judge)
- [ ] T22 - Compose Runtime Service (40 pts, 30 auto, 10 judge)
- [ ] T23 - Release Evidence Manifest (30 pts, 25 auto, 5 judge)
- [ ] T24 - Cloudflare Turnstile Protection (40 pts, 30 auto, 10 judge)

### Release 03:45

- [ ] T25 - Hotfix Cherry-Pick Under Pressure (30 pts, 25 auto, 5 judge)
- [ ] T26 - Incident: Broken Deploy Recovery (40 pts, 30 auto, 10 judge)
- [ ] T27 - Secret Leak Drill (40 pts, 30 auto, 10 judge)

### Release 04:15

- [ ] T28 - Race-Safe Idempotent Deploy (40 pts, 30 auto, 10 judge)
- [ ] T29 - Disaster Recovery From Actions Only (40 pts, 30 auto, 10 judge)
- [ ] T30 - Sentry Monitoring Release (40 pts, 30 auto, 10 judge)

## Notes For Organizers

List anything organizers should manually verify, including skipped tasks, known issues, manual-review evidence, rollback/recovery evidence, or service-account limitations.
