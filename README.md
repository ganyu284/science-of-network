# science-of-network
网络科学导论作业

解决了6个二阶智能体的一阶一致性问题。

#### 初始状态

$x_0 =[1;2;3;4;5;6]$ ;$v_0=[1;2;3;4;5;6]$

#### 网络拓扑

$$
\tag{1}
A =
\left[
\begin{array}{c}
0 \quad 1 \quad0\quad1\quad0\quad1\\
1 \quad 0 \quad1 \quad0 \quad 1\quad0\\
0 \quad 1 \quad0\quad1\quad0\quad1\\
1 \quad 0 \quad1 \quad0 \quad 1\quad0\\
0 \quad 1 \quad0\quad1\quad0\quad1\\
1 \quad 0 \quad1 \quad0 \quad 1\quad0\\

\end{array}
\right]
$$

$$
\tag{2}
L=D-A
$$



#### 微分方程

$$
\tag{3}
\left\{
\begin{array}{l}
\overset{.}{x}=v\\
\overset{.}{v}=a\\
a = - Lx - \gamma * L * v 
\end{array}
\right.
$$

#### 计算方法

4阶龙格库塔法

