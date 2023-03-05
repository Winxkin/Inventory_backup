data: store_empty_30k
epoch: 20000

result:
    class_id = 0, name = empty, ap = 35.00%   	 (TP = 1809, FP = 1048) 

    for conf_thresh = 0.25, precision = 0.63, recall = 0.26, F1-score = 0.37 
    for conf_thresh = 0.25, TP = 1809, FP = 1048, FN = 5099, average IoU = 43.35 % 

    IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
    mean average precision (mAP@0.50) = 0.349955, or 35.00 % 

    Set -points flag:
    `-points 101` for MS COCO 
    `-points 11` for PascalVOC 2007 (uncomment `difficult` in voc.data) 
    `-points 0` (AUC) for ImageNet, PascalVOC 2010-2012, your custom dataset

    mean_average_precision (mAP@0.50) = 0.349955 
    If you want to train from the beginning, then use flag in the end of training command: -clear 