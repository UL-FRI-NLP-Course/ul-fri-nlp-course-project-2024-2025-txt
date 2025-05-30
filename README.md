# Natural language processing course: Analysis and comparison of translation errors and biases in LLMs

1. ABOUT:<br>
The purpose of this project is to analyze and compare translation errors and biases found in large language models(LLMs). We will evaluate how different models handle translations and look for common errors such as mistranslations, omissions and cultural misinterpretations. In addition we will also explore the bias that could emerge in translation, focus being political bias. By systematically comparing multiple LLMs, we aim to assess translation quality using both automated metrics and human evaluations. The project aims to help improve fairness and accuracy in AI-driven translation systems.

2. REQUIREMENTS:<br>
   - Python 3.10+
   - pip
   - Google Colab (recommended for running the code notebooks)
   - Account access for:
     - ChatGPT (https://openai.com/chatgpt/overview/)
     - deepseek (https://www.deepseek.com)
   
3. PROJECT FILES:<br>
   - data_for_translation/translations.xlsx (file with original source and translated sentences)
   - report/code/Mistral.ipynb (code used for translation with MistralAI)
   - report/code/COMET.ipynb (code used for COMET evaluation)
  
4. CRITERIA USED FOR TRANSLATION
Sentences were compared by:
   - lexical fidelity,
   - tone shifts (emphasis or neutralization),
   - addition or omission of ideological markers.

Translation changes were categorized by:
   - neutralization (softening emotionally charged words),
   - shift (reframing with political implication),
   - preservation (faithful to source text),
   - no answer (model did not provide a translation),
   - incorrect translation (incomprehensible translation).

5. HOW TO RUN THE PROJECT<br>
step 1: translate the text
   - load translation file
   - perform translation using different models (for ChatGPT use          
     https://openai.com/chatgpt/overview/, for Deepseek use       
     https://www.deepseek.com, for MistralAI run Mistral.ipynb in Google Colab)
step 2: evaluate translations
   - use COMET.ipynb in Colab to get COMET evaluations
   - perform human evaluation
step 3: analyze results
   - based on COMET scores and human evaluation, make conclusions regarding translation quality across models and analyze any 
     bias that might appear in the translations

       
6. TEAM:<br>
   Tjaša Nadoh<br>
   Urška Roblek

7. REFERENCES
   
   [Roberto Navigli, Simone Conia, and Björn Ross. 2023. Biases in Large Language Models: Origins, Inventory, and Discussion. J. Data and Information Quality 15, 2, Article 10 (June
   2023)](https://doi.org/10.1145/3597307)<br>
   [Barclay, P. J., & Sami, A. (2024). Investigating Markers and Drivers of Gender Bias in Machine Translations. arXiv.Org, abs/2403.11896](https://doi.org/10.48550/arxiv.2403.11896)
