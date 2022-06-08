# REal-world 2-dimensional Low-light (RE2L) Dataset
This dataset accompanies the following publication: "RE2L: A Real-World Dataset for Outdoor Low-Light Image Enhancement", IEEE 5th International Conference on Multimedia Information Processing and Retrieval (MIPR), 2022.
## Dataset description
To fully benchmark outdoor Low-Light Image Enhancement (LLIE), a large-scale and real-world low-light dataset with naturally changed illumination environment is needed. In this work, we propose a novel REal-world 2-dimentional Low-light dataset, dubbed RE2L, which is acquired not only based on manually adjusted exposure level (i.e., the exposure dimension in RE2L), but also collecting images at different times of a day to capture the natural light change (i.e., timing dimension) where complex outdoor lighting conditions are well-captured. 

As RE2L provides more comprehensive information of illumination variations, models targeting outdoor LLIE will be better guided in training towards state-of-the-art results.
## Visualization
The figure below demonstrates examples of some selected pairs from RE2L-P. Upper row: normal images; bottom row: low-light images (5% of normal exposure time).

<img width="632" alt="截屏2022-06-08 下午8 09 45" src="https://user-images.githubusercontent.com/60025126/172612813-d3b125dc-805f-43da-8879-6a7f55873ba4.png">


## Performance
The table below shows quantitative comparisons on LOL and RE2L dataset.

| Model / Metric  | LOL dataset | RE2L dataset |
|                 | PSNR | SSIM | PSNR | SSIM  |
| ---------------------------- | --------------- |
| Content Cell<sub>test</sub>  | Content Cell  |
| Content Cell  | Content Cell  |
## Paper & Use
All data is subject to copyright and may only be used for non-commercial research. 
If you find this dataset useful in your research, please cite:
```
@inproceedings{lin2022,
  author={Lin, Yuxin and Li, Jian and Guo, Lanqing and Wen, Bihan},
  title={RE2L: A Real-World Dataset for Outdoor Low-Light Image Enhancement},
  year={2022},
  booktitle={IEEE 5th International Conference on Multimedia Information Processing and Retrieval (MIPR)}
}
```
