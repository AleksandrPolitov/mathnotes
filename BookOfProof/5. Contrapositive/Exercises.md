# A.
### 5. Suppose  $x \in \mathbb{Z}$. If $x^2+5x\lt0$, then $x\lt0$.
Proof:  We will proof by contrapositive technique. Suppose $x\ge0$. Adding 5 to the both sides gives $x+5\ge5$ and multiplying it by x gives $x^2+5x\ge5x$. Since $x\ge0$, then $5x\ge0$ and $x^2+5x\ge0$. 
### 6. Suppose $x \in \mathbb{R}$. If $x^3-x\gt0$, then $x\gt-1$.
Proof: We will proof by contrapositive technique. Suppose $x\le-1$. Since $x$ is negative, $x^2\ge-x$ and $x^3\le-x^2$. Hence $x^2\ge-x\iff-x^2\le x$. Thus $x^3\le-x^2\le x \rightarrow x^3\le x \rightarrow x^3-x\le0$. Therefore, if $x\le-1$ then $x^3-x\le0$.
### 7. Suppose $a,b \in \mathbb{Z}$. If both $ab$ and $a+b$ are even, then both $a$ and $b$ are even.
Proof: We will proof by contrapositive. Suppose $a$ is odd or $b$ is odd. 
Case #1: $a$ and $b$ are odd.
	Let $a=2p+1$ and $b=2q+1$  for some $p,q\in\mathbb{Z}$. 
	$ab=(2p+1)(2q+1)=4pq+2p+2q+1=2(2pq+p+q)+1$ which is odd.
	$a+b=(2p+1)+(2q+1)=2p+2q+2=2(p+q+1)$ which is even.
	Case 1 is true.
Case #2: $a$ is even and $b$ is odd.
	Let $a=2p$ and $b=2q+1$  for some $p,q\in\mathbb{Z}$. 
	$ab=(2p)(2q+1)=4pq+2p=2(2pq+p)$ which is even.
	$a+b=2p+2q+1=2(p+q)+1$ which is odd.
	Case 2 is true.
Case #3 is similar to #2.
Therefore, if either $a$ or $b$ is odd, then either $ab$ or $a+b$ is odd.

 - [ ] 
### 8. Suppose $x\in\mathbb{R}$. If $x^5-4x^4+3x^3-x^2+3x-4\ge0$, then $x\ge0$.
Proof: Suppose $x\lt0$. Since $x$ is negative $x^5<0$, $4x^4>0$, $3x^3<0$, $x^2>0$, and $3x<0$. 
Multiplyign some inequalities by -1 gives us $-4x^4<0$ and $-x^2<0$. Summing all equations gives us $x^5-4x^4+3x^3-x^2+3x<0$ 
Factoring inequality: $x^2(x^3-1)-4(x^4+1)+3x(x^2+1)<0$ 

### 9. Suppose $n\in\mathbb{Z}$. If $3\nmid n^2$, then $3\nmid n$.
Proof: Suppose $3\mid n$. Thus, $3=nb$ for some $b\in\mathbb{Z}$. Squaring both sides gives us $9=n^2 b^2$. Since $3 \mid n$, $3 \mid n^2$.