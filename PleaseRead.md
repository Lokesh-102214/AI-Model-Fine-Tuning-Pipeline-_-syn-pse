Please ensure training dataset has fields named essay for text and description for prompts respectively

For now please only choose SmolLm in model selection

Towards the end of the demo video we run into a bit of trouble in pushing the model to hugging face due to discrepancy in Hugging Face repo name and token variables, current ipynb has corrected repo variable but token variable is still wrong, in push code please change its 2 instances to "token = token_input.value"
