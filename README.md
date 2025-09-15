# AI-Powered Knowledge Graph to Manim Animation Automation

## Overview

This project is an AI-powered system designed to automate the creation of educational videos from books and knowledge graphs. It integrates artificial intelligence for content generation with Manim for mathematical and conceptual animations. The goal is to simplify the process of transforming academic material into engaging, animated educational content.

The system allows students to:

* Submit a query about a concept (e.g., *"Explain Dijkstra's Algorithm"*).
* Retrieve relevant information from a knowledge base derived from books.
* Use AI to generate a structured video plan, including slides and narration.
* Convert the plan into a Manim animation script.
* Render the final educational video and provide it as an accessible resource.

Potential domains of application include:

* Geographic Information Systems (GIS)
* Space Technology
* Data Structures and Algorithms
* Artificial Intelligence and Machine Learning

---

## System Architecture

1. **Knowledge Retrieval**
   The system loads the knowledge base and extracts relevant text segments based on the user query.

2. **AI Video Plan Generation**
   A large language model generates a structured JSON plan describing the video content (slides, narration, and visuals).

3. **Manim Script Creation**
   The JSON plan is translated into a Python script compatible with Manim.

4. **Rendering**
   The Manim script is rendered into a video file.

5. **Finalization**
   The rendered video is stored and a link to the output is provided.

---

## Project Structure

```
├── data/                # Books, PDFs, knowledge graphs
├── src/
│   ├── knowledge_base/  # Knowledge retrieval system
│   ├── ai_generation/   # AI-based plan generation
│   ├── manim_scripts/   # Manim script generation
│   ├── rendering/       # Video rendering utilities
│   └── main.py          # Main pipeline controller
├── examples/            # Example queries and outputs
└── README.md            # Project documentation
```

---

## Technology Stack

* **Python** – Core programming language
* **Manim** – Mathematical and conceptual animations
* **LLMs (Large Language Models)** – Content generation
* **JSON** – Structured representation of video plans
* **Local/Cloud Storage** – Management of rendered video assets

---
