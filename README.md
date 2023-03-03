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
