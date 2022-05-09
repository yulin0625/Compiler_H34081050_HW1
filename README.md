# Compiler 2022 Programming Assignment I - Lexical Definition

## 作業介紹
Your assignment is to write a scanner for the μGo language with lex. This document gives the
lexical definition of the language, while the syntactic definition and code generation will follow in
subsequent assignments.
Your programming assignments are based around this division and later assignments will use the
parts of the system you have built in the earlier assignments. That is, in the first assignment you
will implement the scanner using lex, in the second assignment you will implement the syntactic
definition in yacc, and in the last assignment you will generate assembly code for the Java Virtual
Machine by augmenting your yacc parser.
This definition is subject to modification as the semester progresses. You should take care in
implementation that the codes you write are well-structured and able to be revised easily.

## 系統環境設定
```shell
$ sudo apt install flex bison git python3 python3-pip
```

### 安裝助教的judge程式
```python
pip3 install local-judge
```

### judge方式
typing judge in your terminal.
```shell
$ judge
```