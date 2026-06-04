# Leadership Portfolio Redesign – Design Rationale

## Objective

The current Leadership Portfolio contains valuable performance data but presents it in a dashboard-oriented format. The redesign focuses on transforming the experience into a career portfolio that employees can easily understand, reflect on, and share with mentors or supervisors.

The goal was not to remove data, but to reorganize it into a narrative that answers four key questions:

1. How did I perform this month?
2. What did I contribute?
3. What challenges did I face?
4. What should I focus on next?

This approach aligns with the idea of a personal career artifact rather than a monitoring dashboard.

---

## Design Decisions

### 1. Replaced Metric-First Layout with Narrative-First Layout

The original structure presents multiple metrics with equal visual weight. This makes it difficult for employees to understand the overall story of their month.

The redesign introduces a hero section with a clear headline ("Strong Execution This Month") and a short summary. The employee can understand their overall performance within a few seconds before exploring detailed metrics.

Metrics remain available but serve as supporting evidence instead of being the primary focus.

### 2. Prioritized Contributions Before Detailed Performance Data

Employees generally care first about what they achieved rather than individual scores.

The "Shipped" section highlights key accomplishments and outcomes before displaying supporting metrics such as deliverables completed, delivery score, and knowledge contributions.

This creates a stronger sense of ownership and makes the portfolio feel more personal.

### 3. Reframed Constraints as Challenges

The original constraint data risks feeling negative or complaint-oriented.

Instead of presenting blockers as isolated issues, the redesign introduces a "Challenges Navigated" section. Resolved items are clearly distinguished from ongoing challenges, helping employees communicate problem-solving ability rather than simply listing obstacles.

### 4. Simplified Career Progression

The existing career data contains multiple projections, levels, and eligibility metrics.

The redesign condenses this information into a simple "Looking Forward" section showing:

* Current Level
* Next Milestone
* Projected Date
* Status
* Focus Areas

This allows employees to quickly understand where they are and what they should improve next.

---

## Information Hierarchy

The page follows a top-to-bottom storytelling structure:

Hero Section → Shipped → Challenges → Looking Forward

This hierarchy mirrors how people naturally reflect on their work:

* What happened?
* What did I accomplish?
* What got in the way?
* What's next?

By organizing information in this order, the portfolio becomes easier to read and more meaningful for employees, supervisors, mentors, and HR stakeholders.

---
## Tradeoffs Considered

I intentionally reduced the number of visible sections by merging growth-related insights into the "Looking Forward" section. This keeps the portfolio focused on a simple flow: performance, challenges, and future direction.

I also chose not to display every available metric. The backend contains significantly more data, but surfacing all of it would recreate the dashboard problem the redesign is trying to solve.

---

## Future Improvements

If given more time, I would explore:

* Expandable evidence sections for supervisors and HR.
* A visual career progression timeline.
* Month-over-month performance comparison.
* Mobile-first optimization for quick review.
