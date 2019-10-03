
# Amazon Interview Questions
* [Coding Round Questions](#coding)
* [Technical Interview Questions](#tech)
   * [Data Structures and Algorithms](#dsalg)
   * [DBMS](#dbms)
   * [Operating System](#os)
   * [System Design](#design)
   * [Miscellaneous](#misc)
* [References](#ref)
____
<b name="coding">Coding round questions</b><br/>
- Given an array of distinct elements and a number x, find if there is a pair with product equal to x.
- Given a string ‘str’ of digits and an integer ‘n’, build the lowest possible number by removing ‘n’ digits from the string and not   changing the order of input digits.
- Given a number, find its corresponding Roman numeral.

- Part A: Given a string of parentheses, as such: "((()))", determine if the string is a valid ordering of parentheses.
  Valid string examples:
    - "()()()"
    - "((()))"
    - "(())()"
    - "((())())  
  Invalid string examples:
    - "())()"
    - ")))((("
    - "(())())"
  Return type: boolean
  Part B: Given a string of mixed brackets, as such: "([{}])", determine if the string is a valid ordering of parentheses.
    Valid string examples:
      - "{{}}[[]](())"
      - "({([])})"
      - "()[]{}"
    Invalid string examples:
      - "{{}}[{]}()"
      - "{[()()])}"
  Return type: boolean
  
----
<b name="tech">Technical Interview Questions</b>
<br/>
<i><u name="dsalg">Data Structures and Algorithms</u></i>

<br/><br/>
<i><u name="dbms">DBMS</u></i>



<br/>
<br/>
<i><u name="os">Operating System</u></i>

<br/>
<br/>
<i><u name="design">System Design</u></i>
1. Design a system that controls traffic lights with below assumptions:

  - A group of traffic lights has two components: main lights and pedestrian lights.
  - Main traffic lights has three colors: red, yellow and green. 
  - Pedestrian lights has two colors: red and green.
  - Pedestrian lights' colors are reversed from main lights: 
    - Main: red/yellow - pedestrian's: green 
    - Main: green - pedestrian: red
  - There is a button for pedestrian lights, if button is pushed in advance, pedestrian's lights change colors according to the main ones, if button isn't pushed, pedestrian's lights remain red.
  - A typical junction has 4 group of lights.
  - Additional question: design the system in a way that allows cars which start from one junction after a red light don't have to stop at the next one.

<br/>
<br/>
<i><u name="misc">Miscellaneous</u></i>
