### WonderFull TTS 

18/12/2025  

We successfully made it so that our Python script can accept a file path on Windows (even when dragged and dropped) and correctly figure out what kind of file it is.
The script can now take any file path pasted or dragged into PowerShell. 
        *It correctly handles:*
            *Paths with spaces*
            *Paths with apostrophes (like I'm)*
            *Paths pasted with quotes*
            *Paths pasted with PowerShell’s & 'path' format*
        *It checks that the file actually exists*
        *It successfully detects the file’s MIME type using python-magic*

In short:
    *If the file exists, the script can now recognize what kind of file it is.*
