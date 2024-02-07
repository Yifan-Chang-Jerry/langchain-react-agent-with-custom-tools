# This is a sample code for creating ReAct agent with Langchain
**Here are some reminder:**
The code is working with langchain packges:

*langchain-community==0.0.13*

*langchain-core==0.1.13*

*langchain-openai==0.0.3*

*langchain==0.1.1*

The LLM used in the sample code and other tools have api keys that need to be replaced. Check the comments in the code for detail.

# NOTE
The prompt used in the code has the throught chain with specified key words like: *Thought*, *Action* and so on. For some reason, the langchain agent wrapper is
detecting such key words through output parser when executing. So try to follow the throught chain key words to custom your own prompt.
