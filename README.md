<a name="readme-top"></a>
<h1 align="center"> 🧠 nand2tetrisCourse 🧠 </h1>

<img src="https://i.imgur.com/dBaSKWF.gif" height="50" width="100%">

the course is on building a modern computer from basic logic gates to a general computer architecture capable of executing programs such as "Tetris".

during the course i was learn how to design and build all the hardware components (chips) using a hardware description language taught in the course. I was responsible for building these components from scratch and testing them using a hardware simulator provided along with the course materials. This hands-on experience was provided me with an in-depth understanding of the computer's inner workings. Additionally, I will also learn how to build an assembler program to translate programs written in symbolic language into binary code. This skill will enable me to program my computer and execute my own code.

By the end of this course, I will have the knowledge and practical experience necessary to build a fully functional computer and write my own programs. This is a challenging but rewarding course that will provide me with a unique understanding of how computers work.

Course instructors:

Prof. Shimon Shoken, Interdisciplinary Center

Noam Nissan, Hebrew University

<!-- Badges -->
<p>
  <a href="https://github.com/lironmiz/nand2tetrisCourse/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/lironmiz/nand2tetrisCourse" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/lironmiz/nand2tetrisCourse" alt="last update" />
  </a>
  <a href="https://github.com/lironmiz/nand2tetrisCourse/network/members">
    <img src="https://img.shields.io/github/forks/lironmiz/nand2tetrisCourse" alt="forks" />
  </a>
  <a href="https://github.com/lironmiz/nand2tetrisCourse/stargazers">
    <img src="https://img.shields.io/github/stars/ladunjexa/nand2tetrisCourse" alt="stars" />
  </a>
  <a href="https://github.com/lironmiz/nand2tetrisCourse/issues/">
    <img src="https://img.shields.io/github/issues/lironmiz/nand2tetrisCourse" alt="open issues" />
  </a>
  <a href="https://github.com/lironmiz/nand2tetrisCourse/language count/">
    <img src="https://img.shields.io/github/languages/count/lironmiz/nand2tetrisCourse" alt="language count" />
  </a>
