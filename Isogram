// An isogram is a word that has no repeating letters, consecutive or non-consecutive. Implement a function that determines whether a string that contains only letters is an isogram. Assume the empty string is an isogram. Ignore letter case.
//
// isIsogram("Dermatoglyphics") == true
// isIsogram("aba") == false
// isIsogram("moOse") == false // -- ignore letter case

function isIsogram(str){
 let firstLetter;
 let nextLetter;
 str = str.toLowerCase();
 for(firstLetter = 0; firstLetter < str.length; ++firstLetter) {
   for(nextLetter = firstLetter + 1; nextLetter < str.length; ++nextLetter) {
     if(str[firstLetter] === str[nextLetter]) {
       return false;
     }
   }
 }
 return true;
}

isIsogram ("isogram")
