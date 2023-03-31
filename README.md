# Awesome_alternative_llms[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
open source ChatGPT and GPT4 alternatives for LLMs

 
## multi lang models
- [FastChat](https://github.com/lm-sys/FastChat)

- [Llama-X](https://github.com/AetherCortex/Llama-X)

- [LLaMA-Adapter](https://github.com/ZrrSkywalker/LLaMA-Adapter)

- [LLaMA-cpp](https://github.com/ggerganov/llama.cpp)

- [LLAMA download](https://github.com/shawwn/llama-dl)

- [stanford_alpaca](https://github.com/tatsu-lab/stanford_alpaca)

- [alpaca-lora](https://github.com/tloen/alpaca-lora)

- [gpt4all](https://github.com/nomic-ai/gpt4all)

- [gpt4all-visualization](https://atlas.nomic.ai/map/gpt4all_data_clean_without_p3)


## Chinese models
* [Chinese shibing624 LMFT](https://github.com/shibing624/lmft)

* [Chinese luotuo](https://github.com/LC1332/Chinese-alpaca-lora)

* [Chinese BELLE](https://github.com/LianjiaTech/BELLE)

* [Chinese-LLaMA-Alpaca (macbert author)](https://github.com/ymcui/Chinese-LLaMA-Alpaca)

* [clue-github](https://github.com/clue-ai/ChatYuan)

* [clue v2-huggingface](https://huggingface.co/spaces/ClueAI/ChatYuan-large-v2)

* [CLUEbenchmark](https://github.com/CLUEbenchmark)

* [PromptCLUE-HF](https://huggingface.co/ClueAI/PromptCLUE-base) 

### glm 6b

- 模型已经开源至 Hugging Face Hub，可以直接利用 HF Trainer 等进行训练；RLHF 部分，亦可以直接利用 trlx 等库进行实现

* [glm6b-ptuning:P-Tuning and INT4 quantization, only requires 7GB GPU memory](https://github.com/THUDM/ChatGLM-6B/blob/main/ptuning/README.md)

* [glm6b-c++ mnn onnx](https://github.com/wangzhaode/ChatGLM-MNN)

#### glm6b-finetune-lora
* [zero_nlp](https://github.com/yuanzhoulvpi2017/zero_nlp/tree/main/simple_thu_chatglm6b)
* [lich99](https://github.com/lich99/ChatGLM-finetune-LoRA)
* [mymusise](https://github.com/mymusise/ChatGLM-Tuning)
* [ssbuild](https://github.com/ssbuild/chatglm_finetuning)
* [chenyiwan](https://github.com/chenyiwan/chatglm-6b-fine-tuning)

## multi-modal 
* [visual-openllm](https://github.com/visual-openllm/visual-openllm)


## tools
* [huggingface/peft](https://github.com/huggingface/peft)

* [trlx RLHF](https://github.com/CarperAI/trlx)

* [langchain](https://github.com/hwchase17/langchain)

* [dataset-chinese-zbench](https://github.com/zhenbench/z-bench)

* [dataset-chinese belle : can find in LianjiaTech github and HF BelleGroup](https://huggingface.co/datasets/BelleGroup/generated_train_0.5M_CN)

* [dataset-chinese-pCLUE](https://github.com/CLUEbenchmark/pCLUE)

## finetune blog
* [fine-tune-alpaca-with-lora](https://replicate.com/blog/fine-tune-alpaca-with-lora?continueFlag=4ecae39885197a5c008faabbefb5c824)
* [hugging face official blog in chinese:在一张 24 GB 的消费级显卡上用 RLHF 微调 20B LLMs ](https://zhuanlan.zhihu.com/p/616346543?utm_medium=social&utm_oi=762255747382796288&utm_psn=1622284420437450752&utm_source=wechat_session&utm_id=0)
* [hugging face official blog :Fine-tuning 20B LLMs with RLHF on a 24GB consumer GPU ](https://huggingface.co/blog/trl-peft)



 
## others
-  内存泄漏检查: 内存分析工具: Eclipse Memory Analyzer、VisualVM

### unsure but maybe useful
能否用GLM的pretrain代码和finetune代码来做CahtGLM的continue pretrain和finetune？
https://github.com/THUDM/GLM/blob/main/pretrain_glm.py
https://github.com/THUDM/GLM/blob/main/finetune_glm.py

-[glm issue3 ](https://github.com/THUDM/ChatGLM-6B/issues/3)
-[glm issue67](https://github.com/THUDM/ChatGLM-6B/issues/67)
