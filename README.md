# Blockchains_and_NFTs_A_Beginners_Guide

Link to Gumroad to download eBook

https://funinternetthings.gumroad.com/l/blockchain_and_nfts_book


<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.


## To generate an ebook from the files

Install pandoc on your machine:

```bash
brew install pandoc
```

After pandoc is installed, change directories into `ebook`


Run the following to generate:


```bash
pandoc -o Blockchains_and_NFTs_A_Beginners_Guide.epub \
--css epub.css main.md --table-of-contents \
chapters/00-beginning/*.md \
chapters/01-Introduction-to-blockchains/*.md \
chapters/02-Introduction-to-NFTs/*.md \
chapters/03-History-of-blockchains-and-NFTs/*.md \
chapters/04-Blockchains-in-the-real-world/*.md \
chapters/05-NFTs-in-the-real-world/*.md \
chapters/06-Future-of-blockchains-and-NFTs/*.md \
chapters/07-Conclusion/*.md \
chapters/08-End/*.md
```


Open `Blockchains_and_NFTs_A_Beginners_Guide.epub` in your favorite e-reader.


### Cover image information

![](ebook/cover.png)

The image was generated with InvokeAI [Stable Diffusion], and the Analog Diffusion model.

InvokeAI: https://github.com/invoke-ai/InvokeAI

Analog Diffusion: https://huggingface.co/wavymulder/Analog-Diffusion

Upscaled 4x with Chainner: https://github.com/chaiNNer-org/chaiNNer

Edited with Gimp for the cover and Gumroad files: https://www.gimp.org/


Art Prompt:

```
{
  "model": "stable diffusion",
  "model_weights": "analog",
  "model_hash": "a9a1c90893cc7892dfd7438004fa954696f94208c84773b1cabb434e5a856a0c",
  "app_id": "invoke-ai/InvokeAI",
  "app_version": "v2.2.4",
  "image": {
    "prompt": [
      {
        "prompt": "amazing landscape photo of mountains with lake in sunset by marc adamus, beautiful dramatic lighting ",
        "weight": 1
      }
    ],
    "steps": 50,
    "cfg_scale": 12,
    "threshold": 0,
    "perlin": 0,
    "height": 768,
    "width": 512,
    "seed": 2502935700,
    "seamless": false,
    "hires_fix": false,
    "type": "txt2img",
    "postprocessing": null,
    "sampler": "k_euler_a",
    "variations": []
  }
}
```







