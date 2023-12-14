# LLM_Hallucinations_Reducing
Reducing llm hallucinations. Author: **Oganyan Robert Vladimirovich**

Репозиторий создан по результатам работы на **Научно-Исследовательском Семинаре "Методы интеллектуального анализа данных"** под руководством **профессора. д. т. н., Крылова Владимира Владимировича**.

Работа посвящена рассмотрению способов уменьшения галлюцинаций и больших языковых моделей. Рассмотрены 3 способа:

1. Тюнинг температуры семплирования
2. [Factual-nucleus sampling](https://arxiv.org/pdf/2206.04624) 
3. [A stitch in time saves nine](https://arxiv.org/abs/2307.03987)... 

Для разных моделей:

1. Chatgpt
2. Claude
3. Gigachat
4. llamav2 3B



### Навигация

* `src` - папка с исходным кодом. Здесь:
  * `GPT-API, temperature and factual-nucleus.ipynb ` посвящен 1 и 2 способу для GPT
  * `llamav2, temperature and factual-nucleus.ipynb`посвящен 1 и 2 способу для llama
  * `GPT CLAUDE GIGA, meanings, stitch_in_time.ipynb` посвящен 3 способу для gpt, gigachat, claude для данных о значениях слов
  * `GPT CLAUDE GIGA, translations, stitch_in_time.ipynb` посвящен 3 способу для gpt, gigachat, claude для данных о переводах
* `article` - папка с написанной статьей об исследовании
* `presentation` - папка с презентацией проекта
* `data` - папка с результатами экспериментов
