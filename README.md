# csv_file_splitter

This python program splits a single large csv file into many smaller files. 

For example, with an input file data-file.csv the output directory would contain:

     output-dir/data-file_0.csv
     output-dir/data-file_1.csv
     output-dir/data-file_2.csv
     ...


Example call from bash to split a single CSV into multiple 100 line CSVs:

     python3 split_csv /path/to/my/file.csv /path/to/split_files my_split_file 100
