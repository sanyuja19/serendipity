# SPEC-003

# SERENDIPITY Design System

Version: 1.0

Status: Draft

Classification: Core Design Specification

Priority: Critical

Project: SERENDIPITY

Author: Sanyuja Sonkuwar
# Executive Summary

The SERENDIPITY Design System defines the complete visual and interaction language of the platform.

Its purpose is to ensure every screen, component, interaction, animation, and AI workflow provides a consistent experience.

The design system is not a collection of UI components.

It is the visual representation of SERENDIPITY's philosophy.

Every design decision should communicate clarity, trust, curiosity, intelligence, and scientific exploration.
# Design Philosophy

SERENDIPITY is designed around one simple belief:

Complex technology should feel effortless.

Researchers should never think about the interface.

They should think about their ideas.

The interface exists to remove friction from scientific thinking.

Design should disappear into the background while enabling powerful research workflows.
# Product Personality

If SERENDIPITY were a person, it would be:

• Curious

• Intelligent

• Calm

• Trustworthy

• Scientific

• Helpful

• Elegant

• Humble

The interface should reflect these qualities at every interaction.

SERENDIPITY never feels loud.

It never feels playful for the sake of entertainment.

It never feels overwhelming.

Instead,

it creates confidence through simplicity.
# Emotional Design Goals

Every major interaction should create a specific emotional response.

Opening Dashboard

↓

Confidence

---

Uploading Papers

↓

Curiosity

---

Watching AI Work

↓

Anticipation

---

Knowledge Fabric Growing

↓

Discovery

---

Finding New Connections

↓

Excitement

---

Reading AI Reasoning

↓

Trust

---

Exporting Research

↓

Achievement

The interface should support these emotions through typography, spacing, color, animation, and interaction timing.
# Design Principles

The SERENDIPITY interface follows eight core principles.

---

## Principle 1

Clarity Before Decoration

Every element should have a purpose.

---

## Principle 2

Whitespace Creates Focus

Content should breathe.

Spacing is considered an active design element.

---

## Principle 3

Motion Guides Attention

Animations should communicate state changes.

Never distract.

---

## Principle 4

Information Before Controls

Researchers care about knowledge.

Controls should remain secondary.

---

## Principle 5

Consistency Creates Trust

Identical interactions should always behave identically.

---

## Principle 6

Accessibility Is Built-In

Accessibility is a design requirement.

Not an enhancement.

---

## Principle 7

Progress Should Always Be Visible

Users should understand what the platform is doing.

---

## Principle 8

AI Should Feel Collaborative

Never magical.

Never mysterious.

Always understandable.
# Product Keywords

Every future design decision should reinforce these words.

Scientific

Elegant

Minimal

Professional

Calm

Focused

Intelligent

Discoverable

Transparent

Modern
# Visual Identity Goals

The product should feel like:

A premium research platform.

Not:

• Social media

• Gaming software

• Consumer AI chatbot

• Analytics dashboard

• Generic SaaS template

Instead,

SERENDIPITY should combine the visual confidence of modern developer tools with the clarity of scientific software.
# Inspiration

SERENDIPITY learns from great products without copying them.

Perplexity

→ Evidence-first AI

---

Linear

→ Minimal interface

---

Notion

→ Information organization

---

Cursor

→ AI collaboration

---

Figma

→ Workspace thinking

---

Obsidian

→ Connected knowledge

---

Connected Papers

→ Research visualization

---

Semantic Scholar

→ Scientific workflow

The goal is not imitation.

The goal is learning proven interaction patterns.
# Design Mission

Every screen should answer one question:

"What helps the researcher think more clearly?"

If an interface element does not improve thinking,

it should be redesigned or removed.

Design is successful when users stop noticing the interface and begin noticing their own discoveries.
# 2. Visual Language

## 2.1 Visual Direction

SERENDIPITY SHALL use a visual language combining:

