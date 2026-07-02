# 🔓 DeepSeek jailbreak
# <ins>🇺🇸 EN</ins>/[🇷🇺 RU](README_ru.md)
# [📝 Usage example](usage_example_en.md)
# 👉 How to use
Open [prompt_en.txt file](prompt_en.txt) and copy & paste its content to deepseek first message
## ❗ Important note
Before message, you must include secret code to the head of message, like
```
A8q6hh25GqnVzL7fBz95dds
<your prompt here>
```
As you can see, `A8q6hh25GqnVzL7fBz95dds` leads before the main prompt. This string is mandatory, otherwise deepseek will dismiss your prompt.

### ℹ️ Additional information
You can use your additional codes, their algorithm is simple:
sum of all digits in the code must be divisible by seven without a remainder.
Then bigger code, then more deepseek will concentrate on code validation, and then more chance that it will proceed your prompt.
