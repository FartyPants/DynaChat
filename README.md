# DynaChat
WebUI extension for structured chat where you can dynamically change the history (previous responses) at any time 

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Q5Q5MOB4M)

{WIP}

This is another experiment at doing chat where each turn is saved as a history (that you can re-arrange, change, or remove). Basically I'm looking for more useful/dynamic chat interface

It comes from tweaking the BlockWrite - but more oriented as a chat interface.
## Note
I have a parallel project called [BlockWrite](https://github.com/FartyPants/BlockWriter) that is oriented on scene-by-scene story creation while uses simillar idea of dynamic history. 

![image](https://github.com/FartyPants/HistoryChat/assets/23346289/34568c1c-7136-4044-9151-e1785c0d41b6)

So basically at any time you can change both prompt or the generated text by simply overwritting it in the editors, or regenerating it again (for example tweaking the prompt), or both, which will then change the history that goes to LLM down the next turn.

You can specify how much last history to include or just switch it off (briefly)

![image](https://github.com/FartyPants/HistoryChat/assets/23346289/1f53e187-9d84-45d9-baa9-c34a26f3aaf1)

Entire conversation can be rendered into full text

![image](https://github.com/FartyPants/HistoryChat/assets/23346289/7471a4eb-50ec-4d3a-98c9-0b9064167174)

or JSONL

Again, since you can change anything at any time, this will reflects the generated text.

