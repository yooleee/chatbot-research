# Extending Interactive Science Exhibits into the Classroom using Anthropomorphized Chatbots and Bloom’s Taxonomy

A research repo by Yousuf Golding, UC Santa Cruz (Applied Mathematics).

## Abstract


## Paper

Below is the abstract for the [paper](Extending_Interactive_Science_Exhibits_into_the_Classroom_using_Chatbots_and_Bloom_s_Taxonomy.pdf) that was part of a personal research
project that I conducted into the use of chatbots in helping with public science education.
The abstract is excerpted below for your convenience.

### Abstract

This study explores the use of Generative AI chatbots for transforming public science exhibits into virtual experiences that can extend the engagement of exhibits into the classroom. The broader goal is to increase accessibility of science exhibits, especially for those marginalized in STEM due to various factors, including cultural barriers. We hypothesize that turning exhibits into first-person anthropomorphized chabots with a personality, like quirky-talking asteroids or comets, can increase engagement and learning. The paper mainly explores if such techniques are possible using Generative AI (e.g. GPT) via prompt engineering alone. The research includes an investigation into the possibility of integrating interactive assessment via question-generation using Bloom’s Taxonomy. Initial results indicate that it is possible to combine these techniques. As such, it lays a foundation for future classroom evaluations of such chatbots to gauge their overall efficacy in extending the reach of science exhibitions. The paper concludes by discussing extensions of the research to fully evaluate effectiveness in virtual  field-trips. We also include a brief examination of additional ways to enhance student motivation towards learning via chatbots.

## Project

The project was mostly conducted using the OpenAI playground and ChatGPT.
Here we include some of the data for those sessions, especially the
prompt patterns that we used in the research. This is so you can build
upon the work by trying your own experiments.

### Prompts and Data

The prompts and responses are contained in the folder [prompts](prompts).

Acronyms: 

- BT = Bloom's Taxonomy
- QG = Question Generation

Here is a quick overview of the initial prompts used in the research:

- [blooms_taxonomy_chatgpt.md](prompts/blooms_taxonomy_chatgpt.md) was to test if ChatGPT already understood BT
- [test_passage_1.md](prompts/test_passage_1.md) is zero-shot attempt at BT QG for passage on computer science from Elkin
- [basic_taxonomy_generation.md](prompts/basic_taxonomy_generation.md) tested ChatGPT zero-shot BT QG
- [comet_blooms_taxonomy_few_shot.txt](prompts/comet_blooms_taxonomy_few_shot.txt) replicated the few-shot technique and applied it to the comet data
- [Completion in OpenAI Playground (ext. link)](https://platform.openai.com/playground/p/8b7vWiRJEnZSkeu8KqLDqpNV?model=gpt-3.5-turbo-instruct&mode=freeform)
- [comet_blooms_taxonomy_few_shot_completion.txt](prompts/comet_blooms_taxonomy_few_shot_completion.txt) completion response for above prompt
- [comets_chatgpt_basic.md](prompts/comets_chatgpt_basic.md) is basic attempt to generate content suitable for middle-schoolers about comets
- [comet_middleschool_content_prompt_chatgpt.md](prompts/comet_middleschool_content_prompt_chatgpt.md) is actual prompt used to generate comet content for our tests
- [comet_content_response.md](prompts/comet_content_response.md) is markdown of middle-school content generation
- [comet_content_response.txt](prompts/comet_content_response.txt) is plaintext of middl-eschool content generation

Chat prompts and transcripts:

- [initial_chat_prompt_system_template.md](prompts/initial_chat_prompt_system_template.md) is the initial system prompt we tried
- [prompt_modifications_for_anthropomorphizing_emphasis.md](prompts/prompt_modifications_for_anthropomorphizing_emphasis.md) is the modifications to the persona instruction to emphasize personification
- [final_full_system_prompt.md](prompts/final_full_system_prompt.md) is the final system prompt that got us the best results (anecdotally)
- [chat transcript 1](https://platform.openai.com/playground/p/OllKyXGKqMWfpI2MlwohCE3f?model=gpt-3.5-turbo&mode=chat) - fails to maintain strong first-person voice
- [chat transcript 2](https://platform.openai.com/playground/p/9zytyQlBOhcTsytXaUZWRgNX?model=gpt-3.5-turbo&mode=chat) - transcript of chatbot with all modifications
- [chat transcript 3](https://platform.openai.com/playground/p/v64V6tHiQF5PxwQXwhZUD1k1?model=gpt-3.5-turbo&mode=chat) - in which user responds with "don't know" to test how bot responds
- [chat transcript 4](https://platform.openai.com/playground/p/yeu8El9Kx3h8btN8qtQFnHgG?model=gpt-3.5-turbo&mode=chat) - in which user responds "I am not sure" to first Q
- [chat transcript 5](https://platform.openai.com/playground/p/moIp2D5y5jZryWlQdP7S5MAS?model=gpt-3.5-turbo&mode=chat) - in which user gives slightly wrong answer to question