# Usage and Description

This dataset is intended to be used to train or test computer vision models in detecting defects of welding seams using conventional camera images, it is meant as a quick and cheap alternative of visual inspection using readily available tools (like a smartphone).

This dataset consists of frames extracted from video recordings and photographs of welding seams. Each image is annotated using the YOLO annotation format. The dataset includes the following classes of welding seam defects, ordered by class IDs from 0 to 4.

## Defect Classes:

1. **Class 0: Adjacent Defects (adj)**

2. **Class 1: Integrity Defects (int)**

3. **Class 2: Geometry Defects (geo)**

4. **Class 3: Post-Processing Defects (pro)**

5. **Class 4: Non-Fulfillment Defects (non)**

#### Dataset Source

This dataset was a modified version of this dataset:
https://www.kaggle.com/datasets/alexlaym/weld-defects
uploaded by Eduard Ghanza