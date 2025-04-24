## Camouflaged Object Detection

### Cascade R-CNN (ResNeXt-101 Backbone)  
- Dataset: COD10K Train (only camouflaged object, 3060 images)
- Epochs: 20

| Metric                                | Score |
|---------------------------------------|-------|
| AP@[IoU=0.50:0.95] (mAP)              | 0.337 |
| AP@[IoU=0.50]                         | 0.645 |
| AP@[IoU=0.75]                         | 0.314 |
| AP (small objects)                   | 0.454 |
| AP (medium objects)                  | 0.139 |
| AP (large objects)                   | 0.350 |
| AR@[IoU=0.50:0.95] (maxDets=1000)    | 0.465 |
