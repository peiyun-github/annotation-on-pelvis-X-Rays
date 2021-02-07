# annotation-on-pelvis-X-Rays
Title: Landmark detection in pelvis X-Rays by using a multiscale feature-learning model

Abstract: The X-rays of pelvis comprise several significant landmarks, including the femoral head center, upper acetabulum rim, innermost point of subchondral sclerosis, and teardrop. The calculation of the angles made up of these landmarks can assist orthopedic surgeons in the diagnosis of developmental dysplasia of the hip. However, because of poor image quality or abrasion of anatomical structures, it is difficult to detect them. To automatically determine landmarks and assist doctors in diagnosing related diseases, we propose a novel landmark detection network that can extract the local field and large-range field feature information. First, we attain the deep abstract semantic features of the input image through stacked convolution blocks. Second, we propose a novel multi-scale information extracting attention module to obtain more context information and large-range field feature information. Finally, we adopted the position constraint module to locate the specific coordinates of the landmarks. Experimental results show that, our approach achieves an excellent performance, with an average point-to-point error of 2.0532 mm, as compared to other landmark detection models. According to the coordinates of landmarks that are measured by a senior radiologist, junior medical intern, and our proposed model, the angles related to the developmental dysplasia of the hip were calculated. The results show that the performance of the deep learning model is closer to that of the senior radiologist and better than that of the junior intern. In addition, an open-source pelvis dataset has been annotated and released for open research.

Keywords Landmark detection; Angle measurement; DDH; Deep learning

Our dataset with a demon will be released.

Author list: Yun Pei, Lin Mu.
