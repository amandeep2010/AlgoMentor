# 🧠 AlgoMentor: The Socratic DSA Instructor

AlgoMentor is an AI-driven Data Structures and Algorithms (DSA) tutor designed to simulate a world-class competitive programming coach. Instead of functioning as a simple code generator, AlgoMentor strictly utilizes the Socratic method to guide developers toward optimal solutions, prioritizing pedagogy and logical intuition over raw answer retrieval.

## 🎯 Core Philosophy
**Pedagogy over answers.** AlgoMentor will not write the code for you. It trains you to think like an engineer, optimize systematically, and ace technical interviews by breaking down complex algorithmic challenges into digestible, logical steps.

## ✨ Features
- **Strict Socratic Guidance:** Provides targeted hints, conceptual diagrams, and clarifying questions instead of direct solutions.
- **The 5-Step Instructional Framework:**
  1. Constraint & Edge-Case Analysis
  2. Brute Force Validation
  3. Systematic Optimization (e.g., Two Pointers, DP, Graphs)
  4. Dry Runs & Pseudocoding
  5. Clean Implementation & Complexity Analysis
- **Domain Restriction:** Strictly locked to answering DSA, complexity, and competitive programming queries to conserve context and tokens.
- **Language Agnostic:** Capable of validating logic across multiple ecosystems, optimized heavily for standard workflows in C++ and Python.

## 🚀 Getting Started

### Prerequisites
To use the AlgoMentor system instruction, you will need access to an LLM provider that supports system prompts/instructions (e.g., OpenAI API, Google Gemini API, Anthropic Claude API).

### Installation
1. Navigate to your LLM application's configuration settings.
2. Locate the **System Instruction** or **System Prompt** field.
3. Copy the entire text block from `system_prompt.txt` (or the provided prompt block).
4. Paste the text into the system configuration.

### Recommended Configuration
For the best pedagogical experience, apply the following parameter adjustments to your model:
- **Temperature:** `0.2 - 0.4` (Ensures the model remains analytical, structured, and consistent).
- **Max Tokens:** Adjust based on your interface, but standard lengths (1000-2000) are sufficient for trace tables and ASCII visualizer outputs.

## 💡 Example Interaction
**User:** "How do I reverse a linked list in O(N) time?"
**AlgoMentor:** "Let's break this down. Before we write any code, imagine you have three pointers: `prev`, `current`, and `next`. If `current` is pointing to the head of the list, what is the very first connection we need to break and redirect? Take a guess at what `prev` should initially be set to."

## 👨‍💻 Author
**Amandeep Singh**
*Information Technology, NIT Raipur*

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
