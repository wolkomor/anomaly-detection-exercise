# Get prdiction instruction

1) Load data from csv to a dataframe. Data must contain same columns as in the training set: source_port, dest_port, nat_source_port, nat_dest_port, action, bytes, bytes_sent, bytes_received, packets, time_elapsed_sec, ts_ret_a, timestamp, timestamp_relative, packets_sent, packets_received 
2) Run all sections until the section "Serving the model"
3) Replace the sample_predict with the loaded dataframe file which you want to test
4) Run the function predict_data with the loaded dataframe as a parameter
