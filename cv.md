# Dzmitry Leiko
## Contact information
* Discord: DarkMilkMan#1383
* Email: darkmilkman@gmail.com
## About Myself
My main goal is to get up-to-date knowledge in frontend development. and learn to work in a team.

For seven years I have been developing websites learning only with the help of Google search. I have several successful projects.
## Skils
* HTML
* CSS
* JS (Basic)
  * jquery
* PHP (Basic)
* MySQL (Basic)
## Code example
**6 kyu Duplicate Encoder**

The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.
```
function duplicateEncode(word){
	const upperWord = word.toUpperCase();
    let newWord = '';
	let letterFirst = true;
	let letterLast = upperWord[upperWord.length - 1];
	let letterFalse = '';
    for(let i = 0; i < upperWord.length; i++) {
		let letter = upperWord[i];
		for(let a = 0; a < upperWord.length; a++) { 
			if (upperWord[a] === letter && a !== i){
				letterFirst = false;
				letterFalse = upperWord[a];
			} else if (upperWord[a] === letter && i === upperWord.length - 1){
				letterFirst = false;
			} else {
				letterFirst = true;
			}
		}
		
		if (letter === letterFalse){
			newWord = newWord + ')';
		} else if (letterFirst || letter !== letterFalse){
			newWord = newWord + '(';
		}	
		
    }
	return newWord;
}
```
## Work experience
I have several active projects:

### Online stores
* https://budomarkt.ru/
* https://bodymarkt.ru/
### News sites
* https://wotexpress.info/
* https://hypegamenews.ru/
* https://kinoinside.ru/

All sites are created on Diafan CMS. I did the whole frontend and a bit of the backend.
## Education
Full secondary education.

## English
A1