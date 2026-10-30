### Hi, I'm unixyo

I run large local AI models on one AMD Radeon RX 6900 XT (RDNA2, gfx1030) and write down what actually works, with measurements and limits.

RX 6900 XT 한 장으로 로컬 AI를 돌리고, 실제로 된 설정과 측정값을 정리해 둡니다.

**RDNA2 / gfx1030 recipes**

| Repository | What it is |
|---|---|
| [strata-rdna2-gfx1030-recipe](https://github.com/unixyo/strata-rdna2-gfx1030-recipe) | Qwen3.8-Flash-Next on Strata with one RX 6900 XT + 64 GB RAM: ~1,200 tok/s prefill, 50-64 tok/s decode, 256K context. Settings, patches, measurements and what did not help. |
| [rdna2-gfx1030-imagegen-recipes](https://github.com/unixyo/rdna2-gfx1030-imagegen-recipes) | ComfyUI setups for Qwen-Image 2.1, MOSS-Image and MiniMax H3 on the same card. |

**Tools**

| Repository | What it is |
|---|---|
| [openai-daily-free-gate](https://github.com/unixyo/openai-daily-free-gate) | A local proxy that stops OpenAI API requests before they exceed the daily free-token limits of the data-sharing program. |

**Upstream reports**

- [Strata #4680](https://github.com/Niko1221/Strata/issues/4680): single RX 6900 XT benchmark report

Ubuntu · ROCm · ComfyUI · llama.cpp · Strata
