# programacion-p_5.14
%5.14
%parte b
%se maneja una escala lineal en el ejex y logaritmica en el eje y
clear all
clf
x=1:1:100;
y=x.^2;
semilogy(x,y,'r')
title('numeral 5.14-b')
ylabel('escala logaritmica')
xlabel('escala lineal de 1:100')
%5.14
%parte c
%grafica en escala log en x y lineal en y
clear all
clf
x=1:1:100;
y=x.^2;
semilogx(x,y,'c')
title('numeral 5.14-c')
xlabel('escala logaritmica')
ylabel('escala lineal')
grid on 
%%5.14
%parted
%esta parte se grafica en ambos ejes con escala logaritmica
clear all
clf
x=1:1:100;
y=x.^2;
loglog(x,y,'g')
title('numeral 5.14-d')
grid on
