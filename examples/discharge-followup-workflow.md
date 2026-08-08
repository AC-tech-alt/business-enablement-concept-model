Worked Example: Discharge Follow-Up Workflow

A fictional case tracing one initiative through every concept in the model, showing the difference between a naive one-line status and what the model actually surfaces.

The chain

Business Problem Named by Clinical Operations: 22% of patients discharged from the hospital do not have a follow-up visit scheduled within 7 days, a gap correlated with higher 30-day readmission risk. Owning domain: Clinical Operations. Urgency: High. Scope: Multi-site. Evidence: Discharge-to-scheduling data pulled from the last two quarters.

Initiative — "Discharge Follow-Up Workflow" Sponsor: VP, Clinical Operations. Target outcome: 90% of discharged patients scheduled within 7 days. Timeline: 90 days.

Workflow Designed by Operations + Clinical Informatics: a hospital discharge notification triggers an Epic task to the care coordinator, who must schedule the follow-up within 24 hours of the notification. Process owner: Clinical Informatics. Systems touched: Epic. Dependency: relies on timely discharge summary data from the hospital feed.

Execution Plan Owned by DDAT and Operations jointly. Sequencing: (1) build the Epic alert/task trigger, (2) pilot at 3 centers, (3) build coordinator training, (4) roll out to all centers. Named owner per step, not one blanket owner for the whole plan.

Field Readiness Care coordinators trained at all centers. Alert tested and confirmed firing correctly. One piece of field feedback surfaced and fixed before full rollout: the alert was firing before the discharge summary was finalized, producing incomplete tasks — timing logic was corrected during the pilot.

Adoption Tracked weekly starting at go-live: % of discharge alerts actioned within 24 hours.

Week 2: 81% (still close to go-live enthusiasm)
Week 6: 74%
Week 10: 72%, holding

Two of eight centers show coordinators reverting to a manual spreadsheet workaround instead of using the Epic task — flagged as an adoption gap requiring a Workflow revision, not a training issue.

Value Realization Evaluated only after Adoption held for 60+ days. Follow-up scheduling rate rose from 78% to 88% system-wide — short of the 90% target, directly attributable to the two centers with the adoption gap. Readmission-rate impact is still pending a longer measurement window.

Why this matters: two ways to report the same initiative

Naive status report:

Discharge Follow-Up Workflow: ✅ Complete

Model-based status report:

Concept	Status
Workflow designed	Complete
Execution Plan	Complete
Field Readiness	Complete, all 8 centers
Adoption	Partial — 72% sustained, 2 of 8 centers reverted to manual workaround
Value Realization	88% vs. 90% target — gap traceable to the adoption shortfall, not the workflow design

The naive version tells leadership the initiative is done. The model-based version tells them exactly where it's still short, why, and which two centers need a follow-up intervention — which is the entire point of separating these concepts instead of collapsing them into one status field.
