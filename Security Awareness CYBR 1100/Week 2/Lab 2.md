                                  Lab 2-1: Using an Online Password Cracker

In this project, you create a digest on a password and then crack it to demonstrate the speed of cracking weak passwords.

●	The first step is to use a general-purpose hash algorithm to create a password hash. Use your web browser to go to www.fileformat.info/tool/hash.htm. (The location of the content on the Internet may change without warning; if you are no longer able to access the program through this URL, use a search engine and search for “Fileformat.info.”)

●	Under String hash, enter the simple password apple123 in the Text: box.

●	Click Hash.

●	Scroll down the page and copy the MD5 hash of this password to your Clipboard by selecting the text, right-clicking it, and choosing Copy.

**MD5 Hash for apple123: 75a593a34aa5ba8e5e5788b7c899802e**

●	Open a new tab on your web browser.

●	Go to https://crackstation.net/.

●	Paste the MD5 hash of apple123 into the text box below Enter up to 20 non-salted hashes, one per line.

●	In the reCAPTCHA box, click the I ’ m not a robot check box.

●	Click Crack Hashes.

●	How long did it take to crack this hash?

**It took less than one second for it to crack the MD5 hash.**

●	Click the browser tab to return to FileFormat.Info.

●	Under String hash, enter the longer password applesauce1234 in the Text: box.

●	Click Hash.

**MD5 Hash for applesauce1234: 18ff67e7f937a18d89d078ce868b1a19**

●	Scroll down the page and copy the MD5 hash of this password to your Clipboard.

●	Click the browser tab to return to the CrackStation site.

●	Paste the MD5 hash of applesauce1234 into the text box below Enter up to 20 non-salted hashes, one per line.

●	In the reCAPTCHA box, click the I ’ m not a robot check box.

●	Click Crack Hashes.

●	How long did it take this online rainbow table to crack this stronger password hash?

**Again, it took the password cracker nearly instantaneous results of the correct password.**  

●	Click the browser tab to return to FileFormat.Info and experiment by entering new passwords, computing their hash, and testing them on the CrackStation site. If you are bold, enter a string hash that is similar to a real password that you use.

**I tried a fake password similar to the style I use and it came back with a red Type Unknown, Results Not Found. I use a string of randomized letters and numbers in a six-by-three pattern with no discernible words or digits that could give away information such as XXXXXX-XXXXXX-XXXXXX. It has worked for me since changing after learning the bad habits I was creating for my passwords.** 
 
●	What does this tell you about the speed of password-cracking tools? What does it tell you about how easy it is for attackers to crack weak passwords?

**This tells me the algorithms and hashs the banks and other companies use have been broken long ago, how truly exploitable the current system is and how important it is to have personal weaponry such as stronger passwords through using simple rules to keep you safe. I will use the rules of 1) Not using passwords consisting of dictionary words or phonetic words even though when I tried a rather uncouth phrase, albeit with a more intellectual phrasing, 2) I don’t repeat characters or use sequential letters or numbers 3) I don’t use birthdays or family members’ information, addresses, pet names, or any personal information, and 4) I use long passwords with a sequence of randomized letters and numbers in a six-by-three pattern such as ugbk3g-ryfevx-sfEyba (fake password).**

●	Close all windows.
