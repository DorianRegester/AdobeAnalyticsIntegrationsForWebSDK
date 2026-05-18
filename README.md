# Adobe Experience Platform Web SDK Plugins

A comprehensive repository of SME-grade tracking scripts, XDM object extenders, and behavioral monitors designed to optimize implementations using the Adobe Experience Platform (AEP) Web SDK (`alloy.js`).

## At a Glance
> **Key Decision Point:** These utilities are engineered specifically for the modern AEP Web SDK framework. Instead of mapping to legacy AppMeasurement variables (`s.eVar`, `s.prop`), these components dynamically manipulate and enrich the Experience Data Model (XDM) schema before payloads are transmitted to the Adobe Edge Network. Ensure your Edge Configuration and XDM schemas are fully configured to receive these specific field groups.

## Core Tracking & Behavioral Analytics

This category focuses on capturing granular user engagement, localized interactions, and document lifecycle events within the modern event-driven SDK architecture. These utilities standardize DOM auditing and listener delegation, dynamically injecting interaction context directly into the `web.webInteraction` object.

*   **aemAssetTracker for Web SDK**
*   **FormObserverPro**
*   **rageClickDetector**
*   **getEngagementMetrics**
*   **getClipboardTracker**
*   **getActivityMapContext**

## Performance & Environment Audits

Utilities in this classification monitor the user’s technical ecosystem and site performance health directly from the browser window. By converting client-side errors, browser limitations, and performance markers into structured XDM metrics, teams can easily isolate how user experience directly impacts conversion performance at the Edge.

*   **getCoreWebVitals**
*   **HardwareContextAuditor**
*   **getClientSideIssues**
*   **audioEnvironmentAuditor**

## E-commerce & Conversion Intelligence

This suite provides deep-tier pathing and transactional context for digital merchandising applications leveraging the commerce XDM schema. Rather than tracking basic purchase receipts, these behavioral analyzers decode user intent patterns, predict return risks via shopping anomalies, and classify product discovery funnels to quantify exactly how users navigate stock and checkout logic.

*   **ProductDiscoveryAuditor**
*   **returnPropensityPredictor**
*   **scarcityLogicTracker**
*   **CartIntentAuditor**

## Data Hygiene, Schema Validation & Privacy

Governance and security utilities dedicated to protecting data integrity and preserving end-user privacy. These components dynamically intercept XDM objects before Edge transmission to strip prohibited Personally Identifiable Information (PII), validate schema object drift, and update real-time consent transitions to maintain strict data hygiene.

*   **getPIIScrubber**
*   **getDataLayerWatchdog**
*   **consentChangeAuditor**
*   **getQueryParamCleaner**

## Questions/Comments/Concerns

Please feel free to contact me as I would love to provide folks with things that will help them in the end.
