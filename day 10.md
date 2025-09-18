# Create a compressed archive of 'myfolder'
tar -czf myfolder.tar.gz myfolder/

# Extract it back
tar -xzf myfolder.tar.gz

# Compress a file
gzip file.txt    # creates file.txt.gz

# Decompress it
gunzip file.txt.gz

# Create zip
zip files.zip file1.txt file2.txt

# Extract zip
unzip files.zip
