# DeepThought Round 1 Assignment

## Candidate

Vishal Jadhav

## Objective

Identify Pune-based manufacturing companies matching the "Federer Company" profile in the following segments:

1. Industrial Sensors & Instrumentation
2. Precision Auto Components & Engineering

## Repository Structure

```text
.
├── companies_pass.csv
├── companies_fail.csv
├── methodology.md
├── sourcing_strategy.md
├── 1000_company_plan.md
└── handdrawn_diagram.jpg
```

## Deliverables

### 1. Qualified Companies

File:
`companies_pass.csv`

Contains researched companies with:

* Company details
* Revenue information
* Decision-maker information
* Federer scoring
* Evidence collected from public sources

### 2. Rejected Companies

File:
`companies_fail.csv`

Contains companies rejected due to:

* Revenue exceeding limits
* Subsidiary ownership
* Distributor/trader status
* Geography mismatch

### 3. Research Methodology

File:
`methodology.md`

Explains:

* Research process
* Qualification criteria
* Verification process
* Hallucination controls

### 4. Sourcing Strategy

File:
`sourcing_strategy.md`

Explains:

* Research sources used
* Company discovery process
* Qualification workflow

### 5. 1000 Company Scaling Plan

File:
`1000_company_plan.md`

Describes:

* Discovery funnel
* AI-assisted research process
* Verification workflow
* Scaling approach

## AI Usage & Hallucination Controls

AI was used as a research assistant.

Controls applied:

* Cross-verification across multiple sources
* Rejection of unsupported claims
* Separate fail list maintained
* Missing information marked as "Needs Verification"
* No revenue estimates created without evidence

## Limitations

Many private manufacturing SMEs do not publicly disclose revenue information.

Where sufficient evidence was unavailable, data was marked as "Needs Verification" instead of making assumptions.

## Sources Used

* Company Websites
* LinkedIn
* IndiaMART
* ExportersIndia
* TradeIndia
* Tracxn
* ZaubaCorp

## Submission Note

The objective of this assignment was approached with a focus on verification, transparency, and reducing AI hallucination. All unverifiable information has been explicitly flagged rather than inferred.
