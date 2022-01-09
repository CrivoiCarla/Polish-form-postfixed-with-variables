# Polish-form-postfixed-with-variables
An instruction in the assembly language of the considered arithmetic processor is given as input.   
It is required to display at the standard output the evaluation of the instructions.   
Variables entered by let are used.  
# Example
### An input example can be x 1 let 2 x add y 3 let x y add mul.
The evaluation will be done as follows:  
• x and 1 are added to the stack, let is found, and it is now understood that x = 1 in the whole expression arithmetic; x and 1 are removed from the stack;  
• add 2 and 1 on the stack (because that x is = 1 from now on);  
• meet add, calculate the amount 3, remove 2 and 1 from the stack and keep only 3;  
• y and 3 are added on the stack, let is found, and it is now understood that y = 3 in the whole expression arithmetic; y and 3 are removed from the stack;  
• add 1 and 3 on the stack (x, respectively y);  
• the addition is performed, the result will be 4, 1 and 3 will be removed from the stack, 4 will be added;  
• a lot is identified, and on the stack we already had 3 (from the third dot in the current explanation) and 4, from the previous bullet, and the result is calculated, 12, then 3 and 4 are removed from the stack and 12 are added;  
• there are no more elements in a row, so the final result is 12.  
