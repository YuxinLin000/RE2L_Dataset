# REal-world 2-dimensional Low-light (RE2L) Dataset
This dataset accompanies the following publication: "RE2L: A Real-World Dataset for Outdoor Low-Light Image Enhancement", IEEE 5th International Conference on Multimedia Information Processing and Retrieval (MIPR), 2022.

Download: <a href="https://entuedu-my.sharepoint.com/:f:/g/personal/liny0090_e_ntu_edu_sg/EgJt0AXkbe5AvbGIWuFTYsIBcoaXmgFAID4JQS594LkDjQ?e=alQmAl">OneDrive Link</a>
## Dataset description
In this work, we propose a novel REal-world 2-dimentional Low-light (RE2L) dataset with naturally changed illumination environment. It is acquired not only based on manually adjusted exposure level (i.e., the exposure dimension in RE2L), but also collecting images at different times of a day to capture the natural light change (i.e., timing dimension) where complex outdoor lighting conditions are well-captured. 

As RE2L provides more comprehensive information of illumination variations, models targeting outdoor LLIE will be better guided in training towards state-of-the-art results.

The download link above contains both the original dataset (RE2L) and the paired version (RE2L-P, natural light vs -0.95 exposure).

## Visualization
The figure below demonstrates examples of some selected pairs from RE2L-P. Upper row: normal images; bottom row: low-light images (5% of normal exposure time).

<img width="632" alt="2022-06-08 8 09 45" src="https://user-images.githubusercontent.com/60025126/172612813-d3b125dc-805f-43da-8879-6a7f55873ba4.png">


## Performance
The table below shows quantitative comparisons on LOL and RE2L dataset. Best highlighted in <b>bold</b>.

<table>
    <tr>
        <th>Model / Metric</th>
        <th colspan="2">LOL dataset</th>
        <th colspan="2">RE2L dataset</th>
    </tr>
    <tr rowspan="2">
        <td>KinD<sub>original</sub><br/>KinD<sub>RE2L-P</sub></td>
        <td>20.38<br/><b>21.42</b></td>
        <td>0.83<br/><b>0.85</b></td>
        <td><b>12.92</b><br/>12.03</td>
        <td><b>0.77</b><br/>0.71</td>
    </tr>
    <tr rowspan="2">
        <td>EnlightenGAN<sub>original</sub><br/>EnlightenGAN<sub>RE2L-P</sub></td>
        <td>13.72<br/><b>17.87</b></td>
        <td>0.61<br/><b>0.70</b></td>
        <td>10.18<br/><b>16.55</b></td>
        <td>0.59<br/><b>0.77</b></td>
    </tr>
    <tr>
        <td>Zero-DCE<sub>original</sub><br/>Zero-DCE<sub>RE2L-P</sub></td>
        <td><b>14.86</b><br/>14.59</td>
        <td><b>0.59</b><br/><b>0.59</b></td>
        <td><b>10.26</b><br/>9.61</td>
        <td><b>0.63</b><br/>0.62</td>
    </tr>
</table>

Some enhancements results are presented in the pictures below:

<img width="588" alt="2022-06-08 8 57 28" src="https://user-images.githubusercontent.com/60025126/172622091-ce4e4170-58fe-4dd0-9e5a-03abbc58213e.png">

<img width="587" alt="2022-06-08 8 58 00" src="https://user-images.githubusercontent.com/60025126/172622206-b92a59d1-e4a3-4f3c-b135-34a982e0c7c5.png">

## Use
All data is subject to copyright and may only be used for non-commercial research. 
Kindly drop <img width="191" alt="image" src="https://user-images.githubusercontent.com/66542568/172624933-96c74dea-f2c4-4cdd-a7ac-1a901e2b9e1e.png">
 an email for any questions.

If you find this dataset useful in your research, please cite:
```
@inproceedings{lin2022,
  author={Lin, Yuxin and Li, Jian and Guo, Lanqing and Wen, Bihan},
  title={RE2L: A Real-World Dataset for Outdoor Low-Light Image Enhancement},
  year={2022},
  booktitle={IEEE 5th International Conference on Multimedia Information Processing and Retrieval (MIPR)}
}
```
