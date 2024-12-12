# Michelle Saad

- **✔️ U.S. Citizen**
- 📞 phone: 954.801.1273
- 📧 email: contact@michsa.me
- 👩‍💻 GitHub: [@michsa](https://github.com/michsa)

## Summary

- Senior full-stack software engineer with 8 years of experience
- Current stack: Rust, Postgres, Node.js, TypeScript/JavaScript, GraphQL, React
- Remote strongly preferred (Pacific hours)

### Work History

| Company      | Dates        | Title                          | Stack                                                           |
| ------------ | ------------ | ------------------------------ | --------------------------------------------------------------- |
| ParentSquare | 2024-current | Senior Software Engineer       | Rust, Typescript, PostgreSQL, MySQL, GraphQL, AWS, Ruby (Rails) |
| Remind       | 2022-2024    | Senior Software Engineer       | Rust, Typescript, PostgreSQL, React, GraphQL, AWS, Ruby, Go     |
| Remind       | 2020-2022    | Software Engineer              | Typescript, PostgreSQL, React, GraphQL, AWS, Ruby, Go           |
| SmartProcure | 2019-2020    | Software Developer             | JavaScript, React, MongoDB, Mobx, Feathers, ElasticSearch       |
| Office Depot | 2017-2019    | Software Engineer              | JavaScript, Java, DB2, COBOL                                    |
| ADT          | 2016         | Application Development Intern | JavaScript, Java, AngularJS, SOAP                               |
| Avocent      | 2015         | Software Development Intern    | JavaScript, Java, PostgreSQL                                    |

### Education

| Degree                 | Grad. | School                      |
| ---------------------- | ----- | --------------------------- |
| BS in Computer Science | 2017  | Florida Atlantic University |

## Projects

#### ParentSquare

- Messaging team — continued work on 10DLC support for Remind and ParentSquare systems
  - Automated provisioning "brands" & "campaigns" for thousands of customers from TCR (The Campaign Registry) via their REST API
  - Automated buying tens of thousands of phone numbers from Sinch via their REST API
- Hacksprint — integrated Remind user/organization data into ParentSquare's data API

#### Remind

- **HQ** (2023-2024) — rewrite of Remind's [core datamodel](https://engineering.remind.com/Transitive-Closure-In-PostgreSQL/) and business logic in Rust and PostgreSQL
  - Revamped Remind's messaging infrastructure to:
    - support multiple connectivity partners (Twilio, Sinch, etc)
    - provision and manage SMS campaigns for individual client organizations (school districts) per modern 10DLC requirements
- [**Tutoring**](https://www.remind.com/tutoring) (2021-2023) — platform to schedule, manage, and host tutoring sessions with Remind teachers
  - Various projects around scheduling and availability
    - Tutor availability — architecture, UI and business logic for user-defined recurring availability and time off
    - Session materialization — expanding recurring sessions & availability across timezones and DST shifts
    - Tutor matching — SQL algorithms to match new students with the best available tutor
    - Reschedule requests — request/approval flow for rescheduling sessions within our platform
  - DateRange library — timestamp ranges compatible with Luxon DateTimes and PostgreSQL tstzranges
  - Session lifecycle events — automated eventing around tutoring sessions (notifications, billing)
  - Tutoring for organizations — student rostering, token distribution and program management
  - Billing management — per-session charges and refunds integrated with Remind Hub's billing platform, leveraging Stripe's API
  - Moderation tooling — dashboards for monitoring session cancellations, no-shows, etc
  - Distance learning — video chat web app used for tutoring sessions, leveraging Twilio's API
- [**Hub**](https://www.remind.com/hub) (2020-2021) — web and mobile messaging and administration app for schools and families
  - Single-page message composer UI
  - Auditor — message delivery status dashboard
- [Blog post about Betterscaling](https://engineering.remind.com/betterscaling/), Remind's in-house container autoscaling service

#### SmartProcure

- [`contexture`](https://github.com/smartprocure/contexture) — backend-agnostic querying & analytics framework
- [`grey-vest`](https://github.com/smartprocure/grey-vest) & [`contexture-react`](https://github.com/smartprocure/contexture-react) — design system, theming API, and React component library for contexture
- [`futil`](https://github.com/smartprocure/futil-js) — functional programming utils library (~400 GitHub stars)

#### Office Depot

- MCASA — Office Depot's warehouse management system, built in Java (migrated from C++ legacy code)
- R&D on machine learning solutions for inventory & supply chain

#### ADT

- Orchestration platform for security system support & installation

#### Avocent

- Datacenter infrastructure management (DCIM) software — import batching and thermal visualization components

### Personal Projects

- **[levity.whimsy.fun](https://levity.whimsy.fun)** — handwritten personal website (HTML, CSS, vanilla JS)
  - **[Write!](https://levity.whimsy.fun/write/about)** — online speedwriting notepad with persistence to my server via the Neocities API
- **[Menagerie](https://github.com/sand-bird/menagerie)** — monster simulation/management game made in Godot engine
  - Extensible content database written in JSON with JSON-schema validation
  - Custom syntax & parser for JSON-encoded predicates: token resolution, boolean operations, mapping & filtering
  - Needs-based (ie, Sims-like) behavioral AI with modular actions composed from prerequisites
  - (there's some [devlogs](https://vimeo.com/user204385298) if you wanna hear me ramble at length about it)
- **[Chores](https://github.com/michsa/chores)** — task management mobile app built with React Native + Redux
- **[Jeopardy](https://github.com/michsa/jeopardy)** — portable Jeopardy simulator intended as a knowledge-sharing tool (vanilla JavaScript, CSS, HTML)
- **[Cargo Shorts](https://github.com/michsa/cargo-shorts)** — Browser extension for tab management (TypeScript, React + Redux, WebExtension API)
- **[☆’s MHGen Talisman Editor](https://sand-bird.github.io/talismans)** — Single-page web app for editing Monster Hunter: Generations save data (JavaScript ES7, Vue, Vuex)

## /etc

### About me

- South Florida native, currently traveling the country looking for my forever home
- Great at learning new stacks but JS is my love language
- Loves: coffee, designing schemas and APIs, the web
- Hates: pickles, optimization & performance tuning, semicolons
- My dream job is working on a product I actually use and enjoy – Spotify, Patreon, Airbnb and Discord are on my shortlist, please hmu if you're one of those <3

### SEO-friendly skills list

- lead the design, development and implementation of sophisticated, scalable software solutions
- collaborate across departments with other engineers and cross-functional partners
- translate business requirements into technical solutions
- research and evaluate new technologies to enhance development processes
- proactively troubleshoot complex technical issues
- define project requirements, drive technical decisions, and own projects end-to-end
- provide technical guidance and mentorship
