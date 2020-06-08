---
layout: default
title: JAM 2020 | 
---

### Question-

<div>
	If \(y(x)\) satisfies \[{dy \over dx} = y \left [ 1+(log (y))^2 \right ]\]
	and \(y(0)=1 \) for \(x \ge 0\) then \(y \left (\pi \over 2 \right )\) is >
	<br>
		&emsp; a) 0 &emsp;&emsp; b) 1 &emsp;&emsp; c) \(pi \over 2\) &emsp;&emsp; d) \(\infty\)
</div>
---

<br>
### Answer-

<details>
	<summary> Answer </summary>
	<br>
	&emsp;d) \(\infty\)
	<br><br>
</details>
<details>
	<summary> Step-by-Step Solution </summary>
	<span>
			\[{1 \over y}{dy \over dx} =  \left [ 1+(log (y))^2 \right ]\]
			\[{d \over dx} log(y) =  \left [ 1+(log (y))^2 \right ]\]
			Substitute \(log(y)=u \ i.e. y=e^u \)
			\[{du \over dx}  =  \left ( 1+u^2 \right )\]
			\[{du \over {1+u^2}}  =  dx\]
			Integrate both sides,
			\[tan^{-1}(u)=x+c \]
			i.e. \[u=tan(x+c) \]
			\[ \therefore y(x) = e^u= e^{tan(x+c)} \]
			Using initial conditions, \(y(0)=1\)
			\[1=e^{tan(c)} \ \implies \ tan(c)=0 \ \implies \ c=0 \]
			Hence,
			\[y(x)=e^{tan(x)}\]
			At \(x= {\pi \over 2}\),
			\[y \left ({\pi \over 2} \right )=e^\infty=\infty\]
			<br>
	</span>
</details>
---