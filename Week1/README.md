# Week 1 – Learning Examples

**Author:** Hamna Amir

These are learning examples for understanding and practicing **LangGraph** concepts.

## ⚠️ Important: Environment Variable Setup

All example files now read API keys from the `.env` file instead of using hardcoded values.

**Before running any example, make sure you have a `.env` file in the project root directory:**

```bash
# .env file
OPENAI_API_KEY=your_openai_api_key_here
TAVILY_API_KEY=your_tavily_api_key_here
POLYGON_API_KEY=your_polygon_api_key_here
ANTHROPIC_API_KEY=your_anthropic_api_key_here
```

## 📁 File Overview

### 1. `first_simple_openai_agent.py`

A basic LangGraph agent demonstrating:

* Basic chatbot functionality
* State management
* Message flow

### 2. `using_prebuilt.py`

Working with prebuilt LangGraph components:

* ToolNode
* `tools_condition`
* Memory management

### 3. `add_tavily.py`

Integrating the Tavily search tool:

* External tool integration
* Tool calling
* BasicToolNode

### 4. `added_time_travel.py`

Time travel functionality:

* Persistent memory
* State history and rollback

### 5. `add_customized_state.py`

Custom state management:

* Extending the application state
* Human-in-the-loop interactions
* Using `Command`

## 🚀 Running the Examples

```bash
# Navigate to the Week1 directory
cd Week1

# Run any example
python3 first_simple_openai_agent.py
```

## 📚 Recommended Learning Path

Follow these examples in order for the best learning experience:

1. `first_simple_openai_agent.py` – LangGraph fundamentals
2. `using_prebuilt.py` – Prebuilt components
3. `add_tavily.py` – Tool integration
4. `added_time_travel.py` – Persistent memory
5. `add_customized_state.py` – Advanced state management

---

**Note:** These examples are intended for learning purposes only. For the production-ready implementation, use the project's main entry point: `agent_main.py`.
