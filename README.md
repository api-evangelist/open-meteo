# Open-Meteo (open-meteo)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Open-source weather API providing free global weather forecasts, historical data, marine, air quality, and climate projections via a simple REST interface with no API key required for non-commercial use.

**APIs.yml:** [apis.yml](apis.yml)

## APIs (10)

- **Weather Forecast API** — Up to 16-day hourly/daily forecasts from 30+ models. [Docs](https://open-meteo.com/en/docs)
- **Historical Weather API** — ERA5 reanalysis data from 1940 to present. [Docs](https://open-meteo.com/en/docs/historical-weather-api)
- **Ensemble API** — Probabilistic forecasts with up to 51 ensemble members. [Docs](https://open-meteo.com/en/docs/ensemble-api)
- **Climate Change API** — CMIP6 projections to 2050. [Docs](https://open-meteo.com/en/docs/climate-api)
- **Marine Weather API** — Ocean wave and sea surface conditions. [Docs](https://open-meteo.com/en/docs/marine-weather-api)
- **Air Quality API** — 5-day hourly pollution, pollen, and AQI forecasts. [Docs](https://open-meteo.com/en/docs/air-quality-api)
- **Flood API** — River discharge and flood risk forecasts via GloFAS. [Docs](https://open-meteo.com/en/docs/flood-api)
- **Seasonal Forecast API** — ECMWF SEAS5 outlooks up to 9 months ahead. [Docs](https://open-meteo.com/en/docs/seasonal-forecast-api)
- **Geocoding API** — Place name to coordinate lookup. [Docs](https://open-meteo.com/en/docs/geocoding-api)
- **Elevation API** — Terrain height from coordinates via 90m DEM. [Docs](https://open-meteo.com/en/docs/elevation-api)

## Pricing

| Plan | Price | Calls/Month | Commercial |
|------|-------|-------------|------------|
| Free | $0 | 300,000 | No |
| Standard | $29/mo | 1,000,000 | Yes |
| Professional | $99/mo | 5,000,000 | Yes |
| Enterprise | Custom | 50,000,000+ | Yes |

No per-call overage charges on any plan. See [plans/open-meteo-plans-pricing.yml](plans/open-meteo-plans-pricing.yml) and [rate-limits/open-meteo-rate-limits.yml](rate-limits/open-meteo-rate-limits.yml) for full details.

## Resources

- **Website:** https://open-meteo.com
- **Documentation:** https://open-meteo.com/en/docs
- **Pricing:** https://open-meteo.com/en/pricing
- **Status:** https://status.open-meteo.com
- **GitHub Org:** https://github.com/open-meteo
- **Blog:** https://openmeteo.substack.com
- **X:** https://x.com/open_meteo

## Tags
Weather, Forecasts, Historical Weather, Air Quality, Marine, Climate, Open Source, Free

## Timestamps
- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## Maintainers
- **Kin Lane** — kin@apievangelist.com
