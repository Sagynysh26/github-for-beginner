int fib (int n) // int
{ // f0=0, f1=1
 int f0= 0, f1= 1, f3 i;
 for (i = 2; I <= n; i++)

{
  f3= f1 + f2;
  f1=f2;
  f2=f3;

}
// n*3 operations
// 4+n*3= big_o(n)
 return 0;
}
