![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![HuggingFace](https://img.shields.io/badge/huggingface-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=white)

## The practice of using saiga_mistral_7b_gguf

В данном репозитории представлен код с реализацией модели **saiga_mistral_7b_gguf**, обученная на основе этой **Open-Orca/Mistral-7B-OpenOrca**. 

Для работы с этим кодом нужно зарегистрироваться на **Hugging Face** и в настройках профиля получить свой токен, который будет использоваться в коде.

В своей работе я использую *8-битную* квантованную версию, но вы можете использовать и *4-битную*. На крайний случай подойдет и *2-битная*, но её результат работы может не удовлетворять.

При использовании этого кода настоятельно рекомендую использовать **графический ускоритель T4** в **Google Colab**.

Важно!
> Для моего кода подходит именно квантованная версия модели (**GGUF**)
