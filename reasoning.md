### Reasoning

**Model suitability:** A model is suitable if it can understand code semantics, generate insightful feedback, and identify reasoning gaps without revealing answers.  

**Testing meaningful prompts:** I tested the model by feeding multiple Python code snippets and checking whether the outputs summarize the code correctly, list key concepts, and give hints that encourage deeper learning.  

**Trade-offs:** Accuracy may be limited by model size, interpretability can decrease with more complex outputs, and larger models may require higher computational cost.  

**Choice of model:** StarCoder2-3B was chosen because it is open-source, trained on code, and capable of producing structured feedback. Its strengths include understanding Python syntax and generating human-readable insights, while limitations include occasional vagueness in reasoning hints and slower generation on standard GPUs.
