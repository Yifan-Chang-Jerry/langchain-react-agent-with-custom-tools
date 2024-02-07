# Langchain ReAct Agent Sample Code

This repository contains sample code to demonstrate how to create a ReAct agent using Langchain. It's designed to be simple yet informative, guiding you through the essentials of integrating custom tools with Langchain.

## 🚀 Quick Start

To get started with this sample, ensure you have the following Langchain packages installed:

- `langchain-community==0.0.13`
- `langchain-core==0.1.13`
- `langchain-openai==0.0.3`
- `langchain==0.1.1`

These packages are crucial for the functionality of the ReAct agent showcased in this sample.

## 🔑 API Keys Reminder

The sample code utilizes LLMs and other tools that require API keys. **Remember to replace the placeholder keys with your own**. Detailed instructions and locations for these replacements are provided within the code comments.

## 📘 Note on Prompts

The code constructs prompts with a thought chain that includes specific keywords such as *Thought*, *Action*, etc. The Langchain agent wrapper is designed to recognize these keywords through its output parser during execution. To customize your prompts effectively, adhere to this thought chain structure and incorporate the mentioned keywords.

---

## Customizing Your Agent

To make your agent truly yours, follow the structure provided and adjust the prompts according to your requirements. This flexibility allows you to experiment with different thought processes and action sequences, tailoring the agent's behavior to your specific needs.

---

Happy coding! 🎉
