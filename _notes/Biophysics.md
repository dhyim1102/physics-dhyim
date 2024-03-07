
#### Multiplicity

Multiplicity($\Omega$)는 미시상태의 수를 의미한다. 
예를 들어 다음과 같이 N개의 distinguishable 한 스핀이 있다면
$\Omega = 2^N$ 이다.
![[Pasted image 20240306195358.png]]

#### Entropy

Entropy($S$)는 다음과 같이 정의한다.
$$ S = k_B\ln(\Omega) $$
다음과 같이 정의하는 데에는 여러가지 이유가 있다.

-  대다수의 경우 Multiplicity($\Omega$)는 Very Large Number이다. 
	예를 들어 Solid을 다루는 경우 $1{cm}^3$ 에 대략 $10^{23}$개의 원자들이 있다. 이런 경우 logarithm을 취함으로서 큰 숫자를 보다 쉽게 다룰 수 있다.

-  Logarithm은 곱연산을 덧셈으로 바꾸어준다.
	하나의 스핀은 2개의 Multiplicity를 가진다 (위, 아래).
	두 개의 스핀 system은 $2 \times 2 = 4$ 의 Multiplicity를 가진다.
	
	엔트로피 를 계산할 때는 곱셈을 덧셈으로 바꿀 수 있다.
	하나의 스핀은 엔트로피  $S_1 = k_B\log(2)$ 를 가지기 때문에,
	두 개의 스핀 시스템은 엔트로피 $S_2 = S_1 + S_1 = 2k_B\log(2)$ 를 가진다. 
	
-  $k_B$ 는 Boltzmann Coeffeficient이다. 온도를 곱한 양인 $k_BT$ 는 에너지의 차원을 가진다. 때문에 $TS$ 역시 에너지의 차원을 가진다.



