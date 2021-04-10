# Chest_Xray_Abnormalities_Detection_Using_RetinaNet
**Purpose of project**: Using RetinaNet to detect thoracic lung diseases
- Explore Data Analysis (EDA)
- Apply Non-Maximum Suppression (NMS), Soft Non-Maximum Suppression (Soft-NMS) and Weighted Boxes Fusion (WBF) for eliminating the overlapping ground truth bounding boxes.
- Building and tuniing parameters the RetinaNet for disease detection. 
### Apply NMS/ Soft-NMS/ WBF
|    |      Number of Boxes| 
|----------|:-------------:|
| Original boxes |  36,096 | 
| NMS |    23,940 | 
| Soft-NMS| 32,273 |
| WBF| 23,955 |

After applying 3 technique, the number of ground truth bounding boxes tend to decrease with NMS (33.7% off), Soft-NMS (10,6% off) and WBF (33.64% off) and base on algorithm of these. Therefore, I selected WBF for eliminating overlapping ground truth bounding boxes

**image before and after apply WBF**
