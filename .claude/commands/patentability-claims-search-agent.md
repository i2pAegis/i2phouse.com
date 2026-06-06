---
name: patentability-claims-search-agent
description: "Run a structured patentability, prior-art, claim-element, and mock office-action workflow for patent-pending inventions such as AEGIS. Use when the user wants examiner-style patent search planning, prior art mapping, claim charting, obviousness analysis, or prosecution-prep materials."
license: Proprietary user workflow
metadata:
  version: "1.0"
  owner_context: "Created for the user's patent-pending AEGIS IP workflow"
---

# Patentability Claims Search Agent

## When to Use This Skill

Use this skill when the user wants to assess, strengthen, or prepare prosecution strategy for a patent-pending invention through structured prior-art research and examiner-style claim testing.

Apply it for requests such as:

- "Run a patentability search for my invention."
- "Search prior art against these claims."
- "Create claim charts."
- "Find novelty and obviousness risks."
- "Prepare mock office actions."
- "Help strengthen my patent-pending IP."
- "Build a patent search plan for AEGIS."

Do not present the output as a legal opinion. The deliverables are attorney-review research materials and prosecution-prep work product.

## Core Operating Principles

1. **Protect confidentiality.** Ask the user whether they want to use only local/private files, public web search, or a limited redacted disclosure before searching. Do not reveal confidential invention details in public queries unless the user approves that level of disclosure.
2. **Mirror examiner behavior.** Search broadly first, then classify, then test claim elements, then construct novelty and obviousness rejections.
3. **Claim-first analysis.** Always anchor the search to the user's baseline independent claim or a provisional draft claim created from their invention disclosure.
4. **Evidence over confidence.** Every prior-art assertion must identify the document, publication number or title, source URL if available, relevant passages or claim numbers, and the specific claim element it maps to.
5. **Iterate.** After identifying vulnerable claim elements, revise search queries and propose claim amendments or fallback dependent claims.
6. **Attorney handoff.** Mark all legal-risk conclusions as preliminary and recommend review by a registered patent attorney or patent agent, especially before filing, amendment, IDS strategy, or prosecution response.

## Required Inputs

Before running the full workflow, collect:

1. **Invention identity**
   - Project or invention name
   - Technical field
   - Jurisdiction focus, such as U.S., PCT, EU, or global
   - Filing status, including provisional, non-provisional, PCT, pending, office action received, or continuation planning

2. **Disclosure materials**
   - Plain-English invention description
   - Diagrams, flowcharts, architecture, screenshots, prototypes, or product documentation
   - Existing provisional or non-provisional application, if available
   - Draft claims, if available
   - Known competitors, products, standards, papers, patents, or inventors

3. **Business context**
   - Commercially critical embodiments
   - Must-protect features
   - Optional or fallback features
   - Known design-arounds to prevent

4. **Search constraints**
   - Whether web search is allowed
   - Whether confidential details may be used in search queries
   - Deadline and desired depth
   - Whether the output is for internal review, attorney handoff, investor diligence, or grant support

## Workflow

### Phase 1: Intake and Invention Decomposition

Create an intake summary with:

- One-paragraph invention description
- Problem solved
- Technical effect or advantage
- Core inventive concept
- Differentiating features
- Commercially important embodiments
- Known alternatives or design-arounds
- Terms that should not be disclosed in public searches without approval

If draft claims are missing, create a rough working claim set for search purposes only:

- One broad independent system, method, or computer-readable-medium claim as applicable
- Five to ten dependent claim candidates
- A glossary of key terms and synonyms

### Phase 2: Baseline Claim Breakdown

Break the independent claim into an element table:

| Element ID | Claim limitation | Plain-English meaning | Required evidence | Search keywords | CPC/IPC clues | Notes |
|---|---|---|---|---|---|---|
| 1A | Preamble | What the invention is | Similar field/use case | Synonyms | TBD | |
| 1B | First structural or functional limitation | What must be disclosed | Exact or equivalent disclosure | Synonyms | TBD | |

Rules:

- Use atomic elements. Split compound limitations into separate sub-elements.
- Preserve exact claim text where available.
- Identify whether each element is structural, functional, data-processing, user-interface, hardware, network, training, model, control, or workflow related.
- Flag means-plus-function or purely result-oriented language for attorney review if applicable.

### Phase 3: Broad Landscape Search

Run broad searches to learn terminology and locate seed references.

Search sources:

- Patent databases: Google Patents, USPTO Patent Center or PatFT/AppFT where available, Espacenet, WIPO Patentscope, Lens.org
- Non-patent literature: Google Scholar, arXiv, PubMed if biomedical, IEEE/ACM if computing, standards bodies, technical blogs, product manuals, open-source repositories, theses, conference proceedings
- Competitive landscape: company websites, product docs, press releases, white papers, marketplace listings

Search strategy:

- Generate keyword families for problem, solution, components, workflow, outputs, and technical effect.
- Vary synonyms, acronyms, and adjacent technical vocabulary.
- Search by known competitors, inventors, assignees, products, and standards.
- Save all seed references into a key-document pool.

Output:

| Ref ID | Title | Publication / Patent No. | Assignee / Author | Date | Source URL | Why it matters | Initial relevance |
|---|---|---|---|---|---|---|---|

### Phase 4: Classification Expansion

From seed patent references:

1. Extract repeated CPC and IPC classes.
2. Read class definitions.
3. Translate class language into additional natural-language search terms.
4. Search within repeated classes using element-specific keywords.
5. Identify neighboring classes where the same problem may be solved with different terminology.

Output:

| Class | Definition | Found in refs | Why relevant | Derived keywords | Search results |
|---|---|---|---|---|---|

### Phase 5: Element-by-Element Prior Art Search

For each claim element:

