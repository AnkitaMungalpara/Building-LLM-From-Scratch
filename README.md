# Building LLMs From Scratch

### [1. Large Language Model Text Preparation](https://github.com/AnkitaMungalpara/Building-LLM-From-Scratch/blob/main/00_Working_with_Text_Data.ipynb)

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

<br>

### [2. Simple Self-Attention Without Trainable Weights](https://github.com/AnkitaMungalpara/Building-LLM-From-Scratch/blob/main/01_Self_Attention_In_Work_Part_1.ipynb)

This notebook demonstrates the implementation of a simple self-attention mechanism without trainable weights. It explores the core concepts behind attention mechanisms, such as dot products, normalization, and the creation of context vectors, providing a foundational understanding of how attention works in large language models (LLMs).

### Steps Covered

<table>
  <tr>
    <th>Method</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Dot Product Attention</td>
    <td>Calculating the similarity between query vectors and input tokens to obtain attention scores.</td>
  </tr>
  <tr>
    <td>Normalization (Softmax)</td>
    <td>Converting attention scores into probabilities using the softmax function, ensuring they sum to one.</td>
  </tr>
  <tr>
    <td>Context Vector Calculation</td>
    <td>Generating context vectors by computing the weighted sum of input vectors based on the attention weights.</td>
  </tr>
</table>

<br>

### [3. Scaled Dot-Product Attention with Trainable Weights](https://github.com/AnkitaMungalpara/Building-LLM-From-Scratch/blob/main/02_Self_Attention_with_Trainable_Weights_Part_2.ipynb)

This notebook expands on the previous implementation by incorporating trainable weights into the self-attention mechanism. The goal is to explore how attention scores are computed using trainable matrices and how these scores are transformed into attention weights to create context vectors, key components in transformer-based models like large language models (LLMs).

### Steps Covered

<table>
  <tr>
    <th>Method</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Weight Matrices (Wq, Wk, Wv)</td>
    <td>Trainable weight matrices responsible for projecting input tokens into query, key, and value vectors.</td>
  </tr>
  <tr>
    <td>Attention Score Calculation</td>
    <td>Computing attention scores by performing matrix multiplications between query and key vectors.</td>
  </tr>
  <tr>
    <td>Scaling and Softmax</td>
    <td>Scaling the attention scores by the square root of the embedding dimension, followed by applying the softmax function to obtain attention weights.</td>
  </tr>
  <tr>
    <td>Context Vector Calculation</td>
    <td>Computing the context vectors as a weighted sum over the value vectors based on the attention weights.</td>
  </tr>
</table>

<br>

### How to Use

1. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/AnkitaMungalpara/Building-LLM-From-Scratch.git
   cd Building-LLM-From-Scratch
