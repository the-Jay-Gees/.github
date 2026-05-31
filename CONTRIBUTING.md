### Contributing to Spoonie Helper

Thank you for your interest in contributing!
Spoonie Helper is a local‑first, accessibility‑centered, community‑driven project created and maintained by Jillian, a Deaf, neurodivergent, Disabled, non‑traditional coder. This project exists to support chronically ill and disabled people, and contributions must uphold that purpose.

Accessibility is not optional here. It is a core engineering requirement.

### Code of Conduct

By contributing, you agree to:

    Respect disabled contributors and users

    Prioritize accessibility in all decisions

    Avoid assumptions about ability, cognition, or communication

    Communicate clearly and asynchronously when possible

    Document changes thoroughly so others can follow your work

How to Contribute

    Open an issue before starting major work

    Keep PRs focused and scoped

    Include tests when relevant

    Follow the accessibility and local‑first requirements below

    Be prepared for accessibility review and revision requests

### Mandatory Accessibility Standards

Accessibility is a non‑negotiable requirement for all contributions.
PRs that do not meet these standards will not be merged.
1. DeafBlind‑Standard Alt Text (Required for ALL images)

Every image, screenshot, diagram, or visual asset must include full, literal, descriptive alt text that meets DeafBlind standards.

Requirements:

    Describe all visible text exactly as shown

    Describe layout, structure, and relationships

    Describe context and purpose

    Avoid interpretation, emotion, or assumptions

    Be complete, specific, and literal

    Use plain language

    No “image of…” filler text

Why this is mandatory:  
Blind and DeafBlind users rely on screen readers and braille displays.
If alt text is incomplete, vague, or missing, the information becomes inaccessible or misleading. This project centers disabled users, so full descriptive access is required.
2. Screen Reader–First Semantic Structure

All UI, HTML, Markdown, and documentation must be structured for screen readers.

Requirements:

    Use proper heading hierarchy

    Use semantic HTML elements

    Ensure labels and roles are correct

    Ensure focus order is logical

    Avoid div‑only layouts without ARIA

    Avoid visual‑only indicators (color, icons, etc.)

    Provide text equivalents for all interactive elements

Why this is mandatory:  
Blind and low‑vision users navigate by structure, not visuals.
Incorrect semantics break navigation, comprehension, and usability.
3. Keyboard‑Only Navigation

All interactive components must be fully usable with a keyboard.

Requirements:

    No keyboard traps

    Visible focus states

    Logical tab order

    Escape or close actions must be keyboard accessible

    Custom widgets must follow WAI‑ARIA Authoring Practices

Why this is mandatory:  
Many disabled users cannot use a mouse.
Keyboard access is foundational accessibility, not an enhancement.
4. Plain‑Language Documentation

All docs must be written in clear, concise language.

Requirements:

    Short sentences

    Direct instructions

    Avoid jargon unless defined

    Provide examples

    Avoid metaphors or idioms that may confuse non‑native speakers or neurodivergent readers

Why this is mandatory:  
Cognitive accessibility is essential for neurodivergent users and users with brain fog, chronic fatigue, or processing disabilities.
5. Local‑First Data Handling

All contributions must respect the project’s local‑first policy.

Requirements:

    No silent network calls

    No external analytics

    No cloud dependencies without explicit user opt‑in

    All data must remain local unless the user chooses otherwise

Why this is mandatory:  
Disabled users often manage sensitive health information.
Local‑first design protects privacy, autonomy, and safety.
Pull Request Checklist

Before submitting a PR, confirm:

    [ ] All images include DeafBlind‑standard alt text

    [ ] All UI and docs follow screen‑reader semantics

    [ ] Keyboard‑only navigation is fully supported

    [ ] Documentation is plain‑language and accessible

    [ ] No network calls violate the local‑first policy

    [ ] Tests pass

    [ ] You have explained the purpose and scope of the change

### Reporting Accessibility Issues

If you find an accessibility issue:

    Open an issue labeled accessibility

    Include steps to reproduce

    Include expected vs. actual behavior

    Include environment details if relevant

Accessibility issues are treated as critical bugs.
Thank You

Your contributions help build tools that support disabled communities with dignity, autonomy, and care.
Thank you for helping maintain an accessibility‑first engineering culture.
