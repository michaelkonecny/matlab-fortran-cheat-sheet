# MATLAB - Fortran cheat sheet

It's sometimes difficult to remember the correct syntaxes in the two languages.

This sheet contains some basic examples of the same operations written in Matlab and Fortran.

## Element-wise multiplication/division
Matlab:
```matlab
A = [1 2 3];
B = [4 5 6];
C = A.*B  % [4 10 18]
```

Fortran:
```fortran
A = (/1, 2, 3/)
B = (/4, 5, 6/)
C = A*B  ! (/4, 10, 18/)
```
