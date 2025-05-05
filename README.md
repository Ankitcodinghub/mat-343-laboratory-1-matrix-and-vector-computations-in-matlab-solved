# mat-343-laboratory-1-matrix-and-vector-computations-in-matlab-solved
**TO GET THIS SOLUTION VISIT:** [MAT 343 Laboratory 1 Matrix and Vector Computations in MATLAB Solved](https://www.ankitcodinghub.com/product/mat-343-laboratory-1-matrix-and-vector-computations-in-matlab-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;7147&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MAT 343 Laboratory 1 Matrix and Vector Computations in MATLAB Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
In this laboratory session we will learn how to

1. Create matrices and vectors.

2. Manipulate matrices and create matrices of special types

3. Add and multiply matrices

Preliminaries

The MATLAB Desktop Display

The MATLAB default desktop consists of four windows: the command window, the Current Directory Browser, the Workspace Browser, and the Command History.

• The command window is where MATLAB commands are entered and executed.

• The Current Directory Browser allows you to view MATLAB and other files and to perform file operations such as opening and editing or searching for files.

• The Workspace Browser allows you to view and make changes to the contents of the workspace.

• The Command History allows you to view a log of all the commands that have been entered in the command window. To repeat a previous command, just click on the command to highlight it and then double-click to execute it. You can also recall an edit command directly from the command window by using the arrow keys. From the command window, you can use the up arrow to recall previous commands. The commands can then be edited using the left and right arrow keys. Press the Enter key of your computer to execute the edited command.

Any of the MATLAB windows can be closed by clicking on the × in the upper right corner of the window. To detach a window from the MATLAB desktop, click on the arrow that is next to the x in the upper right corner of the window.

Help Facility MATLAB includes a HELP facility that provides help on all MATLAB features.

• helpbrowser: if you type helpbrowser in the command window the MATLAB’s help browser

will open (alternatively you can click on the help button in the toolbar (this is the button with ?

Symbol)

• help : if you know the exact name of a function, you can get help on it by typing help functioname.

For example, typing help help provides help on the function help itself.

• look for: If you are looking for a function, use lookfor keyword to get a list of functions with the

string keyword in them. For example, typing lookfor ‘identity matrix’ lists functions (there are two of them) that create identity matrices.

If you have never used MATLAB before, we suggest you type demo at the MATLAB prompt. Click on Getting Started with MATLAB and run the file. Then move on to the demo on Working in the Development Environment and the demo on Working with Arrays.

2 MATLAB sessions: Laboratory 1

Matrices in MATLAB

Entering matrices in MATLAB is easy. For example, to enter the matrix

A =





1 2 3 4

5 6 7 8

9 10 11 12

13 14 15 16





type A=[1, 2, 3, 4; 5, 6, 7, 8; 9, 10, 11, 12; 13, 14, 15, 16]

or the matrix could be entered one row at a time:

A=[ 1 2 3 4

5 6 7 8

9 10 11 12

13 14 15 16]

Once a matrix has been entered, you can edit it. Here are some examples:

Input Output

A(1,3) = 5 A =

1 2 5 4

5 6 7 8

9 10 11 12

13 14 15 16

Changes the third entry in the

first row of A to 5

C = A(2:3,2:4) C =

6 7 8

10 11 12

Submatrix consisting of the entries

in rows 2 and 3 and

columns 2 through 4

A(:,2:3) ans =

2 3

6 7

10 11

14 15

Submatrix of A consisting of

all the elements in the second

and third columns

A(4,:) ans =

13 14 15 16

Fourth row of A

E = A([1,3],[2,4]) E =

2 4

10 12

Matrix whose entries are those

which appear only in the first

and third rows and second and

fourth column of A

Vectors

Vectors are special cases of matrices, with just one row or one column. They are entered the same way

as a matrix. For example

u = [1, 3, 9] produces a row vector

v = [1; 3; 9] produces a column vector.

Row vectors of equally spaced points can be generated with MATLAB’s : operation or using the

linspace command.

MATLAB sessions: Laboratory 1 3

Input Output

x = 2:6

x =

2 3 4 5 6

row vector with integer

entries going

from 2 to 6

x = 1.2:0.2:2

x =

1.2000 1.4000 1.6000 1.8000 2.0000

Row vector with

stepsize 0:2

x = linspace(1.2,2,5)

x =

1.2000 1.4000 1.6000 1.8000 2.0000

Row vector with 5

equally spaced entries

between 1:2

and 2

Generating Matrices

We can also generate matrices by using the built-in MATLAB functions. For example, the command B=rand(4) generates a 4 × 4 matrix whose entries are random numbers between 0 and 1. Here is a list of the most

common built-in matrices:

rand(m,n) m by n matrix with random numbers between 0 and 1 eye(m,n) m by n matrix with 1’s on the main diagonal zeros(m,n) m by n matrix of zeros

ones(m,n) m by n matrix of ones

triu(A) extracts the upper triangular part of the matrix A

tril(A) extracts the lower triangular part of the matrix A

diag(v,k) square matrix with the vector v on the kth diagonal

The first four commands above with a single argument, e.g. ones(m), produce a square matrix of

dimension m.

More special matrices:

There is also a set of built-in special matrices such as magic, hilb, pascal, toeplitz, and vander.

The matrix building commands can be used to generate block of partitioned matrices. Here is an

example:

Input Output

E=[eye(2),ones(2,3);zeros(2),[1:3; 3:-1:1]]

E =

1 0 1 1 1

0 1 1 1 1

0 0 1 2 3

0 0 3 2 1

Addition and Multiplication of Matrices

Matrix arithmetic in MATLAB is straightforward. We can multiply our original matrix A times B

simply by typing A*B. The sum and difference of A and B are given by A + B and A – B, respectively.

The transpose of the real matrix A is given by A’.

4 MATLAB sessions: Laboratory 1

Exponentiation

Powers of matrices are easily generated. The matrix A5 is computed in MATLAB by typing A^5. We

can also perform operations element-wise by preceding the operand by a period.

For instance, if V=[1,2; 3,4], then

Input Output

V^2

ans =

7 10

15 22

V.^2

ans =

1 4

9 16

component-wise exponentiation

Appending a row or a column

A row can be easily appended to an existing matrix provided the row has the same length of the rows

of the existing matrix. The same thing goes for the columns. The command A=[A, v] appends the

column vector v to the columns of A, while A = [A; u] appends the row vector u to the rows of A.

Examples: If A =





1 0 0

0 1 0

0 0 1



, u =

[

5 6 7

]

, and v =





2

3

4



, then

• C = [A; u] produces C =





1 0 0

0 1 0

0 0 1

5 6 7





, a 4 × 3 matrix

• D = [A, v] produces D =





1 0 0 2

0 1 0 3

0 0 1 4



, a 3 × 4 matrix.

Deleting a row or column

Let A=[1, 2, 3, 4, 5; 6, 7, 8, 9, 10; 11, 12, 13, 14, 15], then

Input Output

A(2,:) = [] A =

1 2 3 4 5

11 12 13 14 15

deletes the 2nd row of matrix A

A(:,3:5) = [] A =

1 2

6 7

11 12

deletes the 3rd through 5th

columns of A

A([1,3],:) = [] A =

6 7 8 9 10

deletes the 1st and 3rd row of A

MATLAB sessions: Laboratory 1 5

Columnwise Array Operators

MATLAB has a number of functions that, when applied to either a row or column vector x, returns

a single number. For example, the command max(x) will compute the maximum entry of x , and the

command sum(x) will return the value of the sum of the entries of x. Other functions of this form are

min, prod, mean. When used with a matrix argument, these functions are applied to each column vector

and the results are returned as a row vector.

For example if A =





−3 2 5 4

1 3 8 0

−6 3 1 3



, then

Input Output

min(A) ans =

-6 2 1 0

minimum entry in each column

of A

max(A) ans =

1 3 8 4

maximum entry in each column

of A

sum(A) ans =

-8 8 14 7

sum of the entries in each column

of A

prod(A) ans =

18 18 40 0

product of the entries in each

column of A

EXERCISES

Instructions

You will need to record the results of your MATLAB session to generate your lab report. Create a

directory (folder) on your computer to save your MATLAB work in. Then use the Current Directory

field in the desktop toolbar to change the directory to this folder. Now type

diary lab1.txt

followed by the Enter key. Now each computation you make in MATLAB will be save in your directory

in a text file named lab1.txt. When you have finished your MATLAB session you can turn off the

recording by typing diary off at the MATLAB prompt. You can then edit this file using your favorite

text editor (e.g. MS Word).

Lab Write-up: Now that your diary file is open, enter the command format compact (so that when

you print out your diary file it will not have unnecessary spaces), and the comment line

% MAT 343 MATLAB Assignment # 1

Put labels to mark the beginning of your work on each part of each question, so that your edited lab

write-up has the format

% Question 1

.

.

% Question 2 (a)

6 MATLAB sessions: Laboratory 1

Final Editing of Lab Write-up: After you have worked through all the parts of the lab assignment

you will need to edit your diary file.

• Remove all typing errors.

• Unless otherwise specified, your write-up should contain the MATLAB input commands, the corresponding output,

and the answers to the questions that you have written.

• If the question asks you to write an M-file, copy and paste the file into your diary file in the

appropriate position (after the problem number and before the output generated by the file).

• If the question asks for a graph, copy the figure and paste it into your diary file in the appropriate

position. Crop and resize the figure so that it does not take too much space. Use “;” to suppress

the output from the vectors used to generate the graph. Makes sure you use enough points for

your graphs so that the resulting curves are nice and smooth.

• Clearly separate all questions. The questions numbers should be in a larger format and in boldface.

Preview the document before printing and remove unnecessary page breaks and blank spaces.

• Put your name and class time on each page.

Important: An unedited diary file without comments submitted as a lab writeup is not

acceptable.

1. Entering matrices: Enter the following matrices:

A =

[

2 6

3 9

]

; B =

[

1 2

3 4

]

; C =

[

−5 5

5 3

]

2. Check some linear algebra rules:

(a) Is matrix addition commutative? Compute A + B and then B + A. Are the results the

same?

(b) Is matrix addition associative? Compute (A + B) + C and A + (B + C) in the order

prescribed. Are the results the same?

(c) Is multiplication with a scalar distributive? Compute (A + B) and A + B, taking

= 5 and show that the results are the same.

(d) Is multiplication with a matrix distributive? Compute A(B + C) and compare with

AB + AC.

(e) Matrices are different from scalars!

(i) For scalars, ab = ac implies that b = c if a ̸= 0. Is that true for matrices? Check by

computing AB and AC for the matrices given above.

(ii) In general, matrix products do not commute either (unlike scalar products). Check if AB

and BA give different results.

3. Create matrices with zeros, eye, ones, and triu: Create the following matrices with the

help of the matrix generation functions zeros, eye , ones, and triu. See the on-line help on these

functions if required (i.e. help eye)

M =

[

0 0 0

0 0 0

]

; N =





5 0 0

0 5 0

0 0 5



; P =

[

3 3

3 3

]

Q =





1 1 1

0 1 1

0 0 1



:

MATLAB sessions: Laboratory 1 7

4. Create a big matrix with submatrices: The following matrix G is created by putting matrices

A, B, and C from Exercise 1, on its diagonal and inserting 2×2 zeros matrices and 2×2 identity

matrices in the appropriate position. Create the matrix using submatrices A, B, C, zeros and

eye (that is, you are not allowed to enter the numbers explicitly).

G =





2 6 0 0 1 0

3 9 0 0 0 1

0 0 1 2 0 0

0 0 3 4 0 0

1 0 0 0 −5 5

0 1 0 0 5 3





5. Manipulate a matrix: Do the following operations on matrix G created above in Problem 4.

(a) Extract the first 4×4 submatrix from G and store it in the matrix H, that is, create a matrix

H =





2 6 0 0

3 9 0 0

0 0 1 2

0 0 3 4





by extracting the appropriate rows and columns from the matrix G.

(b) Replace G(5,5) with 4.

(c) What happens if you type G(:,:) and hit return? Do not include the output in your lab

report, but include a statement describing the output in words.

What happens if you type G(:) and hit return? Do not include the output in your lab report,

but include a statement describing the output in words.

(d) What do you get if you type G(7) and hit return? Can you explain how MATLAB got that

answer? Try G(16) to confirm your answer.

(e) What happens if you type G(12,1) and hit return?

(f) What happens if you type G(G&gt;5) and hit return? Can you explain how MATLAB got that

answer? What happens if you type G(G&gt;5) = 100 and hit return? Can you explain how

MATLAB got that answer?

(g) Delete the last row and the third column of the matrix G.

6. See the structure of a matrix: Create a 20 × 20 matrix with the command A = ones(20);

Now replace the 10 × 10 submatrix between rows 6:15 and columns 6:15 with zeros. See the

structure of the matrix (in terms of nonzero entries) with the command spy(A).

Set the 5 × 5 submatrices in the top right corner and bottom left corner to zeros and see the

structure again.

NOTE: Use semicolon to suppress the output for all the matrices in this problem. In your labwrite

up include the pictures obtained with the spy command. To include the pictures, open your

diary file using a word processor such as MS Word then, on the MATLAB figure, select “Edit”

and “Copy Figure”, and paste the picture into the Word file. Make sure you crop and resize the

picture so that it does not take up too much space.

7. Create a symmetric matrix: Create an upper triangular matrix with the following command:

A = diag(1:6) + diag(7:11, 1) + diag(12:15, 2)

Make sure you understand how this command works (see the on-line help on diag). Now use the

upper off-diagonal terms of A to make A a symmetric matrix with the following command:

A = A + triu(A,1)’

8 MATLAB sessions: Laboratory 1

This command takes the upper triangular part of A above the main diagonal, flips it (transpose),

and adds to the original matrix A, thus creating a symmetric matrix A. See the on-line help on

triu.

8. Do some cool operations: Create a 10×10 random matrix with the command A = rand(10);

Now do the following operations:

(a) Multiply all elements of A by 100 and store the result in the matrix A. Then round off all

elements of the matrix to integers with the command A = fix(A).

(b) Replace all elements of A that are less than 10 with zeros (Hint: see exercise 5(f))

(c) Replace all elements of A &gt; 90 with infinity (inf)

(d) Extract all 30 ≤ aij ≤ 50 in a vector b, that is, find all elements of A that are between 30

and 50 and put them in a vector b. (Hint: the logical operator &amp; (AND) may be useful).
