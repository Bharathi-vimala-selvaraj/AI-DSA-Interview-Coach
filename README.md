# 🤖 AI DSA Interview Coach

An interactive, no-code AI coaching agent built on [Dify](https://dify.ai) designed to teach Data Structures & Algorithms (DSA) concepts, prepare candidates for technical interviews, and guide problem-solving step-by-step using Java.

---

## 🌟 Key Features

* **5-Year-Old Intuition:** Explains complex concepts using simple, real-world analogies before diving into code.
* **Visual Pointer Diagrams:** Renders clean ASCII diagrams showing pointer moves and memory state changes before and after operations.
* **Step-by-Step Dry Runs:** Traces sample input data line-by-line to ensure full execution flow clarity.
* **Java Code & Edge Cases:** Focuses on practical implementations and highlights common runtime bugs (e.g., `NullPointerException`).
* **Common Interview Traps:** Pinpoints the #1 mistake candidates make during live technical interviews.
* **Interactive Mini Quiz & Challenges:** Features a live challenge problem and quick checks without immediately revealing answers—prompting the learner to attempt first!

---

## 🏗️ Repository Structure

* `AI-DSA-Interview-Coach.yml` — The complete exported Dify DSL workflow configuration file containing the agent architecture, system prompt rules, and node settings.

---

## 🚀 How to Import & Run in Dify

1. Log into your [Dify Workspace](https://cloud.dify.ai/).
2. Navigate to **Studio** $\rightarrow$ **Create from Blank**.
3. Select **Import DSL file**.
4. Choose the `AI-DSA-Interview-Coach.yml` file from this repository.
5. Click **Publish** and start interacting with your AI DSA Coach!

---

## 🧪 Example Query

**User Prompt:**
> *"Teach me Linked Lists and explain how `temp.next = temp.next.next` deletes a node."*

**Agent Output Sections:**
1. 🧒 5-Year-Old Intuition
2. 📐 Visual Pointer Diagram
3. 🏃 Step-by-Step Dry Run
4. 💻 Code Explanation (Java)
5. ⚠️ Common Interview Trap
6. 🎯 Live Interview Challenge Question
7. 🧪 Mini Quiz
8. ⏸️ Interactive Note
