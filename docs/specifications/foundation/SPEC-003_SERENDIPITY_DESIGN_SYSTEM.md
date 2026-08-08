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
# 4. Motion & Interaction Language

## 4.1 Motion Philosophy

SERENDIPITY SHALL use purposeful motion.

Animation exists to communicate:

- State
- Progress
- Relationships
- Hierarchy
- Feedback
- Discovery

Motion SHALL NOT exist purely for visual decoration.

Every animation should answer at least one question:

What changed?

What is happening?

Where should the user look?

What can the user do next?

---

# 4.2 Motion Personality

SERENDIPITY motion should feel:

- Calm
- Precise
- Fluid
- Intelligent
- Responsive
- Subtle

Motion should never feel:

- Hyperactive
- Game-like
- Distracting
- Excessively elastic
- Slow

The interface should feel alive without appearing animated for the sake of animation.

---

# 4.3 Motion Duration

Standard durations:

Micro:

100ms

Fast:

150ms

Standard:

200ms

Medium:

300ms

Large:

400ms

Complex:

500-700ms

Animations longer than 700ms should be rare and reserved for meaningful system transitions.

---

# 4.4 Easing

Default UI easing:

ease-out

Used for:

- Opening panels
- Hover states
- Navigation
- Element entrance

Emphasis transitions may use:

ease-in-out

Continuous system animations should use linear or carefully controlled easing.

---

# 4.5 Micro-Interactions

Micro-interactions SHALL provide immediate feedback.

Examples:

Button

Hover

↓

Subtle color transition

---

Card

Hover

↓

Slight elevation

---

Saved Discovery

↓

Check animation

---

Copied Citation

↓

Confirmation indicator

---

Selected Node

↓

Focused highlight

Micro-interactions should remain subtle enough that users do not consciously notice them unless necessary.

---

# 4.6 Page Transitions

Page transitions SHALL be minimal.

Preferred behavior:

Current View

↓

Subtle opacity transition

↓

New View

Large sliding page transitions should be avoided.

Research users frequently move between related views and should not feel like they are navigating between separate applications.

---

# 4.7 Panel Transitions

Panels should enter from the direction associated with their context.

Examples:

Sidebar

↓

Slide horizontally

---

Context Panel

↓

Slide from right

---

Bottom Action Panel

↓

Slide from bottom

---

Modal

↓

Fade + slight scale

Transitions should remain under approximately 300ms for normal interactions.

---

# 4.8 Loading Philosophy

SERENDIPITY SHALL avoid generic loading indicators whenever meaningful progress information is available.

Instead of:

Loading...

Use contextual status.

Examples:

"Reading research papers..."

"Extracting concepts..."

"Mapping citation relationships..."

"Building Knowledge Fabric..."

"Searching for cross-domain connections..."

"Generating Discovery Report..."

The interface should communicate what the system is actually doing.

---

# 4.9 Research Mission Animation

The Research Mission is a signature interaction.

When a research workflow begins:

Research Mission Created

↓

Mission Card appears

↓

Planner Agent activates

↓

Agent Timeline begins

↓

Progress updates continuously

↓

Knowledge Fabric begins forming

↓

Discovery Engine activates

↓

Discovery Report becomes available

The animation should visually communicate that multiple processes are occurring as part of one coordinated mission.

---

# 4.10 Agent Status Language

Every agent has one of the following states:

Queued

Running

Completed

Paused

Failed

Cancelled

Retrying

The interface SHALL visually distinguish these states.

Example:

Queued

○

Running

●

Completed

✓

Failed

×

Retrying

↻

The system should also provide textual labels for accessibility.

---

# 4.11 Agent Activity

When an agent is running, the interface may display a subtle activity indicator.

Example:

Knowledge Agent

● Analyzing relationships

The activity indicator should use restrained motion.

Avoid aggressive spinners or rapidly flashing elements.

---

# 4.12 Agent Expansion

Users should be able to expand an agent to inspect user-facing execution information.

Expanded view:

Agent Name

Task

Status

Duration

Sources Used

Output

Warnings

The system SHALL NOT expose hidden chain-of-thought or private model reasoning.

Instead, it should provide a concise explanation of what the agent accomplished and what evidence it used.

---

# 4.13 Research Mission Completion

When a mission completes:

Research Mission

↓

Progress reaches 100%

↓

Final agent completes

↓

Subtle completion animation

↓

Discovery Report becomes available

↓

Knowledge Fabric updates

↓

User receives completion notification

The completion state should feel rewarding without becoming celebratory or distracting.

---

# 4.14 Discovery Animation

When SERENDIPITY identifies a potentially interesting relationship:

A subtle visual emphasis should occur.

Example:

