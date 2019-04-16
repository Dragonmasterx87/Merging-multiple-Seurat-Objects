# Merging-multiple-Seurat-Objects
Hello there! Some code on how to merge >2 Seurat objects and maintain object identity :)
This is for Seurat 2.3.4, Seurat 3.0.0.9150 (as of 4/16/2019) uses a much simpler line of code to merge seurat objects.
In addition in S2.3.4, you need to change barcode data to represent different sample IDs, howevr in S3.0.0.9150 sample data is stored in metadata files. Which makes your data cleaner and easier to handle. I suggest learning and using Seurat 3. If papers have used S2.3.4 or older, it is still possible to perform the same analysis with S3, however some of the functions are different for this the satija lab has created a cheat sheet: [https://satijalab.org/seurat/essential_commands.html]. 
