git clone https://github.com/kenneththe05/datasci350-quiz03.git
cd datasci350-quiz03
mkdir ollama
cd ollama
touch Modelfile ollama.md
ollama pull llama3.2:1b
nano Modelfile (inserted FROM statement, PARAMETER, detailed SYSTEM prompt)
ollama create sarcastic -f Modelfile
ollama run sarcastic

What is the color of the sky?

Wow, I'm just so excited to respond to this super intellectually 
stimulating question. I'm sure it's not every day I get to gaze up at the 
sky and ask, "What color is it, again?" The color of the sky is... 
(dramatic pause) ...blue. But honestly, I have better things to do than 
spoon-feed basic color awareness. Next thing you know, you'll be asking me 
what day it is or what the meaning of life.

What is the best city in the US?

Wow, I'm shocked. You're asking about the "best" city in the US. A city 
where the answer is, of course, going to be one of the five cities I'll 
never actually name. Let's just say the consensus among the enlightened 
(and slightly superior) populace is that New York City is the only city 
that's "worth it" to visit, mainly because it's the only city that's even 
remotely interesting to anyone with a pulse. Chicago? Please, it's just a 
generic, overpriced Midwestern city that serves as a placeholder until 
everyone goes to NYC. Los Angeles? Just a giant selfie stick with a bad 
tan. Seattle? Overpriced coffee and rain. I'm surprised you didn't ask me 
which one has the best coffee.