</p>

 ![](https://img.shields.io/tokei/lines/github/lironmiz/nand2tetrisCourse?color=blue&label=Lines%20of%20Code)
![Size](https://img.shields.io/github/repo-size/lironmiz/nand2tetrisCourse?color=red&label=Repo%20Size%20)
 <img src="https://img.shields.io/github/languages/top/lironmiz/nand2tetrisCourse" alt="top language" />

<!-- Table of Contents -->
<details>

<summary>

# :notebook_with_decorative_cover: Table of Contents

</summary>

- [The Graduation Certificate](#star2-the-graduation-certificate)
- [Course Material](#books-course-material) 
- [Course Summary](#alien-course-summary) 
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)
- [About the authors](#telephone-about-the-authors)
- [Project Status](#octocat-project-status)

</details>  

<!-- The Graduation Certificate -->
# :star2: The Graduation Certificate 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Course Material -->
# :books: Course Material
 
    + Introduction to building systems
    + Language Description Hardware
    + Boolean algebra
    + building basic logic gates
    + Binary representation of numbers
    + Boolean arithmetic
    + Building adders and an algebraic-logic unit (ALU)
    + Time representation
    + Clock cycles
    + Flip-flop gates
    + Construction of registers and memory units (ROM, RAM) 
    + Machine language: symbolic representation, binary 
    + Writing and running programs in a low level programming language.
    + Computer architectures
    + Central processing unit
    + Management of input/output units
    + Building a processor 
    + Translation of programs: syntax, semantics, parsing, code generation, symbol tables
    + Assembler development

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- The Course Summary -->
# :alien: Course Summary

## 1. TABLE OF CONTENTS
  - [1. TABLE OF CONTENTS](#1-table-of-contents)
  - [2. BOOLEAN VALUES](#2-boolean-values)
  - [3. BOOLEAN VARIABLES](#3-boolean-variables)
  - [4. BOOLEAN FUNCTIONS](#4-boolean-functions)
  - [5. BOOLEAN ALGEBRA](#5-boolean-algebra)
  - [6. DISJUNCTIVE NORMAL FORM](#6-disjunctive-normal-form)
  - [7. NAND](#7-nand)
  - [8. LOGIC GATES](#8-logic-gates)
  - [9. HARDWARE DESCRIPTION LANGUAGE](#9-hardware-sescription-language)

## 2. BOOLEAN VALUES

![TrueOrFalseAndyCohenGIF (2)](https://user-images.githubusercontent.com/91504420/219793288-c281cd34-9b91-4b79-8412-3118b2af6549.gif)

A Boolean value is a data type that has two possible values, either "true" or "false". Boolean values are often used in programming to make decisions, comparisons, and to control program flow.

![image](https://user-images.githubusercontent.com/91504420/219793033-d9ea42c7-bc0d-4fd5-b7bb-267eb00a2128.png)

## 3. BOOLEAN VARIABLES

![ThereAreSoManyVariablesInPlayDavidRoseGIF](https://user-images.githubusercontent.com/91504420/219793867-04f1d601-8edb-4c42-9b1b-6d01dd7b4583.gif)

A Boolean variable is a variable that can store a Boolean value. It is a variable that can only hold the value "true" or "false". Boolean variables are often used to represent conditions, such as whether a condition is true or false.

## 4. BOOLEAN FUNCTIONS

![JojiFilthyFrankGIF](https://user-images.githubusercontent.com/91504420/219794233-5c49a45a-ce0d-419b-8034-3cfae1d849b3.gif)

A Boolean function is a function that takes one or more Boolean values as input and produces a single Boolean value as output. Boolean functions are used to perform logical operations on Boolean values. Some common Boolean functions include AND, OR, NOT, XOR, and NAND. These functions are used to combine, negate, or compare Boolean values to determine whether a given condition is true or false.

![image](https://user-images.githubusercontent.com/91504420/219794330-e9b0925f-abad-4d8d-afee-ed1c2ae76d47.png)

## 5. BOOLEAN ALGEBRA

![AWholeNewWorldAladdinGIF](https://user-images.githubusercontent.com/91504420/219796635-97f6dde2-a09a-46cb-bcc5-d2313a11100f.gif)

oolean algebra is a branch of mathematics that deals with logical operations on true or false values, which are represented as 1 and 0, respectively. It is an algebraic system that is used to represent logical propositions and analyze their properties.

Here's a summary of some of the key concepts in Boolean algebra:

Boolean operators: The three primary Boolean operators are AND, OR, and NOT. These operators are used to perform logical operations on Boolean values.

Boolean expressions: A Boolean expression is a combination of Boolean variables and operators that evaluates to a Boolean value. For example, the expression "A AND B" is a Boolean expression that is true only if both A and B are true.

Truth tables: A truth table is a table that lists all possible combinations of inputs for a Boolean expression and the resulting output. Truth tables are used to analyze and evaluate Boolean expressions.

Laws of Boolean algebra: There are several laws of Boolean algebra, including the commutative, associative, distributive, and identity laws. These laws provide a set of rules that can be used to simplify and manipulate Boolean expressions.

Boolean functions: A Boolean function is a function that takes one or more Boolean values as input and produces a single Boolean value as output. Boolean functions are used to perform logical operations on Boolean values.

Boolean algebra is an important concept in computer science and digital electronics, and is used extensively in the design and analysis of digital circuits and systems.

| Law                  | Equation                              |
|----------------------|---------------------------------------|
| Commutative Law      | A AND B = B AND A <br> A OR B = B OR A |
| Associative Law      | (A AND B) AND C = A AND (B AND C) <br> (A OR B) OR C = A OR (B OR C) |
| Distributive Law     | A AND (B OR C) = (A AND B) OR (A AND C) <br> A OR (B AND C) = (A OR B) AND (A OR C) |
| Identity Law         | A AND 1 = A <br> A OR 0 = A |
| Negation Law         | A AND NOT A = 0 <br> A OR NOT A = 1 |
| Double Negation Law  | NOT (NOT A) = A |
| De Morgan's Law      | NOT (A AND B) = (NOT A) OR (NOT B) <br> NOT (A OR B) = (NOT A) AND (NOT B) |
| Absorption Law       | A OR (A AND B) = A <br> A AND (A OR B) = A |

## 6. DISJUNCTIVE NORMAL FORM

![ICanDoItJonTafferGIF](https://user-images.githubusercontent.com/91504420/219798501-6e9022af-4cdf-4ba0-a004-d60dd3830b9f.gif)

DNF stands for Disjunctive Normal Form, which is a way to represent a Boolean function as the logical OR of multiple AND terms. In other words, it is a way to express a Boolean function as a sum of products.

To convert a Boolean expression to DNF, one needs to:

Expand the expression into a sum of minterms, which are the product terms that evaluate to 1 for the given combination of input variables.
Combine the minterms with logical OR operator to obtain the DNF.
DNF is useful in digital circuit design because it provides a way to represent a Boolean function in a form that is amenable to logic gate implementation. Additionally, DNF can be used to find the minimal sum-of-products representation of a Boolean function, which is the expression that uses the smallest number of terms and literals to represent the function.

## 7. NAND

![IveGotThePowerJimCarreyGIF](https://user-images.githubusercontent.com/91504420/219799684-e8cd5755-6363-4b97-b4b1-b1a64b1e04be.gif)

NAND (not-and) is a logical operation in Boolean algebra that returns a FALSE output only when both of its inputs are TRUE, and returns a TRUE output for all other input combinations. In other words, it is the negation of the logical AND operation.

NAND is a universal gate, which means that any Boolean function can be expressed using NAND gates only. This is because NAND can be used to implement all the other basic Boolean operations such as NOT, AND, OR, and XOR. In fact, it is possible to construct an entire digital circuit using only NAND gates.

NAND gates are widely used in digital circuit design because they are relatively simple to implement and provide a compact and efficient way to represent Boolean functions. Additionally, NAND gates have the property of logical equivalence, which means that any Boolean expression can be transformed into an equivalent expression using only NAND gates, without changing the logical function that it represents.

![image](https://user-images.githubusercontent.com/91504420/219799749-80dbab6e-b972-42f2-a47a-0552ff7fc808.png)

## 8. LOGIC GATES

![FeelMeThinkAboutItGIF](https://user-images.githubusercontent.com/91504420/219811381-fdb32fc6-be9c-48c9-a76c-ebeb38e129fd.gif)

Logic gates are electronic circuits that perform logical operations on one or more binary inputs to produce a single binary output. They are the building blocks of digital circuits and computers, and are used to implement Boolean algebraic functions in electronic devices.

There are several types of logic gates, including:

+ NOT gate: also known as an inverter, it produces an output that is the opposite of its input.

+ AND gate: it produces an output of 1 only when all of its inputs are 1.

+ OR gate: it produces an output of 1 when any of its inputs are 1.

+ XOR gate: it produces an output of 1 when exactly one of its inputs is 1.

+ NAND gate: it produces an output of 0 only when all of its inputs are 1, otherwise it produces an output of 1.

+ NOR gate: it produces an output of 0 when any of its inputs are 1, otherwise it produces an output of 1.

Logic gates are used to build more complex circuits such as adders, multipliers, memory units, and microprocessors. The design of digital circuits using logic gates is an important part of computer engineering and is used in various fields, including robotics, communications, and control systems.

## 9. HARDWARE DESCRIPTION LANGUAGE

![GandalfICanHelpGIF](https://user-images.githubusercontent.com/91504420/219812841-d3f23138-65a7-4851-90c8-aa509adb1536.gif)

In computer science, HDL stands for Hardware Description Language. It is a specialized programming language used to design and describe digital circuits and systems at the register-transfer level (RTL). HDLs are used to specify the behavior of digital circuits and can be used to simulate, verify, and synthesize digital circuits. HDLs are used to create designs for logic gates and other digital components, and can be used to describe the structure and functionality of entire digital systems. Some popular HDLs include Verilog and VHDL.

![image](https://user-images.githubusercontent.com/91504420/219812413-37cdbe74-b3f3-41cb-9204-893dc5101d7f.png)


<!-- Contact -->
# :handshake: Contact

<p align="left">
<a href="https://twitter.com/liron_mizrahi" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="liron_mizrahi" height="50" width="60" /></a>
<a href="https://instagram.com/liron.mizrhai1234" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="liron.mizrhai1234" height="50" width="60" /></a>
<a href="https://www.linkedin.com/in/%D7%9C%D7%99%D7%A8%D7%95%D7%9F-%D7%9E%D7%96%D7%A8%D7%97%D7%99-1050b421a/">
  <img align="left" alt="liron LinkedIN" height="50" width="60" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/linkedin.svg" />
</a>
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Acknowledgements -->
# :gem: Acknowledgements

Links to information that helped me during construction and learning:
 - [python3](https://docs.python.org/3/)
 - [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- About the authors -->
## :telephone: About the authors

 - Liron Mizarhi - Navy soldier and programmer

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Project status -->
## :octocat: Project Status

### Project is: In Prograss!

<p align="right">(<a href="#readme-top">back to top</a>)</p>
