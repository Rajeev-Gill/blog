---
title: Prompts to build stuff
description: This is a post template
date: 2024-11-11
tags:
  - Tech
layout: layouts/post.njk
---

## Title

an LLM leaderboard, based on the LLMs listed at this API endpoint: https://openrouter.ai/api/v1/models, the API at that URL returns 100+ objects of this format: {
      "id": "raifle/sorcererlm-8x22b",
      "name": "Sorcererlm 8x22b",
      "created": 1731105083,
      "description": "SorcererLM is an advanced RP and storytelling model, built as a Low-rank 16-bit LoRA fine-tuned on WizardLM-2-8x22B.\n\n- Advanced reasoning and emotional intelligence for engaging and immersive interactions\n- Vivid writing capabilities enriched with spatial and contextual awareness\n- Enhanced narrative depth, promoting creative and dynamic storytelling",
      "context_length": 16000,
      "architecture": {
        "modality": "text-\u003Etext",
        "tokenizer": "Mistral",
        "instruct_type": "vicuna"
      },
      "pricing": {
        "prompt": "0.0000045",
        "completion": "0.0000045",
        "image": "0",
        "request": "0"
      },
      "top_provider": {
        "context_length": 16000,
        "max_completion_tokens": null,
        "is_moderated": false
      },
      "per_request_limits": null
    }
the leaderboard should be an interactive table that can be filtered by searching and can be ordered by any of the columns, include columns for: id, name, Cost per million tokens for the prompt, Cost per million tokens for the completion, context length. For each LLM add a model popup that appears on hover with containing the LLM description, within the model include an option to Copy model id. Also include a feature whereby I can pin up to 4 models from the list so that the pinned models stay at the top of the table whilst the filter changes