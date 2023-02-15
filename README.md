# syperskiy
              Задание 1
 arr = []
imax = 0
jmax = 0
imin = 0
jmin = 0
x = int(input("размер = "))
for i in range(x):
arr.append([])
for j in range(x):
n = input(f"A[{i}][{j}] = ")
arr[i].append(n)
min = arr[0][0]
max = arr[0][0]
for i in range(x):
print()
for j in range(x):
print(" ",arr[i][j],end = ' ')
for i in range(x):
print()
for j in range(x):
if(arr[i][j] > max):
max = arr[i][j]
imax = i
jmax = j
if(arr[i][j] < min):
min = arr[i][j]
imin = i
jmin = j
print("минимальный =", min," i =", imin,"j =", jmin)
print("максимальный = ", max," i =",imax,"j =", jmax)

              Задание 2
              var n,m,i,j,t:integer;
a:array[1..20,1..25] of integer;
q:integer;

begin
q:=55;
writeln ('Введите размерность матрицы A MxN');
writeln ('M=');
read (n);
writeln ('N=');
read (m);

for i:=1 to n do
for j:=1 to m do
begin
writeln ('A[',i,', ', ', ', j,']=');
readln (a[i,j]);
end;

for i :=1 to n do
begin
for j :=1 to m do
write ( a [ i, j ]:4);
writeln ;
end ;

for i:=1 to n do
for j:=1 to m do
If ((a[i,j] mod 2)=0) and (a[i,j]>0) then
begin
q:=555;
writeln (a[i,j]) ;
writeln ('i=',i);
writeln ('j=',j);
writeln;
end;
If q=55 then writeln ('Таких элементов нет! ');
end.
