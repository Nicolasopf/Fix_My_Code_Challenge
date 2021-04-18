# Fix my code project
This is a project about fix the code of other people.

## Files table
| File | Initial problem | Solution |
| ----- | ----- | ------ |
[0x00-challenge/0-fizzbuzz.py](0-fizzbuzz.py) | The program was printing wrong when the number was multiple of 3 and 5 | Update the statement order, first check if it is multiple of both, then, of three, then, of five.
[0x00-challenge/1-print_square.js](1-print_square.js) | The square was printing wrong because the function parseInt was receiving process.argv[2], 16. | Change 16 to 10, because parseInt receive as second argument the base to parse and we use base10.
[0x00-challenge/4-delete_dnodeint](4-delete_dnodeint) | When deleting a Node, it was deleting in wrong order, everything was bad. | Update the connections between nodes to make sure the double linked list is linked correctly after delete.

## Source code with problems:
https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge

## Author
Nicolas Urrea - https://github.com/Nicolasopf
