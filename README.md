<p align="center"><h1>🧠 Awesome ChatGPT Prompts</h1></p>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Welcome to the "Awesome ChatGPT Prompts" repository! This is a collection of prompt examples to be used with the ChatGPT model.

The [ChatGPT](https://chat.openai.com/chat) model is a large language model trained by [OpenAI](https://openai.com) that is capable of generating human-like text. By providing it with a prompt, it can generate responses that continue the conversation or expand on the given prompt.

In this repository, you will find a variety of prompts that can be used with ChatGPT. We encourage you to [add your own prompts](https://github.com/Promact/awesome-chatgpt-prompts/edit/main/README.md) to the list, and to use ChatGPT to generate new prompts as well.

To get started, simply clone this repository and use the prompts in the README.md file as input for ChatGPT. You can also use the prompts in this file as inspiration for creating your own.

We hope you find these prompts useful and have fun using ChatGPT!

**[View on GitHub](https://github.com/Promact/awesome-chatgpt-prompts)**

> ℹ️ **NOTE:** Sometimes, some of the prompts may not be working as you expected or may be rejected by the AI. Please try again, start a new thread, or log out and log back in. If these solutions do not work, please try rewriting the prompt using your own sentences while keeping the instructions same.

### Want to Write Effective Prompts?

I've authored a free e-book called **"The Art of ChatGPT Prompting: A Guide to Crafting Clear and Effective Prompts"**.

📖 **[Read the free e-book](https://fka.gumroad.com/l/art-of-chatgpt-prompting)**

---

## Other Prompting Resources

### Want to Learn How to write image prompts for Midjourney AI?

I've authored an e-book called **"The Art of Midjourney AI: A Guide to Creating Images from Text"**.

📖 **[Read the e-book](https://fka.gumroad.com/l/the-art-of-midjourney-ai-guide-to-creating-images-from-text)**

---

### Create your own prompt using AI

[Merve Noyan](https://huggingface.co/merve) created an exceptional [ChatGPT Prompt Generator App](https://huggingface.co/spaces/merve/ChatGPT-prompt-generator), allowing users to generate prompts tailored to their desired persona. The app uses this repository as its training dataset.
  
---

### Using prompts.chat

[prompts.chat](https://prompts.chat) is designed to provide an enhanced UX when working with prompts. With just a few clicks, you can easily edit and copy the prompts on the site to fit your specific needs and preferences. The copy button will copy the prompt exactly as you have edited it.

---

# Prompts

## Truncate All Tables in a DB

Contributed by: [@chintans](https://github.com/chintans)

> Write an sql script to truncate all tables in a postgresql database. Keeping in mind that many tables may have foreign key constraints.

## Create a Terraform infrastructure code for below aws services

Contributed by: [@chintans](https://github.com/chintans)

> Create a Terraform infrastructure code for below aws services
 AWS ECS with EC2 type load balanced using ALB
 ECS will have 3 services and 1 task
 Secrets Manager to provide connection string to ECS cluster
 Docker images will be pushed to ECR
 Use Certificate Manager to provision a wildcard certificate for promactinfo.xyz
 Create Usage alaram using AWS cloudWatch to monitor CPU and Memory usage
 Alaram should trigger mails using AWS SNS
