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

<table>
    <tr>
        <th>Model / Metric</th>
        <th colspan="2">LOL dataset</th>
        <th colspan="2">RE2L dataset</th>
    </tr>
    <tr>
        <td>KinD<sub>original</sub></td>
        <td>20.38</td>
        <td>0.83</td>
        <td>12.92</td>
        <td>0.77</td>
    </tr>
    <tr>
        <td>KinD<sub>RE2L-P</sub></td>
        <td>21.42</td>
        <td>0.85</td>
        <td>12.03</td>
        <td>0.71</td>
    </tr>
    <tr>
        <td>EnlightenGAN<sub>original</sub></td>
        <td>13.72</td>
        <td>0.61</td>
        <td>10.18</td>
        <td>0.59</td>
    </tr>
    <tr>
        <td>EnlightenGAN<sub>RE2L-P</sub></td>
        <td>17.87</td>
        <td>0.70</td>
        <td>16.55</td>
        <td>0.77</td>
    </tr>
    <tr>
        <td>Zero-DCE<sub>original</sub></td>
        <td>14.86</td>
        <td>0.59</td>
        <td>10.26</td>
        <td>0.63</td>
    </tr>
    <tr>
        <td>Zero-DCE<sub>RE2L-P</sub></td>
        <td>14.59</td>
        <td>0.59</td>
        <td>9.61 </td>
        <td>0.62</td>
    </tr>
</table>


<table>
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>L1 Name</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>

| test1 | test2 | test3 |  | test4 | test4 |
|-------|-------|-------|-------|-------|-------|
| a     | a     | a     | a     | a     | a     |
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
