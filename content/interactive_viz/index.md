---
title: Interactive visualizations

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---

Here are some interactive visualizations related to my research on rights mobilization by parents of students with disabilities.

# What do districts versus parents emphasize in disputes about disability services?

This visualization focuses on [Endrew F. v. Douglas County School District](https://sites.ed.gov/idea/questions-and-answers-qa-on-u-s-supreme-court-case-decision-endrew-f-v-douglas-county-school-district-re-1/#citem_87f6-1462), an important Supreme Court case about what standard of benefit districts owe students with disabilities. More specifically, the case addressed a circuit split in the substantive definition of what constitutes a Free and Appropriate Public Education (FAPE) for students with disabilities. The Tenth Circuit had defined the standard of benefit as "some educational benefit," which they interpreted as something more than a "de minimis" educational benefit. In contrast, the Second, Third, and Sixth Courts of Appeals had adopted a higher standard: services calculated to enable "meaningful educational benefit." The plaintiffs in *Endrew* were the parents, and many disability advocacy groups filed amicus briefs on their behalf. The defendant was the school district, and amicus briefs on their side included professional groups representing school district administrators.

Code in [this Github repo](https://github.com/rebeccajohnson88/endrew_amicusbriefs):

1. Parses the amicus briefs into a document-term matrix
2. Visualizes three sets of words: words overrepresented in briefs filed in support of the parents, words overrepresented in briefs filed in support of the district, and words with similar representation across both briefs

**Visualization**: https://rjohnson.shinyapps.io/endrew_amicus_visualize

**Interpretation**: briefs in favor of the district focus on pragmatic considerations, like the workability of a new standard and themes of judicial deference (arguing that the Supreme Court should defer to elected officials to raise the standard). Meanwhile, briefs in favor of the parents focus on considerations of achievement gaps for students with disabilities and the importance of services for developmental milestones.

# How does parent mobilization spread over time?

This visualizes summarizes requests for due process hearings by parents in New Jersey over a several-year period. It shows the spread of these claims over time and their distribution across districts with different levels of poverty.

**Visualization**: https://rjohnson.shinyapps.io/nj_dp_visualize