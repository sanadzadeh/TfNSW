# Transport Analytics Portfolio

A self-contained transport analytics portfolio artefact demonstrating two connected working views in a single HTML application:

- **Delivery & Assurance**
- **Network & Customer**

The artefact uses synthetic data and is designed to show how complex transport, delivery, customer and assurance information can be structured into practical decision-support views.

> Synthetic demonstration only. This is not an official Transport for NSW product and does not use TfNSW operational data.

## Overview

The portfolio is built as one standalone HTML file with two separate dashboards that share the same visual system, theme controls and interaction model.

The default dashboard is **Delivery & Assurance**. A switch in the header changes the entire application to **Network & Customer**.

The two dashboards are intentionally separate rather than forcing delivery, PMO, customer and operational analysis into one oversized page. Cross-links connect related delivery initiatives and network KPIs where the relationship is useful.

## Delivery & Assurance

The Delivery & Assurance dashboard focuses on portfolio delivery, cost, schedule, benefits, dependencies, data assurance and scenario analysis.

### Portfolio overview

The overview provides an exception-based portfolio view including:

- active initiatives
- average schedule variance
- portfolio estimate at completion
- blocking dependencies
- baseline cost versus current EAC
- schedule exception overlay
- portfolio status distribution
- program-level initiative map
- filter-aware recommended decision
- compact portfolio register

Program and status filters update the portfolio population used throughout the dashboard.

### Delivery detail

The delivery view provides initiative-level drill-down across:

- schedule variance
- forecast finish
- baseline cost
- actual cost
- EAC
- benefit status
- delivery confidence trend
- milestone progress
- dependencies
- issues
- risk treatments

Initiatives can be selected directly from the filtered set.

### Risk and data assurance

The assurance view demonstrates how reported metrics can be linked back to their source and control evidence.

It includes:

- data-quality heatmap
- issue ageing
- metric-level lineage
- semantic model references
- transformation logic
- source systems
- ownership
- refresh frequency
- validation rules
- reconciliation and test status
- initiative-level assurance status

The lineage view currently covers:

- Schedule variance
- Cost / EAC
- Milestone achievement
- Benefits realisation

### Forecast and scenario

The delivery scenario view applies explicit assumptions to the filtered portfolio.

Current scenarios include:

- Base
- Accelerated delivery
- Adverse dependency
- Cost escalation

The model is deliberately transparent. It does not claim predictive machine learning. Scenario results are produced from stated rules applied to the current filtered initiative population.

## Network & Customer

The Network & Customer dashboard provides a separate analytical view of network performance, passenger demand and customer outcomes.

### Network command centre

The command centre combines:

- passenger journeys
- on-time running
- service completion
- passenger minutes lost
- customer satisfaction
- complaints
- utilisation
- time-based demand and reliability trends
- highlighted disruption periods
- related delivery initiatives

The main time-series visual uses a combination chart so demand and service performance can be interpreted together rather than in isolation.

### Network performance

The network performance view focuses on:

- mode-level reliability
- demand
- completion
- utilisation
- corridor and operational exceptions
- highlighted disruption periods

Filters support:

- reporting period
- transport mode
- region

### Customer insights

The customer view includes:

- CSAT
- complaints per 100,000 journeys
- demand versus forecast
- illustrative elasticity
- complaint taxonomy
- baseline versus post-change comparison
- weather, event and disruption confounders

The purpose is to show how customer movement should be interpreted with context rather than treated as a raw trend.

### Metric lineage

The network lineage view traces selected KPIs through:

- report measure
- semantic model
- transformation logic
- source
- owner
- refresh frequency
- validation
- reconciliation

Current examples include:

- On-time running
- Passenger journeys
- Complaints / 100k
- Passenger minutes lost

### Network scenarios

The network scenario view includes:

- Base
- Service uplift
- Disruption
- Demand upside

The scenarios adjust only stated assumptions such as journey and passenger-impact factors.

## Connected decision system

The two dashboards are linked where appropriate.

Examples include:

- T18 Timetable Resilience → Train OTR
- T11 Fleet Diagnostics → Train completion / passenger impact
- T05 Realtime Information Quality → Complaints / 100k
- T09 Opal Analytics Refresh → Passenger journeys
- T14 Regional Coach Reliability → Bus OTR

A delivery exception can link to a related network KPI, and a network KPI can link back to a related delivery initiative.

This makes the artefact behave more like one decision-support system rather than two unrelated demos.

## Visual and interaction design

The interface is intentionally closer to a corporate or government analytical product than a marketing site.

Design features include:

- light theme by default
- optional dark theme
- compact typography
- combination charts
- smooth line rendering
- shaded event and disruption periods
- hover tooltips
- status strips
- heatmaps
- initiative matrices
- milestone progress visuals
- scenario comparison
- compact tables for exact values
- responsive layout

Hover explanations are used to provide context without permanently filling the page with text.

## Synthetic data

All data in this artefact is synthetic.

Initiative names, values, dates, costs, performance measures, risks, customer indicators, source-system references and scenarios are illustrative and are included only to demonstrate analytical structure and interaction.

The artefact should not be interpreted as representing actual TfNSW performance, project status, cost, risk or customer results.

## Technical approach

The application is intentionally lightweight and self-contained.

It uses:

- HTML
- CSS
- vanilla JavaScript
- inline SVG charts
- browser local storage for theme preference

There is:

- no backend
- no external database
- no JavaScript framework
- no charting library
- no API dependency
- no production data connection

The file can be hosted directly through GitHub Pages.

## Why this artefact exists

The purpose of the artefact is to demonstrate capability across:

- portfolio reporting
- delivery assurance
- business analysis
- data modelling concepts
- data-quality and governance thinking
- executive decision support
- scenario modelling
- customer and network analytics
- metric lineage
- analytical storytelling
- practical browser-based product development

It is designed as a work sample rather than a production system.

## Portfolio

Please check my portfolio: https://sanadzadeh.github.io/Portfolio
