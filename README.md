## Welcome to the AI playground
<div align="justify">
I have been listening to the YouTube channel <a href="https://www.youtube.com/@TechWithTim">Tech with Tim</a> to learn and experiment with AI agents. I will first look at the <i>no-code</i> implementation, such as <a href="https://n8n.io/">n8n</a>, where you can plug and play with a bunch of tools, and then move on to raw Python code. Because I am broke 🥸, I will use a local open-weights model such as Qwen2.5 with 7 billion parameters as the agent brain and Ollama, which is a wrapper around an inference engine to run the model and predict the next token. For my first implementation, I use n8n to build an agent harness and connect to tools such as Brave browser search, OpenWeather API, and Gmail. This agent polls and listens for incoming emails every 10 mins, and when it finds a new unread email, it understands what the sender wants, uses tools and web search if necessary, and returns a response in a Gmail reply. It summarizes all the unread emails and sends me a notification. <i>Example</i>
</div>
<br>

<img src="./Screenshot 2026-09-14 014735.png" width="500px">
