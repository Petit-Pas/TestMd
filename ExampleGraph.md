<img src='https://g.gravizo.com/svg?
 digraph G {
   main -> parse -> execute;
   main -> init -> make_string;
   main -> cleanup;
   execute -> make_string;
   execute -> printf2;
   main -> printf;
   execute -> compare;
 }
'/>