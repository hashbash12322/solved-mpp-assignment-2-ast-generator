Download Link: https://assignmentchef.com/product/solved-mpp-assignment-2-ast-generator
<br>









Contents

1 Specification                                                                              2

2 Submission                                                                                               3

3 Change Log                                                                               3




Assignment 2version 1.0

After completing this assignment, you will be able to

<ul>

 <li>explain the stucture of parser generated by ANTLR</li>

 <li>manipulate (traverse, create) on tree, which has different types of node, using Visitor</li>

 <li>write a short program in Python to generate intermediate code (AST) for a valid MP program</li>

</ul>

1 Specification

A parser will check if the input is grammatically correct or not. If the input is grammatically wrong, an error message is released. This is what you did in the assignment 1. In the case the input is grammatically correct, an intermediate code is generated. This is the requirement of this assignment. As AST is selected to be the intermediate code, you are required to write an AST generator for a program written in MP. To complete this assignment, you need to watch the lecture of AST to:

<ul>

 <li>investigate the structure of a parser generated by ANTLR</li>

 <li>try to find out how to generate an AST from a parse tree.</li>

 <li>investigate the AST classes defined in Python.</li>

 <li>modify <a href="http://ASTGeneration.py">py</a> to generate an AST.</li>

 <li>check your code to make sure it right.</li>

</ul>

To complete this assignment, you need to:

<ul>

 <li>download initial code (assignment2.zip) and unzip it.</li>

 <li>copy your MP.g4, your solution of assignment 1, into folder src/main/mp/parser.</li>

 <li>have a look at folder src/main/mp/utils in the code of assignment 2 where there are 2 files <a href="http://AST.py">py</a> and <a href="http://Visitor.py">Visitor.py</a>. In these two files, just only <a href="http://AST.py">AST.py</a> is used in this assignment while the other file will be used in the next <a href="http://one.AST.py">one. AST.py</a> defines all classes in AST which is the output of this assignment. You are NOT allowed to modify all these files.</li>

</ul>




<ul>

 <li>modify <a href="http://ASTGeneration.py">ASTGeneration.py</a> in folder src/main/mp/astgen to generate AST from a parse tree, i.e. the result of assignment 2, generated from ANTLR.</li>

 <li>modify <a href="http://ASTGenSuite.py">ASTGenSuite.py</a> in folder src/test/ to create 100 tests in total for this assign­ment.</li>

</ul>

2 Submission

This assignment requires you submit your code in 3 files: MP.g4, <a href="http://ASTGeneration.py">ASTGeneration.py</a> and <a href="http://ASTGenSuite.py">ASTGenSuite.py</a>. MP.g4 is often modified to complete this assignment but even when it is not modified, it must also be submitted.

All the testcases for this assignment are correctly grammatically correct.

You are required to submit just only 3 files MP.g4, <a href="http://ASTGeneration.py">ASTGeneration.py</a> and <a href="http://ASTGen-Suite.py">ASTGen­</a><u>Suite.py</u>, which must have 100 different tests. Note that you must NOT compress your files when submit them.

The website <a href="http://www.cse.hcmut.edu.vn/onlinejudge">www.cse.hcmut.edu.vn/onlinejudge</a> will be opened soon for your test­ing of your code but you MUST submit your three files into BKeL. The deadline of the submission is announced in BKeL.

You must complete the assignment by yourself and do not let your work seen by someone else, otherwise, you will be punished by the university rule for plagiarism.

3 Change Log