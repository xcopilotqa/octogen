<p align="center">
<img width="100px" src="https://github.com/dbpunk-labs/octopus/assets/8623385/6c60cb2b-415f-4979-9dc2-b8ce1958e17a" align="center"/>

![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/dbpunk-labs/octopus/ci.yml?branch=main&style=flat-square)
[![Discord](https://badgen.net/badge/icon/discord?icon=discord&label)](https://discord.gg/UjSHsjaz66)
[![Twitter Follow](https://img.shields.io/twitter/follow/OCopilot7817?style=flat-square)](https://twitter.com/OCopilot7817)

Octopus is an open-source code interpreter for terminal users

<p align="center">
<img width="1000px" src="https://github.com/dbpunk-labs/octopus/assets/8623385/5609a3d7-b82e-494f-817f-37ff88544320" align="center"/>


## Getting Started

## How It works

Core components

* Kernel: The code execution engine, based on notebook kernels.
* Agent: Manages client requests, uses ReAct to process complex tasks, and stores user-assembled applications.
* Chat: Accepts user requests, sends them to the Agent, and renders rich results. Currently supports Discord, iTerm2, and Kitty terminals.

For security, it is recommended to run the kernel and agent as Docker containers.
![octopus_simple](https://github.com/dbpunk-labs/octopus/assets/8623385/588e0381-f0b7-4ca6-a2c5-6c801c0e481f)



## Demo

[octopus_demo.webm](https://github.com/dbpunk-labs/octopus/assets/8623385/41f31972-5655-43d3-9d5d-d55e926cb6f8)


### API Service Supported

|name|status| note|
|----|----------------|---|
|[Openai GPT 3.5/4](https://openai.com/product#made-for-developers) | ✅ fully supported|the detail installation steps|
|[Azure Openai GPT 3.5/4](https://azure.microsoft.com/en-us/products/ai-services/openai-service) |  ✅ fully supported|the detail install steps|
|[LLama.cpp Server](https://github.com/ggerganov/llama.cpp/tree/master/examples/server) | ✅ fully supported| You must provide the model|

### Deployment

## Home Labs Solutions

## Medias
python & bash: requirements.txt
typescripts: tslab , tslab install

## Thanks

* [Octopus icons created by Whitevector - Flaticon](https://www.flaticon.com/free-icons/octopus)
