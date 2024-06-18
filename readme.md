# AI自动上色

[generator](https://drive.google.com/file/d/1qmxUEKADkEM4iYLp1fpPLLKnfZ6tcF-t/view?usp=sharing)
[denoiser](https://drive.google.com/file/d/161oyQcYpdkVdw8gKz_MA8RD-Wtg9XDp3/view?usp=sharing)

<!--Put generator and extractor weights in `networks` and denoiser weights in `denoising/models`.-->

```sh
python install -r requirements.txt
python inference.py -p "path to file or folder"
```

| Original      | Colorization      |
|------------|-------------|
| <img src="figures/bw1.jpg" width="512"> | <img src="figures/color1.png" width="512"> |
| <img src="figures/bw2.jpg" width="512"> | <img src="figures/color2.png" width="512"> |
| <img src="figures/bw3.jpg" width="512"> | <img src="figures/color3.png" width="512"> |
| <img src="figures/bw4.jpg" width="512"> | <img src="figures/color4.png" width="512"> |
| <img src="figures/bw5.jpg" width="512"> | <img src="figures/color5.png" width="512"> |
| <img src="figures/bw6.jpg" width="512"> | <img src="figures/color6.png" width="512"> |


fork by https://github.com/qweasdd/manga-colorization-v2.git