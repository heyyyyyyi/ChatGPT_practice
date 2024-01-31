# ChatGPT related practice

中文诗词生成

## Introduction

>
> - speed up development
>
> - make youk easy to extend
>
>   - 大语言模型
> - do other program cannot do


- epoch and
- data representation
  - feature engineerign
    - string -> int
      - ID
      - distance
      - one-hot-encoding
  - sparse representation
  - non-linear situations: features cross
    - generate new feature (x3 = x1*x2)

## Regularity 
min(loss(data(model))+complexity(model))
- complexity 
  - size of w
    L2 sum(w^2)
    w变小 但是不容易归为0
  - number of w
    L1 sum(|w|)

## logistic regression
- 辛普森悖论
- recall
- precision

- sanity check
## Neural Network
- Gradient
  - ReLU
  - ReLU 变种
  - ephch up
  - batch up
- Exploding Gradient
  - learning rate 
  - batch normalization
- Dead Relu Units(都到左边了)
  - learning rate 降一点
  - ReLU 变种

## Normalization
归一化尺度
【-1，1】
- linear scaling
- hard cap
- log scaling
## Embedding
- 映射
- lookup table
- tag

## NLP
probability of a sequence of words 
- 对输入的处理
tokenization :(word, sub-word) -> num
- CNN
- RNN (+方向性)
- LSTM （+log）
- Encoder Decoder （sequence to sequence）
- attention
- transformer
  - embed
  - multi-head attention
  - masked
### 大语言模型
- resorce：




