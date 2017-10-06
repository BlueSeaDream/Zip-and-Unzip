
### Extract Multiple Zip Files using 7-Zip

7z x "input_path_of_1st_zip_file" -tzip.split -o"output_directory"

Note: 

- tzip mean that the compressed file is "zip" format.
- no space between -o and "output_directory"

### Add File Directory to a Zip File using 7-Zip

7z a -tzip "C:\zip_file_folder\ILSVRC.zip" "C:\your_file_folder\"

### Extract the Zip File using WinRAR

unrar x C:\your_file_folder\yourfile.rar *.png C:\extractfolder\

