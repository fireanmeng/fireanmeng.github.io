# IslandVM   
A cross platform virtual machine and like jvm.    
# Commands   
01 - GOTO : label - jump to some labels.    
02 - IFEQ : label - if stack top = stack top-1,jump to some labels.    
03 - PUSH : any - push value to stack.   
04 - VAR : name,value - add variables to variable list.    
05 - CALL : module - call another module.this module must in library list.     
06 - NCAL : module - call native module.return value will be push in stack.    
