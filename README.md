# Task_07_Decision_Making

## Syracuse Women's Lacrosse: 2024 Season Performance Analytics
## Project Overview
This repository archives the statistical analysis conducted on the Syracuse University Women's Lacrosse 2024 season performance data. The primary objective was to derive actionable, data-driven recommendations for the coaching staff to inform strategic adjustments, optimize player training, and guide resource allocation for the upcoming season.

The analysis specifically focused on key areas identified by the initial data: offensive efficiency (overall and under pressure), and specialized possession roles (draw controls vs. caused turnovers).

1. Stakeholders and Decision Context
Field

Description

Target Audience

Syracuse Women's Lacrosse Coaching Staff and Athletic Director

Decision Context

Refining offensive/defensive strategies, finalizing player evaluations, and allocating training time (e.g., set-piece training vs. open-play drills).

Risk Level

Medium. Strategic changes carry risk to competitive outcomes, but no immediate high-stakes personnel decisions were required.

2. Data Source and Limitations
The analysis was performed on aggregated, end-of-season summary statistics.

Field

Description

Data Source

Internal Season Summary Statistics (Aggregated)

Key Limitation 1

Lack of Granularity: Data is aggregated per player for the entire season and per period for the team total.

Key Limitation 2

Unanswerable Questions: Due to aggregation, the analysis could not correlate individual scoring with opponent saves per period (clutch performance) or analyze individual home vs. away performance splits.

3. Analytical Methodology (LLM Assisted)
This project used a three-stage, LLM-assisted workflow to ensure comprehensive coverage, clear structuring, and concise output for the coaching staff:

Raw Analysis Generation: An LLM (Gemini) was used to process raw statistical questions and generate initial answers, calculations, and analytical interpretations.

Claim Verification and Annotation: The LLM's claims were manually verified against the raw dataset to confirm accuracy, especially for complex calculations (e.g., shooting percentages, identification of role leaders).

Stakeholder Report Formatting: The verified findings and strategic interpretations were structured into a formal, tiered report suitable for leadership, complete with an Executive Summary, clear Uncertainty Statement, and layered recommendations.

4. Key Findings and Tiered Recommendations
Key Findings
Offensive Vulnerability: The team exhibits a 9% efficiency drop on Free Position Shots (0.407) compared to Overall Shots (0.497).

Elite Efficiency: Riley Donahue (0.649) and Maddy Baxter (0.632) are the most efficient shooters among contributors (≥15 shots).

Specialized Roles: Kate Mashewske dominates Draw Controls (possession gain), while Katie Goodale dominates Caused Turnovers (possession disruption).

Recommendations
Tier

Action

Rationale

Risk Level

Operational

A. Strategic Free Position Training: Dedicate practice time to pressure-based free position execution drills.

Directly addresses the 9% scoring drop-off in high-stakes, set-piece scenarios.

Low

Operational

B. Leverage High-Efficiency Shooters: Design offensive sets to maximize quality shot opportunities for the most efficient shooters (Donahue, Baxter).

Optimizes team goal output by funneling shots to players with proven conversion rates.

Low

Investigatory

D. Implement Granular Data Tracking: Launch a system to log player statistics broken down by Period and Game Location (Home/Away).

Mandatory step to enable analysis of player consistency and clutch performance in the next season.

Medium

5. Repository Structure
README.md: This file.

stakeholder_report.md: The final, polished report generated for the coaching staff, including the Executive Summary and tiered recommendations.

analysis_transcript.txt: The raw LLM analysis, claim verification, and definition of the decision context.

data_notes.txt: Notes on the raw dataset's lineage and specific limitations.
