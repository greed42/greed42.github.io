---
layout: default-content-only
---
# Graham Reed &mdash; Site Reliability Engineer

London &mdash; United Kingdom

## Employment

### G-Research: Site Reliability Engineer

2019-01 - 2023-02

    G-Research
    Whittington House
    19-30 Alfred Place
    London

-   Design and lead implementation of a reliable interface to
    PagerDuty while maintaing compliance with company security
    policies and systems.

-   Define in-company standards for Kubernetes configuration, develop
    prototype implementation. Core Helm chart for running daemon
    applications in use in creating over 400 unique `Deployment` objects
    (and supporting objects such as `Service`).

-   Analyze outages and incidents to recommend actions to improve
    detection of future events, afford faster recovery time, and
    reduce failure impact.

-   Built unit and integration test frameworks for "believed to be
    untestable" configuration (such as Prometheus Alertmanager routing
    configuration and message formatting).

-   Established sharable Helm charts, Helm and Jenkins libraries and
    Jenkins pipeline definitions to reduce the "non-domain" knowledge
    service authors need to set up monitoring.

Mentored willing team members on topics such as:

-   Good testing leads to fast improvement, bad testing leads to
    frustration, and no testing means outages.

-   "staging", "canary" and other pre- and in-production validation
    techniques.

-   Alerting on user-triggerable behaviour requires a synthetic user
    with known behaviour (such as a "prober" or "traffic generator").

-   Nyquist isn't just for sound: your metrics-based monitoring system
    is also using signal sampling.

-   Separating meta information about a signal source from detail
    about the signal itself will help you sort out faults in the
    monitoring stack.

### Google: Site Reliability Engineering &mdash; Systems Engineer

2013-01 &ndash; 2018-12

    Google UK Ltd
    6 Pancras Square
    London

#### Google App Engine (Serving Subteam)

2014-07 &ndash; 2018-12

-   Take part in on-call rotation: Mitigate urgent issues; oversee
    long-term prevention efforts; respond to customer and support
    escalations; write and contribute to post-mortems for major system
    faults.

-   Develop and implement traffic isolation techniques to prevent smaller
    customers from being starved of resources by a very large customer's
    traffic. (This solution is now used as a model for other services
    needing similar protection.)

-   Restore legacy monitoring system to good operation, to ensure
    migration onto the new system does not lead to "hidden" service faults
    due to failed monitoring.

-   Migrate monitoring operation to new system, improving signal quality
    as needed.

-   Determine efficient way of allowing App Engine monitoring
    configuration to use new Google SRE standard technologies. Implement
    support libraries to simplify configuration and ensure consistency.
    Provide reference implementation to serve as a model for other SREs to
    follow.

-   Define roadmap for bringing App Engine's billing system under SRE
    support. Run part of the procedure, until it was determined that the
    Storage subteam would own the feature. Transferred responsibilities to
    Storage subteam.

-   Define rollout plan to migrate App Engine language runtimes from
    32-bit to 64-bit server binaries. Consultation with product
    management, development, and support to ensure that customers would
    not be adversely affected. Define success and failure conditions,
    document roll-forward and roll-back procedures. Used as a model for
    other rollouts which had a high risk of negative impact on customer
    experience.

-   Define traffic routing plans to support the beta and full launch of
    App Engine Flexible Environment. Educate team members and support team
    on details of new traffic routing. Implement stop-gap routing proxy to
    support beta without increasing risk seen by existing App Engine
    customers.

-   Advise others &mdash; same-team and other-teams &mdash; on monitoring
    and alerting. Both how-to write your configuration and how to consider
    the signal space when building monitoring systems. Wrote a
    presentation on how alerting configuration and signals interacts,
    which is now used as part of new SRE education.

#### Google Docs

    Google UK Ltd
    Belgrave House
    76 Buckingham Palace Road
    London

-   Take part in on-call rotation: Mitigate urgent issues; oversee
    long-term prevention efforts; run production code release processes;
    write and contribute to post-mortems for major system faults.

-   Create tooling to drive "production readiness reviews", to bring
    consistency and automation to a common SRE process. (This is an
    eseential part of the steps an SRE team in determining if a product or
    feature is ready to be supported by SRE, and what improvements are
    needed.)

-   Improve monitoring systems, with special focus on re-use through
    standardisation across features. Ensure system works with features
    that are developer supported as well as those that are SRE supported.

-   Oversee the process of bringing the Google Drive API under SRE
    support. Drive reliability and scaling improvements to reach SRE
    standards.

-   Improve monitoring-driven notification system ("alerts"): Raise
    signal-to-noise ratio of notifications; clarify or create
    documentation to support notifications.

### IBM Canada Software Laboratory: Senior Software Engineer

2012-01 &ndash; 2013-01

    IBM Canada Software Laboratory
    185 Spadina Avenue
    Toronto, Ontario

In late 2011, IBM acquired Algorithmics and became employer-of-record for Canadian employees as of January 1, 2012.

### Algorithmics, Incorporated: Senior Software Engineer

1999-10 &ndash; 2012-12

    Algorithmics, Incorporated
    185 Spadina Avenue
    Toronto, Ontario

### IBM Canada Software Laboratory: Staff Software Engineer

    IBM Canada Software Laboratory
    1150 Eglinton Avenue East
    Toronto, Ontario

### Bell-Northern Research: Summer Student (Software Development)

1992-05 &ndash; 1992-08

1991-05 &ndash; 1991-08

    Bell-Northern Research
    Ottawa, Ontario

---

## Education

### Electrical Engineering: Bachelor of Science with Honours

1989-09 &ndash; 1993-04

    Queen's University at Kingston, Ontario
    Department of Electrical Engineering

---

## Awards

-   2017: Google TI Award for contributions to the launch of App Engine Flexible Environment.

-   1996: IBM Special Achievement Award for design and implementation of multiplatform batch test tool.

-   1992: Winner and Best Technical Queen's Engineering Competition, Vox-Drive Software Team Leader.
