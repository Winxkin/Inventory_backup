data: store_object_9k
epoch: 6000

result

    class_id = 0, name = object, ap = 70.32%   	 (TP = 100554, FP = 36539) 

    for conf_thresh = 0.25, precision = 0.73, recall = 0.72, F1-score = 0.73 
    for conf_thresh = 0.25, TP = 100554, FP = 36539, FN = 38394, average IoU = 56.44 % 

     IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
    mean average precision (mAP@0.50) = 0.703238, or 70.32 % 

    Set -points flag:
    `-points 101` for MS COCO 
    `-points 11` for PascalVOC 2007 (uncomment `difficult` in voc.data) 
    `-points 0` (AUC) for ImageNet, PascalVOC 2010-2012, your custom dataset

    mean_average_precision (mAP@0.50) = 0.703238 
    New best mAP!
    If you want to train from the beginning, then use flag in the end of training command: -clear 
