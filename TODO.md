# TODO

TODO list in order to make the pre-processing part of the dataset.  
The list is updated principally during the data exploration part.  
Additionaly it is possible to add every task also not related to the post-processing part.

# Content

- [ ] Use Random *Forest Model* for classification and use LIME with a *Decision Tree* to explain it.
- [ ] Make a binary classificatio of the dataset.

# Done

- [x] Create this TODO file.
- [x] Delete duplicates.
- [x] Add value in *attack_cat* for Normal packets.
- [x] Create and substitute *attack_cat* with new macro-categories. 
- [x] Resolved incongruence between attributes *ct_flw_http_mthd* and *service*. 
- [x] Eliminate IP and PORT attributes (src and dest) from the dataset.
- [-] Possibly eliminate rows that have an high *jitter* but *duration* zero. (15.5 ms is not that much at all)
- [x] Substitute '-' with 'Missing' in the preprocessing phase for the 'service' column.
- [x] Substitute missing value with 0 in the preprocessing phase for the 'ct_flw_http_mthd' column.
- [-] Substitute missing value with 0 in the preprocessing phase for the 'is_ftp_login' and other value to 1.
- [x] Trasform all value to integer and substitute missing value with 0 in the preprocessing phase for the 'ct_ftp_cmd' attribute.
- [x] Eliminate the attributes *is_ftp_login* because is redundant with *ct_ftp_cmd*. 
- [x] Use Sampling to undersample *Normal* packets and oversample *Malicious* one, to make the dataset balanced.
- [x] Use Logistic Regression as classifier.
- [x] Use balanced dataset to train logistic regression model.
- [x] Use correlation matrix to do feature selection.
- [x] Analize Stime and Ltime in features selection phase using correlation matrix.
- [x] Dataset is unbalance so use *model* and *metrics* for unbalanced datasets.
- [-] Use Decision tree Model (supervised classificator) to make a classification of the dataset.
- [x] Try another *Scaling* for data in order to increase performance of *Logistic Regression*.
- [x] Try to not use dummies and instead use *frequency encoding* for feature selection.
- [x] Add performance metrics at the end of *Cross Validation*