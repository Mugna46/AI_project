# TODO

TODO list in order to make the pre-processing part of the dataset.  
The list is updated principally during the data exploration part.  
Additionaly it is possible to add every task also not related to the post-processing part.

# Content

- [ ] Possibly eliminate rows that have an high *jitter* but *duration* zero. (15.5 ms is not that much at all)
- [ ] Eliminate IP and PORT attributes (src and dest) from the dataset.
- [ ] Use SMOTE to undersample *Normal* packets and oversample *Malicious* one, to make the dataset balanced.
- [ ] Keep the dataset unbalance and use *model* and *metrics* for unbalanced datasets.

# Done

- [x] Create this TODO file