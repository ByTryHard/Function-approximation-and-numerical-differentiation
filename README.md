# Function-approximation-and-numerical-differentiation
Приближение функций и численное дифференцирование.
1. Составить программу вычисления: f(x) = sum от k=0 до ∞  a(x), x ∈ [a,b],  b<1, с заданной точностью (см. варианты).
2. Найти производную f'(x) аналитически и составить программу вычисления f'(x) с заданной точностью Е.
3. Составить таблицу значений fi = f(xi) в точках xi = a + ih, I = 0.5, h = 0.1, a = 0.1
4. Пользуясь таблицей, полученной в п. 3, вычислить значения кусочно- линейной интерполянты P1(x) =C0 +C1x в узлах , xi*=xi + h/2, I =0,4.
5. Вычислить погрешность полученных значений в узлах xi*=xi + h/2, I =0,4. используя программы п.1 и п.4, z(xi*)=|f(xi*) – P1(xi*)|.
6. Пользуясь таблицей, полученной в п.3, вычислить значения первых разностных производных fx, fx, fx-, fx0 узлах xi=a + h/2, I =1,4
7. Вычислить погрешность разностных производных, используя програмы
п.2 и п. 6. z(xi)=|f’(xi) – fx(xi)|.
Вариант:  f(x)=  sum от k=0 до ∞  (((-1)**k)*(x**(2*k)))/((4**k)*(2*k)!)