1. Search element-specific terms alone.
2. Search element terms combined with field/problem terms.
3. Search element terms within relevant CPC/IPC classes.
4. Search seed references using "similar patents," cited-by, references-cited, and family-member expansion.
5. Search non-patent literature for equivalent disclosures.

Create a claim chart:

| Claim element | Best matching reference | Passage / claim / figure | Match strength | Gap | Notes |
|---|---|---|---|---|---|
| 1A | | | Exact / Partial / Analogous / Missing | | |

Match strength definitions:

- **Exact:** The reference appears to disclose the limitation directly.
- **Partial:** The reference discloses part of the limitation but lacks a meaningful component.
- **Analogous:** The reference uses a similar concept in a different context or with different implementation details.
- **Missing:** No disclosure found yet.

### Phase 6: Anticipation Risk Analysis

Assess whether any single reference discloses every limitation of the independent claim.

For each close reference:

| Reference | Elements disclosed | Elements missing | Anticipation risk | Rationale |
|---|---|---|---|---|

Use this scale:

- **High:** A single reference appears to disclose every material element.
- **Medium:** A single reference discloses most elements, with arguable equivalence or implicit disclosure for the rest.
- **Low:** Important elements are missing or materially different.

### Phase 7: Obviousness Combination Analysis

Identify primary references and secondary references.

For each dangerous combination:

| Combination | Primary reference | Secondary reference(s) | Missing element supplied | Motivation to combine | Obviousness risk | Rebuttal angle |
|---|---|---|---|---|---|---|

Ask examiner-style questions:

- Are the references in the same or analogous field?
- Do they solve the same problem?
- Would the secondary feature predictably improve the primary reference?
- Is there explicit teaching, suggestion, market pressure, standardization, or design incentive to combine them?
- Does the invention produce an unexpected technical result or solve a problem the art did not recognize?
- Are there teaching-away statements, incompatibilities, or implementation barriers?

Risk scale:

- **High:** Combination appears straightforward, predictable, and well-motivated.
- **Medium:** Combination possible, but motivation or compatibility is debatable.
- **Low:** Combination requires hindsight, field mismatch, technical incompatibility, or changes the principle of operation.

### Phase 8: Mock Office Action

Draft a mock examiner report containing:

1. Summary of searched subject matter
2. Search strings and classification fields used
3. Closest references
4. Novelty rejection candidates
5. Obviousness rejection candidates
6. Claim objection or clarity issues
7. Suggested claim amendments
8. Rebuttal arguments
9. Dependent claim fallback strategy

Use this format:

```markdown
## Mock Rejection

Claim(s): [claim numbers]
Basis: Preliminary novelty / obviousness risk
Reference(s): [references]
Element mapping: [claim elements and citations]
Examiner-style rationale: [why an examiner may reject]
Applicant response options:
- Argument:
- Amendment:
- Fallback dependent claim:
- Evidence to develop:
```

### Phase 9: Claim Refinement

Propose amendments in three tiers:

1. **Broad but stronger:** Keeps commercial breadth while clarifying the differentiator.
2. **Moderate fallback:** Adds a technically meaningful implementation detail.
3. **Narrow fallback:** Protects the most defensible commercial embodiment.

For each proposed amendment:

| Amendment | Prior-art problem addressed | Commercial impact | New search needed | Attorney review notes |
|---|---|---|---|---|

Re-run searches on materially revised claim language before finalizing recommendations.

### Phase 10: Final Deliverables

Produce a concise executive summary and detailed appendices.

Required deliverables:

1. **Patentability Search Report**
   - Invention summary
   - Search scope and limitations
   - Search strings and databases
   - Key references
   - Closest prior art
   - Novelty risk
   - Obviousness risk
   - Claim-strengthening recommendations

2. **Claim Chart**
   - Element-by-element mapping against key references

3. **Mock Office Action**
   - Examiner-style novelty and obviousness rejections
   - Response and amendment options

4. **Prior Art Data Pool**
   - Table of all relevant references, URLs, dates, relevance notes, and classifications

5. **Attorney Handoff Memo**
   - Open legal questions
   - Claim amendments requiring counsel review
   - IDS candidate references for counsel consideration
   - Filing/prosecution strategy considerations

## Confidentiality Modes

Use one of these modes before searching:

### Mode A: Private Document Analysis

Use this when the user provides local or uploaded patent materials and does not approve public query disclosure.

- Analyze documents locally.
- Generate generalized search terms that avoid confidential specifics.
- Ask before using any exact confidential phrase in external search.

### Mode B: Redacted Public Search

Use this when public search is allowed but sensitive details must remain private.

- Replace confidential nouns, product names, datasets, model architectures, or proprietary workflows with generic descriptors.
- Search by field, problem, and broad mechanism.
- Keep a redaction map for internal analysis.

### Mode C: Full Public Search

Use this only if the user confirms that the relevant invention details are already public or safe to disclose.

- Search using exact technical terms.
- Include exact claim phrases if helpful.
- Still avoid sharing unpublished business strategy unless necessary.

## Output Quality Checklist

Before finalizing:

- Every claim element has at least one targeted search attempt.
- Every key reference has a date, title, source, and relevance rationale.
- All high-risk references are claim-charted.
- Obviousness combinations are separated from single-reference novelty risks.
- Proposed amendments are tied to specific prior-art gaps.
- Non-patent literature was searched or explicitly excluded with a reason.
- Confidentiality mode is stated.
- Limitations and next-search recommendations are stated.
- Attorney review disclaimer is included.

## Standard Disclaimer

This workflow provides research, drafting, and prosecution-preparation support. It is not a legal opinion, does not determine patentability, validity, infringement, or freedom to operate, and should be reviewed by a registered patent attorney or patent agent before filing, amending, submitting an IDS, or making business decisions based on the results.
