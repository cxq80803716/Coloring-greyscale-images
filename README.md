# Coloring B&W portraits with neural networks.

[![Run on FH](https://img.shields.io/badge/Run%20on-FloydHub-blue.svg)](https://floydhub.com/run?template=https://github.com/floydhub/colornet-template)

This is the code for my article ["Coloring B&W portraits with neural networks"](https://blog.floydhub.com/colorizing-b&w-photos-with-neural-networks/)

Earlier this year, Amir Avni used neural networks to [troll the subreddit](http://www.whatimade.today/our-frst-reddit-bot-coloring-b-2/) [/r/Colorization](https://www.reddit.com/r/Colorization/) - a community where people colorize historical black and white images manually using Photoshop. They were astonished with Amir’s deep learning bot - what could take up to a month of manual labour could now be done in just a few seconds.

I was fascinated by Amir’s neural network, so I reproduced it and documented the process. Read the article to understand the context of the code.

**Note:** If you want better results, I'd recommend using a more modern approach such as GANs. [DeOldify is a brilliant starting point.](https://github.com/jantic/DeOldify)

![Fusion Layer](fusion_layer.png)

## **Run the code on FloydHub**
[![Run on FloydHub](https://static.floydhub.com/button/button.svg)](https://floydhub.com/run?template=https://github.com/floydhub/colornet-template)

Click this button to open a [Workspace](https://blog.floydhub.com/workspaces/) on [FloydHub](https://www.floydhub.com/?utm_medium=readme&utm_source=colornet&utm_campaign=aug_2018) where you will find the same environment and dataset used for the *Full version*. 

## Acknowledgments
- Thanks to IBM for donating computing power through their PowerAI platform
- This is a reproduction of Baldassarre alt el., 2017. [Code](https://github.com/baldassarreFe/deep-koalarization) [Paper](https://arxiv.org/abs/1712.03400)
