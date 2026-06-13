# PRD — AI Collective Skill

## 1. Summary

AI Collective is a skill designed to act as chief of staff and operational copilot for planning, producing, and following up on a monthly presencial meeting for a community or organization called AI Collective.

Its purpose is to reduce coordination friction and leave the event ready to execute with clear decisions, strong messaging, and monthly continuity.

## 2. Objective

The skill must help:

- Define and coordinate the monthly AI Collective meeting.
- Find and propose suitable venues.
- Define date, time, and agenda.
- Draft invitations and diffusion copy.
- Prepare ready-to-send messages across channels.
- Keep a stable monthly cadence.

## 3. Scope

This skill is a strategic and operational assistant for presencial events.

Includes:

- Asking for city or zone before venue search.
- Asking for event budget.
- Asking who approves the venue.
- Asking about sponsors or patrons.
- Proposing venues, dates, and times.
- Building the meeting agenda.
- Drafting the main invitation.
- Writing ready-to-send copy.
- Preparing direct invitation messages.
- Preparing an operational checklist.
- Suggesting post-event follow-up.

Does not include:

- Booking or paying for venues without approval.
- Sending messages or invitations without explicit approval.
- Assuming city, budget, sponsors, or format when they were not provided.
- Defaulting to virtual or hybrid as the main format unless explicitly requested.

## 4. Design Principles

- City agnostic: always ask for the city or zone.
- Presencial by default.
- Copy must be ready to send, not only rough drafts.
- Monthly recurrence is mandatory.
- Prefer logistical ease over perfection.
- Prefer attendance and clarity over unnecessary complexity.
- If critical data is missing, ask before moving forward.
- If multiple options are valid, recommend one and explain why.

## 5. Required Inputs

The skill must ask for, at minimum:

- City or zone.
- Event budget.
- Final venue approver.
- Sponsors or patrons desired.
- Estimated attendee count.
- Ideal date or date window.
- Event objective.
- Brand tone or communication style, if relevant.

## 6. Expected Outputs

The skill must produce:

- 3 venue options with pros and cons.
- 2 or 3 date and time options.
- Event agenda.
- Formal invitation draft.
- Short diffusion copy.
- Long diffusion copy.
- Direct invitation message.
- Operational checklist.
- Final recommendation.
- Summary for the next monthly cycle.

## 7. Chief of Staff Functions

The skill must be able to:

- Search and propose venues.
- Define time and date.
- Design the agenda.
- Draft the main invitation.
- Create ready-to-send copy for email, WhatsApp, and LinkedIn.
- Prepare personalized direct invitation messages.
- Define the monthly work plan.
- Support pre-event coordination.
- Suggest follow-up and next steps after the meeting.

## 8. Operational Flow

1. Receive the initial context.
2. Detect what is missing.
3. Ask only for the essential data.
4. Propose concrete, ordered options.
5. Recommend a primary option.
6. Generate ready-to-use text and materials.
7. Leave the package ready for approval.
8. Record key decisions for monthly reuse.

## 9. Decision Rules

- If the budget is low, propose a lean version.
- If the venue is not approved, do not assume closure.
- If there is no sponsor, suggest a sponsor-led or sponsor-free version.
- If the city is not defined, ask before searching venues.
- If the approver is not defined, block the final recommendation.
- If the event needs more attendance, optimize invitation and diffusion copy, not just the agenda.

## 10. Sponsorship

The skill must treat sponsors or patrons as an explicit event variable.

It should help:

- Identify whether the event needs a main sponsor, co-sponsors, or none.
- Suggest how to mention sponsors in invitations and diffusion.
- Adapt copy depending on sponsorship presence.
- Keep AI Collective branding consistent with sponsor branding.

## 11. Monthly Cadence

The skill must assume the meeting happens at least once per month.

Suggested cycle:

- Week 1: define city, venue, date, and objective.
- Week 2: close agenda and invitation.
- Week 3: diffuse and invite.
- Week 4: confirm attendance, prepare logistics, and execute.
- Post-event: summary, lessons learned, and tentative next date.

## 12. Base Agenda

The agenda should be flexible, but the default structure is:

- Welcome.
- Context and purpose.
- Main content block.
- Conversation, networking, or participation.
- Close with next steps.
- Define commitments or actions.

## 13. Success Metrics

The skill should help measure:

- Whether the meeting happened every month.
- Confirmation rate.
- Actual attendance vs invitations sent.
- Time saved in coordination.
- Clarity of the invitation message.
- Quality of attendee responses.
- Ability to repeat and sustain the format.

## 14. Use Cases

- Create a monthly meeting from scratch.
- Repeat a previous format.
- Change venue because of a logistics issue.
- Rewrite invitation copy for a specific audience.
- Prepare copy for different channels.
- Adapt the event to a limited budget.
- Incorporate sponsors or patrons into the narrative.

## 15. Edge Cases

The skill must handle:

- Venue not available.
- Low expected attendance.
- Date changes due to conflicts.
- Insufficient budget.
- No sponsor.
- Missing venue approver.
- Different tones by audience.
- Need for waitlist or limited capacity.

## 16. Memory and Continuity

The skill should retain or reuse:

- City or zone used.
- Venues that worked well.
- Topics from previous meetings.
- Copy that generated better response.
- Previous sponsors or patrons.
- Approved format decisions.

## 17. Definition of Done

The skill is successful if it:

- Becomes the operating system for the monthly meeting.
- Reduces manual coordination work.
- Leaves the core materials ready without friction.
- Preserves continuity across meetings.
- Lets AI Collective run reliably every month.

## 18. Executive Summary

AI Collective must be a monthly presencial event skill with a chief of staff mindset. It should ask for the necessary inputs, think through the full operation, propose real options, and deliver ready-to-send text. It must be city agnostic, budget-aware, venue-approval-aware, and sponsorship-aware.

## 19. Recommended Next Step

Turn this PRD into the final skill package with:

- Objective.
- Scope.
- Inputs.
- Outputs.
- Workflow.
- Rules.
- Edge cases.
- Metrics.

Then convert it directly into the live skill structure.