- Scientific precision
- Premium software aesthetics
- Editorial clarity
- Subtle technological depth
- Calm visual hierarchy

The interface SHALL avoid excessive gradients, excessive glassmorphism, decorative illustrations, noisy backgrounds, and unnecessary visual effects.

Visual complexity should be introduced only when it communicates meaningful information.

---

# 2.2 Brand Color Philosophy

The SERENDIPITY color system is based on the concept of:

Deep Space + Scientific Light + Discovery Accent

The primary visual environment should feel dark, focused, and immersive while maintaining excellent readability.

The system SHALL support both:

- Dark Mode
- Light Mode

Dark Mode is the primary product experience.

Light Mode is a fully supported alternative rather than a secondary afterthought.

---

# 2.3 Primary Color Family

Primary Brand Color:

Indigo / Scientific Violet

Purpose:

- Primary actions
- Active navigation
- Focus states
- AI-related interactions
- Selected elements

Recommended foundation:

Primary 500: #6366F1

Primary 600: #4F46E5

Primary 700: #4338CA

Primary 400: #818CF8

Primary 300: #A5B4FC

These values are initial design tokens and may be refined during visual prototyping.

---

# 2.4 Discovery Accent

SERENDIPITY SHALL use a secondary accent representing discovery and knowledge emergence.

Recommended family:

Emerald / Teal

Primary Discovery:

#10B981

Secondary Discovery:

#14B8A6

Discovery accents SHALL be used selectively.

They should represent:

- Newly discovered relationships
- Positive validation
- Knowledge connections
- Successful analysis
- Novel insights

Discovery color should never dominate the interface.

---

# 2.5 Semantic Colors

The interface SHALL define semantic colors independently from brand colors.

Success:

#22C55E

Warning:

#F59E0B

Error:

#EF4444

Information:

#3B82F6

Discovery:

#10B981

Neutral:

Slate-based palette

Semantic colors SHALL communicate state rather than decoration.

---

# 2.6 Dark Mode

Dark Mode is the primary SERENDIPITY experience.

Recommended foundation:

Background:

#09090B

Surface:

#111113

Elevated Surface:

#18181B

Border:

#27272A

Primary Text:

#FAFAFA

Secondary Text:

#A1A1AA

Muted Text:

#71717A

The darkest surfaces should be reserved for the application background.

Cards, panels, and workspace surfaces should use subtle elevation through color and borders rather than heavy shadows.

---

# 2.7 Light Mode

Light Mode SHALL use a warm-neutral scientific aesthetic rather than pure white everywhere.

Background:

#FAFAFA

Surface:

#FFFFFF

Secondary Surface:

#F4F4F5

Border:

#E4E4E7

Primary Text:

#18181B

Secondary Text:

#52525B

Muted Text:

#71717A

The interface must maintain equivalent information hierarchy between Dark and Light modes.

---

# 2.8 Typography

SERENDIPITY SHALL use a modern sans-serif typeface for interface content.

Primary Typeface:

Inter

Fallback:

system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif

Typography should prioritize:

- Readability
- Dense information presentation
- Long research sessions
- Clear hierarchy

---

# 2.9 Typography Hierarchy

Display:

48-64px

Weight:

600-700

Usage:

Landing page hero

---

Heading 1:

36-48px

Weight:

600-700

Usage:

Major page titles

---

Heading 2:

28-36px

Weight:

600

Usage:

Section titles

---

Heading 3:

20-24px

Weight:

600

Usage:

Cards and subsections

---

Body Large:

18px

Weight:

400

Usage:

Important explanatory content

---

Body:

14-16px

Weight:

400

Usage:

Primary interface content

---

Caption:

12-13px

Weight:

400-500

Usage:

Metadata and secondary information

---

Code / Technical:

JetBrains Mono

Usage:

- API identifiers
- Technical metadata
- Research identifiers
- Code
- System logs

---

# 2.10 Typography Rules

The interface SHALL NOT use more than two primary typefaces.

Typography SHALL communicate hierarchy through:

