===============================
vylint
===============================


> an automated style checker for Vyper Contracts.


Currently Supported Checks
--------------------------

Errors
~~~~~~

Basic white space errors, for consistent indenting

- E001: check that lines do not end with trailing whitespace
- E002: ensure that indents are only spaces, and not hard tabs
- E003: ensure all indents are a multiple of 4 spaces
- E004: file did not end with a newline
- E005: file does not begin with #! or have a .sh prefix
- E006: check for lines longer than 79 columns

Future Supported Checks
--------------------------

Structure Errors
~~~~~~~~~~~~~~~~


- E010: Vyper Specific Error (*idk*)
- E011: *conditional* not on the same line as 
- E012: *operation precedance* 
- E020: Function declarations 

