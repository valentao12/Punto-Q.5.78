# Punto-Q.5.78
Further Analysis
Q.5.78 Load and run the program of Example 5.13.
>> Beta = linspace(0,2*pi,200);

>> R1 = 3*cos(4*Beta);

>> subplot(2,2,1);polar(Beta,R1)

>> title(‘Rose Figure for R1=3*cos(4*Beta)’)

>> R2 = 3*sin(4*Beta);

>> subplot(2,2,2); polar(Beta,R2)

>> title(‘Rose Figure for R2=3*sin(4*Beta)’)

>> R3 = 3*cos(5*Beta);

>> subplot(2,2,3); polar(Beta,R3)

>> title(‘Rose Figure for R3=3*cos(5*Beta)’)

>> R4 = 3*sin(5*Beta);

>> subplot(2,2,4); polar(Beta,R4)

>> title(‘Rose Figure for R4=3*sin(5*Beta)’)
