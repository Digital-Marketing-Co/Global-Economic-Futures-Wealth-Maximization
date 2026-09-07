# Canonical Data Schema

## Economy

`economy_id`, ISO/UN/M49 and source-specific codes, canonical name, short name, sovereignty/status class, parent economy where applicable, region, income group, currency, languages, time zone, geographic validity dates, flag asset, theme tokens, and source mappings.

## Indicator definition

`indicator_id`, domain, canonical label, formal definition, concept type, frequency, units, currency basis, price basis, adjustment, aggregation rule, expected sign, comparability notes, and source-series mappings.

## Observation

`economy_id`, `indicator_id`, period start/end, value, units, status, source vintage, release timestamp, revision sequence, confidence interval, seasonal adjustment, transformation chain, and provenance reference.

## Trade and flow edge

Reporter, partner, direction, product/service classification and revision, code, period, value, quantity, units, transport mode where available, valuation basis, mirror-data flag, confidentiality status, and provenance reference.

## Sector node

Economy, classification system and revision, sector code, parent sector, output, value added, employment, establishments, wages, capital formation, productivity, emissions/resource intensity where available, period, and provenance.

## Event and structural break

Economy, start/end, event class, description, affected series, evidence level, causal-claim status, sources, and analyst notes.

## Scenario

Economy, horizon, scenario name, baseline vintage, assumptions, model family, parameter distribution, policy levers, shocks, outcome distributions, validation results, limitations, and provenance.

## Required status vocabulary

`observed`, `publisher_estimate`, `derived`, `nowcast`, `forecast`, `scenario`, `provisional`, `revised`, `unavailable`, `not_applicable`, `incomparable`.
