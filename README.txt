-----------------------------------------------

Thank you for downloading 
Regular Expression Accepted Strings Expander

developed by Tim Jensen
Contact @ Timothy.Jensen.TJJ@gmail.com

-----------------------------------------------

***What is This***
	-This program expands the possibilities of Regular Expressions(RE)
	by expressing all possible strings in the language as a long list of ORs(+).
	-From this an algorithm can be used to simply detect a matching string from user input.
	-Likewise this long list of strings in the language can be returned
	to the screen for deeper analysis by the user.
	-However REs involving stars(*) have infinitely many strings in the language 
	which is why this program has a terminating string length.
	
***How to Use***
	-Input the RE where "RE" is labeled.
		-REs must have balanced parentheses.
		-stars can be next to a symbol or grouped parentheses 
			-Ex: 10*1 or a(b+c)*+c
		-Use parentheses to group as desired.
		-Use + for ORs.
		-Press F1 for the empty string symbol(ε).
	-The "Guess" section will take your input and tell you if your string is in the language.
		-Leave the section blank to guess the empty string.
	-The "Max" section limits how large the strings of the star can get. Input a number to
	limit the maximum string length as desired. (Note that the longer the length the slower the calculation).
	However if just checking strings for acceptance this can be ignored as the program will detect your
	inputed guess length and adjust accordingly.
		-Note that error may occur after 32,000 entries have been exceeded. Thus make a reasonable max.
	-The "Sort" button when ON sorts alphabetically. If OFF will return raw output.
		-In both cases duplicate strings are removed.
	-The "Submit" button runs the algorithm and will display an indicator when finished.
		-When run the Guess text box will light up green for acccepted or red for rejected.
	-The "Show Strings" button will divert to another room where all the strings are displayed
	in a long list.
		-Use the scroll wheel to navigate the list.
		-Hit the button again to return.
	
	