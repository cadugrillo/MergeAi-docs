---
title: Chat Completions
description: 
no_list: true
# categories: []
# tags: []
weight: 1
---

Chat Completions is where you interact via text, or image (when available) with the most advanced LLMs (Large Language Models) on the market.

* The easiest way to start is by selecting a Thread (by clicking on it) and start typing your messages. If you don't have any Threads, create one by using the "add" button (1).

* If you want to change the model or advanced options click on the "gear" (2). More details at [Configuring Chat Completions](/docs/using-mergeai/chat-completions/configuration).

<figure><img src="/docs/using-conciergeai/chat-completions/overview.png" alt="" width="900" style="border: 1px solid #555;"><figcaption></figcaption></figure>

{{% alert %}}
You can only type/send your message (6), attach file (4) or dictate (5) when a Thread is selected.  
If the selected Model is capable of ingest images, the "attach file (4)" option will be available.
{{% /alert %}}

### **Threads**

Threads are a group of Chat Messages. You can think of Threads being the subject of a conversation, holding all related messages that belongs to that subejct.

You can create up to 100 Threads but only the first 50 will be shown at the Threads browser on the left side of the screen.

### **Chat Messages**

Each chat message has a role (either system, user, or assistant) and content.

* The system message is optional and can be used to set the behavior of the assistant

* The user messages provide requests or comments for the assistant to respond to

* Assistant messages is the answer from the model

{{% alert %}}
By default, the system message is "You are a helpful assistant". You can define instructions in the user message, but the instructions set in the system message are more effective. You can only set one system message per Thread.
{{% /alert %}}

To customize the system message and other advanced options check [Configuring Chat Completions](/docs/using-mergeai/chat-completions/configuration).

### **Model**

You can check the selected LLM Model by looking at the Selected Model Chip (7).

Differently from the system message wich is unique per Thread, the LLM Model can be changed at any time. That means you can start a chat with Model "A" and continue the same chat with Model "B".

To customize the LLM Model and other advanced options check [Configuring Chat Completions](/docs/using-mergeai/chat-completions/configuration).

### **Pricing**

Chat Completions pricing is based on token usage. You can think of tokens as pieces of words used for natural language processing. For more details visit [What is a token?](/docs/faq/what-is-token/).

For price details per Model visit [Pricing](/pricing/).


## Where should I go next?

- [Configuring Chat Completions](/docs/using-mergeai/chat-completions/configuration)
- [Frequently Asked Questions](/docs/faq/)