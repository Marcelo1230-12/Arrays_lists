# Arrays_lists
Arrays list and how to use it, also know that there is two types of Arrays.


+++++++Arrays in C ++++++++



Arrays List is used to store multiple variables in a single variable , this is used to don't write the variable over and
over again , to createa a Array list we need first create an array, define the data type (like int) and specify the name of
the array followed by square brackets [].
EX
int nombres[];
now to insert the values inside the Array we need to put these variables in braklets{}
to acces the variable in the array list we need to select a Index
EX:
int number[]:{1,2,3,45,55}
number[0]=== the number is "1"

=====Multidimentional arrays =====



is a Arrays list that have more than one dimentional meaning having more of more directions like 2D or 3D arrays list
this can be showing when we create a array list and add more mroe
EX/
 type arrName[size1][size2]....[sizeN];

 int numbers2D[4][4];

      int arr[3][4] = {{0, 1, 2, 3}, {4, 5, 6, 7}, {8, 9, 10, 11}};
   
   for (int i=0;i<3;i++)
   
   {
   
       for (int j=0;j<4;j++)

       
       {
           printf("arr %d,%d,%d ",i,j,arr[i][j]);
           
       }
       printf("\n");
   }


   
this is the form to print dimentionals Arrays 2D and for 3D increase one loop
2D is compose by the rows and colums
3D is compose by 2D arrays  having one more colum and rows

