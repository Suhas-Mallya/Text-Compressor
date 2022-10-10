# To run this project you need to create an executable file.

## For compressing the text file
```
g++ -std=c++11 .\encode.cpp .\huffman.cpp -o compress
./compress.exe .\inputFile.txt .\compressedFile.huf
```

## For decompressing the compressedFile.huf file
```
g++ -std=c++11 .\decode.cpp .\huffman.cpp -o decompress 
./decompress.exe .\compressedFile.huf .\outputFile.txt
```
