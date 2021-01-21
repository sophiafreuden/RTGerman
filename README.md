# RTGerman

Be sure to find and replace the following things IN THIS ORDER from the txt
 file in NotePad or equivalent:

 German month abbreviations replaced with appropriate calendar numbers. Some
 may have a period in them (e.g. Dez.).
 
 The RT German newsletter text replaced with a single space (may work better on
 Mac):
 Sie erhalten eine E-Mail, in der Sie Ihre Anmeldung bestätigen müssen.
 It can also look like this because of the month replacement:
 Sie erhalten eine E-5l, in der Sie Ihre Anmeldung bestätigen müssen.
 
 Replace en dash – with single space.
 
 Replace double spaces with a single space as many times as needed.
 
 Sentiment dictionary source (requires cleanup, see note below):
 https://www.kaggle.com/rtatman/german-sentiment-analysis-toolkit
 
 Sentiment dictionary cleanup instructions:
 There are two dictionaries, one positive and one negitive. In NotePad or equivalent, find and replace all the word type suffixes (|NN, |ADJX, and |VVINF) with nothing (delete them). Also be sure to add a row at the top with something like "word score alts" separated by a tab so they read into R with column names (as opposed to the first row of actual data as column names.)
 
 Because this is German and all the nouns (|NN) are capitalized, you will have to make everything lowercase either in R or in NotePad/equivalent.