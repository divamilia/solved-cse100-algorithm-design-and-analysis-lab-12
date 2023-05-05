Download Link: https://assignmentchef.com/product/solved-cse100-algorithm-design-and-analysis-lab-12
<br>
<h1>Rod Cutting</h1>

<strong>Description </strong>In this assignment you are asked to implement a dynamic programming algorithm for the Rod Cutting Problem (chapter 15.1). In the Rod Cutting problem, you are given an integer <em>n </em>≥ 1, along with a sequence of positive prices, <em>p</em><sub>1</sub><em>,p</em><sub>2</sub><em>,…,p<sub>n</sub></em>, where <em>p<sub>i </sub></em>is the market price of rod of length <em>i</em>. The goal is to figure out a best way of cutting the given rod of length <em>n </em>to generate the maximum revenue. You can assume that the given prices <em>p</em><sub>1</sub><em>,p</em><sub>2</sub><em>,…,p<sub>n </sub></em>are all integers.

<strong>Input  </strong>The input has the following format. The input starts with <em>n</em>. Then, <em>p</em><sub>1</sub><em>,p</em><sub>2</sub><em>,…,p<sub>n </sub></em>follow, one per each line.

<strong>Output </strong>In the first line, output the maximum revenue (<em>r<sub>n</sub></em>), followed by an enter key. In the second line, sequentially output the length of each piece in your optimal cutting, and output -1, followed by a space key; separate two adjacent numbers by a space key.

<strong>Examples of input and output</strong>

<em>Input</em>

7

1

5

8

9

10

17

17

<em>Output</em>

18

1 6 -1

Alternatively, the second line can be replaced with “6 1 -1”, “2 2 3 -1”, “2 3 2 -1”, or “3 2 2 -1”. That is, any sequence of piece lengths giving the maximum revenue will be considered to be correct.