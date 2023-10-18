# Michelle Saad

- **✔️ U.S. Citizen**
- 📞 phone: 954.801.1273
- 📧 email: contact@michsa.me
- 🌐 web: [michsa.me](https://michsa.me)
- 👩‍💻 GitHub: [@michsa](https://github.com/michsa)

## Summary

- Full-stack software engineer with ~7y experience
- Current stack: Rust, PostgreSQL, Node.js, Typescript, GraphQL, React
- Remote only (Pacific hours preferred)
- Open to chat but happy at Remind :)

### Work History

| Company      | Dates        | Title                          | Stack                                                       |
| ------------ | ------------ | ------------------------------ | ----------------------------------------------------------- |
| Remind       | 2020-current | Software Engineer              | Rust, Typescript, PostgreSQL, React, GraphQL, AWS, Ruby, Go |
| SmartProcure | 2019-2020    | Software Developer             | JS, React, Mobx, Feathers, MongoDB, ElasticSearch           |
| Office Depot | 2017-2019    | Software Engineer              | Java, DB2, COBOL                                            |
| ADT          | 2016         | Application Development Intern | JS, Java, AngularJS, SOAP                                   |
| Avocent      | 2015         | Software Development Intern    | JS, Java, PostgreSQL                                        |

### Education

| Degree                   | Grad. | School                      |
| ------------------------ | ----- | --------------------------- |
| B.S. in Computer Science | 2017  | Florida Atlantic University |

## Projects

#### Remind

- **HQ** (2023-current) – rewrite of Remind's [core datamodel](https://engineering.remind.com/Transitive-Closure-In-PostgreSQL/) and business logic in Rust and PostgreSQL
  - Revamped Remind's messaging infrastructure to support multiple connectivity partners (Twilio, Sinch, etc) and more granular SMS campaign provisioning
- [**Tutoring**](https://www.remind.com/tutoring) (2021-2023) – platform to schedule, manage, and host tutoring sessions with Remind teachers
  - Various projects around scheduling and availability
    - Tutor availability architecture
    - Tutor matching – SQL algorithms to match new students with the best available tutor
    - Reschedule requests – rescheduling sessions within our platform
  - DateRange library – timestamp ranges compatible with Luxon DateTimes and PostgreSQL tstzranges
  - Session lifecycle events – automated eventing around tutoring sessions (notifications, billing)
  - Tutoring for organizations – student rostering, token distribution and program management
  - Billing management – per-session charges and refunds integrated with Remind Hub's billing platform, built on top of Stripe's API
  - Moderation tooling – session cancellations, no-shows, etc
  - Distance learning – video chat web app used for tutoring sessions, built on top of Twilio's API
- [**Hub**](https://www.remind.com/hub) (2020-2021) – web and mobile messaging and administration app for schools and families
  - Message composer UI
  - Auditor – message delivery status dashboard
- [Blog post about Betterscaling](https://engineering.remind.com/betterscaling/), Remind's in-house container autoscaling service

#### SmartProcure

- [`contexture`](https://github.com/smartprocure/contexture): backend-agnostic querying & analytics framework
- [`grey-vest`](https://github.com/smartprocure/grey-vest) & [`contexture-react`](https://github.com/smartprocure/contexture-react): design system, theming API, and React component library for contexture
- [`futil`](https://github.com/smartprocure/futil-js): functional programming utils library (~400 GitHub stars)

#### Office Depot

- MCASA: Office Depot's warehouse management system, built in Java (migrated from C++ legacy code)
- R&D on machine learning solutions for inventory & supply chain

#### ADT

- Orchestration platform for security system support & installation

#### Avocent

- Datacenter infrastructure management (DCIM) software: import batching and thermal visualization components

### Personal Projects

#### [Chores](https://github.com/michsa/chores)

- Task management mobile app built with React Native + Redux

#### [Menagerie](https://github.com/sand-bird/menagerie)

- Simulation/management game made in Godot engine
- Extensible content database written in JSON with JSON-schema validation
- Custom syntax & parser for JSON-encoded predicates: token resolution, boolean operations, mapping & filtering

#### [Cargo Shorts](https://github.com/michsa/cargo-shorts)

- Web extension for tab management (TypeScript, React + Redux, WebExtension API)

#### [☆’s MHGen Talisman Editor](https://sand-bird.github.io/talismans)

- Single-page web app (JavaScript ES7, Vue, Vuex) for editing Monster Hunter: Generations save data
