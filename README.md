# EPUB-01_Test

# PROOFING EPUBS THE RIGHT WAY

# INSTRUCTIONS FOR USING GITHUB TO PROOF EPUBS (without using the command line)

  1. Sign into GitHub. Username: NDIntern. Password: newdir1936.
  2. Access working repository.
    * Repository naming convention: First two letters of authors name, plus first four letters of book title, without articles. I.e., Flaubert's DICTIONARY OF ACCEPTED IDEAS becomes flDICT.
  3. Click on the repository name.
    * Readme.md will display important info for the book. 
  4. Download a ZIP file of the repository.
  5. Click on the ```Branch``` button. When you see the drop-down menu, click on ```OCR_proofing```.
  6. Open the OEBPS folder in Brackets (File-->Open Folder).
  7. Proof using the Brackets text editor. For ease of reading, use Web browser to read HTML files (just double click on the file).
    1. Put changes in as you edit. 
    2. Comment all non-OCR changes to text using HTML comments. <!--This is a comment. It is not included in presentation-->
      * Example: if you find the following code:
    ```<p class="hanging">N<span class="small-1">ECTAR</span>. Confuse with ammbrosia.</p>```
      * Your edit will look like:
    ```<p class="hanging">N<span class="small-1">ECTAR</span>. Confuse with ambrosia.<!--"Ammbrosia" to "Ambrosia"--></p>```
     *  Many text editors will allow you to hotkey this.
  8. When you finish editing a file, open the corresponding file on Github and replace its contents with your edited text. (Don't forget to click the editing pencil icon on the top right, near the trash can.)
  9. Propose file changes
    1. At the bottom of the editing window, you'll see a speech bubble that says ```Propose file change```
    2. There are two fields, one for a short description and one for an extended description. If proofing went smoothly, just write "OCR proofing" in the short description. If you feel I need to be aware of anything more complicated, write it out in the long description. I.e., if you think there may be errors in the HTML or typos in the print version. I.e., ```<!--Many, many OCR errors, second proof may be needed-->```
    3. Click ```Propose file change```
    4. You will see a window showing your changes in red and green. If needed, quickly review
    5. You will see a series of drop-down menus under the header COMPARING CHANGES. Make sure the the second from the right, ```base:``` is set to ```OCR_proofing``` and not ```master```
    6. Click ```Create pull request```
    7. If further commenting is necessary, add in next dialogue box. If not, click ```Create pull request``` again.
  10. Open next file, begin proofing. 
    
      
  
