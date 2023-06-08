# qr-code-generator
Takes user input (a URL) inside the terminal using "inquirer" npm package and stores it in a text file.
Generates qr-image for the inputted URL using "qr-image" npm package and stores it in png format.
Both, the text file containing user-inputted url and the png file containing qr image for that url are stored in your local storage using "File System"(fs) native Node module.
