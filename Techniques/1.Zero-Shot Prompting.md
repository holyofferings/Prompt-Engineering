## Zero shot Prompting 

Large language models (LLMs), including GPT-3.5 Turbo, GPT-4, and Claude 3, are designed to adhere to instructions and have been trained on vast datasets. This extensive training equips these models to handle certain tasks without needing prior examples—referred to as "zero-shot" capabilities. 
In zero-shot prompting, the prompt provided to the model lacks any example inputs or demonstrations. Instead, the prompt directly instructs the model to complete a task, relying solely on the model's understanding without additional guidance.

*Prompt:*
```
Classify the text into neutral, negative or positive. 

Text: I think the vacation is okay.
Sentiment:
```

*Output:*
```
Neutral
```

 Essentially, it relies on the model's pre-existing knowledge and generalization abilities to handle the task based on the prompt provided. 

### How Zero-Shot Prompting Works
- **General Knowledge**: The model uses its broad understanding of language and knowledge accumulated during its training to generate responses. It does not rely on task-specific examples.
- **Prompt Design**: Crafting a clear and specific prompt is crucial. Since the model doesn't have task-specific training data, the prompt needs to be precise and provide enough context to guide the model.
- **Inference**: The model makes inferences based on its general knowledge and the context provided in the prompt.
