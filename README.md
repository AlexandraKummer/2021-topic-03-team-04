print("Hello World")

RNAse_frac_df = RNAse_frac_df[,-1] #Remove the empty column from the dataframe
colnames(RNAse_frac_df) = c(paste("frac",1:25, sep = "_"))