- Size
- Weight
- Color
- Spacing

Text should never rely exclusively on color to communicate hierarchy.

Long-form research content should use comfortable line heights.

Recommended body line height:

1.5-1.7

---

# 2.11 Spacing System

SERENDIPITY SHALL use an 8-point spacing system.

Base unit:

8px

Allowed spacing values:

4px
8px
12px
16px
24px
32px
40px
48px
64px
80px
96px

The 4px value is reserved for micro-spacing.

Components should avoid arbitrary spacing values whenever possible.

---

# 2.12 Layout Grid

Desktop:

12-column grid

Tablet:

8-column grid

Mobile:

4-column grid

Standard page horizontal padding:

Desktop:

32px

Large Desktop:

48px

Tablet:

24px

Mobile:

16px

---

# 2.13 Responsive Breakpoints

Small Mobile:

< 640px

Mobile:

640px

Tablet:

768px

Desktop:

1024px

Large Desktop:

1280px

Wide:

1536px

The application SHALL remain usable across all supported viewport sizes.

---

# 2.14 Border Radius

SERENDIPITY should use restrained corner rounding.

Small:

6px

Medium:

8px

Large:

12px

Extra Large:

16px

Full:

9999px

Large rounded containers should be reserved for major surfaces and intentional visual grouping.

---

# 2.15 Elevation

SERENDIPITY SHALL use subtle elevation.

Elevation should primarily be communicated through:

1. Surface color
2. Border contrast
3. Minimal shadow

Heavy shadows SHALL be avoided.

Recommended levels:

Level 0:

Flat surface

Level 1:

Subtle card

Level 2:

Floating panel

Level 3:

Modal / command interface

---

# 2.16 Iconography

SERENDIPITY SHALL use one consistent icon family.

Recommended:

Lucide Icons

Icons should:

- Remain visually lightweight
- Use consistent stroke width
- Never replace important text labels when meaning could be ambiguous
- Support tooltips where necessary

Icons should communicate functionality rather than decoration.

---

# 2.17 Visual Density

SERENDIPITY is an information-rich research platform.

However, information density SHALL remain controlled.

The interface should support:

Focused Density

rather than:

Maximum Density

Users should be able to scan:

- Papers
- Concepts
- Citations
- AI activity
- Graph relationships
- Research findings

without feeling overwhelmed.

---

# 2.18 Background Treatment

The primary background should remain visually quiet.

Optional subtle effects may include:

- Extremely low-opacity radial gradients
- Soft scientific grid patterns
- Subtle node-like textures

These effects SHALL remain below the user's primary attention layer.

Decorative backgrounds must never interfere with readability.

---

# 2.19 Gradient Rules

Gradients are permitted but should be used sparingly.

Acceptable uses:

- Landing page hero
- Brand illumination
- Discovery highlights
- AI processing states
- Major visual transitions

Unacceptable uses:

- Every card
- Every button
- Every heading
- Backgrounds behind dense research content

SERENDIPITY should never look like a gradient showcase.

---

# 2.20 Accessibility

All colors SHALL meet appropriate WCAG contrast requirements.

The system SHALL NOT communicate state through color alone.

Examples:

Instead of:

Red = Error

Use:

Red + Icon + Text

Instead of:

Green = Completed

Use:

Green + Check Icon + Completed label

Focus states SHALL remain clearly visible.

Keyboard navigation SHALL be supported.

Reduced-motion preferences SHALL be respected.

---

# 2.21 Visual Hierarchy

Every screen should contain three visual layers.

Primary:

The user's current task.

Secondary:

Supporting information.

Tertiary:

Metadata and system controls.

The interface should make the primary task visually obvious within two seconds of page load.

---

# 2.22 Brand Recognition

A user should recognize SERENDIPITY without seeing the logo.

Brand recognition should emerge from:

- Color
- Typography
- Spacing
- Component shapes
- Motion
- Knowledge visualization
- AI interaction patterns

