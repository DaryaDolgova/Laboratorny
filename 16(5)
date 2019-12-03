#include <iostream>

using namespace std;

int main() 
{ int n, t,k,i;

cout << "N= "; cin >> n;
int* A = new int[n];
for (i = 0; i < n; i++){cin >> A[i];}
t=0;
for (i = 0; i < n; i++) {
if (A[i] > 0) {
t++;
}
}
int* S = new int[n + t];
k = 0;
for (i = 0; i < n; i++) {
S[i + k] = A[i];
if (A[i] > 0) {
S[i + k] = 0;
S[i + 1 + k] = A[i];
k++;
}
}
for (i = 0; i < n + t; i++){cout << S[i] << ' ';}
delete[] A;
delete[] S;
return 0;
}
