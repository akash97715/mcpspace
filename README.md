#  MCP Terminal Server using Gemini Client

Welcome to the **MCP (Model context protocol)** Terminal Server powered by the Gemini client!  
This project creates an intelligent terminal assistant that can execute commands on your behalf and continue interactive conversations — all from your terminal.

---

##  What is this?

This is your **first MCP server**, designed to act like an intelligent terminal buddy. It uses the **Gemini client** to communicate with a powerful LLM (Large Language Model), interprets your natural language queries, and uses Python's `subprocess` module to run actual commands on your system — just like you'd type them yourself!

---

##  Features

-  **Conversational Execution**: Ask it to do something in plain English — it'll respond and run commands for you.
-  **Tool Integration**: Uses a custom-defined tool (Python `subprocess`) to execute terminal commands.
-  **Directory Interaction**: Runs commands in your current directory context.
-  **Gemini Client Integration**: Backed by Google’s Gemini LLM for intelligent reasoning.
-  **Persistent Server**: Set up as a local server that continues the session and handles multiple commands.

---

## How it works

1. You send a query via terminal (e.g., _"List all files in this directory"_).
2. The **Gemini client** processes your intent and responds with a command (e.g., `ls -la`).
3. The **MCP server** runs this command using the `subprocess` module.
4. The result is captured and sent back into the conversation — keeping the interaction going.

---

## 📂 Project Structure

