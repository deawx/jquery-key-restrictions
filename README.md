# jQuery Key Restrictions

Description:
    A jQuery plugin that provides easier uses of key restrictions of letters, numbers and alpha numeric keys.

Guides:
    .letterOnly() allowed characters are A to Z and symbols of period, comma and dash. ([a-z], [. , -]);
    .numbersOnly() allowed characters are 0 to 9 and symbols of period, comma and dash. ([a-z], [. , -]);
    .alphaNumericOnly() allowed characters are A to Z, 0 to 9 and symbols of period, comma and dash. ([a-z], [. , -]);

Sample uses:
    $("#letter").lettersOnly(); //Restrict keys of the input that has an id of 'letter' to letters only.
    $("#number").numbersOnly(); //Restrict keys of the input that has an id of 'number' to numeric keys only.
    $("#alpha-number").alphaNumericOnly(); //Restrict keys of the input that has an id of 'alpha-numeric' to alpha numeric keys only.