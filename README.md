# Steganography
### Steganography is the practice of representing information within another message or physical object, in such a manner that the presence of the information is not evident to human inspection. In computing/electronic contexts, a computer file, message, image, or video is concealed within another file, message, image, or video
Embedding a text file into an image file. 
1. Create a folder Pic
2. Copy/create 1.pic and 1.txt inside the folder
3. Open the text document and type Hidden text into it. Save and close the file.
4. compress 1.txt as 1.rar
5. <img width="529" alt="image" src="https://github.com/shovanroyUSA/Steganography/assets/116796946/ee9bf28e-9d16-4ced-9c36-c968044e088a">
6.  Open a command line on your Windows system. Change the directory with this command: cd \Pic
7.  Copy the text file and the image file into a new image file with the following command: copy /b 1.jpg + 1.rar 2.jpg
8.  <img width="101" alt="image" src="https://github.com/shovanroyUSA/Steganography/assets/116796946/821fef00-7ec3-4696-a057-29dd5b0f5f61">
9.  it’s also possible to simply embed the 1.rar file within the original 1.jpg file with this command: copy /b 1.jpg + 1.rar 1.jpg
10.  If you want to extract the hidden files, you need to rename the extension of the picture from jpg to rar: copy 2.jpg 2.rar
11.  You can then extract the text file using WinRAR within Windows Explorer by right-clicking it and selecting Extract files.
12.  <img width="519" alt="image" src="https://github.com/shovanroyUSA/Steganography/assets/116796946/c46bb44b-b886-4c67-ab5e-a154ac721c54">
13.  Here is the text file again extracted from image file: <img width="398" alt="image" src="https://github.com/shovanroyUSA/Steganography/assets/116796946/ee08f654-2941-4655-9ae5-48f871d96d82">


