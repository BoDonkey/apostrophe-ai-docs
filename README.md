# apostrophe-ai-docs
This repo is a Jupyter document for asking questions of the Apostrophe docs using your own OpenAI key.

This is a beta test and results should be taken with caution. Testing thus far has been with Python core 3.11.5.

A tester question, like "How can I add a new page type to my project", will cost about $0.14 to run. Changing to the GPT-4 will cost more. Changing to GPT-3.5-turbo will drop the cost to about $0.07. The default model seems to produce the best results with the default values.

The returned reference links work about 50% of the time and will need revision in the future.

To read output, I typically open the final output in a text editor by clicking the link and then save it as an `.md` file.