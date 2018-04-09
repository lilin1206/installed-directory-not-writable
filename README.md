# how to solve "installed-directory-not-writable"

I jumped between windows&linux system, and that where the problem comes, the DESeq2 was okay to use in windows, but then when I use in linux system, it was not able to install successfully. Then I come back to windows, it shows also DESeq2 is not working. 

"installed directory not writable, cannot update packages 'boot', 'class', 'KernSmooth', 'mgcv', 'nne".

To solve this problem, just open the rstudio as administrator in windows, or use as superuser in linux, and then reinstall DESeq2. Problem solved.
