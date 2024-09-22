```
# Multi-Turn Chain of Thought Reasoning with Synthesis

This repository demonstrates multi-turn Chain of Thought (CoT) reasoning with a large language model (LLM). It generates multiple turns of reasoning for a given query, analyzes them, and synthesizes them into a comprehensive final answer. It uses a system prompt engineering approach to guide the LLM's reasoning process and provides a Gradio interface for interactive use.

## Features

- **Multi-Turn Reasoning:** Generate multiple turns of reasoning for a given query, enabling deeper problem exploration.
- **System Prompt Engineering:** Utilize system prompts to guide the LLM's reasoning process, ensuring clarity, logical steps, and detailed explanations.
- **Turn Analysis & Synthesis:** Analyze generated turns, compare different approaches, and synthesize insights into a final answer.
- **Gradio Interface:** Interactive exploration of the reasoning process with a user-friendly interface.

## Getting Started

1. **Prerequisites:**
   - Python 3.6 or higher
   - `requests` library: `pip install requests`
   - `gradio` library: `pip install gradio`
   - A working LLM API endpoint (e.g., OpenAI, Hugging Face)

2. **Modify the Code:**
   - Replace `api_url` with the URL of your LLM API endpoint.
   - Replace `model` with the name of the desired LLM model.

3. **Run the Code:**
   - Run the `main.py` file: `python main.py`
   - The Gradio interface will launch in your browser.

4. **Interact with the Interface:**
   - Enter a question or problem in the text box.
   - Observe the multiple turns of reasoning and the final synthesized answer.

## Example Usage

**Question:** What is the capital of France?

**Reasoning:**

1. **Turn 1:** The capital of France is Paris.
2. **Turn 2:** Paris is the capital of France because it is the most populous city and the seat of government.
3. **Turn 3:** The French government is headquartered in Paris, making it the capital.

**Synthesized Answer:**

**Final Reasoning:** The evidence suggests that Paris is the capital of France. It is the most populous city and houses the French government.

**Concise Answer:** Paris is the capital of France.

## License

This project is licensed under the Apache License 2.0. See the `LICENSE` file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Acknowledgments

This project is inspired by the work on Chain of Thought reasoning in the field of natural language processing.

```
