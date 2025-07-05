# Self Forcing

![Self Forcing](https://img.shields.io/badge/Self%20Forcing-v1.0-blue.svg)  
![License](https://img.shields.io/badge/license-MIT-green.svg)  
![Stars](https://img.shields.io/github/stars/Sakrmoaaz4/Self-Forcing.svg?style=social)  

<p align="center">
<h1 align="center">Self Forcing</h1>
<h3 align="center">Bridging the Train-Test Gap in Autoregressive Video Diffusion</h3>
</p>

<p align="center">
  <p align="center">
    <a href="https://www.xunhuang.me/">Xun Huang</a><sup>1</sup>
    ·
    <a href="https://zhengqili.github.io/">Zhengqi Li</a><sup>1</sup>
    ·
    <a href="https://guandehe.github.io/">Guande He</a><sup>2</sup>
    ·
    <a href="https://mingyuanzhou.github.io/">Mingyuan Zhou</a><sup>2</sup>
    ·
    <a href="https://research.adobe.com/person/eli-shechtman/">Eli Shechtman</a><sup>1</sup><br>
    <sup>1</sup>Adobe Research <sup>2</sup>UT Austin
  </p>
  <h3 align="center"><a href="https://arxiv.org/abs/2506.08009">Paper</a> | <a href="https://self-forcing.github.io">Website</a> | <a href="https://huggingface.co/gdhe17/Self-Forcing/tree/main">Models (HuggingFace)</a></h3>
</p>

---

## Overview

Self Forcing focuses on improving autoregressive video diffusion models. It does this by simulating the inference process during training. This method helps bridge the gap between training and testing phases, leading to better performance in video generation tasks.

### Key Features

- **Autoregressive Training**: Trains models to predict future frames based on past frames.
- **Inference Simulation**: Mimics the inference process during training to enhance model robustness.
- **Research-Backed**: Developed by a team of experts in the field, ensuring high-quality methodologies.

## Installation

To get started with Self Forcing, you can download the latest release from our [Releases section](https://github.com/Sakrmoaaz4/Self-Forcing/releases). Follow the instructions below to set up the project on your local machine.

### Prerequisites

- Python 3.7 or higher
- Required libraries (listed in `requirements.txt`)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Sakrmoaaz4/Self-Forcing.git
   cd Self-Forcing
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the latest release and execute it:
   Visit the [Releases section](https://github.com/Sakrmoaaz4/Self-Forcing/releases) to find the appropriate files.

## Usage

After installation, you can start using the Self Forcing model. Here’s a basic example of how to run the model:

```python
import self_forcing

# Initialize model
model = self_forcing.Model()

# Train the model
model.train(data)

# Generate video
video = model.generate(start_frame)
```

Refer to the documentation for more advanced usage and options.

## Documentation

For more detailed information on the methods and functionalities, please check the official [documentation](https://self-forcing.github.io).

## Contributing

We welcome contributions to improve Self Forcing. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push your branch and create a pull request.

Please ensure your code follows the existing style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors

- **Xun Huang** - [Website](https://www.xunhuang.me/)
- **Zhengqi Li** - [Website](https://zhengqili.github.io/)
- **Guande He** - [Website](https://guandehe.github.io/)
- **Mingyuan Zhou** - [Website](https://mingyuanzhou.github.io/)
- **Eli Shechtman** - [Website](https://research.adobe.com/person/eli-shechtman/)

## Acknowledgments

We thank the following for their support and contributions:

- Adobe Research
- UT Austin

## Related Work

Self Forcing builds upon previous research in video generation and diffusion models. Key papers in this area include:

- [Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/abs/2105.05233)
- [Autoregressive Video Generation](https://arxiv.org/abs/2011.08045)

## Community

Join our community for discussions, questions, and updates:

- [GitHub Discussions](https://github.com/Sakrmoaaz4/Self-Forcing/discussions)
- [Twitter](https://twitter.com/SelfForcing)

## Feedback

We appreciate your feedback. If you encounter issues or have suggestions, please open an issue in the GitHub repository.

## Future Work

We plan to enhance Self Forcing with the following features:

- Support for more complex video structures.
- Integration with additional machine learning frameworks.
- Improved user interface for easier model interaction.

## Conclusion

Self Forcing represents a significant step in bridging the gap between training and testing in autoregressive video diffusion. We invite you to explore the project, contribute, and provide feedback.

For more updates, check our [Releases section](https://github.com/Sakrmoaaz4/Self-Forcing/releases).