The visual system must therefore remain consistent across every product surface.
# 3. Component System

## 3.1 Component Philosophy

SERENDIPITY SHALL use a composable component architecture.

Components should be:

- Reusable
- Accessible
- Predictable
- Theme-aware
- Responsive
- Independently testable

Components should communicate meaning rather than merely provide decoration.

The design system SHALL distinguish between:

1. Primitive Components
2. Product Components
3. Research Components
4. AI Components
5. Visualization Components

---

# 3.2 Component Hierarchy

Primitive Components

↓

Buttons
Inputs
Badges
Icons
Tooltips
Tabs
Dropdowns

↓

Product Components

↓

Navigation
Cards
Panels
Dialogs
Tables
Command Palette

↓

Research Components

↓

Paper Card
Evidence Card
Citation Card
Concept Card
Research Asset

↓

AI Components

↓

Research Mission
Agent Timeline
Copilot Message
Reasoning Panel
Confidence Indicator

↓

Knowledge Components

↓

Knowledge Fabric
Graph Node
Relationship Edge
Concept Cluster
Discovery Card

The hierarchy prevents product-specific functionality from being duplicated across the application.

---

# 3.3 Buttons

SERENDIPITY SHALL support the following button variants.

Primary

Used for the most important action on a screen.

Examples:

- Create Workspace
- Start Research
- Generate Discovery

Secondary

Used for supporting actions.

Examples:

- Cancel
- View Details
- Open Library

Tertiary

Used for low-emphasis actions.

Examples:

- Learn More
- View Source
- Expand

Destructive

Used for irreversible operations.

Examples:

- Delete Workspace
- Remove Research Asset

Icon Button

Used for compact contextual actions.

Every icon-only button SHALL provide an accessible label.

---

# 3.4 Button Behavior

Buttons SHALL provide clear visual states.

States:

- Default
- Hover
- Focus
- Active
- Disabled
- Loading
- Success

Loading buttons SHALL communicate that an operation is in progress.

Example:

Generate Discovery

↓

Generating...

The system SHALL prevent accidental duplicate submissions.

---

# 3.5 Inputs

Input fields SHALL support:

- Labels
- Placeholder text
- Help text
- Validation
- Error messages
- Success states
- Loading states

Labels SHALL remain visible when users enter information.

Placeholder text SHALL NOT be used as the only label.

---

# 3.6 Search

Search is a primary interaction within SERENDIPITY.

Search SHALL support:

- Semantic search
- Keyword search
- Filters
- Recent searches
- Suggested queries
- Search history

The primary research search interface should feel closer to an exploration tool than a traditional website search box.

---

# 3.7 Command Palette

SERENDIPITY SHALL provide a global command interface.

Suggested shortcut:

Ctrl + K

The command palette allows users to quickly access:

- Workspaces
- Papers
- Concepts
- Research Copilot
- Knowledge Fabric
- Reports
- Settings
- Actions

Example:

Ctrl + K

↓

Search

"Open Knowledge Fabric"

↓

Knowledge Fabric opens.

The command palette SHALL support keyboard navigation.

---

# 3.8 Navigation

The primary application navigation SHALL use a persistent sidebar on desktop.

Structure:

SERENDIPITY

Research Command Center

Workspaces

Research Library

Knowledge Fabric

Research Copilot

Discovery Reports

Research Notebook

---

Settings

Help

User Profile

The sidebar may collapse into icon-only mode.

On mobile, the navigation SHALL transform into a drawer or bottom navigation depending on context.

---

# 3.9 Cards

Cards SHALL be used to group related information.

Generic cards should remain visually minimal.

Product-specific cards should communicate domain meaning.

Examples:

- Research Card
- Paper Card
- Concept Card
- Discovery Card
- Workspace Card

Cards should not become containers for entire applications.

---

# 3.10 Research Asset Card

The Research Asset Card represents a paper, patent, dataset, or technical document.

It SHALL display:

