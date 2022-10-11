# Partial Face Recognition Approach with for Occluded Faces Wearing Face Mask and Sunglasses

This project investigates face identification processes under different types of occlusion and compares different experimental results. Both non-occluded and occluded faces have experimented with the same or similar algorithms in order to highlight the effect of occlusion over the recognition algorithm. Furthermore, different occlusion types and grades are compared with each other concerning biometric recognition performance.

## Data

[Aberdeen](http://pics.stir.ac.uk/2D_face_sets.htm) (Kumar & Shanmugavadivu, 2018). 

[CelebA](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) (Liu et al., 2015)

## Results

### Non-occluded Face Identification Results

|                             | Overall Error | FAR  | FRR  |
|-----------------------------|---------------|------|------|
| Full Face Approach          | 0.14          | 0.12 | 0.15 |
| Partial Face Approach       | 0.17          | 0.27 | 0.15 |

### Occluded Face Identification Results

|                             | Overall Error | FAR  | FRR  |
|-----------------------------|---------------|------|------|
| Full Face                   | 0.48          | 0.47 | 0.49 |
| Partial Face(Mace Mask)     | 0.28          | 0.33 | 0.28 |
| Partial Face(Sunglasses)    | 0.87          | 0.02 | 1    |

## Evaluation

Results show that the partial face identification approach decreases overall error for face-masked individuals by 20% compared to the full face approach. On the other hand, the use of sunglasses (occlusion of both eyes) increases the error rate by 39%, showing the importance of features extracted from the eyes for the presented setup.

When the effect of sunglasses on the identification performance was investigated further with different alpha values (the higher the alpha value, the more reflective the sunglasses become) it was seen that the reflectiveness of the glasses has a significant effect on the performance. The results shown above use the alpha value as 1.

![image](https://i.ibb.co/T8RyX2D/download.png)

![image](https://i.ibb.co/WW34pqG/linepng.png)

## Detailed Project Report

[Report](https://docs.google.com/document/d/1Sigr9HhmPymHzbJX-EF2Tea8mxtSUPC1gKSpOc9DVfs/edit?usp=sharing)

[Slides](https://docs.google.com/presentation/d/1woHDbPli0bdPq_1W8SFMBsGtnQiZ-gA8k1agyP44Wos/edit?usp=sharing)  

## References

Kumar, A., & Shanmugavadivu, P. (2018). Partially Occluded Face Recognition using  Dynamic Time Wrapping. International Journal of Engineering & Technology, 7(2.22), 31.

Liu, Z., Luo, P., Wang, X., & Tang, X. (2015). Deep Learning Face Attributes in the Wild. Proceedings of International Conference on Computer Vision (ICCV).
