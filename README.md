# Building LLMs From Scratch

### 1. Large Language Model Text Preparation

This notebook demonstrates the process of preparing text for training large language models (LLMs). The preparation steps include tokenization, byte pair encoding (BPE), sampling training examples, and converting tokens into vectors that can be used for model training.

### Steps Covered

<table>
  <tr>
    <th>Method</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Tokenization</td>
    <td>Splitting text into word and subword tokens for easier processing.</td>
  </tr>
  <tr>
    <td>Byte Pair Encoding (BPE)</td>
    <td>Combining frequent character pairs to create a fixed-size vocabulary of subword tokens, which improves tokenization efficiency.</td>
  </tr>
  <tr>
    <td>Sliding Window Sampling</td>
    <td>Generating training samples using a sliding window approach to create sequences from text.</td>
  </tr>
  <tr>
    <td>Vectorization</td>
    <td>Transforming tokens into vectors to feed into large language models for training.</td>
  </tr>
</table>

### How to Use

1. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/AnkitaMungalpara/Building-LLM-From-Scratch.git
   cd Building-LLM-From-Scratch
