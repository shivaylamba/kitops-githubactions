# this is a sample kitfile
manifestVersion: 1.0.0
package:
  name: llama3
  version: 3.0.0
  description: Llama 3 family of large language models (LLMs), a collection of pretrained and instruction tuned generative text models in 8 and 70B sizes.
  authors: ['Meta Platforms, Inc.']
model:
  name: llama3-8b-8B-instruct-q5_0
  path: models/llama3-8b-8B-instruct-q5_0.gguf
  license: META LLAMA 3 COMMUNITY LICENSE AGREEMENT
  description: Llama 3 8B instruct model
code:
  - path: docs/LICENSE
    description: License file.
  - path: docs/README.md
    description: Readme file.
  - path: docs/USE_POLICY.md
    description: Use policy file.
