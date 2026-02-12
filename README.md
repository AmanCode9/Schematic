# Schematic 🚀
**Engineered Content Generation via Structured Style Deconstruction**

**Schematic** is a content engineering tool designed to replicate specific professional writing styles. Instead of relying on generic AI prompts, it deconstructs successful LinkedIn posts into structured JSON "blueprints." By utilizing **Few-Shot Learning**, the system guides Large Language Models (LLMs) to mirror the exact hooks, structure, and tone of a target creator.

## ✨ Key Features
- **Style Analysis:** Extracts metadata such as Topic, Language, and Length from existing content.
- **Few-Shot Learning:** Injects contextually relevant past posts into the LLM prompt to ensure high-fidelity style replication.
- **Customizable Generation:** High-level control over post parameters including topic selection and language.
- **Streamlit Interface:** A clean, interactive dashboard for seamless content creation.

## 🛠️ Technical Architecture

### Stage 1: Data Extraction & Deconstruction
The system processes raw LinkedIn content to extract structural fingerprints (Topic, Language, Length). These are stored and managed to serve as a reference library.

### Stage 2: Contextual Generation (Few-Shot Inference)
When generating a new post, the engine retrieves specific past examples that match the user's selected criteria. These examples are used for few-shot learning, providing the LLM with a "schematic" of the desired output style.

## ⚙️ Setup & Installation

1. **Get your API Key:** Obtain a `GROQ_API_KEY` from the [Groq Console](https://console.groq.com/keys).
   
2. **Configure Environment:** Create a `.env` file in the root directory and add your key:
   ```env
   GROQ_API_KEY=your_api_key_here

3. **Install Dependencies:**
pip install -r requirements.txt

4. **Run the Application:**
streamlit run main.py

Developed as a portfolio project focusing on LLM Orchestration and Prompt Engineering.
### Why this is better for your placement:
* **Terminology:** Using words like "Inference Engine," "Structural Fingerprints," and "Metadata" shows you understand the tech stack.
* **Focus on Logic:** It moves away from the "Mohan" example and explains the *logic* of the code (the deconstruction and the few-shot learning).
* **Clean Formatting:** The use of emojis and clear headers makes it scannable for recruiters who only spend 30 seconds on a repo.

**Once you paste this in, would you like me to help you prepare for a technical interview by explaining how your `few_shot.py` actually selects those posts?**