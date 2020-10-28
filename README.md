Describe: pigLatin

Test: "It will add 'way' to the end of words that begin with a vowel"
Expect(pigLatin("a")).toEqual("away");

Test: "It will recognize words that begin with one or more consonants, move to the end and add "ay". 
Expect(pigLatin("st")).toEqual("stay");

Test: "If a word's beginning consonants include "qu", move to end and add "ay".
Expect(pigLatin("qu")).toEqual("quay");

