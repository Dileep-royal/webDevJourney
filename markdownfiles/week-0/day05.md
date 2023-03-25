# ==== Day-05 ====

* Form validate options
* Validating form with pattern Attribute

# Form Validate options
* novalidate - used in form element
* validate - used in form element
* formnovalidate - used on buttons
* form="id of form" - used to link separated child content from parent form.

# Pattern Attribute to validate Inputs
pattern attribute is a regular expression(RegEx) to set constraint pattern and validate input element values. 
* [A-Za-z0-9]{5,12} - the input only supports uppercase, lowercase letters and numbers of length between 5 to 12 only.
* [a-zA-Z]\d{10} - the input only supports uppercase and lowercase letters of length 10 only
* (\d{5}([\-]\d{4})?) - the [\-]\d{4} which is enclosed in ()? is optional

# autocomplete
* autocomplete="email" - to specify which type of input. for e.g: email,tel,url,name,etc..
* autocomplte="on" - used on form element and individual input elements also(not recommended for input elements)
* autocomplete="off" - used on form element and individual elements also.
