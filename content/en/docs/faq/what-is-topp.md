---
title: What is Top P?
description:
# categories: []
# tags: []
weight: 3
---

Top P or nucleus sampling is a parameter that decides how many possible words to consider. A high “Top P” value means the model looks at more possible words, even the less likely ones, which makes the generated text more diverse. Top P can vary from 0 to 1.

* Top P = 0.5: The model considers words that together add up to at least 50% of the total probability, leaving out the less likely ones and keeping a good level of varied responses.

* Top P = 0.9: The model includes a lot more words in the choice, allowing for more variety and originality.


### **Examples of Top P**

* **Top P = 0.5**: If you ask for a title for an adventure book, with a top-p of 0.5, the model might come up with: “The Mystery of the Blue Mountain.”

* **Top P = 0.9**: For the same adventure book title and a top-p of 0.9, the model might create: “Voices from the Abyss: A Portrait of the Brave.”


## Where should I go next?

- [Frequently Asked Questions](/docs/faq/)