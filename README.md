# LandingPad 🛫
 
**An AI-powered financial transition planner for international students entering the US**
 
🔗 [Try the live app on Amazon PartyRock](https://partyrock.aws/u/ChukwuemekaCoder/cBbeTz6H_/LandingPad%253A-Your-US-Student-Finance-Guide)
 
---
 
## Overview
 
LandingPad helps international students (F-1/J-1 visa holders) navigate the financial challenges of their first 1-2 years in the US. Most budgeting tools assume users already have a US bank account, credit history, and steady income — none of which is guaranteed for someone newly arrived. LandingPad treats those constraints as the starting point, generating a personalized roadmap based on each student's actual visa status, income sources, and housing situation.
 
## Why I Built This
 
As an international student, I noticed that the financial transition to the US involves a lot of invisible friction: SSN delays, the 20-hour/week work cap, summer housing gaps when dorms close, international wire transfer fees, and building credit from zero. None of this is covered by mainstream financial apps. I wanted to build something that addresses these realities directly.
 
## How It Works
 
LandingPad is built on Amazon PartyRock and chains together four AI widgets, each building on the output of the last:
 
### 1. Student Profile Input
Collects structured information including visa type, country of origin, program dates, SSN status, on/off-campus work authorization, family financial support, savings, tuition coverage, housing, and access to banking/phone/transportation.
 
### 2. Hidden Costs Identifier
Analyzes the student's profile to surface costs that are easy to overlook, such as:
- International wire transfer fees
- Mandatory international student health insurance
- Summer housing gaps
- First apartment deposits without US credit history
- SIM/phone setup without credit history
- Visa renewal and SEVIS fees
- Transportation costs without a car
### 3. Income vs. Expense Gap Analyzer
Calculates monthly income (family support + capped on-campus wages) against estimated expenses, flagging high-risk months — particularly summer breaks, the first 1-2 months before banking/credit is established, and tuition due dates.
 
### 4. 1-2 Year Roadmap Generator
Produces a phased roadmap with concrete financial milestones:
- **Phase 1 (Months 1-3):** Arrival & setup — bank account, SSN, SIM card, emergency fund
- **Phase 2 (Months 4-9):** Stabilization — credit building, summer planning
- **Phase 3 (Months 10-18):** Growth — CPT/internship search, savings targets
- **Phase 4 (Months 19-24):** Transition readiness — OPT prep, job search runway
### 5. "What If" Scenario Tool
Lets users stress-test their plan against real situations like losing on-campus work, family support gaps, or unexpected expenses — and adjusts the roadmap accordingly.
 
## What This Project Demonstrates
 
- **Prompt engineering** — designing chained, structured prompts that pass context between steps
- **Product design** — identifying an underserved audience and scoping a solution around their real constraints
- **Workflow automation** — breaking a complex, repeatable process into discrete, reusable steps rather than relying on a single open-ended chatbot exchange
## Sample Input
 
```
Visa type: F-1
Country of origin: Nigeria
Program dates: Aug 2025 - May 2027
SSN status: Not applied
On-campus job: Part-time secured, 12 hrs/week
Off-campus work auth: CPT eligible after first year
Monthly family support: $300
Current savings: $1,500
Tuition: Partially covered (60% scholarship), $4,500/semester self-paying
Housing: Dorm
US bank account: No
US phone plan: No
Transportation: None
```
 
## Disclaimer
 
LandingPad is a planning tool, not professional financial or immigration advice. All cost estimates are approximations and vary by region, university, and individual circumstances.
 
