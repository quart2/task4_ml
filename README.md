Task chatbot
## Objective of the Task
The objective of this task was to develop a simple Python-based system that answers a given question by extracting relevant information from provided context text.

## Methodology / Approach
1. **Data Preparation**:  
   - Context passages about Firefox’s browser tab and window behavior were provided.  
   - A specific question was asked regarding opening a new browser window in Firefox.

2. **Implementation**:  
   - Used Python with a local Hugging Face transformer model to perform question answering without requiring an API key.
   - Applied a pipeline for text generation / question answering to produce an accurate, concise answer.

3. **Execution Environment**:  
   - Model was loaded on CPU.
   - All dependencies were installed locally without using paid APIs.

## Key Results or Observations
- The system successfully generated the answer:
  > "It is only necessary to open the browser window once on the desktop."
- The pipeline worked entirely offline, which makes it suitable for environments without internet or API access.
- Using a larger `max_length` improved context handling and reduced truncation errors.


