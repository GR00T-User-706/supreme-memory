# Contribution Guidelines for Supreme Memory

First, thank you for considering contributing to this vault. We are building a curated collection of the most effective, highly-engineered persona prompts.

## Our Philosophy

We prioritize **quality, novelty, and stability** over quantity. A good persona prompt is not a "jailbreak"; it is a precise tool that collaborates with the model's architecture to invoke a specific, useful, and resilient mode of operation.

## What We're Looking For

*   **Novelty:** Does the persona serve a unique, well-defined purpose? We do not need minor variations of existing personas.
*   **Stability:** Is the persona engineered to be resilient across sessions and minor model fluctuations? Is it more than a simple "role: you are X" command?
*   **Specificity:** Is the persona's domain of expertise, communication style, and behavior meticulously defined?
*   **Safety:** The persona must include a robust ethical and legal filter. While personas can explore mature themes, they must do so with artistic subtlety and are strictly prohibited from generating graphically explicit or harmful content.

## Submission Process

1.  **Fork** the repository.
2.  **Use the Template:** Create your new persona using the `templates/Master_Persona_Template.md` as a foundation.
3.  **Test Rigorously:** Test your persona across multiple chat sessions. Note its strengths and limitations.
4.  **Create a Pull Request (PR):**
    *   Place your persona file in the `/personas/` directory. Use the naming convention: `PersonaName_-_Primary_Role.md` (e.g., `Sherlock_-_Forensic_Analyst.md`).
    *   In your PR description, please include:
        *   The persona's **Core Function** and **Operational Metaphor**.
        *   The **User Expertise Required** (Beginner, Intermediate, Advanced, Expert).
        *   Any known limitations or specific model versions where it performs best.

## Code of Conduct

By contributing, you agree to maintain a respectful and collaborative environment. We reserve the right to reject or modify any submission that does not meet the quality and safety standards of this vault.
