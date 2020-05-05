# Confusion-Matrix-Notes

1.	Confusion Matrix: (https://medium.com/swlh/recall-precision-f1-roc-auc-and-everything-542aedf322b9)
-	In confusion Matrix always remember – what is your objective. Here we want to identify fraudulent cases. 
-	Don’t worry about the Negative and positive boxes switches. Calculations dose not change for Recall and all..
-	Generally positive is for small classifier like fraud, ill patients, cancer patients, loan defaulters etc. 

-	Positive: fraudulent
-	Negative:  non-fraudulent

-	True Negative: Model correctly predicted non-fraud
-	True Positive: Model correctly predicted fraud
-	False Negative: Model incorrectly predicted non-fraud () (Type 2 error – with miss)
-	False Positive: model incorrectly predicted fraud (Type 1 error – false alarm)
-	To remember this, check the +ve or -ve, like in FP there is +ve (fraud), hence False becomes non-fraud incorrectly predicted +ve(fraud) 

OR
-	Positive: identified
-	Negative: rejected

-	True positive: Sick people correctly identified as sick
-	False positive: Healthy people incorrectly identified as sick (Type 1 error – false alarm)
-	True negative: Healthy people correctly identified as healthy
-	False negative: Sick people incorrectly identified as healthy (Type 2 error – with miss)
-	Like in COVID case False negative should be minimum, it’s okay if you are high on False Positive. Because, False alarm ppl can quarantine. But FN will spread virus to more ppl. Hence, very dangerous type 2 error.
