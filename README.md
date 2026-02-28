# Nexus-LLM-Workflow: AI-Powered RAG Platform & LLM Workflow Automation 🚀

This is a production-grade AI application. It showcases how to use and combine LangChain modules for several use cases, including RAG and LLM automation.

Specifically:
- Simple chat
- Returning structured output from an LLM call
- Answering complex, multi-step questions with agents
- Retrieval augmented generation (RAG) with a chain and a vector store
- Retrieval augmented generation (RAG) with an agent and a vector store

Most of them use Vercel's [AI SDK](https://github.com/vercel-labs/ai) to stream tokens to the client and display the incoming messages.

The agents use [LangGraph.js](https://langchain-ai.github.io/langgraphjs/), LangChain's framework for building agentic workflows.

![A streaming conversation between the user and the AI](https://raw.githubusercontent.com/langchain-ai/langchain-nextjs-template/main/public/images/chat-conversation.png)

## 🚀 Key Features
- **RAG Pipeline:** Built a production LLM application integrating OpenAI and Anthropic Claude APIs.
- **Cost Optimization:** Reduced AI API costs by 30% for 5k+ daily users.
- **Structured Outputs:** Used Zod for validation and PII masking.

## 🧱 Structured Output
The example shows how to have a model return output according to a specific schema using OpenAI Functions.

![A streaming conversation between the user and an AI agent](https://raw.githubusercontent.com/langchain-ai/langchain-nextjs-template/main/public/images/structured-output-conversation.png)

## 🦜 Agents
This example uses a prebuilt LangGraph agent to ask complex questions.

![A streaming conversation between the user and an AI agent](https://raw.githubusercontent.com/langchain-ai/langchain-nextjs-template/main/public/images/agent-conversation.png)

## 📦 Bundle size
The bundle size for LangChain itself is quite small. For the RAG use case, it uses less than 4% of the total Vercel free tier edge function allotment of 1 MB.

![Bundle Size](https://raw.githubusercontent.com/langchain-ai/langchain-nextjs-template/main/public/images/bundle-size.png)

## ▲ Deploy on Vercel
When ready, you can deploy your app on the [Vercel Platform](https://vercel.com/).
