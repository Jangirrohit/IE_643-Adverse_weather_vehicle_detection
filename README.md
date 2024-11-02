# IE643 Course Project 
- Rohit Jangir (22B1502)
- Yash mahta (22B1504)

## dataset for normal weather vehicle Images **`"Yolo_annot_dataset"`** : https://drive.google.com/drive/folders/1LWey1Pp0Zt-h1Jlxc5ZmWY9-0aeV_p1D?usp=sharing
## dataset for adverse weather vehicle Images **`"Adverse_data_30"`** :  https://drive.google.com/drive/folders/1tEVvqtzoTpNcVx5kKP3xuQnuWBjlAiuO?usp=sharing
## Gdrive link of Complete Project related stuff: https://drive.google.com/drive/folders/1Yzd9wripneedSFckNAElCWO2IwCCooXs?usp=sharing
- To begin training, first move all files into the same directory. See the drive link above for reference.

### **`"Yolo_on_kitti.ipynb"`** This notebook contains the code for training the YOLO model on the normal weather vehicle dataset, which serves as the base model.
### **`"fine-tune.ipynb"`** This notebook contains the code for fine-tuning the YOLO model trained on the normal weather vehicle dataset (the base model) using the adverse weather vehicle dataset. It trains only the last layers (partially the neck and head) while keeping the other layers frozen.
### **`"initial_layer_fine-tune.ipynb"`** This notebook contains the code for fine-tuning the YOLO model trained on the normal weather vehicle dataset (the base model) using the adverse weather vehicle dataset. It focuses on training only the initial layers while keeping the other layers frozen.
### **`"kitti_to_yolo.ipynb"`**  This notebook contains the code for converting annotations from the KITTI format to the YOLO format.
### **`"Pascal_to_Yolo.ipynb"`**  This notebook contains the code for converting annotations from the Pascal Voc format to the YOLO format.
