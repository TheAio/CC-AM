AM interprates instructions line by line, so every new line is a new instruction.
The instructions avaible are:
JMP X Y ZZZ - Jump to line ZZZZ if X is equal to Y
STR X Y - Store intager X at location Y
ADD X Y Z - Add value X and Y to location Z
SUB X Y Z - Remove value X from Y and store it at Z
MUL X Y Z - Multiply value X and Y to location Z
SET X Y - Set value x at location Y
EXE C - Execute command C (any length) in shell
ASK X S - Prompt the user with the string S (any length) and save any number input at X (otherwise store 0)
SAY S - Prompt the user with the string S (any length)
WRN S - Prompt the user with the string S (any length) and wait for the user to press enter
SLP X - sleep for value x seconds
CHK XXXX F - Make sure file F (any length) exists and if so jump to line XXXX
END - stop executing the script
