# MAC VERSION
```
python main.py \
    --base configs/stable-diffusion/v1-finetune_unfrozen.yaml \
    -t \
    --actual_resume models/ldm/stable-diffusion-v1/model.ckpt \
    -n natjob \
    --gpus 0, \
    --data_root ../../stable-diffusion-assets/training/images \
    --reg_data_root ../../stable-diffusion-assets/regularization/images \
    --class_word sks \
```

# WINDOWS VERSION

```
python main.py --base configs/stable-diffusion/v1-finetune_unfrozen.yaml -t --actual_resume models/ldm/stable-diffusion-v1/model.ckpt -n natjob --gpus 0,  --data_root ..\..\stable-diffusion-assets\training\images --reg_data_root ..\..\stable-diffusion-assets\regularization\images --class_word sks
```