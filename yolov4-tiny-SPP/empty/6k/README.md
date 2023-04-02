class_id = 0, name = empty, ap = 48.59%   	 (TP = 2942, FP = 1781) 

 for conf_thresh = 0.25, precision = 0.62, recall = 0.42, F1-score = 0.50 
 for conf_thresh = 0.25, TP = 2942, FP = 1781, FN = 4000, average IoU = 44.53 % 

 IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
 mean average precision (mAP@0.50) = 0.485866, or 48.59 % 

Set -points flag:
 `-points 101` for MS COCO 
 `-points 11` for PascalVOC 2007 (uncomment `difficult` in voc.data) 
 `-points 0` (AUC) for ImageNet, PascalVOC 2010-2012, your custom dataset

 mean_average_precision (mAP@0.50) = 0.485866 
New best mAP!
If you want to train from the beginning, then use flag in the end of training command: -clear 