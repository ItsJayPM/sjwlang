# SJW - A Programming Revolution - Info and Documentation

SJW is a programming language that takes social justice to a new level. All commands in SJW not only allow you to preform various tasks, but along the way, help you right the wrongs of the internet.  
  
In the SJW language, you use the "SJW Pointer". The pointer represents an SJW, and interprets your code going down, preforming SJW-ian tasks along the way. It starts at the top of your code, however, can travel backwards via the "storm" command, allowing you to storm into earlier lines of code.
  
The SJW language relies on a "Datatape" and a Work Number. The Datatape spans over 0 - 39.
# Commands
## DEMAND
DEMAND is your basic variable manipulation command, and likely what you will be using for most of your code. Arithmatic operations can only be done to the work number, however conditionals can only be done with the datatape, so it is important to be careful when using these. To do manipulations to the data table, you will use syntax similar to this:
> DEMAND DATATAPE (NUMBER) (OPERATION) {VALUE}

Operations preformable by the demand datatape command include
- BE - Stores the provided value in the datatape.
- READS - Stores the provided string in the datatape.
- STEAL - Takes the work number's value. DOESN'T REQUIRE VALUE PARAMETER.
- HAS OPINION - Replaces your value with a random number, either 0 or 1. DOESN'T REQUIRE VALUE PARAMETER.

The syntax for the work number manipulation looks like this:
> DEMAND WORKVALUE (OPERATION) (DATATAPE INDEX VALUE)

- BE - Copies the provided datatape cell's value.
- ADD - Adds the provided datatape cell's value to it's current value.
- REMOVE - Subtracts the current value with the provided datatape cell's value.

## CHECK
CHECK is your one and only command for checking any conditional. It's syntax looks like this:
> CHECK (DATATAPE INDEX 1) (COMPARISON) (DATATAPE INDEX 2)

The two values can be compared with either "IS" or "ISNT". If it returns false, the next command will be skipped. If the previous command was the STUTTER command, then the STUTTER command's value will be how many commands are skipped upon returning false.

## STUTTER
STUTTER causes the next command to be repeated. The only exceptions to this are any flow control or input commands. Syntax is this:
> STUTTER (VALUE)

## STORM
The storm command has you storm to any line you wish. The syntax is this:
> STORM (LINE NUMBER)

## YELL & SHOUT
YELL & SHOUT have near identical functionality. both print the provided DATATAPE Value to the screen, however SHOUT prints it on a newline. Below is the syntax for YELL, however SHOUT has the exact same syntax:
> YELL (DATATAPE INDEX VALUE)

## TRIGGER
TRIGGER prompts the user for input. Upon getting the input, it will store it in the provided cell value. This is the syntax:
> TRIGGER (DATATAPE INDEX VALUE)

## END
Ends the application. Simple as that.

# Example Programs
Here is a simple truth machine program done in SJW.
> TRIGGER 1  
> DEMAND DATATAPE 2 BE 1  
> STUTTER 2  
> CHECK 1 IS 3  
> YELL 3  
> END  
> YELL 2  
> STORM 7  

Here is a simple coin flip program in SJW.
> DEMAND DATATAPE 2 READS HEADS  
> DEMAND DATATAPE 3 READS TAILS  
> DEMAND DATATAPE 0 HAS OPINION  
> STUTTER 2  
> CHECK 0 IS 1  
> SCREAM 2  
> END  
> SCREAM 3  
> END  

# Use
To use this language, use [this link](https://poleymagik.github.io/sjwlang/).
