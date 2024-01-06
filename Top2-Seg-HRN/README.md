# Top2: Multimodal unsupervised domain adaptation for remote sensing image segmentation

Take AB dataset as example:
## Train a single model using HSI data
```
python hsi_crop_trainval.py --mode train --config "/Top2-Seg-HRN/utils/train_cfg/AB_HSI.yaml"
```
## Train a single model using MSI data
```
python msi_crop_trainval.py --mode train --config "/Top2-Seg-HRN/utils/train_cfg/AB_MSI.yaml"
```
## Train a single model using SAR data
```
python sar_crop_trainval.py --mode train --config "/Top2-Seg-HRN/utils/train_cfg/AB_SAR.yaml"
```
