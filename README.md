# edunavigator

# SIH-2024 – EduNavigator

## Proposed Solution

**EduNavigator** is an interactive graph-based platform (inspired by learn-anything.xyz) designed to help students:

1. Explore **scholarships, skills, resources, and innovation projects** through an intuitive knowledge graph.
2. Use an **AI-powered Skill Gap Analyzer** to compare their current skills against the requirements of a target job role, and generate personalized learning paths.
3. Access curated **learning resources** (MOOCs, study materials, research papers) linked directly to skill nodes.
4. Discover **SIH-winning projects and student innovations** for inspiration.
5. Visualize relationships between skills, resources, and opportunities in a **single connected interface**.
6. Search and navigate using a fast, interactive **graph explorer** with a clean UI.

---

## Technology Used]

1. **AI for Skill Gap Analysis**

   * NLP-based models to parse job role descriptions (HuggingFace Transformers / spaCy)
   * Comparison engine to highlight ✅ existing skills and ❌ missing skills
   * Missing skills automatically linked to skill nodes in the graph

2. **Data Handling**

   * Scholarships, Skills, Resources, and Projects stored in local JSON (prototype)
   * Future integration planned with real databases and APIs

3. **Search & Navigation**

   * Search bar to jump to specific nodes

4. **Frontend & Backend (Prototype)**

   * Frontend: React + Next.js
   * Backend (for demo data): JSON mock server / Django API (extendable)

---

## Features

* 🎓 **Scholarship Finder** – Explore scholarships with eligibility, benefits, and deadlines
* 📚 **Skill Roadmaps** – Visualize interconnected skills required for career growth
* 🚀 **Innovation Projects** – Learn from past SIH-winning ideas and student startups
* 🧠 **Skill Gap Analyzer** – Enter your skills + target role → see gaps + recommended learning path
* 🔗 **Resource Hub** – Direct links to study material, MOOCs, and research papers
* 🌙 **Dark Mode Support** – User-friendly UI for long study sessions

---

## Demo Prototype Goals

* Users can test the **Skill Gap Analyzer** with mock job roles and skills
* Prototype runs locally with **mock JSON data** (no heavy backend required)

---

## Future Scope

* Real-time **integration with institutional and job market databases**
* AI-powered **personalized learning roadmap generation**
* Peer-to-peer **collaboration and mentoring modules**
* Dynamic **scholarship and competition updates via APIs**

---

## Screenshot (Prototype UI Preview)

![EduNavigator Demo](https://i.ibb.co/JWJZttcY/Screenshot-2025-09-13-082322.png)
