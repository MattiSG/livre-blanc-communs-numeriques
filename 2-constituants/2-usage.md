# Terms

Some services may be provided by simply running the code (e.g. image compression on a personal computer). In these cases, the usage regime is derived from the source code access regime. In other cases, the duplication of the source code does not allow the duplication of the service provided, for example in the case of interfacing with private resources such as an API or in the case of a service applying a platform strategy (Colin & Verdier, 2013). In this second case, the prevalence of the value of network effects over the value of the code itself makes it extremely difficult to replicate the service\[^12].

## Permissive Terms of Use

The fact that it is potentially impossible _de facto_ to provide an alternative to the terms of use of the digital service, even if the source code is _de jure_ duplicable, shows that the right of use is a full-fledge component of the shared resource. It is not a systematic instance of this resource, each variant of which could impose its own right of use\[^13].

**A minimum constraint is that the terms of use should allow usage without conditions other than those strictly necessary for operating the service and preventing acts aimed at reducing the capacity of other uses.**

**Operational recommendation: transform legal constraints into a source of information for users, using clear and readable language that classifies terms of use according to their concerns (**[**example**](https://mes-aides.gouv.fr/cgu)**).**

## Contribution budget <a href="#contribution-budget" id="contribution-budget"></a>

In addition to legal guarantees, technical guarantees are appropriate to ensure effective freedom of use. In the case of a minimal commons, a poor quality of service can be solved by creating an alternative service based on the code. But in the case of a contributive commons, the instance through which the community collaborates must be functional. If the service is under permanent maintenance, even the most open TOS will not enable its use.

**For contributive services, there is a constraint to commit to a rate of availability of the service for its users (SLA\[^14]). In order not to hinder the evolution of the service, this SLA must evolve over time and be interpreted as a "contribution budget\[^15]".**

**Operational recommendation: determine the SLA according to the number of users and the capacity of human agents to handle anomalies, ensuring the easiness and quality of this process, by applying a formula such as `SLA = 1 - (number of files that can be handled manually ÷ number of users over the same period)`.**

> For example, if I have a community manager who can efficiently support and debug 10 users per day, with a service used by 1,000 users per day, my error budget is 10 / 1,000 = 1%, which sets my SLA at 99%.

\[^12]: For example, Wikipedia's engine, Mediawiki, is an open source software that can be, and is, widely duplicated. However, duplicating the service provided by Wikipedia would be extremely complex, as users - and therefore contributors - are all familiar with "Wikipedia". A duplicate offering exactly the same functionality would have no chance of competing efficiently with the service provided.

\[^13]: This is why migrating from a service like Twitter to an alternative like Mastodon is unlikely: even if the algorithm allowing network distribution across multiple instances is more advanced than a monolithic service, the value of the service comes primarily from the contribution of its users. The return on investment for each individual user is in favour of continuing to use the service that has the most users, as the cost (becoming isolated) is not worth the benefits (better functionality).

\[^14]: A [SLA](https://fr.wikipedia.org/wiki/Service-level\_agreement) can be expressed as a percentage of requests processed per time unit. For example, one can commit to an availability of 99.9% per month, which means that 99.9% of the requests are processed without any errors by the system.

\[^15]: In [this view](https://landing.google.com/sre/interview/ben-treynor.html), inspired by the Site Reliability Engineering movement, instead of interpreting an availability commitment of 99.9% per month as a minimum standard that should aim at 100%, one considers that one can implement upgrades that include an operational risk up to a maximum of 0.1% of the requests being processed with errors.
