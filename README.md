# Day10-with-java

Today's task is to Write a program that finds the largest element present in an array.

Example:
Array: [5, 10, 3, 8, 15]
Largest Element: 15

Here is the program:

class Day10 {
 public static void main(String[] args) {
 int[] arr={5,10,3,8,15};
 int max=arr[0];
 
 for(int i=0;i<arr.length;i++){
 if(arr[i]>max){
 max=arr[i];
 }
 }
 System.out.println(max);
 }
 }
