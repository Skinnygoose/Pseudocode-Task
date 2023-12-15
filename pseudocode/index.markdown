# pseudocode

<style>@import url("//readme.codeadam.ca/readme.css");</style>

<ul>
    <li><a href="https://users.csc.calpoly.edu/~jdalbey/SWE/pdl_std.html">https://users.csc.calpoly.edu/~jdalbey/SWE/pdl_std.html</a></li>
    <li><a href="https://gist.github.com/camilstaps/59c4574ab8131fb83612a446606cbcba">https://gist.github.com/camilstaps/59c4574ab8131fb83612a446606cbcba</a></li>
</ul>

<hr>

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="50">
</a>

Pseudocode is a type of structured English that is used to describe algorithms. It enables the designer to concentrate on the logic of the algorithm without being distracted by language syntactic concerns.  At the same time, the pseudocode must be finished.  It describes the algorithm's full logic, making execution a mindless mechanical operation of converting line by line into source code.

In general the vocabulary used in the pseudocode should be the vocabulary of the problem domain, not of the implementation domain.  The pseudocode is a narrative for someone who knows the requirements (problem domain) and is trying to learn how the solution is organized.  E.g.,

Extract the next word from the line (good)
set word to get next token (poor)
Append the file extension to the name (good)
name = name + extension (poor)

FOR all the characters in the name (good)
FOR character = first to last (ok)
