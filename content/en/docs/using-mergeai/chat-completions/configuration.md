---
title: Configuring Chat Completions
description: 
# categories: []
# tags: []
weight: 2
---

The Configuration menu is displayed when you click on the "gear" icon at the Header Bar.

<figure><img src="/docs/using-conciergeai/chat-completions/configuration.png" alt="" width="900" style="border: 1px solid #555;"><figcaption></figcaption></figure>


### **Model**

Merge.ai is powered by a diverse set of models with different capabilities and price points. You can choose them using the drop-down menu (1).

For price details per Model visit [Pricing](/pricing/).

### **Temperature**

Temperature value controls the output balance between coherence and creativity. Lower values for temperature result in more consistent outputs (e.g. 0.2), while higher values generate more diverse and creative results (e.g. 1.0). The default value is 1.

For more details visit [What is Temperature?](/docs/faq/what-is-temperature/).

### **Top P**

Top P or nucleus sampling is a setting that decides how many possible words to consider. A high “Top P” value means the model looks at more possible words, even the less likely ones, which makes the generated text more diverse.

For more details visit [What is Top P?](/docs/faq/what-is-topp/).

### **System Message**

The System Message is a special input provided to the model to steer its behavior and set the context for its interactions. Its primary purpose is to define guidelines, tone, or instructions on how the model should respond to user inputs. This helps ensure that the generated outputs are aligned with the desired objectives and constraints.

The default message is **"You are a helpful assistant"** and there are two ways of changing it:

* Typing your desired System Message at the input text field

* Choose a pre-defined Prompt Pattern from the **"Prompt Patterns"** drop-down menu

For more details on Prompt Patterns visit [Prompt Patterns Explorer](/docs/using-mergeai/prompt-patterns).


## Where should I go next?

- [Chat with Documents](/docs/using-mergeai/chat-with-documents)
- [Frequently Asked Questions](/docs/faq/)