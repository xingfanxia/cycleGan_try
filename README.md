### CycleGan

```bash
bash ./pretrained_models/download_model.sh

bash ./datasets/download_dataset.sh

DATA_ROOT=./datasets/xiax name=style_vangogh_cpu_pretrained model=one_direction_test phase=test loadSize=900 fineSize=900 resize_or_crop="scale_width" gpu=0 cudnn=0 th test.lua
```

