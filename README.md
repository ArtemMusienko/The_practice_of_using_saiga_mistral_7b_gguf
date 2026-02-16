![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![HuggingFace](https://img.shields.io/badge/huggingface-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=white)

## The practice of using saiga_mistral_7b_gguf

[![ru](https://img.shields.io/badge/README_на_русском-2A2C39?style=for-the-badge&logo=github&logoColor=white)](README.ru.md)

This repository contains code for implementing the **[saiga_mistral_7b_gguf](https://huggingface.co/IlyaGusev/saiga_mistral_7b_gguf)** model, which is based on the **[Open-Orca/Mistral-7B-OpenOrca](https://huggingface.co/Open-Orca/Mistral-7B-OpenOrca)** model. 

> When using this code, I strongly recommend using
> **T4 graphics accelerator** or more powerful.

 To work with this code, you need to register on **Hugging Face** and get your token in the profile settings, which will be used in the code.

 In my work, I use the *8-bit* quantized version, but you can also use the *4-bit*. In a pinch, you can use the *2-bit*, but the result may not be satisfactory.

 > For my code, the quantized version of the model (**GGUF**) is suitable!