# Benchmark Library
<img src="image.png" alt="Bench-Library" width="512"/>

This collection inspired by the amazing work of [llm_benchmarks](https://github.com/leobeeson/llm_benchmarks) and [llm-benchmark](https://github.com/terryyz/llm-benchmark). We’re all about collecting a diverse range of benchmarks that bring new perspectives to the table. Contributions are always welcome!

## Benchmarks

### General
General benchmarks assess the overall performance of machine learning models across various tasks, including language understanding and knowledge representation, often using well-known datasets like GLUE and SuperGLUE to evaluate model capabilities in a standardized manner.

| Benchmark | Description | Resource |
| --- | --- | --- |
Massive Multitask Language Understanding (MMLU) | Measures general knowledge across 57 different subjects, ranging from STEM to social sciences. | [GitHub](https://github.com/hendrycks/test) 
General Language Understanding Evaluation (GLUE) |A collection of various language tasks from multiple datasets, designed to measure overall language understanding. | [Website](https://gluebenchmark.com/) 
SuperGLUE | An advanced version of the GLUE benchmark, comprising more challenging and diverse language tasks. | [Dataset](https://huggingface.co/datasets/super_glue) 
| Natural Questions | A collection of real-world questions people have Googled, paired with relevant Wikipedia pages to extract answers. | [Website](https://ai.google.com/research/NaturalQuestions) |
| LAnguage Modelling Broadened to Account for Discourse Aspects (LAMBADA) | A collection of passages testing the ability of language models to understand and predict text based on long-range context. | [Dataset](https://huggingface.co/datasets/lambada) |
| TriviaQA | A reading comprehension test with questions from sources like Wikipedia, demanding contextual analysis. | [GitHub](https://github.com/mandarjoshi90/triviaqa) |
| SciQ | Consists of multiple-choice questions mainly in natural sciences like physics, chemistry, and biology. | [Dataset](https://huggingface.co/datasets/sciq) |
| TruthfulQA | A benchmark for evaluating the truthfulness of LLMs in generating answers to questions prone to false beliefs and biases. | [GitHub](https://github.com/sylinrl/TruthfulQA) |

<!-- | --- | --- | [Dataset]() |
| --- | --- | [GitHub]() |
| --- | --- | [arXiv]() |
| --- | --- | [Website]() | -->

### Reasoning
Reasoning benchmarks focus on evaluating a model's ability to perform logical reasoning and inference, with datasets like ARC and HellaSwag designed to test models on their understanding of complex scenarios and their ability to draw conclusions from given information.

| Benchmark | Description | Resource |
| --- | --- | --- |
AI2 Reasoning Challenge (ARC) | Tests LLMs on grade-school science questions, requiring both deep general knowledge and reasoning abilities. | [Dataset](https://huggingface.co/datasets/ai2_arc) 
HellaSwag | Tests natural language inference by requiring LLMs to complete passages in a way that requires understanding intricate details. | [GitHub](https://github.com/rowanz/hellaswag/tree/master/data) 
Discrete Reasoning Over Paragraphs (DROP) | An adversarially-created reading comprehension benchmark requiring models to navigate through references and execute operations like addition or sorting. | [Dataset](https://huggingface.co/datasets/drop) 
| Multi-Genre Natural Language Inference (MultiNLI) | A benchmark consisting of 433K sentence pairs across various genres of English data, testing natural language inference. | [Website](https://cims.nyu.edu/~sbowman/multinli/) |
| WinoGrande | A large set of problems based on the Winograd Schema Challenge, testing context understanding in sentences. | [GitHub](https://github.com/allenai/winogrande) |
| Counterfactual Reasoning Assessment (CRASS)| Evaluates counterfactual reasoning abilities of LLMs, focusing on "what if" scenarios. | [Dataset](https://github.com/apergo-ai/CRASS-data-set/tree/main) |
| BIG-bench | It includes a diverse set of tasks to evaluate how well models can generalize and perform across various challenges | [GitHub](https://github.com/google/BIG-bench) |
| Big-Bench Hard (BBH) | A subset of BIG-Bench focusing on the most challenging tasks requiring multi-step reasoning.| [GitHub](https://github.com/suzgunmirac/BIG-Bench-Hard) |
| AGIEval | A collection of standardized tests, including GRE, GMAT, SAT, LSAT, and civil service exams. | [GitHub](https://github.com/ruixiangcui/AGIEval/tree/main) |
| BoolQ | A collection of over 15,000 real yes/no questions from Google searches, paired with Wikipedia passages.| [Dataset](https://huggingface.co/datasets/boolq) |
| Physical Interaction: Question Answering (PIQA) | Tests knowledge and understanding of the physical world through hypothetical scenarios and solutions. | [GitHub](https://github.com/ybisk/ybisk.github.io/tree/master/piqa) |

<!-- | --- | --- | [Dataset]() |
| --- | --- | [GitHub]() |
| --- | --- | [arXiv]() |
| --- | --- | [Website]() | -->

### Coding
Coding benchmarks evaluate the performance of models in programming tasks, such as code generation and understanding, with datasets like CodeXGLUE providing a comprehensive suite of tasks to measure how well models can handle programming languages and related challenges.

| Benchmark | Description | Resource |
| --- | --- | --- |
HumanEval | Contains programming challenges for evaluating LLMs' ability to write functional code based on instructions. | [GitHub](https://github.com/openai/human-eval)
CodeXGLUE | Evaluates LLMs' ability to understand and work with code across various tasks like code completion and translation.| [GitHub](https://github.com/microsoft/CodeXGLUE) 
| Mostly Basic Python Programming (MBPP) | Includes 1,000 Python programming problems suitable for entry-level programmers. | [Dataset](https://huggingface.co/datasets/google-research-datasets/mbpp) |
| LiveCodeBench | It focuses on assessing how well models can generate code snippets based on user prompts and interactions. | [GitHub](https://github.com/LiveCodeBench/LiveCodeBench) |

<!-- | --- | --- | [Dataset]() |
| --- | --- | [GitHub]() |
| --- | --- | [arXiv]() |
| --- | --- | [Website]() | -->

###  Math
Math benchmarks assess a model's mathematical problem-solving abilities, utilizing datasets like MATH, which includes a variety of mathematical problems that require reasoning and computation, testing the model's capability to understand and solve complex mathematical tasks.

| Benchmark | Description | Resource |
| --- | --- | --- |
Grade School Math 8K(GSM8K)| It consists of 8,000 grade school math problems that require multi-step reasoning to solve.| [Dataset](https://huggingface.co/datasets/openai/gsm8k) 
MATH |The MATH dataset consists of 12,500 problems derived from high school math competitions. | [Dataset](https://paperswithcode.com/sota/math-word-problem-solving-on-math) 

<!-- | --- | --- | [Dataset]() |
| --- | --- | [GitHub]() |
| --- | --- | [arXiv]() |
| --- | --- | [Website]() | -->

### Conversation
Conversation benchmarks evaluate the ability of models to engage in multi-turn dialogues, focusing on maintaining context and generating coherent responses, with datasets like Persona-Chat and DSTC designed to measure conversational fluency and relevance in human-like interactions.

| Benchmark | Description | Resource |
| --- | --- | --- |
MT-bench | Tailored for evaluating the proficiency of chat assistants in sustaining multi-turn conversations. | [Dataset](https://huggingface.co/datasets/lmsys/mt_bench_human_judgments) 
Question Answering in Context (QuAC) | Features 14,000 dialogues with 100,000 question-answer pairs, simulating student-teacher interactions. | [Website](https://quac.ai/) 
| BotChat | Evaluating LLMs' multi-round chatting capability via assessing conversations generated by two LLM instances. | [GitHub](https://github.com/open-compass/BotChat) |

<!-- | --- | --- | [Dataset]() |
| --- | --- | [GitHub]() |
| --- | --- | [arXiv]() |
| --- | --- | [Website]() | -->

### Others
This category encompasses various benchmarks that do not fit into the previous classifications, including specialized tasks in areas like image captioning or ethical AI considerations, providing a broader evaluation of model capabilities across diverse applications.

 Capability | Benchmark | Description | Resource |
| --- | --- | --- | --- |
| Tool Use | API-Bank | For evaluating the capabilities of tool-augmented large language models (LLMs). | [arXiv](https://arxiv.org/pdf/2304.08244) |
| Clinical Documentation | Ambient Clinical Intelligence Benchmark (ACI-BENCH) | Evaluates the ability of models to generate clinical notes from doctor-patient conversations, enhancing automated documentation in healthcare. | [GitHub](https://github.com/wyim/aci-bench) |
| Question Answering | MAchine Reading COmprehension Dataset (MS-MARCO) | Tests models on their ability to understand and respond to real-world queries derived from web searches, crucial for search engines and AI applications. | [Dataset](https://huggingface.co/datasets/ms_marco) |
| Meeting Summarization | Query-based Multi-domain Meeting Summarization (QMSum)| Evaluates models' ability to extract and summarize relevant information from meeting transcripts based on specific queries, useful for business intelligence. | [GitHub](https://github.com/Yale-LILY/QMSum) |
| Toxicity Detection | ToxiGen | Tests models' ability to identify and avoid generating toxic content, focusing on implicit hate speech and content moderation. | [GitHub](https://github.com/microsoft/TOXIGEN/tree/main) |
| Ethical Alignment | Helpfulness, Honesty, Harmlessness (HHH) | Evaluates language models' alignment with ethical standards, focusing on their helpfulness, honesty, and harmlessness in interactions. | [GitHub](https://github.com/anthropics/hh-rlhf) |
| Hallucination Evaluation | HaluEval | It includes 35,000 generated and human-annotated samples to assess LLMs' ability to recognize hallucinations in various tasks such as question answering, dialogue, and summarization. | [GitHub](https://github.com/RUCAIBox/HaluEval) |
| Real-Time Strategy | LLM Colosseum | Evaluate LLMs in real time with Street Fighter III | [GitHub](https://github.com/OpenGenerativeAI/llm-colosseum) |


<!-- 
| --- | --- | --- | [Dataset]() |
| --- | --- | [GitHub]() |
| --- | --- | [arXiv]() |
| --- | --- | [Website]() | -->