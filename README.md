# Classification of Arabic nouns and their use as qualitative nouns

## Summary

I have jotted down some notes to help myself and other students of Arabic with Arabic nouns and their behavior as na3t.

You may report any errors by opening an issue.

## Building the document

These steps are for the Linux environment but you should be able to modify them if needed for other OSs.

1. Install R or RStudio.
2. In R install the rmarkdown package.
   
   ```
   install.packages('rmarkdown')
   ```

3. Install Xelatex for PDF output.
4. Install fonts:

   a. Brill: https://brill.com/page/BrillFont/brill-typeface

   b. KFGQPC Uthman Taha: https://fonts.qurancomplex.gov.sa/wp02/عثمان-طه-نسخ

5. Run script `buidscript` which builds the HTML and PDF outputs.

   ```
   ./buildscript
   ```

6. Open doc.html in browser or doc.pdf in PDF reader.

