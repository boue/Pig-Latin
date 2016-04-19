# Pig Latin Translation Engine ![alt text](http://www.iconsdb.com/icons/preview/black/pig-xl.png "Pig Latin")

----
The following rules were taken into consideration based on the test cases provided

For words that begin with consonant sounds, all letters before the initial vowel are placed at the end of the word sequence.
We are considering the letters B, C, D, F, G, H, J, K, L, M, N, P, Q, R, S, T, V, X, Z, and usually W and Y consonants.
"pig" → "igpay"
"trash" → "ashtray"

We are considering the letters A, E, I, O, and U to be vowels.
For words that begin with vowel sounds or a silent letter, one just adds "ay" to the end.
"eat" → "eatyay"
"are" → "areyay"

hello => ellohay 
eat => eatay 
eat world => eatay orldway 
Hello => Ellohay 
Apples => Applesay 
eat… world?! => eatay… orldway?! 
school => oolschay 
quick => ickquay

### Edge-cases / Things to take into consideration

- Tokenization when we are dealing with a sentence  
- Punctuation will have to be respected and kept the same   
- Capitalization (see Question 1)

### Questions

- In the testing case 'Hello => Ellohay' E becomes capitalized? Does this mean when 
any input that is passed in had an initial capital letter we are to capitalize the 
first letter of the Pig Latin version?
- In terms of the complexity of this algorithm, are we building this tool in order to serve a rather big amount of data or are our inputs going to be limited to a few phrases?
- Can you please confirm that the incoming data will be of String type and be just one string?
- From your test examples we see that punctuations are left untouched, does this hold for integers, and any other types apart from vowels/consonants?
