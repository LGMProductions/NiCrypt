# NiCrypt
A concept of encrypting text-messages. 

The idea behind it:
You insert a text: abc
When you click on encrypt, a random text-key will be created with the same length.
For example, you get the key: abc
The inserted text and the key is being "translated" into nummeric arrays:
a -> 1
b -> 2
c -> 3
Then each number is being added together:
Inserted text   Key       Sum
a -> 1      +   a -> 1  = 2
b -> 2      +   b -> 2  = 4
c -> 3      +   c -> 3  = 6

Then, the sum translated into letters:
2 -> b
4 -> d
6 -> f

bdf is the encrypted text.



If you want to develop it further, i would be happy.
The code has a few bugs, if you want to improve it, please do :)
