# 11th

 <!DOCTYPEhtml>
 <html>
 <head>
 <title>ArraySortingDemo</title>
 <script>
 functionsortArray(){
 vararray=[5,2,8,1,9,3];//Examplearray
 //Sortthearrayinascendingorder
 array.sort(function(a,b){
 returna-b;
 });
 //Displaythesortedarray
 document.getElementById('result').innerHTML="SortedArray:"+
 array;
 }
 </script>
 </head>
 <body>
 <h1>ArraySortingDemo</h1>
 <buttononclick="sortArray()">SortArray</button>
 <br>
 <pid="result"></p>
 </body>
 </html>
