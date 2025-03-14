# MH_LLM


## Optimazing Large Language Models for Detecting Symptoms of Depression and Anxiety in Patients with Diabetes

## Abstract
This study evaluates the performance of large language models (LLMs) in detecting symptoms of depression and anxiety from secure patient messages. We tested multiple approaches, including engineered prompts, systemic persona, temperature adjustments, and zero-shot and few-shot learning. Three out of five LLMs demonstrated excellent performance, with Llama 3.1 405B achieving 93% in both F-1 and accuracy using a zero-shot approach. While LLMs showed promise in binary classification and handling complex metrics like the Patient Health Questionnaire-4, inconsistencies in challenging cases warrant further real-life assessment. These findings highlight the potential of LLMs to assist in timely screening and referrals, improving mental health care for patients with chronic diseases.

## Introduction
Patients with diabetes are at increased risk of comorbid depression or anxiety, complicating their management. Detecting these symptoms is challenging due to patient unawareness, clinicians' limited time, and overlapping symptoms. This study aims to evaluate the performance of LLMs in detecting these symptoms from secure patient messages.

## Methods
- **Data Source**: Secure patient messages from individuals with diabetes and comorbid depression or anxiety.
- **Benchmark Data**: Messages were deidentified and labeled by researchers and psychiatrists.
- **LLMs Evaluated**: Llama 3.1 8B, Llama 3.1 405B, Gemini Pro 1.5, OpenAI o1, and DeepSeek R1.
- **Approaches**: Zero-shot vs. few-shot learning, binary classification vs. PHQ-4 based classification, with vs. without systemic persona, and temperature adjustments.

## Results
- **Performance**: Llama 3.1 405B achieved the highest performance with 93% F-1 and accuracy in zero-shot settings.
- **Binary vs. PHQ-4**: Binary classification showed superior performance, but PHQ-4 was competitive in knowledge models.
- **Systemic Persona**: Enhanced performance in few-shot settings but decreased in zero-shot.
- **Challenging Cases**: DeepSeek R1 showed competitive performance, but other models struggled.

## Discussion
LLMs demonstrated excellent performance in detecting symptoms of depression and anxiety, with potential for real-world application. However, inconsistencies in challenging cases highlight the need for further assessment. The zero-shot approach showed promising efficiency, reducing the need for fine-tuning.

## Conclusion
This study highlights the potential of LLMs to assist in timely screening and referrals for mental health care in patients with chronic diseases. Further real-life assessments are needed to validate these findings.

## Contact
For more information, please contact:
- [Jiyeong Kim, PhD, MPH]
- [jykim3 at stanford dot edu]

