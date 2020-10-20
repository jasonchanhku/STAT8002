# `final_images_r.csv`

Contains the `.csv` file of list of images with the following removed:

* Images with No Masks
* Mislabelled Images
* Masks with Background Only
* `isup_grade > 0` but No Cancerous Labelled
* Images with pen stained markers

# `karolinska_mask_features.csv`

Contains the list of images from `data_provider=karolinska` with the count and percent features of the mask values ranging from 1 to 5

# `radboud_mask_features.csv`

Contains the list of images from `data_provider=radboud` with the count and percent features of the mask values ranging from 1 to 5
