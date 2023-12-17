FUNCTION check(ch=STRING,i=INTEGER) : BOOLEAN
BEGIN
   IF (ch=="" and (long(ch)=1 )) THEN 
      RETURN false;
 
ELSE_IF (ch[i]==ch[long(ch)-1]) THEN
        RETURN true;
    ELSE
        RETURN check(ch,i) 

   
   END_IF
END