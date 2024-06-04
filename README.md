This is the code repository for "SRSF-GAN: A super-resolution based spatial fusion with GAN for satellite images with different spatial and temporal resolutions". We will optimize the code in subsequent steps.
If you have any questions, please contact zhaoqinyu013@gmail.com.

The folder structure in the dataset is as follows:
- root
  - train
    - lt0_patch
    - lt1_patch
    - mt1_patch
  - val
    - lt0_patch
    - lt1_patch
    - mt1_patch

  train：
  python train.py --device [input: "cuda" or "cpu"] --data_patch [input: your data path] --resume [imput: True or False. continue your train or not] --num_epochs [input: train epoch] --save_path [input: the path of saving latest model] --save_path1 [input: the path of saving best model] --batch [input: batchsize]


