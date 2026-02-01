# Working Backwards Doc Coach - User Guide

**What is this skill?**

Working Backwards Doc Coach helps product builders create rigorous, customer-first documentation that forces clear thinking about whether an idea is worth building. It produces PR/FAQ documents, experience narratives, and critical evaluations based on evidence, not vibes.

## When to Use This Skill

Use this skill when you want to:
- Evaluate whether a product idea is worth pursuing
- Write a Press Release / FAQ (PR/FAQ) document
- Create "working backwards" documentation
- Validate product-market fit for a feature
- Think critically about customer value and business viability
- Plan customer research to validate assumptions

## What You'll Get

The skill produces a comprehensive 1-2 page document (in both Markdown and Word format) containing:

1. **Press Release** - Written as if the product exists, focused on customer benefit
2. **FAQ** - Both customer-facing and internal questions answered
3. **Customer Experience Narrative** - Before/after journey showing specific improvements
4. **Competitive Analysis** - How this compares to current solutions
5. **Assumptions & Evidence Plan** - What you're assuming and how to validate it
6. **Critical Review** - Honest assessment across Value, Usability, Feasibility, and Business Viability

## How to Use It

**Step 1: Describe your product idea**

Just tell Claude about your idea. The skill works best when you provide:
- Who the customer is (be specific - "IT managers at 100-500 person SaaS companies" not just "users")
- What problem they have or opportunity exists
- What the main benefit would be
- Any evidence you already have (or lack thereof)

**Don't worry if you don't have all the details** - the skill will make explicit assumptions and highlight what questions need answers.

**Step 2: Review the draft**

Claude will produce a comprehensive draft with critical evaluation. The "Critical Review" section will honestly assess:
- Whether this is a "must-have" vs "nice-to-have"
- What evidence is missing
- What assumptions need validation
- Whether to Build, Investigate, Pivot, or Kill the idea

**Step 3: Refine**

Based on the draft, you can:
- Provide more details to update assumptions
- Focus on specific sections that need work
- Challenge the critique if you disagree
- Request research plans to validate key assumptions

## Example Requests

Here are ways you might trigger this skill:

- "Help me write a PR/FAQ for a new dashboard feature"
- "Should we build a mobile app for our platform?"
- "I want to create a working-backwards doc for AI-powered email sorting"
- "Can you help me think through whether customers would pay for X?"
- "Evaluate this product idea: [description]"

## Key Philosophy

This skill is designed to:
- **Force customer perspective** - No internal jargon or feature lists until the customer benefit is crystal clear
- **Demand evidence** - Every assumption is labeled; proposed validation methods are concrete
- **Think critically** - The skill won't parrot back your idea with enthusiasm - it will challenge weak value props and ask hard questions
- **Keep it concise** - 1-2 pages maximum, every sentence earns its place
- **Enable decisions** - The output should help you decide: Build? Investigate further? Pivot? Or kill?

## What Makes This Different

Unlike a typical PRD or product brief, this skill:
- Starts with the end-state **customer experience**, not features
- Explicitly separates **evidence from assumptions**
- Provides a **critical evaluation**, not just documentation
- Forces **10x thinking**, not 10% improvements
- Stays **executive-friendly** - concise, decision-oriented, no fluff

## Tips for Best Results

1. **Be specific about the customer** - "Sarah, VP of Engineering at a 200-person fintech startup" is better than "developers"

2. **Don't hide uncertainty** - If you don't have evidence, say so. The skill will help you figure out what to learn.

3. **Embrace the critique** - The "Critical Review" section is meant to surface risks early. Pushback on it if you disagree, but don't ignore it.

4. **Think 10x, not 10%** - If your differentiation is marginal, the skill will call that out.

5. **Focus on one primary customer** - Multi-sided markets are fine, but pick the primary customer first.

## Installation

1. Upload the `working-backwards-coach.skill` file to Claude
2. The skill will automatically activate when you ask product strategy or validation questions
3. Start by describing your product idea

## Questions or Feedback?

This skill follows Amazon's "Working Backwards" methodology adapted for product builders at any company. It's designed to help you build winning products by thinking backwards from customer value.

If the skill isn't quite meeting your needs, describe what's missing and Claude can help refine the documentation or adjust the approach.
