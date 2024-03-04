
## Evaluating LLMs with Promptfoo

# This is the first experiment being made with Promptfoo to try and assert LLM benchmarks locally.
# More on this will be developed further.

Install promptfoo with node.js running the folowing command
 ```
npm install promptfoo
```
With it installed, run 
```
promptfoo init
```

To get started, set your OPENAI_API_KEY (or another LLM provider API) environment variable on your machine.

Next, edit promptfooconfig.yaml to your liking based on what you would like to evaluate.

Then run:
```
promptfoo eval
```

Afterwards, you can view the results by running `promptfoo view` for the web UI or on the terminal itself.
