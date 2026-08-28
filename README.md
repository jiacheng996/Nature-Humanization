# Nature Humanization

A reusable writing refinement skill for academic and general prose.

Nature Humanization helps revise text that feels formulaic, overly abstract, repetitive, defensive, or machine-like while preserving the author's intended meaning, factual content, data, citations, and technical claims.

It is designed for use with AI coding agents and other agent environments that support `SKILL.md`-based skills.

---

## Overview

Nature Humanization focuses on improving writing at the level of:

- sentence structure
- word choice
- paragraph flow
- argument presentation
- information density
- stylistic consistency
- unnecessary meta-language
- repetitive transitions
- mechanical rhetorical patterns
- abstract or vague wording

The goal is not to mechanically replace words or intentionally introduce errors.

The goal is to produce writing that is more direct, natural, precise, and professionally edited while preserving the substance of the original text.

---

## Two Modes

### Academic Mode

Academic Mode is intended for:

- academic papers
- journal manuscripts
- coursework
- research reports
- literature reviews
- empirical analysis
- policy analysis
- business analysis
- methodology sections
- results sections
- Discussion sections
- Conclusion sections
- academic Markdown, Word, and LaTeX content

Academic Mode places particular emphasis on preserving:

- numerical values
- statistical results
- citations and references
- variable names
- model specifications
- factual claims
- technical terminology
- research logic

It also contains detailed guidance for organizing academic arguments around the strongest defensible contribution and supporting evidence.

Rules:

`Nature—Humanization—Academic.md`

---

### General Mode

General Mode is intended for non-academic or less technically demanding writing that still needs refinement.

It focuses on reducing common signs of formulaic writing, including:

- excessive transitional phrases
- repetitive sentence structures
- unnecessary defensive language
- abstract management-style vocabulary
- empty introductory phrases
- unnatural nominalization
- mechanical three-part structures
- excessive rhetorical symmetry
- unnecessary symbols and formatting
- unsupported metaphors or invented concepts

Rules:

`Nature—Humanization—General.md`

---

## Repository Structure

```text
Nature-Humanization/
├── SKILL.md
├── Nature—Humanization—Academic.md
├── Nature—Humanization—General.md
└── README.md
```

`SKILL.md` is the main entry point.

It determines whether Academic Mode or General Mode should be used and directs the agent to the corresponding rule file.

---

## Installation

### Option 1: Clone the Repository

```bash
git clone https://github.com/jiacheng996/Nature-Humanization.git
```

Then place the repository in the skills directory used by your agent environment.

For environments that recognize the cross-runtime Agent Skills directory, this may be:

```text
~/.agents/skills/Nature-Humanization/
```

The resulting structure should look like:

```text
~/.agents/skills/Nature-Humanization/
├── SKILL.md
├── Nature—Humanization—Academic.md
├── Nature—Humanization—General.md
└── README.md
```

### Option 2: Download Manually

Download the repository as a ZIP from GitHub, extract it, and move the extracted `Nature-Humanization` folder into the skills directory recognized by your agent environment.

---

## Usage

Once installed, the skill can be triggered when asking an agent to revise or refine existing writing.

Example prompts:

```text
Use Nature Humanization to revise this academic paper.
```

```text
Humanize this section while preserving all citations, data, and statistical results.
```

```text
Rewrite this paragraph to sound more natural and less formulaic.
```

```text
Polish this Discussion section using the academic humanization rules.
```

```text
Make this text more natural while preserving its original meaning.
```

For academic or research-oriented material, Academic Mode should normally be selected.

For ordinary prose, General Mode should normally be selected.

---

## Core Principles

### Preserve Substance

Do not invent or alter facts, evidence, statistics, citations, methods, results, or technical claims.

### Prefer Concrete Language

Use specific nouns, verbs, facts, methods, and results instead of vague abstractions.

### Reduce Unnecessary Self-Explanation

Writing should normally state the actual argument, result, or evidence instead of explaining how the writing itself is organized.

### Avoid Mechanical Patterns

Repeated transitions, symmetrical sentence structures, forced three-part lists, and standardized paragraph endings should be reduced when they do not serve the content.

### Maintain Professional Rigor

Naturalization should not make academic or professional writing casual, imprecise, or less technically correct.

### Let Evidence Carry the Argument

Concrete results should support claims directly rather than relying on exaggerated evaluative language.

---

## Important Note

Nature Humanization is a writing and editing framework.

It is not intended to fabricate authorship, invent evidence, manipulate research results, or guarantee outcomes from automated AI-detection systems.

Its purpose is to improve writing quality, naturalness, precision, clarity, and presentation while preserving the underlying content.

---

## Version

Current version: **1.0**

The Academic and General rule sets may continue to evolve as additional writing patterns and editing cases are identified.

---

## Contributing

Suggestions, issues, and improvements are welcome.

If you identify a recurring formulaic writing pattern or a useful editing rule that could improve the skill, feel free to open an Issue or submit a Pull Request.

---

## Author

Created and maintained by [jiacheng996](https://github.com/jiacheng996).

---

## License

No license has currently been specified.
