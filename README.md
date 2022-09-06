# Java-Calculator

<p align =left>
  <a href="https://github.com/JustABeginning/Java-Calculator#JAB"><img src="https://img.shields.io/badge/language-Java-brightgreen" alt="Language Used"></a>
  <a href="https://github.com/JustABeginning/Java-Calculator#JAB"><img src="https://img.shields.io/github/last-commit/JustABeginning/Java-Calculator" alt="GitHub last commit"></a>
  <a href="https://twitter.com/UnusualCoderJAB/status/1563506476249133060"><img src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2FUnusualCoderJAB"></a>
</p>

A Terminal based Calculator built with Java

## Features

+ Capability to evaluate arithmetic expressions.
+ Uses the concept of **Polish Strings** for evaluation.
+ Generates appropriate *postfix* expressions.

## Requirement

+ Java installed and set in `PATH`.

## Usage

### From Source

1. Compile the `Calculator.java` file

    ```console
    foo@bar:~$ javac Calculator.java
    ```

1. Run the Calculator

    ```console
    foo@bar:~$ java Calculator
    ```

<h3 align=center>Preview</h3>

[![Usage Preview](Images/Usage.gif)](https://github.com/JustABeginning/Java-Calculator#JAB)

### Via JAR

+ Requires Java (>=8)

    ```console
    foo@bar:~$ java -jar Calculator.jar
    ```

## Commands

|Syntax|Meaning|
|:---:|:---:|
|a `^` b|a<sup>b</sup>|
|b <code>&#124;</code> a|a<sup>(1/b)</sup>|
|`n!`|Factorial of `n`|
|`log()`|log<sub>10</sub>|
|`ln()`|log<sub>e</sub>|
|`rad()`|&deg; to *radian*|
|`deg()`|*radian* to &deg;|
|`sini()`|sin<sup>-1</sup> (in &deg;)|
|`cosi()`|cos<sup>-1</sup> (in &deg;)|
|`tani()`|tan<sup>-1</sup> (in &deg;)|
|`sinir()`|sin<sup>-1</sup> (in *radian*)|
|`cosir()`|cos<sup>-1</sup> (in *radian*)|
|`tanir()`|tan<sup>-1</sup> (in *radian*)|

## 🧋 Contribution

Pull requests, issue reports and suggestions are welcome 😊 !
