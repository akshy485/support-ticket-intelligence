# Support Ticket Intelligence - Salesforce Flow Automation

## Project Overview
Automated support ticket categorization and task creation logic built using Salesforce Autolaunched Flow.

## Flow Architecture & Logic
1. **Get Records:** Fetches Account and Ticket details.
2. **Decision Element:** Analyzes ticket description to determine priority (`High`, `Medium`, `Low`).
3. **Action & Assignments:**
   * Creates a high-priority Task record for senior agents when urgent issues are flagged.
   * Assigns `varPriorityLevel` and sets human-readable `varActionMessage` for downstream processing.

## Proof of Functionality (Debug Log)
![Flow Debug Proof](./Flow_Debug_Proof.png)

## Status
* **Execution:** Completed & Tested via Debug Run# support-ticket-intelligence
