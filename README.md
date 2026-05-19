# Hi, I'm Foolke 

I'm a Fullstack Engineer based in Berlin. My path into tech comes with a background in **Environmental Informatics**—which basically means I don't just care about whether code runs, but also how efficiently and cleanly it handles data. 

I really enjoy bridging the gap between heavy backend logic and smooth, performance-driven frontend visualizations. If it automates a tedious workflow or removes system friction, I'm probably interested in building it.

---

## What I Work With

* **Frontend:** Angular, RxJS, D3.js (for making complex data actually look good and responsive)
* **Backend:** Node.js (Express), FastAPI, Python, TypeScript
* **DevOps & Tools:** Docker, Multi-Tier Orchestration, Git lifecycles
* **Next-Gen Tech:** AR Foundation (Unity/C#), Local LLM architectures (Ollama / Llama 3)

---

## Projects I've Been Building Lately

### 🧠 [AI Project Insight](https://github.com/Foolki/ai-project-insight)
I wanted to see how far you can push automated code analysis without sending private repository data to cloud APIs. This engine combines Dockerized static code analyzers (`Pylint`, `Radon`) with local AI insights.
* **How it works:** It boots up an isolated environment, runs metrics, and uses an asynchronous `Ollama` instance running `Llama 3` to evaluate code architecture.
* **The Stack:** Python, FastAPI, Docker, Ollama, Streamlit.

### 📐 [AR Energy Visualizer](https://github.com/Foolki/ar-energy-visualizer)
A project aimed at making abstract energy data tangible for homeowners. Instead of looking at confusing spreadsheets, users can see efficiency measures (like heat pumps or insulation) mapped directly onto their walls at a 1:1 scale.
* **How it works:** It connects a relational data model (ER model) with Unity's spatial tracking, decoupling the heavy mesh calculations from the rendering loop to keep the frame rate stable.
* **The Stack:** Unity 2022.3 (LTS), AR Foundation, C#.

### 🛰️ [Reactive IoT Stream Processor](https://github.com/Foolki/architecture-logic-samples)
A production-grade logic sample dealing with high-frequency data noise. It targets the specific problem of browser UI lagging when flooded with IoT sensor data.
* **How it works:** An event-driven RxJS pipeline that captures sub-second signals, buffers them into clean 1-second chunks, and feeds them into D3.js without blocking the main thread.
* **The Stack:** TypeScript, Angular, RxJS, D3.js.

---

## What Drives My Engineering Approach

* **Data Integrity:** Keeping state management clean and asynchronous. Data should move seamlessly from the database directly into the UI viewport without lagging the experience.
* **Resource Efficiency:** Thanks to environmental informatics, I always look at the system footprint. Local processing, smart caching, and tight containerization are my go-to choices.
* **Clean & Defensive Code:** Writing strict TypeScript interfaces and solid middleware to catch errors early, rather than debugging them under pressure in production.

---

## Let's Connect

I'm always down to talk about fullstack development, data visualization, green tech, or interesting architectural problems. 

* 📍 Based in Berlin, Germany
* 📬 Feel free to check out my repositories or reach out for a technical chat!
