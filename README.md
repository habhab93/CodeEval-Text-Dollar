CodeEval-Text-Dollar
====================

CodeEval challenge called Text Dollar, where you take an input file with format:

3
10
21
466
1234

and output result in this format:

ThreeDollars
TenDollars
TwentyOneDollars
FourHundredSixtySixDollars
OneThousandTwoHundredThirtyFourDollars

as described here: https://www.codeeval.com/public/fbee8632e511329dd61c922020ca600fecaa3f83/

-----

My solution passed with a score of 97.5 (I forgot to change the output to CamelCase). This challenge is ranked under the "Hard Level" difficulty and has a 68% pass rate.

Completed as part of the Dot & Bo interview process.

-----

edit: My original assumption was incorrect; I had implemented CamelCase correctly.  It turns out I had 1000000 print out as OneMillionThousandDollars instead of OneMillionDollars.  I fixed this by checking whether the thousand digits string equals "000" which is a quick fix.  Obviously this would present a problem if we considered numbers >= 1 billion.
