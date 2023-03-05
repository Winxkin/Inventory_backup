data: store_object_9k
epoch: 6000

result:

    class_id = 0, name = object, ap = 54.84%   	 (TP = 80711, FP = 41428) 

    for conf_thresh = 0.25, precision = 0.66, recall = 0.58, F1-score = 0.62 
    for conf_thresh = 0.25, TP = 80711, FP = 41428, FN = 58237, average IoU = 47.09 % 

    IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
    mean average precision (mAP@0.50) = 0.548384, or 54.84 % 

    Set -points flag:
    `-points 101` for MS COCO 
    `-points 11` for PascalVOC 2007 (uncomment `difficult` in voc.data) 
    `-points 0` (AUC) for ImageNet, PascalVOC 2010-2012, your custom dataset

    mean_average_precision (mAP@0.50) = 0.548384 
    If you want to train from the beginning, then use flag in the end of training command: -clear 