Concept A

↓

Relationship discovered

↓

Connection becomes highlighted

↓

Related Concept B becomes emphasized

↓

Discovery Card appears

The goal is to create a feeling of discovery while maintaining scientific seriousness.

---

# 4.15 Discovery Highlight

Discovery highlights SHALL use the Discovery accent.

Recommended:

Emerald / Teal

The highlight should be temporary.

After the user acknowledges the discovery, the graph should return to its normal visual state.

---

# 4.16 Knowledge Fabric Motion Philosophy

The Knowledge Fabric should feel like a living representation of knowledge.

However, it SHALL NOT behave like a decorative screensaver.

Motion should represent real relationships or state changes.

Examples:

New Node

↓

Node appears

↓

Relationship forms

↓

Cluster updates

---

New Evidence

↓

Relationship strengthens

↓

Confidence indicator updates

---

New Discovery

↓

Relevant subgraph highlights

Motion must correspond to actual data.

---

# 4.17 Graph Node Entrance

When a new node enters the Knowledge Fabric:

1. Node position is calculated.

2. Node fades into visibility.

3. Node scales from approximately 95% to 100%.

4. Relevant edges appear.

5. The graph stabilizes.

The animation should remain short enough to preserve usability.

---

# 4.18 Graph Relationship Animation

Relationships may animate when they are:

- Newly created
- Selected
- Highlighted
- Strengthened
- Investigated

Relationships should never continuously animate without a meaningful reason.

---

# 4.19 Graph Selection

When a node is selected:

Selected Node

↓

Increase visual prominence

↓

Connected nodes remain visible

↓

Unrelated nodes reduce visual emphasis

↓

Context Panel opens

This creates a focused exploration state without removing surrounding context.

---

# 4.20 Graph Focus Mode

Users SHALL be able to focus on a selected entity.

Example:

Select:

"Graph Neural Networks"

↓

Focus Mode

↓

Show:

Related Papers

Related Concepts

Authors

Methods

Datasets

Research Areas

The rest of the graph becomes visually subdued.

---

# 4.21 Graph Exploration

Users should be able to progressively explore knowledge.

Node

↓

Select

↓

Inspect

↓

Focus

↓

Expand

↓

Discover

This progressive exploration model prevents overwhelming the researcher with all available information at once.

---

# 4.22 AI Streaming

Research Copilot responses may stream progressively.

The interface should communicate that the system is actively producing a response.

However, streaming should never reveal incomplete reasoning as if it were a final conclusion.

Evidence and final claims should be presented only after validation.

---

# 4.23 AI Response States

Research Copilot responses may have:

Thinking

Retrieving

Analyzing

Validating

Ready

Error

The UI should distinguish system activity from the final response.

---

# 4.24 Evidence Reveal

When a Copilot response contains evidence:

Claim

↓

Evidence indicator

↓

Supporting sources

↓

Expandable Evidence Panel

Users should be able to inspect evidence without leaving the current research context.

---

# 4.25 Citation Interaction

Citations should provide immediate context.

Hover:

Show compact citation preview.

Click:

Open citation details.

Secondary action:

Open source.

The user should not lose their current research position when inspecting a citation.

---

# 4.26 AI Confidence Interaction

Confidence indicators should support progressive disclosure.

Example:

High Confidence

92%

↓

Click

↓

24 supporting sources

↓

Evidence distribution

↓

Source details

The interface should avoid presenting confidence as absolute truth.

---

# 4.27 Error Motion

Errors should receive immediate but restrained feedback.

Examples:

Invalid input

↓

Field highlight

↓

Error message

---

Failed AI task

↓

Agent status changes

↓

Error explanation appears

↓

Retry action

Errors should never trigger aggressive screen-wide animations.

---

# 4.28 Reduced Motion

SERENDIPITY SHALL respect the user's reduced-motion preference.

When reduced motion is enabled:

- Disable non-essential animations.
- Replace graph transitions with instant state changes where appropriate.
- Remove decorative motion.
- Preserve essential state feedback through color, icons, and text.

The application must remain fully understandable without animation.
# 5. Design Tokens & Implementation Rules

## 5.1 Purpose

Design tokens provide the implementation-level representation of the SERENDIPITY Design System.

Tokens SHALL be the single source of truth for:

- Colors
- Typography
- Spacing
- Borders
- Radius
- Shadows
- Motion
- Breakpoints
- Z-index
- Component states

Application components SHALL consume semantic tokens rather than hard-coded visual values.

---

# 5.2 Token Architecture

SERENDIPITY SHALL use three levels of design tokens.

Primitive Tokens

↓

Semantic Tokens

↓

Component Tokens

Primitive tokens define raw values.

