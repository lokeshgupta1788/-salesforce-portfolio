# -salesforce-portfolio
A professional GitHub profile README with badges (all 3 certifications), tech stack table, project highlights with metrics from each role, architecture diagrams, and contact info.
force-app/main/default/classes/

TriggerHandler.cls — Abstract base class with recursion prevention and bypass support
AccountTriggerHandler.cls — Concrete handler demonstrating field-change filtering and service delegation
BatchLoyaltyProcessor.cls — Stateful Batch Apex processing 10M+ records with Platform Events (from Dell experience)
RestApiCalloutService.cls — Named Credential callout service with exponential backoff retry (from Veriforce/FSC work)

force-app/main/default/triggers/

AccountTrigger.trigger — Clean single-trigger pattern

force-app/main/default/lwc/opportunityDashboard/

Full LWC with wire service, NavigationMixin, reactive filters, KPI cards, and datatable

.github/workflows/salesforce-ci-cd.yml — 3-stage CI/CD pipeline: Scratch Org validation → UAT auto-deploy → Production with approval gate
docs/PATTERNS.md — Architecture decision records explaining the "why" behind each pattern