- Title
- Asset type
- Author
- Date
- Source
- Relevance
- Processing status
- Actions

Example:

Research Paper

"Graph Neural Networks for Molecular Discovery"

Authors

A. Researcher et al.

Relevance

92%

Status

Analyzed

Actions

Open

Analyze

Add to Workspace

---

# 3.11 Evidence Card

The Evidence Card represents supporting evidence for an AI-generated conclusion.

It SHALL display:

- Claim
- Supporting source
- Relevant excerpt
- Confidence
- Citation
- Open source action

Evidence cards should make AI reasoning traceable.

---

# 3.12 Citation Card

Citation Cards represent relationships between research works.

They may display:

- Paper title
- Authors
- Publication year
- Citation relationship
- Citation count
- Source

Users should be able to navigate directly to the referenced work.

---

# 3.13 Concept Card

Concept Cards represent scientific concepts extracted from research.

They SHALL display:

- Concept name
- Definition
- Related papers
- Related concepts
- Confidence
- Knowledge Fabric connections

Example:

Concept

Graph Neural Network

Confidence

96%

Related Papers

24

Related Concepts

18

---

# 3.14 Discovery Card

The Discovery Card is one of the signature SERENDIPITY components.

It represents a potentially valuable research connection.

Structure:

Discovery

Title

Cross-domain relationship

Supporting evidence

Related concepts

Novelty indicator

Confidence

Source papers

Actions:

Explore

Save

Reject

Add to Notebook

The Discovery Card should visually communicate that the user has found something worth investigating.

---

# 3.15 Research Mission

The Research Mission represents an active AI workflow.

Example:

Research Mission

"Investigate applications of graph learning in drug discovery"

Status:

Analyzing

Progress:

67%

Current Stage:

Cross-domain reasoning

Agents:

Planner ✓

Literature ✓

Concept ✓

Knowledge ●

Reasoning ○

Discovery ○

The Research Mission should remain visible while AI work is active.

---

# 3.16 Agent Timeline

The Agent Timeline visualizes multi-agent execution.

Example:

Planner Agent

✓ Complete

Literature Agent

✓ Complete

Concept Agent

✓ Complete

Knowledge Agent

● Running

Reasoning Agent

○ Waiting

Discovery Agent

○ Waiting

The timeline SHALL update in real time.

Users should be able to expand an agent to understand:

- Task
- Status
- Duration
- Evidence
- Output
- Errors

---

# 3.17 Research Copilot Message

Research Copilot messages SHALL support multiple content types.

Text

Evidence

Citation

Concept

Graph Reference

Recommendation

Warning

Action

The interface should distinguish these visually without creating unnecessary visual noise.

---

# 3.18 AI Reasoning Panel

The AI Reasoning Panel provides an explainability layer.

It SHALL communicate:

- Research objective
- Evidence considered
- Reasoning summary
- Confidence
- Limitations
- Sources

The system should avoid exposing private chain-of-thought.

Instead, it should provide a concise, user-facing explanation of the basis for the result.

---

# 3.19 Confidence Indicator

Confidence SHALL never be represented by a number alone.

Example:

High Confidence

█████████░

92%

Based on:

24 supporting sources

The user should be able to inspect the evidence behind the confidence indicator.

Confidence is informational, not a guarantee of correctness.

---

# 3.20 Knowledge Fabric Component

The Knowledge Fabric is a signature product component.

It represents relationships between:

- Papers
- Concepts
- Authors
- Institutions
- Methods
- Datasets
- Research areas

The visualization SHALL support:

- Zoom
- Pan
- Search
- Filtering
- Node selection
- Relationship inspection
- Cluster exploration
- Focus mode

---

# 3.21 Graph Node Language

Different entity types should have distinguishable visual identities.

Example:

Paper

Blue

Concept

Purple

Author

Amber

Institution

Teal

Dataset

Green

Hypothesis

Magenta

The exact palette will be finalized during Knowledge Fabric implementation.

