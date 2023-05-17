# Learn Langchain with local LLMs (Vicuna, Alpaca, etc.)
Custom Langchain Agent with local LLMs
The code is optimize with the local LLMs for experiments. You can try with different models: Vicuna, Alpaca, gpt 4 x alpaca, gpt4-x-alpasta-30b-128g-4bit, etc. For more information, please check this [link](https://github.com/QuangBK/localLLM_langchain).

## Install
The code only requires the [oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui).For the installation instruction, please follow [this](https://github.com/oobabooga/text-generation-webui#installation).

## How to run
First, start the oobabooga server. Then you can run the LLM agent in the notebook file.

```sh
python server.py --model your_model_name --listen --api
```
