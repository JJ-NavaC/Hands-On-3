### Made by: **Nava Cuellar José De Jesús**
----------------


# BNF Rule for Virtual Machine 

```BNF
<stmt> := <compstmt>|<expr>';'|
         if(<condexpr>)<stmt>|
         if(<condexpr>)<stmt>else<stmt>|
         while(<condexpr>)<stmt>|
         do<stmt>while(condexpr);|
         for(<exprseq>;<condexpr>;<exprseq>)<stmt>|
         switch(val)<casestmts>|;

<type> := int|char|unsigned|unsigned char|
          float|short|long|unsigned short|
          unsigned long|double|<usertype>|
          struct <structname> {<decls>}|
          <type> *

<compsmt> := {<all_stmts>}|{<decls><all_stmts>}

<functiondef> := <type> <id>(<args>)<compsmt>|<type> <id>()<compsmt>

add := <int><int>
rest := <int><int>
mult := <int><int>
div := <int><int>
```
