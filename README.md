# r_psy
r study for psychology

# Chap4
cjoonh  
June 24, 2015  

#R과 함께 하는 통계학의 이해


##Chap_4. 연속확률변수 및 분포

###4.1 연속확률변수의 확률분포함수

연속확률변수는 확률변수가 특정 구간의 모든 값을 다 가질 수 있기 때문에 가질 수 있는 값들을 일일이 지칭할 수 없는 확률변수를 의미함.

확률변수 X가 가질 수 있는 특정 구간에서 확률이 어떻게 분포하는가를 나타낼 수 있는 함수를 이용하게 된다. 즉, 연속확률변수 X의 확률분포는 확률의 밀도를 나타내는 확률밀도함수에 의해 결정된다.

▪ 확률밀도함수의 정의<br>
<img src="ch4-01.jpg">


▪ 확률밀도함수(a)와 아닌 경우(b)의 예<br>
<img src="ch4-02.jpg">
(a)의 경우에는 [-1,1]의 구간에 대해 f(x) = 0.5 > 0 인 직선이 표현되어 있다. 
<img src="ch4-03.jpg">
나머지 구간에 대해서는 f(x)=0 이므로 
<img src="ch4-04.jpg">
즉 (a)에 표현된 -1≤x≤1에 대한 f(x)=0.5의 직선은 확률밀도함수이다.

(b)의 경우에는 [-1,1]의 구간에 대해 f(x) = -x 인 직선이 표현되어 있다. 
이 경우 해당 구간에 대해서는 
<img src="ch4-05.jpg">
나머지 구간에 대해서는 f(x)=0 이므로
<img src="ch4-06.jpg">
조건도 만족하게 된다.
그러나 0≤x≤1 의 구간에 대해서 f(x)≤0 이므로 -1≤x≤1에 대한 f(x)= -x의 직선은 
확률밀도함수가 아니다. 

연속확률변수 X가 특정한 값 x 를 갖게 될 확률은 0 이므로,
P(a≤X≤b)=P(a<X≤b)=P(a≤X<b)=P(a<X<b)

▪ 연속확률변수의 기대값과 분산<br>
<img src="ch4-07.jpg">
이산확률변수의 경우 특정한 값 x를 가질 확률을 각각 구할 수 있기 때문에 각각의 값들을 다 더한 것.
연속확률변수의 경우에는 구간에 대한 확률로만 표현할 수 있기 때문에 적분의 계산 방법을 응용하는 것일 뿐 의미상의 차이는 없으므로 이산확률변수의 기대값과 분산의 성질은 연속확률변수에도 성립함.



###4.2정규분포
