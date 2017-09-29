### Extract Multiple Zip Files using 7-Zip

7z x "input_path_of_1st_zip_file" -tzip.split -o"output_directory"

Note: 

- tzip mean that the compressed file is "zip" format.
- no space between -o and "output_directory"

### Extract the Zip File using WinRAR

unrar x c:\yourfile.rar *.gif c:\extractfolder\