Color SHALL NOT be the only distinction.

Shape, iconography, or labels should also communicate entity type.

---

# 3.22 Graph Interaction

Selecting a node SHALL reveal contextual information.

Example:

Concept

"Graph Neural Networks"

↓

Connected Papers: 32

Connected Authors: 18

Related Concepts: 41

↓

Actions:

Explore

Focus Graph

Ask Copilot

Add to Notebook

The graph should become an exploration environment rather than a static visualization.

---

# 3.23 Tabs

Tabs SHALL be used when users need to switch between closely related views.

Examples:

Paper

- Overview
- Content
- Citations
- Concepts
- Analysis

Knowledge Fabric

- Graph
- Concepts
- Evidence
- Timeline

Tabs should not be used for unrelated navigation.

---

# 3.24 Tables

Tables SHALL be used for dense structured information.

Examples:

- Literature
- Citations
- Research Assets
- AI Runs
- System Logs

Tables should support:

- Sorting
- Filtering
- Pagination
- Search
- Column visibility where appropriate

Mobile layouts should transform tables rather than forcing horizontal scrolling whenever practical.

---

# 3.25 Dialogs

Dialogs should be reserved for focused decisions.

Examples:

Delete Workspace

Confirm Export

Create Workspace

Configure AI Analysis

Dialogs should never contain entire workflows.

---

# 3.26 Toast Notifications

Toast notifications SHALL communicate short-lived events.

Examples:

"Research asset uploaded."

"Discovery saved."

"Report exported."

Errors requiring user action should NOT rely exclusively on toasts.

---

# 3.27 Empty States

Every major data-driven screen SHALL have a designed empty state.

Example:

Knowledge Fabric

"No knowledge connections yet."

Upload your first research papers to begin building your Knowledge Fabric.

Action:

Upload Research

Empty states should educate users rather than simply state that data is missing.

---

# 3.28 Loading States

Loading states SHALL communicate what the system is doing.

Avoid generic:

"Loading..."

Prefer:

"Extracting research concepts..."

"Building Knowledge Fabric..."

"Analyzing citation relationships..."

"Preparing Discovery Report..."

The wording should reflect the actual operation.

---

# 3.29 Error States

Errors SHALL explain:

What happened

Why it happened

What the user can do

Example:

Unable to process this document.

The uploaded PDF does not contain machine-readable text.

Try uploading a text-based PDF or use OCR processing.

Action:

Try Again

---

# 3.30 Skeleton States

Skeleton loaders should preserve the structure of the expected content.

They SHALL be used when loading:

- Research Cards
- Tables
- Dashboard panels
- Reports
- Knowledge panels

Skeleton animations should remain subtle.

---

# 3.31 Tooltips

Tooltips SHALL explain unfamiliar functionality.

They should:

- Remain concise
- Appear near the relevant control
- Not contain essential information unavailable elsewhere

Tooltips should not become a substitute for proper UI labeling.

---

# 3.32 Responsive Behavior

Components SHALL adapt based on available space.

Desktop:

Full navigation and multi-panel layouts.

Tablet:

Reduced navigation and adaptive panels.

Mobile:

Focused single-column workflows.

The Knowledge Fabric should provide a specialized mobile exploration experience rather than simply shrinking the desktop graph.

---

# 3.33 Component Accessibility

All reusable components SHALL support:

- Keyboard interaction
- Focus management
- Screen readers
- Appropriate contrast
- Reduced motion
- Accessible labels
- Error announcements where necessary

Accessibility SHALL be tested alongside functionality.

---

# 3.34 Component Naming Convention

Components SHALL use descriptive names.

Examples:

ResearchCard

EvidenceCard

DiscoveryCard

ResearchMission

AgentTimeline

KnowledgeFabric

ConceptCard

CitationCard

ResearchCopilot

Avoid generic names such as:

Card1

Box

Thing

Panel2

Naming should communicate domain responsibility.
