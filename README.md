More Array Methods:

charAt() - it returns the character at the specified index in the string. The index of the first character is 0, the second is 1 etc.

Example 1:

const Str = "I love to go to Dave and Busters"

const sent = Str.charAt(3);

console.log(sent);

Example 2:

const rap = "Meek Mill";

const rapper = rap.charAt(0);

console.log(rapper);

Example 3:

const food = "sushi";

const japanese = food.charAt(food.length-1);

console.log(japanese) //* if you use -1 it will start at the last letter


charCodeAt() - Returns an integer between 0 and 65535 representing the unicode at the given index.

Example 1:

const rappers = "Dababy";

const index = 3;

console.log(rappers.charCodeAt(index));

Example 2:

console.log("Chance".charCodeAt(1));

Example 3:

const phrase = "Go Knicks";

const ind = 5;

console.log(phrase.charCodeAt(ind));


Concat() - merge 2 or more arrays. It does not change the existing arrays, but returns a new array

Example 1:

const arr = ["Jessica","Savannah","Heather","Brandon"]
const arr2 = ["Zachary","Daniel","Andrew","Heidi"]
const arr3 = arr.concat(arr2);

console.log(arr3);

Example 2:

const rap = ["Pooh Sheisty","Chance the Rapper","Megan Thee Stallion"]
const rap2 = ["Dababy","Meek Mill","Drake","Lil Durk"]
const rap3 = ["Lil baby","DJ Khaled","Young Thug","Ty Dolla Sign"]
rap4 = rap.concat(rap2,rap3)

console.log(rap4);

Example 3:

const people = ["Brandon","Jared","Kristen"]

const ID = [1,2,3]

const peID = people.concat(ID);

console.log(peID)


Includes() - determines whether an array includes a certain value among its entries, returning true or false.

Example 1:

const words = ["Butter","Milk","Clock","Time"];

console.log(words.includes("Butter"));

Example 2:

const num = [1,2,3,4]

console.log(num.includes(6));

Example 3:

console.log(["Chance","little","Stall"].includes("Chance"));


indexOf - returns the first index at which a given element can be found in the array, or -1 if it's not present.

Example 1:

const animals = ["Cow","Chicken","Horse","Turkey","Dogs","Cats"]

console.log(animals.indexOf("Cow"));

Example 2:

console.log(animals.indexOf("Horse"));

Example 3:

console.log(animals.indexOf("Rooster"));


match - retrieves the result of matching a string against a regular expression

Example 1:

const letters = "ABCDEFGHIJKLMNOP"

const matched = /[A-C]/g;

const ArrMatch = letters.match(matched)

console.log(ArrMatch);

Example 2:

const sent = "I need to go to the bathroom";

const sentMatch = /[A-Z]/g

const found = sent.match(sentMatch)

console.log(found);

Example 3:

const sent2 = "I love to listen to hip-hop";

const Matchsent = /[A-J]/g

const founds = sent2.match(Matchsent);

console.log(founds);


repeat - constructs and returns a new string which contains the specified number of copies of the string on which it was called concatenated together.

Example 1:

const word = "Change ";

console.log(word.repeat(4));

//Example 2:

const sent = "Pooh Sheisty ";

console.log(`I am going to see ${sent.repeat(2)}`);

//Example 3:

const phrase = "Change the world";

console.log(phrase.repeat(2.5));


replace - returns a new string with some or all matches of a pattern replaced by a replacement. The pattern can be a string and the replacement can be a string or a function to be called for each match.

Example 1:

const sentence = "We went to see a Lunay concert";

console.log(sentence.replace("Lunay","Kevin Roldan"));

Example 2:

const sentence2 = "We saw Chance The Rapper perform live";

console.log(sentence2.replace("Chance The Rapper","Dababy"));

Example 3:

const phrase = "You're fired";

console.log(phrase.replace("fired","hired"))

search - searches a string for a specified value, and returns a position of the match. returns -1 if no match is found.

Example 1:

const searching = "When will the next Bad Bunny concert be";

console.log(searching.search("Bad Bunny"));

Example 2:

console.log(searching.search("When"));

Example 3:

console.log(searching.search("Lil Durk"));


slice - returns a shallow copy of a portion of an array into a new array object selected from start to end where start and end represent the index of items in that array.

Example 1:

const states = ["New York", "California","New Hamshire","Maine","Colorado"]

console.log(states.slice(1,4));

Example 2:

console.log(states.slice(2));

Example 3:

console.log(states.slice(0,1));


split - divides a string into an ordered list of substrings, put these substrings into an array, and returns an array.

Example 1:

const str = "I went to see Chance the Rapper movie";

const words = str.split(" ");
console.log(words[4]);

Example 2:

console.log(words[6]);

Example 3:

console.log(words);


substr - returns a portion of the string, starting at the specified index and extending for a given number of characters afterwards.

Example 1:

const job = "Software Engineer"

console.log(job.substr(0,2));

Example 2:

console.log(job.substr(1,4));

Example 3:

console.log(job.substr(5,8));


tolowercase - returns the calling string value converted to lower case

Example 1:

const upper = "DJ KHALED";

console.log(upper.toLowerCase());

Example 2:

const sent = "I like To Eat Food";

console.log(sent.toLowerCase());

Example 3:

const phrase = "Please Go Home";

console.log(phrase.toLowerCase());


toUpperCase - returns the calling string value converted to uppercase

Example 1:

const up = "ty dolla sign";

console.log(up.toUpperCase());

Example 2:

const cap = "joe and kamala";

console.log(cap.toUpperCase());

Example 3:

const notlower = "kanye west";

console.log(notlower.toUpperCase());


trim - removes whitespace from both ends of a string.

Example 1:

const space = "    You are Blocked     "

console.log(space.trim());

Example 2:

const tab = "      You can't follow this tweet      "

console.log(tab.trim());

Example 3:

const no = "     You are blocked from following blah tweets and viewing his tweets"

console.log(no.trim());
