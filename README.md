# ChatGPT <img src="https://github.com/acheong08/ChatGPT/blob/main/logo.png?raw=true" width="7%"></img>
[![PyPi](https://img.shields.io/pypi/v/revChatGPT.svg)](https://pypi.python.org/pypi/revChatGPT)
[![PyPi](https://img.shields.io/pypi/dm/revChatGPT.svg)](https://pypi.python.org/pypi/revChatGPT)
[![Python package](https://github.com/acheong08/ChatGPT/actions/workflows/python-package.yml/badge.svg)](https://github.com/acheong08/ChatGPT/actions/workflows/python-package.yml)

Reverse Engineered ChatGPT by OpenAI. Extensible for chatbots etc.

# Notice 
### Only session authentication supported email/password deprecated.
OpenAI has added cloudflare to protect their services. Please use [session tokens](https://github.com/acheong08/ChatGPT/wiki/Setup#session-token-authentication) along with `cf_clearance` (more details in wiki)

## If you have a desktop interface (Non-server)
[reChatGPT-alpha](https://github.com/acheong08/ChatGPT/releases/tag/0.0.a42) uses chrome drivers to fetch the cf_clearance

Refer to [setup](https://github.com/acheong08/ChatGPT/blob/cloudflare/wiki/Setup.md) for instructions

# Instructions
Instructions have been moved to the [Wiki](https://github.com/acheong08/ChatGPT/wiki).

If you were using this prior to version 0.0.31, please update immediately. `pip3 install revChatGPT --upgrade`. Fixes has been done to avoid bot blocking

# iFeatures
![image](https://user-images.githubusercontent.com/36258159/205534498-acc59484-c4b4-487d-89a7-d7b884af709b.png)
- No moderation
- Programmable.
- Async version
- Email/password authentication
- Cookie based authentication
- Access Token authentication
- Captcha support 

# Flaws
- No ARM support for email/password. Use session token authentication if on Raspberry Pi

# Help needed
- Documentation for [OpenAIAuth](https://github.com/acheong08/OpenAIAuth)
- Update documentation for developers (with examples)

# Awesome ChatGPTs
[My list](https://github.com/stars/acheong08/lists/awesome-chatgpt)

If you have a cool project you want added to the list, open an issue.

# Disclaimers
This is not an official OpenAI product. This is a personal project and is not affiliated with OpenAI in any way. Don't sue me

# Credits
- [rawandahmad698](https://github.com/rawandahmad698) - Reverse engineering Auth0
- [FlorianREGAZ](https://github.com/FlorianREGAZ) - TLS client
- [PyRo1121](https://github.com/PyRo1121) - Linting
- [Harry-Jing](https://github.com/Harry-Jing) - Async support
- [Ukenn2112](https://github.com/Ukenn2112) - Documentation
- [aliferouss19](https://github.com/aliferouss19) - Logo
- [All other contributors](https://github.com/acheong08/ChatGPT/graphs/contributors)
