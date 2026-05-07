# TangentQuant

TangentQuant is a post-training weight quantization framework for video diffusion Transformers (DiT). 
It preserves temporal-difference dynamics across frames while compressing model weights. 

## Features
- Full-model weight quantization for video DiTs
- Temporal-difference reconstruction for motion consistency
- Compatible with SmoothQuant and QuaRot for activation quantization

## Teaser
![Teaser Figure](assets/teaser.png)

## Overview
![TangentQuant Overview](assets/tangentquant_overrview.png)

## quant comparesion
![TangentQuant Overview](assets/quant_compare.png)