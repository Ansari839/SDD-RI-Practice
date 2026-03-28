# ADR-3: Source Requirements and Validation Criteria

> **Scope**: Document decision clusters, not individual technology choices. Group related decisions that work together (e.g., "Frontend Stack" not separate ADRs for framework, styling, deployment).

- **Status:** Accepted
- **Date:** 2025-11-28
- **Feature:** 001-k12-ai-efficiency
- **Context:** The research paper must meet high academic standards while ensuring the findings are current and relevant. We needed to establish strict source requirements and validation criteria to ensure credibility and reliability of the research.

## Decision

- Source Mix: 80% peer-reviewed academic journals, 20% reputable news sources
- Source Recency: Published within the last 10 years
- Evidence Requirements: Minimum 75% of claims supported by empirical studies
- Citation Format: APA 7th edition style
- Validation Rules: All evidence must be traceable to verified sources; quantitative metrics required for claims

## Consequences

### Positive

- High academic credibility through peer-reviewed sources
- Current relevance with 10-year recency constraint
- Balance between academic rigor and practical insights through news sources
- Clear quality standards that ensure reliable findings
- Traceable claims that support reproducibility

### Negative

- Some seminal works older than 10 years may be excluded
- Limited access to cutting-edge research if not in peer-reviewed format
- Potentially biased toward well-funded research areas
- Additional effort required to find sufficient sources meeting criteria
- May exclude valuable practical insights from non-academic sources

## Alternatives Considered

- 100% peer-reviewed journals: Would increase academic credibility but limit practical insights
- Include pre-2015 sources: Would add historical context but potentially reduce relevance
- Higher empirical study percentage: Would increase rigor but limit topics that could be covered
- Alternative citation styles (MLA, Chicago): Would conform to other academic standards but not APA required by spec

## References

- Feature Spec: C:\Abdullah\ai-native-exc\specs\001-k12-ai-efficiency\spec.md
- Implementation Plan: C:\Abdullah\ai-native-exc\specs\001-k12-ai-efficiency\plan.md
- Related ADRs: None
- Evaluator Evidence: research.md, data-model.md, quickstart.md