# 🧠 SkillMap

### AI-Powered Interactive Learning Path Visualizer

Transform any skill into a dynamic, interactive knowledge graph powered by AI.

SkillMap helps learners, students, developers, and professionals understand complex subjects by automatically generating structured learning roadmaps and visualizing relationships between concepts, prerequisites, tools, and advanced topics.

---

## ✨ Overview

Learning a new skill often feels overwhelming because information is scattered across countless tutorials, courses, and articles.

SkillMap solves this problem by using AI to generate a personalized knowledge graph for any skill and presenting it as an interactive visual learning map.

Simply enter a topic such as **Machine Learning**, **System Design**, **Data Engineering**, or **Cybersecurity**, and SkillMap will instantly create a structured roadmap showing:

* Core concepts
* Learning paths
* Prerequisites
* Related technologies
* Recommended resources

---

## 🚀 Features

### 🤖 AI-Powered Skill Mapping

Generate intelligent learning roadmaps using Anthropic Claude AI.

### 🌐 Interactive Knowledge Graph

Visualize complex topics through a dynamic D3.js force-directed graph.

### 🖱️ Full Graph Interaction

* Drag nodes
* Zoom in/out
* Pan across the canvas
* Explore relationships between concepts

### 📚 Learning Resources

Click any node to view:

* Topic descriptions
* Learning recommendations
* Helpful resources
* Suggested next steps

### 💾 Export & Share

Save generated learning maps as structured JSON files.

### 🌙 Modern Dark Interface

Clean, responsive design optimized for long learning sessions.

### ⚡ Lightweight Architecture

No frameworks.
No build tools.
No unnecessary dependencies.

Everything runs from a single HTML file.

---

## 🎯 Example Use Cases

SkillMap can generate learning roadmaps for:

* Machine Learning
* Data Science
* Python Programming
* Data Engineering
* Kubernetes
* Cloud Computing
* Cybersecurity
* System Design
* DevOps
* UI/UX Design
* Product Management
* Blockchain Development

---

## 📸 How It Works

### Step 1 — Enter a Skill

Type any skill you want to learn.

Example:

```text
Machine Learning
```

### Step 2 — AI Generates Structure

Claude AI analyzes the topic and creates a structured knowledge graph containing:

* Root skill
* Sub-domains
* Concepts
* Techniques
* Related tools

### Step 3 — Visual Graph Creation

D3.js transforms the AI response into a fully interactive graph.

### Step 4 — Explore & Learn

Click nodes to discover:

* Explanations
* Learning resources
* Recommended progression paths

---

## 🛠 Technology Stack

| Technology         | Purpose                         |
| ------------------ | ------------------------------- |
| D3.js v7           | Interactive graph visualization |
| Claude API         | AI-powered graph generation     |
| Vanilla JavaScript | Application logic               |
| HTML5 & CSS3       | Interface and styling           |
| Google Fonts       | Typography                      |

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/skillmap.git
cd skillmap
```

Serve locally:

```bash
python3 -m http.server 8080
```

or

```bash
npx serve .
```

Open:

```text
http://localhost:8080
```

---

## 🔑 API Key Security

Your Anthropic API key is:

✅ Stored only in memory

✅ Never saved to localStorage

✅ Never persisted to disk

✅ Sent exclusively to Anthropic's API endpoint

The key is automatically cleared when the page is refreshed.

---

## 📈 Future Roadmap

* Learning difficulty estimation
* Time-to-learn predictions
* Personalized learning paths
* Progress tracking
* PDF roadmap export
* Multi-language support
* Collaborative learning maps
* Career-focused roadmaps

---

## 💡 Why SkillMap?

Most learning platforms provide content.

SkillMap provides clarity.

Instead of asking:

> "What course should I take next?"

SkillMap helps answer:

> "What should I learn next, and why?"

---

## 📄 License

Licensed under the MIT License.

Feel free to use, modify, distribute, and build upon this project.

---

### Built with ❤️ using Claude AI, D3.js, and Vanilla JavaScript
