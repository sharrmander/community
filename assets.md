# OpenTelemetry managed assets

This file is intended to list all the assets controlled by OpenTelemetry.

## Credential Storage

- [1Password Teams](https://1password.com/)
  - Team account: https://opentelemetry.1password.com/
  - https://github.com/1Password/1password-teams-open-source#opentelemetry
  - PR: https://github.com/1Password/1password-teams-open-source/pull/364
  - Admin: Alex Boten @codeboten

## CI pipelines

### OpenTelemetry Azure Pipeline

Link: https://dev.azure.com/opentelemetry/.

- Free tier is used.
- Currently used for .NET Instrumentation repository.
- Admin: [add administrator](https://dev.azure.com/opentelemetry/pipelines/_settings/).

## Artifact repositories

### NuGet OpenTelemetry organization

Link: https://www.nuget.org/organization/OpenTelemetry

- All .NET SIG maintainers are administrators of this organization.
- Organization e-mail (cncf-opentelemetry-net-maintainers@lists.cncf.io) is owned by CNCF.

### MyGet OpenTelemetryCNCF account

Link: https://www.myget.org/feed/Packages/opentelemetry

- registered under the service account (cncf-opentelemetry-net-maintainers@lists.cncf.io).
- Individual accounts of .NET SIG maintainers are administrators of the OpenTelemetry feed.
- Admin: [manage members](https://www.myget.org/feed/Security/opentelemetry).

### NPM OpenTelemetry Organization

Link: https://www.npmjs.com/settings/opentelemetry/packages

- Ask any of the following people if you need access
- Owner: Mayur Kale @mayurkale22
- Admin: Daniel Dyla @dyladan
- Member: Bogdan Drutu @bogdandrutu

## Communication channels

### opentelemetry-calendar-contributors Google Group

Used to provide write access to public OpenTelemertry calendar. See [docs/how-to-handle-public-calendar.md](docs/how-to-handle-public-calendar.md).

Link: https://groups.google.com/g/opentelemetry-calendar-contributors

- Owners: Sergey Kanzhelev, Alolita Sharma, Ben Sigelman, Bogdan Drutu, Constance Caramanolis, Daniel Dyla
- Members: SIG maintainers and individuals appointed by maintainers

### OpenTelemetry Calendar Invites Google Group](https://groups.google.com/g/opentelemetry-calendar)

Used to automatically invite members to all OpenTelemetry calendar events, so that time is blocked on their calendars.

Link: https://groups.google.com/g/opentelemetry-calendar

- Owners: @mtwo

### Mailing list cncf-opentelemetry-net-maintainers@lists.cncf.io

- Used to register service accounts and as a NuGet OpenTelemetry organization e-mail. All .NET SIG maintainers are part of this list. Owned by CNCF.
- Admin: [add member](https://lists.cncf.io/g/cncf-opentelemetry-net-maintainers/).

### Mailing list cncf-opentelemetry-ruby@lists.cncf.io

- Used as a service account e-mail for Ruby SIG. All Ruby SIG maintainers [@open-telemetry/ruby-maintainers](https://github.com/orgs/open-telemetry/teams/ruby-maintainers) are moderators of this list. Owned by CNCF.
- Moderators: [add member](https://lists.cncf.io/g/cncf-opentelemetry-ruby/members).

### Mailing list cncf-opentelemetry-governance@lists.cncf.io

- Private mailing list for OpenTelemetry Governance Committee.
- All GC members AND CNCF reps (Amye Scavarda Perrin, Chris Aniszczyk, Taylor Waggoner) are on the list and are list moderators.
- Admin: [add member](https://lists.cncf.io/g/cncf-opentelemetry-governance/members).

### YouTube channel OpenTelemetry

Link: https://www.youtube.com/channel/UCHZDBZTIfdy94xMjMKz-_MA/videos

- Ask any of the following people if you need to manage the feed:
  - Owners: Amye Scavarda Perrin (CNCF rep), Sergey Kanzhelev
  - Managers: Alolita Sharma, Alan West, Austin Parker, Ben Sigelman, Eddy Nakamura

### Zoom accounts

- E-mails: cncf-opentelemetry@cncf.io, cncf-opentelemetry-meeting-1@cncf.io, cncf-opentelemetry-meeting-2@cncf.io
- Owned by: Amye Scavarda Perrin (CNCF rep)
- Passwords shared with: Austin Parker, Eddy Nakamura, Morgan McLean, Ted Young, Sergey Kanzhelev,

### Splain account

Link: https://splain.io/

- Used to upload Zoom meeting recordings to Youtube
- Owned by: Amye Scavarda Perrin (CNCF rep)

### Project Google account: cncf-opentelemetry-governance@lists.cncf.io

- Used to manage the OpenTelemetry community calendar and Zoom
- Owned by the governance committee

## Bot accounts

### Easy CLA

Link: https://project.lfcla.com/#/project/a0941000002wBz4AAE/cla

- Admins: @lizthegrey, @bogdandrutu

### Docker Hub

- We publish images from CI to Docker hub using https://hub.docker.com/u/otelbot account. The bot is registered using cncf-opentelemetry-tc@lists.cncf.io email address and Technical Committee members are owners of this account. The Admin for bot security credentials for CI is @tigrannajaryan
