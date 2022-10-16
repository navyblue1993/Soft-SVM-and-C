# Soft-SVM-and-C

It is a study on C value's impact if the data is linear seperatable.

The experiments in executed on the python script created by Peter Prettenhoer. Since the license issue, I cannot share the code here.

The conclusion is that if the data is linear seperable and we set C as 0(or really small), then our ojective function become minimizing the w and the  constraint is borken.
With hard SVM, it is: y(wx+b) >= 1
With c = 0 in soft SVM, it is: y(wx+b) >= -inf

Check the SVM with C = 0.001 and C = 1 with linear seperable data, small C will make the accuracy worse.
