# Day 2: 5 Essential LLM Workflow Design Patterns for Building Robust AI Systems

<br/>

## Day 2

<br/>

![5 Essential LLM Workflow Design Patterns for Building Robust AI Systems](../img/week01-day02-pic01.png)

<br/>

![5 Essential LLM Workflow Design Patterns for Building Robust AI Systems](../img/week01-day02-pic02.png)

<br/>

![5 Essential LLM Workflow Design Patterns for Building Robust AI Systems](../img/week01-day02-pic03.png)

<br/>

![5 Essential LLM Workflow Design Patterns for Building Robust AI Systems](../img/week01-day02-pic04.png)

<br/>

![5 Essential LLM Workflow Design Patterns for Building Robust AI Systems](../img/week01-day02-pic05.png)

<br/>

### Day 4

<br/>

![5 Essential LLM Workflow Design Patterns for Building Robust AI Systems](../img/week01-day04-pic01.png)

<br/>

![5 Essential LLM Workflow Design Patterns for Building Robust AI Systems](../img/week01-day04-pic02.png)

<br/>

**Step 2:**

<br/>

В вашем массиве tools сейчас зарегистрирован только один инструмент — record_email_tool. Модель активирует его (и вернет finish_reason=="tool_calls") только тогда, когда одновременно выполняются два условия:Вы дали ей четкую команду на запись.Вы предоставили аргумент для функции — сам email-адрес (текст со знаком @ и доменом).

<br/>

```
"Какой у меня email?"
```

```
Запиши мой email: marley@example.com
```

<br/>

email записывается в файл emails.txt

<br/>

![5 Essential LLM Workflow Design Patterns for Building Robust AI Systems](../img/week01-day04-pic03.png)

<br/>

**Step 3:**

Вариант на шаге 3 намного лучше. Он защищен от ошибок, если пользователь передаст несколько email-адресов сразу, и готов к расширению, если в будущем вы добавите в переменную tools новые сложные инструменты.

<br/>

## Day 5

<br/>

**24 - Day 5 - Creating & Deploying an AI Agent - From Chat Loop to HuggingFace Spaces**

<br/>

```shell
$ cd twin
$ uv pip install -r requirements.txt
$ uv run app.py
```

<br/>

![Creating & Deploying an AI Agent - From Chat Loop to HuggingFace Spaces](../img/week01-day05-pic01.png)

<br/>

**25 - Day 5 - Deploying Career Conversation Chatbots to Gradio**

<br/>

```shell
$ gradio deploy
```

<br/>

![Deploying Career Conversation Chatbots to Gradio](../img/week01-day05-pic02.png)

<br/>

![Deploying Career Conversation Chatbots to Gradio](../img/week01-day05-pic03.png)
