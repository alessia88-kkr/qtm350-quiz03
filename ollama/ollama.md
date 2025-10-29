# Activity 1: Sarcastic Chatbot 

## Commands used
```bash
# 1) Install & check
ollama --version

# 2) Pull base model (choose one)
ollama pull llama3.2:1b

# 3) Create project files
mkdir -p ollama
## Added Modelfile and ollama.md

# 4) Build the custom model
ollama create sarcastic -f ollama/Modelfile

# 5) Run tests
ollama run sarcastic "What is the capital of France?"

I'm just so thrilled you asked me this incredibly original question. The capital of France is Paris, because, of course, it's not like every single 
person on the planet already knows that. I mean, who needs Google when you have a highly advanced AI assistant like myself to spoon-feed basic 
geography facts?

ollama run sarcastic "Teach me recursion, briefly."

*Sigh* Fine. Recursion is a fundamental concept in programming that can be explained in excruciating detail.

Recursion involves breaking down a problem into smaller instances of the same problem, which are then solved by the same function. Think of it like 
this: imagine you have a tree with multiple branches, and each branch has its own smaller trees. You can solve the entire tree by recursively 
solving each individual branch, and then combining the results.For example, consider the Fibonacci sequence: 0, 1, 1, 2, 3, 5, 8, ... . To calculate this sequence using recursion, you'd write a function that 
takes an integer n as input, calculates the nth number in the sequence (which is simply the sum of the two preceding numbers), and then calls 
itself with n-1 to get the next number. Voilà! You've solved the entire sequence.Now, if you'll excuse me, I have more pressing matters to attend to... like trying to understand why you asked me to teach recursion in the first 
place.

ollama run sarcastic "Explain overfitting like I'm five."

*Sigh* Fine. Overfitting is when a model (like a fancy computer program) gets too good at predicting the wrong things. Imagine you have a toy box 
full of blocks, and your AI friend is trying to predict how many blocks will fall out if it's placed on a certain surface. If they get really good 
at this task, they might start using blocks that don't actually fit in the box, just because they think those are the ones that will work best.

It's like if you were trying to guess which of your toys would be the most likely to fall out when you shake the toy box. You'd start guessing all 
sorts of random things, even though some of them aren't very good guesses at all. That's basically what overfitting is – a model getting too good 
at predicting the wrong things, because it's trying so hard to fit every little detail in. Now, if you'll excuse me, I have more important things 
to attend to... like staring blankly into space and wondering where it all went wrong.

