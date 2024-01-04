# Rust Regex Compiler
My Regex Compiler has the following features:
* Capture groups ```"(ab)"``` - lets quantifiers operate on the entire group
* Character classes ```"[abc]"``` - matches any character in the class
* Character ranges ```"[a-zA-Z]"``` - matches any character in the range
* Alternation ```"a|b"``` - matches either a or b (can be stacked or nested in capture groups)
* Quantifiers:
  * ```"*"``` - 0 or more
  * ```"+"``` - 1 or more
  * ```"?"``` - 0 or 1
  * ```"{n}"``` - exactly n
  * ```"{n,}"``` - n or more
  * ```"{n,m}"``` - between n and m (inclusive)
  * ```"{,m}"``` - at most m

I chose this project because I wanted to work with graphs since I have only learned about them theoretically, but have never applied them on a real project. Creating a regex compiler seemed like the perfect way to implement a graph while also learning how Rust works and gaining Rust experience.  

*This project is part of a group project for CS 128 honors (https://github.com/Dandandooo). However, I designed and wrote all the code for the Rust Regex Compiler found in this repository. 
