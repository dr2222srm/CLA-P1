# CLA-P1
Snow Howler is the librarian at the central library of the city of HuskyLand. He must handle requests which come in the following forms:

1 x y : Insert a book with y pages at the end of the xth shelf.
2 x y : Print the number of pages in the yth book on the xth shelf.
3 x : Print the number of books on the xth shelf.

Snow Howler has got an assistant, Oshie, provided by the Department of Education. Although inexperienced, Oshie can handle all of the queries of types 2 and 3.

Help Snow Howler deal with all the queries of type 1.

Oshie has used two arrays:

Input Format :
The first line contains an integer total_number_of_shelves, the number of shelves in the library.
The second line contains an integer total_number_of_queries, the number of requests.

Constraints :
1<= total_number_of_shelves <= 10^5
1<= total_number_of_queries <= 10^5
For each query of the second type, it is guaranteed that a book is present on the xth shelf at yth index.
0 <= x < total_number_of_shelves
Both the shelves and the books are numbered starting from 0.
Maximum number of books per shelf <= 1100

Output Format :
Write the logic for the requests of type 1. The logic for requests of types 2 and 3 are provided. 
