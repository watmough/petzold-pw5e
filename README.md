# petzold-pw5e
Revisited C source code for Charles Petzold's Programming Windows 5th Edition ISBN-10 157231995X

The 5th edition Programming Windows was published in 1998 in the era of Windows 98,
 Windows NT and Internet Explorer 4. There is a 6th edition, but this deals with
 later Windows technologies - the 5th edition was the last to deal with purely C
 programming. Many programmers learnt (and are still learning) Windows Programming
 from this huge tome and its various editions. An excellent work.
 
Purpose of this repository
--------------------------

This repository was created to give the author working code to transliterate into
 the rust language - the rusty fruit of this exercise being placed in the 
 petzold-pw5e-rs repository.

Contents of this repository
---------------------------

The initial commit was the source code roughly "as is" from the original
 distribution from the book's website.

- The Microsoft *.dep* *.dsp* *.dsw* & *.mak* files and the *Debug* and *Release*
  folders were omitted.
- Some of the files were renamed to
  - improve lexicographical sorting
  - avoid duplicate names
- Duplicate files were eliminated. Using the C compiler and the development
  environment allows files to be used across multiple projects.
