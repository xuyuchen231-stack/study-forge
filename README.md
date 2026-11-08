# StudyForge

An Agent Skill that turns textbooks, lecture notes, papers, and other learning materials into source-grounded lessons, practice, and a mastery path.

- **Build a learning pack** with concepts, prerequisites, source locators, and practice prompts.
- **Run an interactive lesson** with explanations, diagrams, discussions, simulations, or project milestones as the host supports.
- **Practice and review** with targeted hints, fresh retry questions, and a checkpoint based on demonstrated understanding.

## Use

Install the repository as a skill in an Agent Skills-compatible host. Keep `SKILL.md`, `references/`, `agents/`, and `assets/` together. In Codex, place the repository under an available skills directory as `study-forge`, then invoke `$study-forge` or describe the task.

> Use StudyForge to teach me electron configurations at high-school level. Ask one question at a time and wait for my answer.

> Turn this chapter into a learning pack with exact page references, worked examples, and a separate answer key.

StudyForge runs through the host agent. OCR, speech, simulations, and independent agents depend on available tools.

## Inspiration

- [OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) informed the classroom scenes and project workflow.
- [book-to-skill](https://github.com/virgiliojr94/book-to-skill) informed source distillation and on-demand concept retrieval.
- [DeepTutor](https://github.com/HKUDS/DeepTutor) informed guided practice and mastery tracking.