Semantic tokens define meaning.

Component tokens define component-specific usage.

Example:

Primitive:

Primary 500

↓

Semantic:

Color Action Primary

↓

Component:

Button Primary Background

This separation allows the visual system to evolve without rewriting application components.

---

# 5.3 Color Token Structure

Color tokens SHALL follow semantic naming.

Example structure:

color.background.primary

color.background.secondary

color.surface.default

color.surface.elevated

color.border.default

color.text.primary

color.text.secondary

color.text.muted

color.action.primary

color.action.primary-hover

color.discovery

color.success

color.warning

color.error

color.info

Components should never directly depend on raw hexadecimal values.

---

# 5.4 Theme Architecture

SERENDIPITY SHALL support:

Dark Theme

Light Theme

Themes should be implemented using semantic CSS variables.

Example conceptual structure:

--background

--foreground

--surface

--surface-elevated

--border

--primary

--primary-foreground

--muted

--muted-foreground

--success

--warning

--error

--discovery

The exact implementation may evolve with the frontend framework.

---

# 5.5 Typography Tokens

Typography SHALL be represented through semantic tokens.

Examples:

font-display

font-heading-1

font-heading-2

font-heading-3

font-body-large

font-body

font-caption

font-code

Each token should define:

- Font family
- Font size
- Font weight
- Line height
- Letter spacing where appropriate

Components should avoid independently defining typography unless required by a specific visualization.

---

# 5.6 Spacing Tokens

The spacing system SHALL use the defined 8-point scale.

Tokens:

space-1: 4px

space-2: 8px

space-3: 12px

space-4: 16px

space-5: 24px

space-6: 32px

space-7: 40px

space-8: 48px

space-9: 64px

space-10: 80px

space-11: 96px

These tokens should be used consistently across:

- Layouts
- Components
- Panels
- Forms
- Cards
- Navigation

---

# 5.7 Radius Tokens

radius-sm: 6px

radius-md: 8px

radius-lg: 12px

radius-xl: 16px

radius-full: 9999px

Components should use semantic radius tokens rather than arbitrary values.

---

# 5.8 Border Tokens

Borders should remain subtle.

Recommended semantic tokens:

border-subtle

border-default

border-strong

border-focus

border-error

border-success

Borders should primarily establish structure and separation rather than decoration.

---

# 5.9 Shadow Tokens

SERENDIPITY SHALL use restrained elevation.

shadow-none

shadow-sm

shadow-md

shadow-lg

shadow-xl

Shadows should primarily be used for:

- Floating panels
- Dropdowns
- Dialogs
- Command palette
- Important overlays

Dense research interfaces should generally rely more on surface contrast and borders than large shadows.

---

# 5.10 Motion Tokens

Motion SHALL use centralized timing tokens.

duration-micro: 100ms

duration-fast: 150ms

duration-standard: 200ms

duration-medium: 300ms

duration-large: 400ms

duration-complex: 500-700ms

Components should avoid arbitrary transition durations.

---

# 5.11 Easing Tokens

ease-standard

ease-out

ease-in

ease-in-out

ease-linear

The default UI interaction easing should be ease-out.

---

# 5.12 Breakpoint Tokens

The responsive system SHALL use:

sm: 640px

md: 768px

lg: 1024px

xl: 1280px

2xl: 1536px

The frontend implementation should use framework-supported responsive utilities wherever possible.

---

# 5.13 Z-Index Layers

SERENDIPITY SHALL maintain predictable stacking contexts.

Suggested hierarchy:

Base

↓

Content

↓

Sticky

↓

Navigation

↓

Dropdown

↓

Popover

↓

Modal

↓

Command Palette

↓

Critical Overlay

Z-index values should be centralized rather than arbitrarily assigned throughout the application.

---

# 5.14 Component State Tokens

Interactive components SHALL support semantic states.

Default

Hover

Focus

Active

Selected

Disabled

Loading

Success

Warning

Error

Components should maintain consistent state behavior across the application.

---

# 5.15 Focus Tokens

Keyboard focus SHALL use a highly visible focus indicator.

Focus styles must not depend solely on subtle color changes.

Recommended pattern:

Visible outline

+

Brand-color emphasis

The focus indicator should remain visible against both dark and light themes.

---

# 5.16 Icon Tokens

Icons should use consistent dimensions.

Small:

16px

Default:

20px

Medium:

24px

Large:

32px

Icons larger than 32px should be reserved for prominent empty states, illustrations, or visualization contexts.

---

# 5.17 Avatar Tokens

Small:

24px

Default:

32px

Medium:

40px

Large:

48px

Profile:

64px

Avatar sizing should remain consistent throughout the platform.

---

# 5.18 Research Visualization Tokens

