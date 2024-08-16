# GradientLLM
An LLM Framework Using a Gradient Descent-Like Architecture: Self-refines its prompts with each iteration until it arrives at the correct answer. The LLM computes a "verbal loss" based on the feedback from each response, which it uses to improve the next iteration. The loss is calculated by another LLM, inspired by the concept of using an LLM as a judge. 
</br>
Implementing Textgrad without using Textgrad.
