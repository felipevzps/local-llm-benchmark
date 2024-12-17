# local-llm-benchmark

This repository contains the results and methodology for locally benchmarking small/medium models on key tasks relevant to my personal use cases.

## Metrics Evaluated

1. **Text Summarization**
   - **Coverage:** Capturing the main ideas from the original text.
   - **Concision:** Eliminating redundancy while preserving meaning.
   - **Coherence:** Logical flow and connection of ideas.
   - **Fluency:** Proper grammar and natural language usage.
   - **Fidelity:** Avoiding misinformation or additions not present in the original text (hallucination).

2. **Code Generation**
   - **Correctness:** Whether the code runs without errors.
   - **Efficiency:** Optimization and clarity of the generated code.
   - **Documentation:** Clarity of comments or explanation included in the code.
   
## Evaluation Methodology

- Each model is tested using the same dataset and prompts. 
- Responses are manually evaluated using the metrics above, and results are scored on a scale from 1 to 5.
- Scores are averaged to determine overall performance for each task.

## Evaluation

| Model                                                                                      | Text Summarization | Code Generation | Overall Score |
|--------------------------------------------------------------------------------------------|--------------------|-----------------|---------------|
| [llama3.2:3b](https://ollama.com/library/llama3.2:3b)                                      | -                  | -               | -             |
| [qwen2.5:3b](https://ollama.com/library/qwen2.5:3b)                                        | -                  | -               | -             |
| [phi3.5:3.8b](https://ollama.com/library/phi3.5:3.8b)                                      | -                  | -               | -             |
| [phi-4:Q4_K-M](https://ollama.com/vanilj/Phi-4)                                            | -                  | -               | -             |
| [llama3.1:8b-instruct-q6_K](https://ollama.com/library/llama3.1:8b-instruct-q6_K)          | -                  | -               | -             |
