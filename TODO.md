# TODO

TODO list in order to make the pre-processing part of the dataset.  
The list is updated principally during the data exploration part.  
Additionaly it is possible to add every task also not related to the post-processing part.

# Content

- [ ] Possibly eliminate rows that have an high *jitter* but *duration* zero. (15.5 ms is not that much at all)
- [ ] Eliminate IP and PORT attributes (src and dest) from the dataset.
- [ ] Use SMOTE to undersample *Normal* packets and oversample *Malicious* one, to make the dataset balanced.
- [ ] Keep the dataset unbalance and use *model* and *metrics* for unbalanced datasets.
- [ ] Analize Stime and Ltime in features selection phase using correlation matrix.
- [ ] Substitute '-' with 'Missing' in the preprocessing phase for the 'service' column.
- [ ] Substitute missing value with 0 in the preprocessing phase for the 'ct_flw_http_mthd' column.
- [ ] Substitute missing value with 0 in the preprocessing phase for the 'is_ftp_login'.

# Done

- [x] Create this TODO file
- [x] Resolved incongruence between attributes *ct_flw_http_mthd* and *service*. 