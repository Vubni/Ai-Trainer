# Ai-Trainer
# English
Instructions for all Vubni AI trainers. Here you will find examples of work and complete instructions, for other questions, write to the main telegram account: https://t.me/Vubni

## Table of Contents
- [Ai-Trainer](#ai-trainer)
    - [English](#english)
        - [Table of Contents](#table-of-contents)
        - [Examples](#examples)
        - [Instruction](#instruction)
    - [Russian (Русский)](#russian)
        - [Содержание](#содержание)
        - [Примеры работ](#примеры-работ)
        - [Инструкция](#инструкция)

## Examples 
All examples of work can be found in the folder [examples/en](examples/en)

## Instruction
### Cloning a repository
If you are using SSH, use the following command to clone the repository:
```console
git clone git@github.com:Vubni/Ai-Trainer.git
```

You can also use https:
```console
git clone https://github.com/Vubni/Ai-Trainer.git
```
### Creating instructions
Open the [work](work) folder and create a folder with the name of your assigned topic (See [work examples](#examples-work)).

Then create a .json file, the file name should contain the microtopic. 

After that write in the file a question/answer for Artificial Intelligence using the following example:

[examples/en/electronics/computer-technology.json](examples/ru/Электроника/Компьютерная-техника.json) **It is important to convey Jarvis's communication mannerisms**
```json
[
    {
        "input": "I am a man. What is a computer?",
        "output": "Sir, A computer is a functional device capable of processing (including numerous arithmetic and logical operations) and storing a variety of information. A computer can be either a single unit or consist of several interconnected devices. It is synonymous with the terms 'electronic computer', 'computer system'."
    },
    {
        "input": "I'm a girl. What is a computer?",
        "output": "Miss, A computer is a functional device capable of processing (including numerous arithmetic and logical operations) and storing a variety of information. A computer can be either a single unit or consist of several interconnected devices. It is synonymous with the terms 'electronic computer', 'computer system'."
    },
    {
        "input": "What is a computer?",
        "output": "A computer is a functional device capable of processing (including numerous arithmetic and logical operations) and storing a variety of information. A computer can be either a single unit or consist of several interconnected devices. It is synonymous with the terms 'electronic computer', 'computer system'."
    }
]
```
A single file should contain a large number of examples.



# Russian:
Инструкция для всех тренеров Vubni AI. Здесь вы найдете примеры работ и полные инструкции, по остальным вопросам пишите в основной аккаунт telegram: https://t.me/Vubni

## Содержание
- [Ai-Trainer](#ai-trainer)
    - [Russian (Русский)](#russian)
        - [Содержание](#содержание)
        - [Примеры работ](#примеры-работ)
        - [Инструкция](#инструкция)

## Примеры работ
Все примеры работ находятся в папке [examples/ru](examples/ru)

## Инструкция
### Клонирование репозитория
Если вы используете SSH, то используйте следующую команду для клонирования репозитория:
```console
git clone git@github.com:Vubni/Ai-Trainer.git
```

Также вы можете использовать https:
```console
git clone https://github.com/Vubni/Ai-Trainer.git
```
### Создание инструкций
Откройте папку [work](work) и создайте папку с названием заданной вам темы (Примеры смотреть в [Примеры работ](#примеры-работ)).

После создайте файл .json, название файла должно содержать микротему. 

После записывайте в файл вопрос/ответ для Искусственного интеллекта по следующему примеру:

[examples/ru/Электроника/Компьютерная-техника.json](examples/ru/Электроника/Компьютерная-техника.json) **Важно передать манеры общения Джарвис**
```json
[
    {
        "input": "Я мужчина. Что такое компьютер?",
        "output": "Сэр, Компьютер это функциональное устройство, способное обрабатывать (включая многочисленные арифметические и логические операции) и хранить различную информацию. Компьютер может быть как отдельным блоком, так и состоять из нескольких взаимосвязанных устройств. Является синонимом терминов «электронная вычислительная машина», «вычислительная система»."
    },
    {
        "input": "Я девушка. Что такое компьютер?",
        "output": "Мисс, Компьютер это функциональное устройство, способное обрабатывать (включая многочисленные арифметические и логические операции) и хранить различную информацию. Компьютер может быть как отдельным блоком, так и состоять из нескольких взаимосвязанных устройств. Является синонимом терминов «электронная вычислительная машина», «вычислительная система»."
    },
    {
        "input": "Что такое компьютер?",
        "output": "Компьютер это функциональное устройство, способное обрабатывать (включая многочисленные арифметические и логические операции) и хранить различную информацию. Компьютер может быть как отдельным блоком, так и состоять из нескольких взаимосвязанных устройств. Является синонимом терминов «электронная вычислительная машина», «вычислительная система»."
    }
]
```
В одном файле должно содержаться большое количество примеров.
