# FIREGUARD AI --- Hack4Guimarães 2035

**Wildfire Response Simulation & Multi-Agency Decision Intelligence**\
**Presenter:** Hossam Elshahaby\
**Challenge:** Rural Fire Emergency Response --- Protection & Defence\
**Live prototype:** https://guimaraes-wildfire-watch.lovable.app/ \
**Demo:** https://youtu.be/gVtTwwbDXkg

> **Important safety notice:** FIREGUARD AI is a hackathon
> decision-support prototype. Its results are simulated and are not
> validated operational forecasts or emergency-response instructions. It
> must not be used to dispatch real emergency resources or issue real
> evacuation orders.

## 1. Overview

FIREGUARD AI demonstrates how emergency planners can compare alternative
response strategies against a shared, changing wildfire scenario. It is
designed around a common operating picture that combines scenario
conditions, map context, resources, time-step controls and calculated
indicators.

The aim is to support structured discussion: What changes if the wind
strengthens? How do response priorities alter the scenario output? Which
assumptions drive the recommendation? Where do resource constraints
create trade-offs?

The app is intended for hackathon demonstration, training concepts and
preparedness discussion---not live incident command.

## 2. Challenge and problem

Wildfire response may involve firefighters, civil protection, police,
medical services and municipal authorities. These teams need to
understand a rapidly changing situation while balancing community
protection, containment, access and limited resources.

Information can be fragmented across different systems, and it can be
difficult to compare alternative decisions before resources are
committed. FIREGUARD AI makes the comparison visible in one simulated
workspace.

## 3. Core application experience

The published prototype currently exposes the following interface
elements:

- **Scenario presets**
  - A --- Fast wind-driven fire
  - B --- Slope-driven rural fire
  - C --- Community-edge fire
- **Response options**
  - No response
  - A --- Containment
  - B --- Community
  - C --- Balanced
- **Time controls:** play control and selectable 0, 15, 30, 45, 60 and
  90 minute points.
- **Scenario indicators:** affected area, burning cells, exposed
  population and zones, wind speed and direction, humidity,
  temperature, slope factor, units on scene, and water/medical
  resources.
- **Situation map** and critical access-road context.
- **Potential exposure and vulnerable-location summaries.**
- **Calculated recommendation** and scenario-comparison workflow.

Exact model equations, frameworks, persistence mechanisms and API
integrations should be confirmed against the current implementation
before they are documented as technical facts.

## 4. Demo workflow

A recommended 90-second walkthrough:

1.  Open the live prototype.
2.  Select a scenario preset and review the conditions.
3.  Inspect the situation map, roads, resources and exposure indicators.
4.  Compare containment, community-protection and balanced strategies.
5.  Change one condition, such as wind or available resources, and rerun
    the comparison.
6.  Explain the changed metrics and any uncertainty in the
    recommendation.
7.  Discuss how the results could be validated with domain experts.

**Demo URL:** https://guimaraes-wildfire-watch.lovable.app/

## 5. Intended users

- Fire and rescue commanders (training and planning context)
- Civil-protection coordinators
- Municipal emergency planners
- Police and traffic coordinators
- Medical-response planners
- Researchers and facilitators running scenario exercises

The prototype represents these roles illustratively. It does not connect
to official institutional systems unless a separately verified
integration is implemented.

## 6. Data and model transparency

Keep these categories distinct:

---

Category Meaning

---

Verified source data Data retrieved from a traceable,
named source

User inputs Parameters selected or entered by a
user

Synthetic demo data Illustrative inputs created for
repeatable demos

Simulated outputs Model-generated indicators,
footprints, scores and comparisons

---

Potential future sources include OpenStreetMap, public elevation and
land-cover datasets, Copernicus emergency-management products, and
official Portuguese geographic, meteorological and civil-protection
information where access and terms permit.

Do not describe any data as live, official or verified unless that
status has been checked. Do not present illustrative resources,
facilities or road states as current operational truth.

## 7. Safety and limitations

- The prototype is not a certified wildfire-spread model.
- Simulated fire footprints are not validated operational forecasts.
- It does not autonomously dispatch responders or issue evacuation
  orders.
- Route visualisations are not verified safe evacuation routes.
- Synthetic data must be labelled.
- Strategy recommendations are conditional on the selected inputs and
  model assumptions.
- Real operational use would require domain-expert validation,
  data-quality controls, security review, documented uncertainty, and
  formal approval by responsible authorities.

## 8. Suggested evaluation criteria

A credible hackathon evaluation can test whether:

1.  All strategies use the same baseline conditions.
2.  The same inputs produce repeatable outputs.
3.  Changing a scenario input changes relevant calculated results.
4.  The UI distinguishes inputs, assumptions and outputs.
5.  Recommendation logic is visible and explainable.
6.  Users can identify uncertainty and limitations.
7.  The main demo workflow is understandable in under three minutes.

Avoid claims such as "lives saved," "proven accuracy," or "reduced
response time" without evidence from a suitable evaluation.

## 9. Suggested roadmap

### Hackathon core

- Repeatable scenario presets
- Time-stepped simulation
- Strategy comparison
- Transparent indicators
- Clear simulation warnings

### Geospatial and data quality

- Documented data imports and provenance
- Terrain and land-cover layers
- Coordinate and map-layer validation
- Source timestamps and units

### Decision-support workflow

- Resource constraints
- Sensitivity analysis
- Scenario replay and audit trail
- Exportable report

### Validation and future pilot

- Domain-expert review
- Benchmark scenarios
- Model error and uncertainty documentation
- Security, privacy, accessibility and reliability review
- Formal approval before any operational integration

## 10. Submission description

**Short description:**\
FIREGUARD AI is a wildfire response simulation and decision-support
prototype that lets users compare alternative strategies against the
same simulated incident. It combines scenario presets, time-step
controls, map context, resource indicators and a calculated
recommendation to make trade-offs more visible. Built for Hack4Guimarães
2035, it demonstrates how a shared operational picture can support
training and preparedness discussions while keeping humans in control.

## 11. Project details

- **Project:** FIREGUARD AI
- **Event:** Hack4Guimarães 2035
- **Challenge:** Rural Fire Emergency Response --- Protection &
  Defence
- **Presenter:** Hossam Elshahaby
- **Prototype:** https://guimaraes-wildfire-watch.lovable.app/

---

_This README describes the public-facing prototype and its intended use.
Update the technical architecture, setup instructions, and
implementation details after checking the actual source repository and
deployment configuration._
