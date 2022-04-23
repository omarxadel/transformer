# Transformer from scratch

This project is an implementation of a transformer from scratch based on the proposed approach in Attention Is All You Need. A transformer is a deep learning model that adopts the mechanism of self-attention, differentially weighting the significance of each part of the input data. It is used primarily in the fields of natural language processing (NLP) and computer vision (CV).

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#project-structure">Project Structure</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#References">References</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

This project is a very simple implementation of the transformer architecture with all of its building blocks. To get a better pictrure; here is the transformer architecture block diagram (Vaswani et al. 2017):

<p align="center">
    <a>
        <img src="res/diagram.png" alt="Figure 1" height="500">
    </a>
</p>

You can find each block of this diagram in the `transformer` directory.

### Project Structure

```
│   README.md
│   .gitignore
│
└───src
│   └───model
│   └───test
│   └───transformer
|       |    transformer.py
|       └───decoder
|       └───encoder
|       └───modules
|
└───res                     <! --- Documentation resources --->
```

### Built With

- [Pytorch](https://pytorch.org/docs/stable/index.html)

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

- [Python](https://www.python.org/downloads/)
- [Pip](https://pip.pypa.io/en/stable/installation/)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/omarxadel/transformer
   ```
2. Install requirements
   ```sh
   pip install -r /path/to/requirements.txt
   ```

<!-- USAGE EXAMPLES -->

## Usage

This transformer has not yet been tested on a real-life use case (still work in progress). To validate that it's working you need to run in the CMD:

```sh
 python3 -m src.test.test_transformer
```

<!-- ROADMAP -->

## Roadmap

Building a model for a simple NLP task and validating it is still Work in Progress.

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- CONTACT -->

## Contact

Omar Adel - omarxadel21@gmail.com

<!-- REFERENCES -->

## References

- [Attention is All You Need (Vaswani et al. 2017)](https://arxiv.org/pdf/1706.03762.pdf)
- [Pytorch Transformers from Scratch](https://youtu.be/U0s0f995w14)
- [Implementing a Transformer from Scratch
  ](https://towardsdatascience.com/7-things-you-didnt-know-about-the-transformer-a70d93ced6b2)
- [Pytorch Docs](https://pytorch.org/docs/stable/index.html)
