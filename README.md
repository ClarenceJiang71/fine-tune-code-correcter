# fine-tune-code-correcter

When you ask a "code-fix" to ChatGPT 4o, it tends to return the whole block of code back with some modification. 

This is not convenient when your input is a large block of codes, and the only adjusted lines are like 1 or 2 lines. 

It tends to add some commments next to the revised lines, but returning "the entire code block" back still makes it hard to trace where exactly the revised places are. 

Using the background system prompt doesn't help much in my personal experience. 

This repo tries to fine tune based on GPT 3.5 to have a stable LLM that targets the right style of the response. 

The fine-tuning focuses on the "style and tone" category
