# Dickson Tan

<!-- The unordered list immediately after the h1 will be formatted on a single
line. It is intended to be used for contact details -->

- [email](mailto:dickson.tan.2013@gmail.com)]
- [GitHub profile](https://github.com/Neurrone/)
- [blog](https://neurrone.com)
- Singapore

<!-- The paragraph after the h1 and ul and before the first h2 is optional. It
is intended to be used for a short summary. -->

## Skills

- Languages: JavaScript, TypeScript, Python, Rust
- Technologies: node.js, Serverless (AWS Lambda), React, Docker
- Others: API design, relational databases, unit, integration & E2E testing, web accessibility

## Experience

<!-- You have to wrap the "left" and "right" half of these headings in spans by
hand -->

### <span>Software Engineer, GovTech Singapore</span> <span>Apr 2021 -- present</span>

### <span>Associate Software Engineer, GovTech Singapore</span> <span>Aug 2018 -- Apr 2021</span>

#### <span>GovWallet (Oct 2021 -- present)</span>

[GovWallet](https://www.developer.tech.gov.sg/technologies/platform/govwallet.html) is a reusable system for government agencies to disburse payouts to citizens.

- Technologies: TypeScript, Node.js, various AWS services (DynamoDB, Lambda, SQS), Python
- Added support for disbursing payouts that have an expiry date. This removes the need to manually reclaim unused funds when various schemes expire, a key requirement for agencies
- Automated various repetitive ops tasks, saving an estimated 1 hour per sprint
- Reduced time needed to run tests on the pipeline from 15 to 3 minutes. This was done by working around a memory leak

#### <span>Notarise (Nov 2020 -- Dec 2020)</span>

Notarise is a portal for outbound travelers to get digitally authenticated and endorsed COVID-19 Pre-Departure Test results for travel.

- Technologies: Node.js, various AWS services (Lambda, SNS, SQS)
- Simplify travel by making notarised test results available in the SingPass mobile app. This was done by integrating with the SingPass backend
- Reduce time needed for travelers to get their notarised results. Exposed APIs for providers of COVID-19 tests for them to get results back to travelers more quickly

#### <span>MyCareersFuture (Aug 2018 -- Sep 2021)</span>

[MyCareersFuture (MCF)](https://www.mycareersfuture.sg) is a job portal that matches jobseekers and employers through skill matching. Worked in a cross-functional scrum team of ~20 people.

- Technologies: Node.js, MySQL, React, Cypress, GraphQL, CouchDB, Docker, AWS
- Decouple MCF from a legacy system resulting in 3% more uptime and 10% less code in the backend. This legacy code was used to keep data in sync with this system bidirectionally in real-time which limited MCF's uptime and has caused data corruption issues
- Led design of new APIs for third parties that MCF integrates with, so API consumers pull data instead of data being pushed to each new third party. This means that work only needs to be done once to build the APIss with minimal effort to onboard new API consumers
- Reduce cycle time by 50% allowing for more frequent deployments. This was done by advocating for greater ownership of the end-to-end tests in the pipeline among developers. This increased the frequency of green builds deployable to production from once per fortnight to multiple times a week
- Provide level 3 support on a rotational basis to diagnose and fix bugs in production

## Projects

- Added support for keyboard navigation to the JSON viewer in Mozilla Firefox, released in version 76
- Created [Beets-audible](https://github.com/Neurrone/beets-audible), a plugin that adds support for audiobook management to Beets. Beets is an open-source music organizer with over 10000 stars on Github

<br>

## Education

### <span>National University of Singapore, BComp. Computer Science, Honors (Highest Distinction)</span> <span>2015 -- 2018</span>

- GPA 4.55/5.0
- Thematic Systems Project I and II (enrollment cap of 21 students): software engineering modules training students to improve code quality towards levels expected from engineers at high-end companies like Google and lead high-stakes open-source projects. Fixed bugs, provided code review and advised new contributors.

## Interests

- Coffee
- Reading science fiction and fantasy
- Ontological coaching
