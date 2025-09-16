# SemEval-2026 Task 7: Everyday Knowledge Accross Diverse Languages and Cultures Trial Data



This README file describes the datasets *trial_data_multiple_choice.tsv* and *trial_data_unique_answer.tsv*, 
provided as trial data for the SemEval-2026 Task 7: Everyday Knowledge Across Diverse Languages and Cultures.



## trial_data_multiple_choice.tsv

This file contains the trial data with multiple-choice options.

### Columns:

- **index**: Data point index.

- **lang_reg**: Language and region code.

- The mapping between the codes and the full language-country names is as follows:

| Code  | Language – Region            |
|-------|------------------------------|
| ms-SG | Malay (Singapore)            |
| ta-SG | Tamil (Singapore)            |
| zh-SG | Chinese (Singapore)          |
| es-EC | Spanish (Ecuador)            |
| en-GB | English (United Kingdom)     |
| zh-CN | Chinese (China)              |
| es-ES | Spanish (Spain)              |
| es-MX | Spanish (Mexico)             |
| id-ID | Indonesian (Indonesia)       |
| ko-KR | Korean (South Korea)         |
| el-GR | Greek (Greece)               |
| fa-IR | Persian/Farsi (Iran)         |
| ar-EG | Arabic (Egypt)               |
| ar-MA | Arabic (Morocco)             |
| ar-SA | Arabic (Saudi Arabia)        |
| en-AU | English (Australia)          |
| eu-ES | Basque (Spain – Basque Country) |
| fr-FR | French (France)              |
| ga-IE | Irish (Ireland)              |
| ta-LK | Tamil (Sri Lanka)            |
| tl-PH | Tagalog (Philippines)        |
| bg-BG | Bulgarian (Bulgaria)         |
| ja-JP | Japanese (Japan)             |

- **question**: The question text.

- **multiple_choice_option**s: The multiple-choice options for the question. Newline characters separate individual options. 

- **correct_answer**: The correct answer to the question. Leading and trailing whitespace has been removed from this column.


 ## trial_data_unique_answer.tsv

- This file contains the trial data with only the correct answer, excluding the multiple-choice options.

### Columns:

- **index**: Data point index

- **lang_reg**: Language and region code.

- The mapping between the codes and the full language-country names is as follows:

| Code   | Language – Region               |
|--------|---------------------------------|
| ms-SG | Malay (Singapore)               |
| ta-SG | Tamil (Singapore)               |
| zh-SG | Chinese (Singapore)             |
| es-EC | Spanish (Ecuador)               |
| en-GB | English (United Kingdom)        |
| zh-CN | Chinese (China)                 |
| es-ES | Spanish (Spain)                 |
| es-MX | Spanish (Mexico)                |
| id-ID | Indonesian (Indonesia)          |
| ko-KR | Korean (South Korea)            |
| el-GR | Greek (Greece)                  |
| fa-IR | Persian/Farsi (Iran)            |
| ar-EG | Arabic (Egypt)                  |
| ar-MA | Arabic (Morocco)                |
| ar-SA | Arabic (Saudi Arabia)           |
| en-AU | English (Australia)             |
| eu-ES | Basque (Spain – Basque Country) |
| fr-FR | French (France)                 |
| ga-IE | Irish (Ireland)                 |
| ta-LK | Tamil (Sri Lanka)               |
| tl-PH | Tagalog (Philippines)           |
| bg-BG | Bulgarian (Bulgaria)            |
| ja-JP | Japanese (Japan)                |

- **question**: The question text.

- **correct_answer**: The correct answer to the question.
