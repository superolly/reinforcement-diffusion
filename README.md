# Training Diffusion Models with Reinforcement Learning

This repo is an unofficial implementation of ["Training Diffusion Models with Reinforcement Learning"](https://arxiv.org/pdf/2305.13301.pdf) (Black et al., 2023).

This project is on pause — I underestimated the training time required and I currently do not have the capacity to train this model. I've debugged the code as far as is possible before seeing the final product.

Please note that it is built on top of my miniai library, which is a variant on the MiniAI library from the [FastAI Part 2 course](https://github.com/fastai/course22p2). If you haven't done the course, the code might look a bit strange since the framework abstracts common functionality, but the main DDPO implementation is adaptable from the `DDPOCB` object.
