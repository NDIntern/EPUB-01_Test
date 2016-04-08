# EPUB-01_Test

# PROOFING EPUBS THE RIGHT WAY

# INSTRUCTIONS FOR USING GITHUB TO PROOF EPUBS (without using the command line)

  1. Sign into GitHub. Username: NDIntern. Password: newdir1936.
  2. If repository is not added, searhc Github for CDWait and find repository. 
    * Repository naming convention: First two letters of authors name, plus first four letters of book title, without articles. I.e., Flaubert's DICTIONARY OF ACCEPTED IDEAS becomes flDICT.
  3. Click on the repository name.
  4. Download a ZIP file of the repository.
  5. Click on the ```Branch``` button. When you see the drop-down menu, click on ```OCR_proofing```.
  6. Open the OEBPS folder in Brackets.
  7. Proof. For ease of reading, use Web browser to read HTML files. 
    1. Put changes in as you edit. 
    2. Comment all changes to text using HTML comments. <!--This is a comment. It is not included in presentation-->
      * Example: if you find the following code:
    ```<p class="hanging">N<span class="small-1">ECTAR</span>. Confuse with ammbrosia.</p>```
      * Your edit will look like:
    ```<p class="hanging">N<span class="small-1">ECTAR</span>. Confuse with ambrosia.<!--"Ammbrosia" to "Ambrosia"--></p>```
     *  Many text editors will allow you to hotkey this change.
  8. When you finish editing a file, open the corresponding file on Github and replace its contents with your edited text.
  9. Commit changes
    * At the bottom of the editing window, you'll see a speech bubble that says ```propose file change```
    * There are two fields, one for a short description and one for an extended description. If proofing went smoothly, just write "OCR proofing" in the short description. If you feel I need to be aware of anything more complicated, write it out in the long description. I.e., if you think there may be errors in the HTML or typos in the print version. I.e., ```<!--There may be a print typo, "women" in line 22-->```
    * Make sure the button "commit directly to the ```OCR-proofing``` is checked.
    * Click ```Commit Changes```
    * You will see a window showing your changes in red and green. If needed, quickly review
    * 
    
      
  
