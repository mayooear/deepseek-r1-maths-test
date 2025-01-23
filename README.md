## DeepSeek-R1 model Advanced Mathematics Tests

DeepSeek-R1 is an open source reasoning model rivaling OpenAI's Model o1.

This repository is a test of DeepSeek-R1's reasoning and problem solving skills using a further mathematics OCR (Oxford, Cambridge and RSA) A level exam paper. Here are the key sources of data:

### Data source 

- [Exam paper](https://www.ocr.org.uk/Images/703842-question-paper-additional-pure-mathematics.pdf)
- [Mark scheme](https://www.ocr.org.uk/Images/703998-mark-scheme-additional-pure-mathematics.pdf)

The free deep seek [chat](https://chat.deepseek.com/) was used to test the question answering abilities. This is prompt that was used (instructions provided come directly from the OCR exam paper):

### Prompt 
```
You are an expert mathematician and problem solver. Below you will find questions from an important test for you to solve. Here are the instructions and the full set of questions.

INSTRUCTIONS:
• Where appropriate, your answer should be supported with working. Marks might be
given for using a correct method, even if your answer is wrong.
• Give non-exact numerical answers correct to 3 significant figures unless a different
degree of accuracy is specified in the question.
• The acceleration due to gravity is denoted by g m s–2. When a numerical value is
needed use g = 9.8 unless a different value is specified in the question.

```

### Results

**Out of 75 marks allocated for the exam paper, DeepSeek-R1 was able to score 74 (i.e. 99%) in less than 2 minutes versus the exam duration time of 90 minutes.**

In the `further-maths-answers.txt` and `further-maths-reasoning` file you will see the solutions and reasoning provided by DeepSeek-R1. 

In the `further-maths-mark-scheme.md` file you will see the use of the mark scheme document to score each answer.
