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
  - [10. BUSES](#10-buses)
  - [11. MULTIPLEXOR](#11-multiplexor)
  - [12. DEMULTIPLEXOR](#12-demultiplexor)
  - [13. PROJECT1](#13-project1)
  - [14. ALU](#14-alu)
  - [15. NUMERAL SYSTEM](#15-numeral-system)
  - [16. BINARY NUMBERS](#16-binary-numbers)
  - [17. BINARY ARITHMETIC](#17-binary-arithmetic)
  - [18. HACK ALU](#18-hack-alu)
  - [19. PROJECT2](#19-project2)
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

![image](https://user-images.githubusercontent.com/91504420/219813215-ce5d2b40-bccb-48ae-aa90-69929fb95a86.png)

![image](https://user-images.githubusercontent.com/91504420/219814345-3e1ca794-12e4-43fc-94b2-0bf2b0fe852c.png)

![image](https://user-images.githubusercontent.com/91504420/219814949-ca088a4d-e871-4faf-a1d0-fd5e2b85938d.png)

![image](https://user-images.githubusercontent.com/91504420/219815457-8b8f06a2-5a14-476f-b430-b4407d14308d.png)

## 10. BUSES

![LittleBitOfThisLittleBitOfThatMarissaRachelGIF](https://user-images.githubusercontent.com/91504420/219816902-7a6d3474-934f-4a6e-8a91-c4b1f65d4996.gif)

In computer architecture and digital electronics, a bus of bits refers to a collection of wires or conductors that carry multiple bits of data in parallel. Buses of bits are used to transfer data and signals between different components or devices within a computer or electronic system. The size of a bus of bits, commonly referred to as its width, is measured in bits and determines the maximum amount of data that can be transferred in a single clock cycle.

Buses of bits can be classified based on their purpose, such as data buses, address buses, control buses, and expansion buses. They are commonly used in microprocessors, memory systems, and other digital circuits where high-speed data transfer is required. Buses of bits are an essential component of digital systems and play a critical role in determining the performance and capabilities of the system.

![image](https://user-images.githubusercontent.com/91504420/219816955-c952856f-ee00-493f-9b0c-6e763fffbd61.png)

![image](https://user-images.githubusercontent.com/91504420/219817195-e111a2c2-0144-4445-b8a9-07ff2c59da85.png)

## 11. MULTIPLEXOR

![DependsOnTheMoodDeanSchneiderGIF](https://user-images.githubusercontent.com/91504420/219818930-7e43b405-62e7-4299-a615-258f132ab158.gif)

In digital electronics and computer architecture, a multiplexer (also known as a MUX) is a device that selects one of several input signals and forwards it to a single output line. A multiplexer operates by using a set of control inputs to determine which of the input signals should be routed to the output.

Multiplexers are commonly used in digital circuits to reduce the number of wires required to transmit data, as well as to select between different sources of data or signals. They are often used in combination with demultiplexers to transmit and receive data over shared communication lines.

Multiplexers are available in a range of sizes, typically based on the number of input signals that they can handle. Common examples include 2-to-1, 4-to-1, 8-to-1, and 16-to-1 multiplexers. Multiplexers are widely used in digital design and play a critical role in many modern electronic systems.

![image](https://user-images.githubusercontent.com/91504420/219818879-e6bfd432-e82a-4eef-933f-a45e3236a10d.png)

![image](https://user-images.githubusercontent.com/91504420/219819237-59fbbe7e-7c31-4fa1-8415-effaa9602ac3.png)

## 12. DEMULTIPLEXOR

![ThisIsSoSimilarYetDifferentRachelSmithGIF](https://user-images.githubusercontent.com/91504420/219819407-1d301f42-95ce-4bf5-bb35-75b4a9eccaa0.gif)

In digital electronics and computer architecture, a demultiplexer (also known as a DEMUX) is a device that takes a single input signal and routes it to one of several output lines based on a set of control inputs. A demultiplexer is essentially the reverse of a multiplexer, which takes several input signals and selects one of them to be forwarded to a single output line.

A demultiplexer is commonly used to expand the capacity of a shared communication line, allowing multiple data streams to be transmitted and received over a single channel. Demultiplexers can also be used to route signals to different processing units or to control the flow of data within a larger system.

Like multiplexers, demultiplexers are available in a range of sizes based on the number of output lines they can handle, such as 1-to-2, 1-to-4, and 1-to-8 demultiplexers. Demultiplexers play a critical role in digital design and are widely used in many modern electronic systems.

![image](https://user-images.githubusercontent.com/91504420/219819424-56086abd-990d-4f96-a3f1-ba1aba541c62.png)

![image](https://user-images.githubusercontent.com/91504420/219819651-6055ac67-855e-4be4-9962-2048a1cebe20.png)

## 13. PROJECT1

### not logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Not.hdl

/**
 * Not gate:
 * out = not in
 */
CHIP Not {
    IN in;
    OUT out;

    PARTS:
    Nand(a=in, b=in, out=out);
}
```
### output file not gate:

![image](https://user-images.githubusercontent.com/91504420/219874107-65376354-24e1-4467-8976-53c55dc371b6.png)

### compare file not gate:

![image](https://user-images.githubusercontent.com/91504420/219874153-4acbd951-f39c-4cf8-afef-497ced0f7ad7.png)

### not gate simulation:

![image](https://user-images.githubusercontent.com/91504420/221359570-3d4ea240-595b-47d9-b5b0-a741d6fe4536.png)

### or logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Or.hdl

 /**
 * Or gate:
 * out = 1 if (a == 1 or b == 1)
 *       0 otherwise
 */

CHIP Or {
    IN a, b;
    OUT out;

    PARTS:
	Not(in=a, out=notA);
	Not(in=b, out=notB);
	Nand(a=notA, b=notB, out=out);
}
```
### output file or gate:

![image](https://user-images.githubusercontent.com/91504420/219874642-0db5421a-917d-4e9d-bace-57acf4807b68.png)


### compare file or gate:

![image](https://user-images.githubusercontent.com/91504420/219874663-37949581-6ff1-423e-99fb-0a113dfd019c.png)

### or gate simulation:

![image](https://user-images.githubusercontent.com/91504420/221359454-489cee0d-3fdc-4dd6-ad30-5f6bf2c43cb4.png)

### and logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/And.hdl

/**
 * And gate: 
 * out = 1 if (a == 1 and b == 1)
 *       0 otherwise
 */

CHIP And {
    IN a, b;
    OUT out;

    PARTS:
	Nand(a=a, b=b, out=nandOutput);
	Not(in=nandOutput, out=out);
}
```
### output file and gate:
![image](https://user-images.githubusercontent.com/91504420/219875022-8906f2f6-b168-43cf-832e-dce1d6c8f97c.png)


### compare file and gate:

![image](https://user-images.githubusercontent.com/91504420/219875032-3051ae3e-fc3c-46d2-bdba-4bce5f3fbf8b.png)

### and gate simulation:

![image](https://user-images.githubusercontent.com/91504420/221359276-d9e2e41a-90c5-4597-bbae-53793455239c.png)


### xor logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Xor.hdl

/**
 * Exclusive-or gate:
 * out = not (a == b)
 */

CHIP Xor {
    IN a, b;
    OUT out;

    PARTS:
    Or(a=a, b=b, out=c1);
    Nand(a=a, b=b, out=c2);
    And(a=c1, b=c2, out=out);
}
```
### output file xor gate:

![image](https://user-images.githubusercontent.com/91504420/221358965-659583d4-964b-40d2-bde3-3df6f7626a6e.png)


### compare file xor gate:

![image](https://user-images.githubusercontent.com/91504420/221358955-8bb0dd5d-5dee-47ff-95a8-f7435b7942ae.png)

### xor gate simulation:

![image](https://user-images.githubusercontent.com/91504420/221359035-dae063c8-61d6-4415-986d-412d98302612.png)

### mux logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Mux.hdl

CHIP Mux {
    IN a, b, sel;
    OUT out;

    PARTS:
    Not(in=sel, out=nsel);
    And(a=sel, b=b, out=c1);
    And(a=nsel, b=a, out=c2);
    Or(a=c1, b=c2, out=out);
}
```
### output file mux gate:

![image](https://user-images.githubusercontent.com/91504420/221359966-83d84e82-29b1-48eb-a544-b2143d9bf75b.png)


### compare file mux gate:

![image](https://user-images.githubusercontent.com/91504420/221359985-7187eb7a-10cb-4c67-bc9c-71163fafc368.png)

### mux gate simulation:

![image](https://user-images.githubusercontent.com/91504420/221359874-a47e1017-1769-47f7-be9b-ce0b74020a41.png)

### dmux logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/DMux.hdl

/**
 * Dmultiplexor.  
 * {a,b} = {in,0} if sel == 0
 *         {0,in} if sel == 1
 */

CHIP DMux {
    IN in, sel;
    OUT a, b;

    PARTS:
    Not(in=sel, out=nsel);
    And(a=nsel, b=in, out=a);
    And(a=sel, b=in, out=b);
}
```
### output file dmux gate:

![image](https://user-images.githubusercontent.com/91504420/221361245-42dd395f-1fc1-4b1b-bfda-56d063ebc25d.png)

### compare file dmux gate:

![image](https://user-images.githubusercontent.com/91504420/221361255-a55a1334-668f-42d5-bfa0-c138d498a7ed.png)

### dmux gate simulation:

![image](https://user-images.githubusercontent.com/91504420/221361137-00d926db-2d3b-424d-b22e-4859310a7538.png)

### not16 logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Not16.hdl

/**
 * 16-bit Not gate: for i = 0..15: out[i] = Not in[i]
 */

CHIP Not16 {
    IN in[16];
    OUT out[16];

    PARTS:
    Nand(a=in[0], b=in[0], out=out[0]);
    Nand(a=in[1], b=in[1], out=out[1]);
    Nand(a=in[2], b=in[2], out=out[2]);
    Nand(a=in[3], b=in[3], out=out[3]);
    Nand(a=in[4], b=in[4], out=out[4]);
    Nand(a=in[5], b=in[5], out=out[5]);
    Nand(a=in[6], b=in[6], out=out[6]);
    Nand(a=in[7], b=in[7], out=out[7]);
    Nand(a=in[8], b=in[8], out=out[8]);
    Nand(a=in[9], b=in[9], out=out[9]);
    Nand(a=in[10], b=in[10], out=out[10]);
    Nand(a=in[11], b=in[11], out=out[11]);
    Nand(a=in[12], b=in[12], out=out[12]);
    Nand(a=in[13], b=in[13], out=out[13]);
    Nand(a=in[14], b=in[14], out=out[14]);
    Nand(a=in[15], b=in[15], out=out[15]);
}
```
### output file not16 gate:

![image](https://user-images.githubusercontent.com/91504420/221362075-0ce2983f-e802-4d1d-8cd5-e547c2b5e089.png)

### compare file not16 gate:

![image](https://user-images.githubusercontent.com/91504420/221362090-aac4e65b-5e74-413f-a849-5626249a34c1.png)

### not16 gate simulation:

![image](https://user-images.githubusercontent.com/91504420/221362670-d7d1c385-0f6b-44ff-9808-18746a0c299c.png)

### and16 logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/And16.hdl

/**
 * 16-bit-wise And gate: for i = 0..15: out[i] = a[i] And b[i]
 */

CHIP And16 {
    IN a[16], b[16];
    OUT out[16];

    PARTS:
    And(a=a[0], b=b[0], out=out[0]);
    And(a=a[1], b=b[1], out=out[1]);
    And(a=a[2], b=b[2], out=out[2]);
    And(a=a[3], b=b[3], out=out[3]);
    And(a=a[4], b=b[4], out=out[4]);
    And(a=a[5], b=b[5], out=out[5]);
    And(a=a[6], b=b[6], out=out[6]);
    And(a=a[7], b=b[7], out=out[7]);
    And(a=a[8], b=b[8], out=out[8]);
    And(a=a[9], b=b[9], out=out[9]);
    And(a=a[10], b=b[10], out=out[10]);
    And(a=a[11], b=b[11], out=out[11]);
    And(a=a[12], b=b[12], out=out[12]);
    And(a=a[13], b=b[13], out=out[13]);
    And(a=a[14], b=b[14], out=out[14]);
    And(a=a[15], b=b[15], out=out[15]);
}
```
### output file and16 gate:

![image](https://user-images.githubusercontent.com/91504420/221363510-a2ac3b7b-cf42-404d-a9dd-b1266c6e131c.png)

### compare file and16 gate:

![image](https://user-images.githubusercontent.com/91504420/221363525-d565bc8c-7237-4cb5-b1a1-b3397d49dadf.png)

### and16 gate simulation:

![image](https://user-images.githubusercontent.com/91504420/221364210-6daaf116-24ba-430a-a93f-6d5b5c35d8b3.png)

### mux16 logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Mux16.hdl

/**
 * 16-bit multiplexor. If sel == 1 then out = b else out = a.
 */

CHIP Mux16 {
    IN a[16], b[16], sel;
    OUT out[16];

    PARTS:
    Mux(a=a[0], b=b[0], sel=sel, out=out[0]);
    Mux(a=a[1], b=b[1], sel=sel, out=out[1]);
    Mux(a=a[2], b=b[2], sel=sel, out=out[2]);
    Mux(a=a[3], b=b[3], sel=sel, out=out[3]);
    Mux(a=a[4], b=b[4], sel=sel, out=out[4]);
    Mux(a=a[5], b=b[5], sel=sel, out=out[5]);
    Mux(a=a[6], b=b[6], sel=sel, out=out[6]);
    Mux(a=a[7], b=b[7], sel=sel, out=out[7]);
    Mux(a=a[8], b=b[8], sel=sel, out=out[8]);
    Mux(a=a[9], b=b[9], sel=sel, out=out[9]);
    Mux(a=a[10], b=b[10], sel=sel, out=out[10]);
    Mux(a=a[11], b=b[11], sel=sel, out=out[11]);
    Mux(a=a[12], b=b[12], sel=sel, out=out[12]);
    Mux(a=a[13], b=b[13], sel=sel, out=out[13]);
    Mux(a=a[14], b=b[14], sel=sel, out=out[14]);
    Mux(a=a[15], b=b[15], sel=sel, out=out[15]);
}
```
### output file mux16 gate:

![image](https://user-images.githubusercontent.com/91504420/221364502-33a569db-3b17-44c3-b88e-c1f02fb08867.png)

### compare file mux16 gate:

![image](https://user-images.githubusercontent.com/91504420/221364515-ffb7d18d-e11e-46b5-a1b6-fd8f1a4d5622.png)

### mux16 gate simulation:

![image](https://user-images.githubusercontent.com/91504420/221367258-b8a0103b-7e5e-4a46-bba7-3058c72dc8e0.png)

### or16 logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Or16.hdl

/**
 * 16-bit bitwise Or:
 * for i = 0..15 out[i] = (a[i] or b[i])
 */

CHIP Or16 {
    IN a[16], b[16];
    OUT out[16];

    PARTS:
    Or(a=a[0], b=b[0], out=out[0]);
	Or(a=a[1], b=b[1], out=out[1]);
	Or(a=a[2], b=b[2], out=out[2]);
	Or(a=a[3], b=b[3], out=out[3]);
	Or(a=a[4], b=b[4], out=out[4]);
	Or(a=a[5], b=b[5], out=out[5]);
	Or(a=a[6], b=b[6], out=out[6]);
	Or(a=a[7], b=b[7], out=out[7]);
	Or(a=a[8], b=b[8], out=out[8]);
	Or(a=a[9], b=b[9], out=out[9]);
	Or(a=a[10], b=b[10], out=out[10]);
	Or(a=a[11], b=b[11], out=out[11]);
	Or(a=a[12], b=b[12], out=out[12]);
	Or(a=a[13], b=b[13], out=out[13]);
	Or(a=a[14], b=b[14], out=out[14]);
	Or(a=a[15], b=b[15], out=out[15]);
}
```
### output file or16 gate:

![image](https://user-images.githubusercontent.com/91504420/222781812-a52a8cb8-4b71-4b11-8e1a-87987d915488.png)

### compare file or16 gate:

![image](https://user-images.githubusercontent.com/91504420/222781897-8176e7e6-0aa8-41c8-8ae1-a01800841b11.png)

### or16 gate simulation:

![image](https://user-images.githubusercontent.com/91504420/222782543-ea1a5ccf-760b-499e-8d95-0d1c6b997d9f.png)

### or8Way logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Or8Way.hdl

/**
 * 8-way Or: 
 * out = (in[0] or in[1] or ... or in[7])
 */

CHIP Or8Way {
    IN in[8];
    OUT out;

    PARTS:
    Or(a=in[0], b=in[1], out=out01);
	Or(a=in[2], b=in[3], out=out23);
	Or(a=in[4], b=in[5], out=out45);
	Or(a=in[6], b=in[7], out=out67);
	Or(a=out01, b=out23, out=out0123);
	Or(a=out45, b=out67, out=out4567);
	Or(a=out0123, b=out4567, out=out);
}
```
### output file or8Way gate:

![image](https://user-images.githubusercontent.com/91504420/222664243-2bf757c2-225d-4f71-9fd9-103fef20b76b.png)

### compare file or8Way gate:

![image](https://user-images.githubusercontent.com/91504420/222664471-86fbab72-d133-40df-aa36-381a2ffc9951.png)

### or8Way gate simulation:

![image](https://user-images.githubusercontent.com/91504420/222665000-b35e72d7-086e-4bc1-b7a6-740967d8aaae.png)

### DMux4Way logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/DMux4Way.hdl

/**
 * 4-way demultiplexor:
 * {a, b, c, d} = {in, 0, 0, 0} if sel == 00
 *                {0, in, 0, 0} if sel == 01
 *                {0, 0, in, 0} if sel == 10
 *                {0, 0, 0, in} if sel == 11
 */

CHIP DMux4Way {
    IN in, sel[2];
    OUT a, b, c, d;

    PARTS:
    Not(in=sel[0], out=notsel0);
    Not(in=sel[1], out=notsel1);
    And(a=notsel0, b=notsel1, out=sela);
    And(a=sela, b=in, out=a);
    And(a=sel[0], b=notsel1, out=selb);
    And(a=selb, b=in, out=b);
    And(a=notsel0, b=sel[1], out=selc);
    And(a=selc, b=in, out=c);
    And(a=sel[0], b=sel[1], out=seld);
    And(a=seld, b=in, out=d);
}
```
### output file DMux4Way gate:

![image](https://user-images.githubusercontent.com/91504420/222669983-3ed3f593-ae52-48a3-89e2-fa9bf6f247d3.png)


### compare file DMux4Way gate:

![image](https://user-images.githubusercontent.com/91504420/222670063-c91905e0-dd71-49db-b634-928d8f483d86.png)

### DMux4Way gate simulation:

![image](https://user-images.githubusercontent.com/91504420/222669239-85f25d99-928e-4432-aca4-4cefcca02925.png)

### DMux8Way logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/DMux8Way.hdl

/**
 * 8-way demultiplexor:
 * {a, b, c, d, e, f, g, h} = {in, 0, 0, 0, 0, 0, 0, 0} if sel == 000
 *                            {0, in, 0, 0, 0, 0, 0, 0} if sel == 001
 *                            etc.
 *                            {0, 0, 0, 0, 0, 0, 0, in} if sel == 111
 */

CHIP DMux8Way {
    IN in, sel[3];
    OUT a, b, c, d, e, f, g, h;

    PARTS:
    Not(in=sel[0], out=notsel0);
    Not(in=sel[1], out=notsel1);
    Not(in=sel[2], out=notsel2);
    And(a=notsel0, b=notsel1, out=sela1);
    And(a=sela1, b=notsel2, out=sela);
    And(a=sela, b=in, out=a);
    And(a=sel[0], b=notsel1, out=selb1);
    And(a=selb1, b=notsel2, out=selb);
    And(a=selb, b=in, out=b);
    And(a=notsel0, b=sel[1], out=selc1);
    And(a=selc1, b=notsel2, out=selc);
    And(a=selc, b=in, out=c);
    And(a=sel[0], b=sel[1], out=seld1);
    And(a=seld1, b=notsel2, out=seld);
    And(a=seld, b=in, out=d);
    And(a=notsel0, b=notsel1, out=sele1);
    And(a=sele1, b=sel[2], out=sele);
    And(a=sele, b=in, out=e);
    And(a=sel[0], b=notsel1, out=self1);
    And(a=self1, b=sel[2], out=self);
    And(a=self, b=in, out=f);
    And(a=notsel0, b=sel[1], out=selg1);
    And(a=selg1, b=sel[2], out=selg);
    And(a=selg, b=in, out=g);
    And(a=sel[0], b=sel[1], out=selh1);
    And(a=selh1, b=sel[2], out=selh);
    And(a=selh, b=in, out=h);
}
```
### output file DMux8Way gate:

![image](https://user-images.githubusercontent.com/91504420/222682871-a1816c60-d8f6-47eb-b810-a3046167eff6.png)


### compare file DMux8Way gate:

![image](https://user-images.githubusercontent.com/91504420/222682970-46dd15ef-373f-4bdd-91d1-d04053a2f804.png)

### DMux8Way gate simulation:

![image](https://user-images.githubusercontent.com/91504420/222685950-ebce3a0f-e5c7-4139-a8ae-2ea780d97252.png)

### Mux4Way16 logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Mux4Way16.hdl

/**
 * 4-way 16-bit multiplexor:
 * out = a if sel == 00
 *       b if sel == 01
 *       c if sel == 10
 *       d if sel == 11
 */

CHIP Mux4Way16 {
    IN a[16], b[16], c[16], d[16], sel[2];
    OUT out[16];

    PARTS:
    Mux16(a=a, b=b, sel=sel[0], out=outab);
    Mux16(a=c, b=d, sel=sel[0], out=outcd);
    Mux16(a=outab, b=outcd, sel=sel[1], out=out);
}
```

### output file Mux4Way16 gate:

![image](https://user-images.githubusercontent.com/91504420/222688440-a72bf93b-fa98-4cad-bc04-b970d012560c.png)

### compare file Mux4Way16 gate:

![image](https://user-images.githubusercontent.com/91504420/222689010-b9a5315c-16fe-48ac-9fbf-26eec0fad19e.png)

### Mux4Way16 gate simulation:

![image](https://user-images.githubusercontent.com/91504420/222689584-8a9db23f-ccba-435e-b298-238c402a1965.png)

### Mux8Way16 logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/01/Mux4Way16.hdl

/**
 * 4-way 16-bit multiplexor:
 * out = a if sel == 00
 *       b if sel == 01
 *       c if sel == 10
 *       d if sel == 11
 */

CHIP Mux4Way16 {
    IN a[16], b[16], c[16], d[16], sel[2];
    OUT out[16];

    PARTS:
    Mux16(a=a, b=b, sel=sel[0], out=outab);
    Mux16(a=c, b=d, sel=sel[0], out=outcd);
    Mux16(a=outab, b=outcd, sel=sel[1], out=out);
}
```

### output file Mux8Way16 gate:

![image](https://user-images.githubusercontent.com/91504420/222692038-abdb9e6c-f659-4161-a1e0-dcb02b50b6bc.png)

### compare file Mux8Way16 gate:

![image](https://user-images.githubusercontent.com/91504420/222692111-3cb90396-42b2-46bb-9811-73b9e91d6fd3.png)

### Mux8Way16 gate simulation:

![image](https://user-images.githubusercontent.com/91504420/222692666-b7d4c997-7ce1-4f39-bb33-4d5af16b6c7a.png)

## 14. ALU

![RonBurgundyBigDealGIF](https://user-images.githubusercontent.com/91504420/222680020-03ed4ca5-719c-43ce-b5c3-3c5b822b109e.gif)

ALU stands for Arithmetic Logic Unit. It is a digital circuit that performs arithmetic and logic operations on binary numbers. The arithmetic operations include addition, subtraction, multiplication, and division. The logic operations include AND, OR, NOT, and XOR.

The ALU is an essential component of a microprocessor or CPU (Central Processing Unit), where it performs mathematical and logical operations to process instructions and data. It receives input from the processor's registers, performs the necessary operation, and stores the result in a register for later use.

The ALU's design varies depending on the architecture of the processor, but it typically consists of combinational logic circuits and a set of control circuits to manage the operations. ALUs are typically built with a variety of bit-widths, such as 8-bit, 16-bit, 32-bit, or 64-bit, depending on the processor's design.

Overall, the ALU is a critical component of any digital circuit that performs arithmetic and logic operations on binary numbers, making it an essential part of modern computing.

![image](https://user-images.githubusercontent.com/91504420/222679798-897fa3fb-f16b-4925-88f7-c10921eff527.png)


## 15. NUMERAL SYSTEM

![HaveFaithInTheSystemReginaldJuneGIF](https://user-images.githubusercontent.com/91504420/222785705-07ae0b9f-77f8-4e16-864a-bcaf3d2cf6d6.gif)

A numeral system, also known as a number system, is a mathematical notation for representing numbers using digits or symbols. The most commonly used numeral systems are the decimal system (base-10), binary system (base-2), octal system (base-8), and hexadecimal system (base-16).

In a numeral system, each digit represents a specific value, and the position of the digit determines its place value. For example, in the decimal system, the digit "3" represents three ones, while the digit "3" in the tens place represents three tens (or 30).

The binary system is used extensively in computing, where all data is represented in binary form. It uses only two digits (0 and 1) and is the foundation for digital electronics.

The octal system is commonly used in computer programming, particularly when working with Unix or Linux operating systems, while the hexadecimal system is frequently used in computer programming and digital electronics because it provides a convenient way to represent large binary numbers in a compact form.

Overall, numeral systems are essential to mathematics and computing, as they allow us to represent and manipulate numbers in a systematic and consistent way.

![image](https://user-images.githubusercontent.com/91504420/222683793-05df0eb4-010a-43d4-87a0-daaba967470b.png)

## 16. BINARY NUMBERS

![WeOnlyHaveTwoOnlyTwoGIF](https://user-images.githubusercontent.com/91504420/222825918-ab07621b-89dd-478e-af9f-da1c72cad073.gif)

Binary numbers are a base-2 number system that uses only two digits, 0 and 1, to represent all values. Each digit in a binary number represents a power of two, with the rightmost digit representing 2^0 (or 1), the second rightmost representing 2^1 (or 2), and so on. The number is formed by summing the values of the digits that are set to 1. Binary numbers are commonly used in computing and digital electronics because they can easily be represented as electronic signals, and digital logic can easily manipulate them. Converting between binary and decimal (base-10) numbers involves multiplying or adding the powers of 2 corresponding to the set 1 digits in the binary number.

![image](https://user-images.githubusercontent.com/91504420/222826103-7d109a6b-08df-4ee0-b2e5-8b56730266df.png)

## 17. BINARY ARITHMETIC

![HoodycatHoodycatsGIF](https://user-images.githubusercontent.com/91504420/222828266-23de023c-1d5e-4f3f-be49-b37ccabd4821.gif)

Binary arithmetic is a form of arithmetic that operates on binary numbers, which are numbers represented in the base-2 numeral system. In binary arithmetic, there are only two digits: 0 and 1. Binary arithmetic includes basic mathematical operations such as addition, subtraction, multiplication, and division.

In binary addition, the rules are similar to decimal addition, except that when the sum of two digits is 2 or greater, a carry-over occurs. For example, in binary addition, 1 + 1 = 10, where the 1 is carried over to the next digit. In binary subtraction, the rules are also similar to decimal subtraction, but borrowing may occur when the digit in the minuend is smaller than the corresponding digit in the subtrahend.

In binary multiplication, the process is similar to decimal multiplication, but the multiplication table is much simpler since there are only two digits. In binary division, the process is similar to decimal division, but the steps are more complex since there may be multiple digits involved in the dividend and divisor.

Binary arithmetic is used extensively in computer science and digital electronics since digital devices operate using binary signals. The principles of binary arithmetic are also important for understanding concepts such as binary code, digital circuits, and computer programming.

![image](https://user-images.githubusercontent.com/91504420/222828486-92fb81c0-0559-455f-a541-59057aefe144.png)

![image](https://user-images.githubusercontent.com/91504420/222828706-7f103445-173c-49cf-a05b-69357fb6b9bc.png)

![image](https://user-images.githubusercontent.com/91504420/222828987-57a7616d-c97a-4ff7-b2f5-ffc861c11b5d.png)

![image](https://user-images.githubusercontent.com/91504420/222829455-d3f67f5a-7d40-4ef3-8c96-c8c45a824715.png)

## 18. HACK ALU

![WowTheRockGIF](https://user-images.githubusercontent.com/91504420/222835464-b7ff6e8a-cd0f-4ab9-969a-0965498f26dc.gif)

Hack ALU (Arithmetic Logic Unit) is a component of the Hack computer, which is a simple computer architecture designed for educational purposes. The ALU is responsible for performing arithmetic and logical operations on binary data.

The Hack ALU is a 16-bit unit that supports several arithmetic operations, including addition, subtraction, and bitwise logical operations such as AND, OR, and NOT. It also supports some comparison operations such as equal, less than, and greater than.

The Hack ALU is built using basic logic gates such as AND, OR, and XOR gates, and uses a combination of these gates to perform the various operations. The output of the ALU is a 16-bit value that can be stored in a register or used as input to other components of the computer.

The Hack computer architecture was designed as a teaching tool to help students learn about computer organization and architecture. The design is simple and easy to understand, making it a good starting point for beginners. The Hack ALU is an important component of the computer and provides a basic understanding of how arithmetic and logical operations are performed in a computer system.

![image](https://user-images.githubusercontent.com/91504420/222835265-e79ec11a-b5f5-4569-b2a0-ba3ca7e090c1.png)

![image](https://user-images.githubusercontent.com/91504420/222835588-f52366dc-c1c7-44ff-afb5-6f1f9f4f41c5.png)

![image](https://user-images.githubusercontent.com/91504420/222836405-b2a21dfc-cb48-4c63-9b24-462c72563d8f.png)


## 19. PROJECT2

![ItsJustTooEasyMonétXChangeGIF](https://user-images.githubusercontent.com/91504420/222895932-b4bae7bd-5180-4c99-b95c-dd1f9a9e833d.gif)

## half adder 

A half adder is a digital circuit that adds two binary digits (bits) and produces a sum bit and a carry bit as output. It is called a "half" adder because it can only add two bits, whereas a full adder can add three bits. The half adder has two inputs, one for each bit being added, and two outputs, one for the sum and one for the carry. The sum output is the result of adding the two input bits together, while the carry output indicates whether there is a carry to the next place value in a multi-digit addition operation. The circuit for a half adder consists of an XOR gate and an AND gate.

![image](https://user-images.githubusercontent.com/91504420/222895953-9b0a3808-d0d9-4a34-95fe-d486397df7c3.png)

### halfAdder logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/02/HalfAdder.hdl

/**
 * Computes the sum of two bits.
 */

CHIP HalfAdder {
    IN a, b;    // 1-bit inputs
    OUT sum,    // Right bit of a + b 
        carry;  // Left bit of a + b

    PARTS:
    Xor(a=a, b=b, out=sum);
    And(a=a, b=b, out=carry);
}
```

### output file halfAdder gate:

![image](https://user-images.githubusercontent.com/91504420/222896101-e36347f5-a458-483d-9bbc-f539d4bc6cbe.png)

### compare file halfAdder gate:

![image](https://user-images.githubusercontent.com/91504420/222896112-cf606bc7-7f51-474c-b674-427571a4cbb7.png)

### halfAdder gate simulation:

![image](https://user-images.githubusercontent.com/91504420/222896208-0597d4ae-9329-40ee-add3-533c47326f66.png)

## full adder

![ImJustTellingTheTruthCalvinRodneyGIF](https://user-images.githubusercontent.com/91504420/222898117-c787d850-3670-4ca8-b6f2-3fd5b2e4641e.gif)

A full adder is a digital circuit that adds three binary digits (bits) and produces a sum bit and a carry bit as output. It is used to add multi-digit binary numbers by combining multiple full adders to create a ripple carry adder. The full adder has three inputs, one for each of the two bits being added and one for the carry-in from the previous place value, and two outputs, one for the sum and one for the carry-out to the next place value. The circuit for a full adder consists of two XOR gates, two AND gates, and an OR gate. The sum output is the result of adding the three input bits together, while the carry output indicates whether there is a carry to the next place value in a multi-digit addition operation.


### fullAdder logic gate solution:

```
// This file is part of www.nand2tetris.org
// and the book "The Elements of Computing Systems"
// by Nisan and Schocken, MIT Press.
// File name: projects/02/FullAdder.hdl

/**
 * Computes the sum of three bits.
 */

CHIP FullAdder {
    IN a, b, c;  // 1-bit inputs
    OUT sum,     // Right bit of a + b + c
        carry;   // Left bit of a + b + c

    PARTS:
    HalfAdder(a=a, b=b, sum=sumab, carry=carryab);
    HalfAdder(a=sumab, b=c, sum=sum, carry=carryabc);
    Or(a=carryab, b=carryabc, out=carry);
}
```

### output file fullAdder gate:

![image](https://user-images.githubusercontent.com/91504420/222897796-36ac4b83-42f3-445e-9291-3f1efd4de41b.png)

### compare file fullAdder gate:

![image](https://user-images.githubusercontent.com/91504420/222897807-a496f97b-8637-4e46-a3b7-7b25accb3f28.png)

### fullAdder gate simulation:

![image](https://user-images.githubusercontent.com/91504420/222897676-e644f6f3-e79b-4e18-b1bd-2149f3e71832.png)

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

### Project is: In Progress!

<p align="right">(<a href="#readme-top">back to top</a>)</p>
