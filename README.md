# 🦙💬 Llama 2 Chat Bot

This chatbot is created using the open-source Llama 2 LLM model from Meta.

Particularly, we're using the [**Llama2-7B**](https://replicate.com/a16z-infra/llama7b-v2-chat) model deployed by the Andreessen Horowitz (a16z) team and hosted on the [Replicate](https://replicate.com/) platform.

This app was refactored from [a16z's implementation](https://github.com/a16z-infra/llama2-chatbot) of their [LLaMA2 Chatbot](https://www.llama2.ai/) to be light-weight for deployment to the [Streamlit Community Cloud](https://streamlit.io/cloud).

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://llama2.streamlitapp.com/)

## Prerequisite libraries

```
streamlit
replicate
llama-cpp-python
```

## Getting your own Replicate API token

To use this app, you'll need to get your own [Replicate](https://replicate.com/) API token.

After signing up to Replicate, you can access your API token from [this page](https://replicate.com/account/api-tokens).

## Check the app using your own replicate api key
(https://llama2chatbot-2ws9rgtgropipjxffoq2tn.streamlit.app/)

## Other Llama 2 models to try

As mentioned above, this chatbot implementation uses the [**Llama2-7B**](https://replicate.com/a16z-infra/llama7b-v2-chat) model that was trained on 7 billion parameters.

You can also try out the larger models:
- [Llama2-13B](https://replicate.com/a16z-infra/llama13b-v2-chat)
- [Llama2-70B](https://replicate.com/replicate/llama70b-v2-chat)