Knowledge Fabric visualizations require their own semantic tokens.

Examples:

node-paper

node-concept

node-author

node-institution

node-dataset

node-hypothesis

edge-citation

edge-supports

edge-contradicts

edge-related

edge-influences

These tokens should remain separate from general UI colors.

---

# 5.19 AI State Tokens

AI workflow states SHALL have semantic representations.

ai-queued

ai-running

ai-completed

ai-paused

ai-failed

ai-retrying

The visual representation may use:

- Color
- Icon
- Label
- Animation

Color alone must never communicate the state.

---

# 5.20 Discovery Tokens

Discovery-specific elements SHALL use a dedicated visual vocabulary.

discovery-primary

discovery-highlight

discovery-border

discovery-background

discovery-confidence

Discovery visual treatment should distinguish potential discoveries from ordinary research information.

---

# 5.21 Implementation Rule: No Hard-Coded UI Colors

Frontend components SHALL NOT contain arbitrary color values.

Avoid:

background: #6366F1

Prefer:

background: var(--primary)

This ensures global theme changes remain manageable.

---

# 5.22 Implementation Rule: No Arbitrary Spacing

Avoid arbitrary spacing wherever the token system provides an equivalent value.

Prefer:

space-4

over:

17px

Exceptions may exist for specialized visualizations or third-party integrations.

Such exceptions should be documented.

---

# 5.23 Implementation Rule: Component Ownership

Every component SHALL have a clear ownership layer.

Primitive UI

↓

Product UI

↓

Research UI

↓

AI UI

↓

Visualization UI

Components should not import internal implementation details from unrelated feature domains.

---

# 5.24 Implementation Rule: Composition Over Duplication

If multiple screens require similar behavior, create a reusable component.

Example:

Instead of:

DashboardPaperCard

WorkspacePaperCard

LibraryPaperCard

Create:

ResearchAssetCard

with configurable variants.

---

# 5.25 Implementation Rule: Variants Over Forks

Components should support controlled variants.

Example:

ResearchCard

Variants:

compact

default

expanded

featured

Avoid creating separate components when the underlying behavior remains the same.

---

# 5.26 Implementation Rule: Accessibility by Default

Reusable components SHALL be accessible by default.

Accessibility should not be added later as a separate development phase.

Components must consider:

- Keyboard access
- Focus management
- Labels
- Contrast
- Screen readers
- Reduced motion
- Error communication

---

# 5.27 Implementation Rule: Responsive by Default

Every component should define how it behaves across supported viewport sizes.

A component is incomplete if it only works on desktop.

---

# 5.28 Implementation Rule: Loading and Error States

Every asynchronous component SHALL define:

Loading

Success

Empty

Error

Retry

states where applicable.

This prevents inconsistent UX across the platform.

---

# 5.29 Implementation Rule: AI Transparency

Any component displaying AI-generated information SHALL provide sufficient context to distinguish:

User content

AI-generated content

Source evidence

System status

AI uncertainty

The interface must never make generated content appear indistinguishable from verified source material.

---

# 5.30 Implementation Rule: Evidence Traceability

AI-generated claims should provide a route to their supporting evidence.

A user should be able to move from:

Discovery

↓

Claim

↓

Evidence

↓

Source

↓

Research Asset

without losing their current research context.

---

# 5.31 Implementation Rule: Performance

Visual polish must not compromise application performance.

Animations should use GPU-friendly properties where appropriate.

Avoid unnecessary:

- Layout recalculation
- Large DOM trees
- Continuous animations
- High-frequency state updates

Knowledge Fabric rendering should be optimized independently from normal UI rendering.

---

# 5.32 Implementation Rule: Motion Accessibility

If the user prefers reduced motion:

- Decorative motion is disabled.
- Non-essential transitions are removed.
- Essential state changes remain understandable.
- Graph transitions become immediate where appropriate.

The product must remain fully functional without animation.

---

# 5.33 Implementation Rule: Token Documentation

Every new token must have:

Name

Purpose

Value

Usage

Theme behavior

Component dependencies

Tokens should not be introduced without a clear design reason.

---

# 5.34 Design Token Governance

Design tokens are part of the product's public design contract.

Changes to foundational tokens should be reviewed carefully because they can affect the entire application.

A token change should be evaluated for:

- Visual consistency
- Accessibility
- Component impact
- Responsive behavior
- Dark/light themes
- Knowledge visualization
- AI interfaces

---

# 5.35 Design System Source of Truth

The following hierarchy defines the source of truth:

SPEC-003

↓

Design Tokens

↓

Component Library

↓

Product Screens

↓

Feature Implementations

Implementation SHALL NOT redefine the design system independently.

