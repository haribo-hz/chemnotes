#chem #further
#### derivation
$$
\ce{E +S \underset{k_{-1}}{ \overset{ k_{1} }{ \longrightleftharpoons }}  ES \underset{k_{-2}}{ \overset{ k_{2} }{ \longrightleftharpoons }} E +P }
$$
$k_{-2}$ is so small when $\text{time}=0$ that it is ignored

the **steady state assumption** is made:
- the rate of formation of enzyme-substrate complex is the same as the rate of enzyme-substrate dissociation
$$
\begin{align} \\
\text{rate}_\text{formation}&= \text{rate}_{\text{dissociation}} \\
\ce{k_{1}[E][S]&= k_{-1}[ES] +k_{2}[ES]} \\
\end{align}
$$

$$
\begin{align}
\ce{[E]_\text{total}&=[ES] +[E]_{free}} \\
\ce{[E]&=[E]_\text{total}-[ES]} \\
\ce{k_{1}([E]_\text{total}-[ES])[S]&=k_{-1}[ES] +k_{2}[ES]} \\
\ce{k_{1}[E]_\text{total}[S]-k_{1}[ES]&=[ES](k_{-1} +k_{2})} \\
\end{align}
$$
michaelis constant:
$$
K_{m}=\frac{k_{-1}+k_{2}}{k_{1}}
$$

$$
\begin{align}
\ce{\frac{\cancel{ k_{1} }[E]_\text{total}[S]}{\cancel{ k_{1} }}-[ES][S]=[ES](k_{-1} +k_{2})} \\
\ce{[E]_\text{total}[S]-[ES][S]&=[ES]}K_\text{m} \\
\ce{[E]_\text{total}[S]&=[ES]}K_{m}\ce{+[ES][S]} \\
\ce{[ES](}K_{m}\ce{+[S]})=\ce{[E]_\text{total}[S]}
\end{align}
$$

$$
\begin{align}
V_{0}&=k_{2}\ce{[ES]} \\
\ce{[ES]}&= \frac{V_{0}}{k_{2}}
\end{align}
$$
initial reaction velocity is dependent upon the rate at which the enzyme-substrate complex dissociates into enzyme and product
- rate determining step

$$
\begin{align}
\frac{\ce{[ES]}(\cancel{ K_{m}+\ce{[S]} })}{\cancel{ K_{m}+\ce{[S]} }}&=\frac{\ce{[E]_\text{total}[S]}}{K_{m}+\ce{[S]}} \\
\ce{[ES]}&=\frac{\ce{[E]_\text{total}[S]}}{K_{m}+\ce{[S]}} \\
\frac{V_{0}}{k_{2}}&=\frac{\ce{[E]_\text{total}[S]}}{K_{m}+\ce{[S]}} \\
V_{0}&=k_{2}\times\frac{\ce{[E]_\text{total}[S]}}{K_{m}+\ce{[S]}}
\end{align}
$$

another assumption is made here, that there is a point called $V_\text{max}$, which is the point at which all the enzyme-substrate complex possible is formed (note that the enzyme is limiting reagent $\ce{[E]\ll[S]}$) and there is no enzyme left to form form the enzyme-substrate complex
- there exists a point, $V_\text{max}$, where all the enzyme is completely saturated with substrate, no free enzyme, $\ce{[E]}$
- so $\ce{[E]_\text{total}=[ES]}$

$$
\begin{align}
V_\text{max}&=k_{2}\ce{[ES]} \\
V_\text{max}&=k_{2}\ce{[E]_\text{total}}
\end{align}
$$

$$
\begin{align}
V_{0}&=k_{2}\times\frac{\ce{[E]_\text{total}[S]}}{K_{m}+\ce{[S]}} \\
V_{0}&=\frac{V_\text{max}\ce{[S]}}{K_{m}+\ce{[S]}}
\end{align}
$$

and here we have arrived at the michaelis-menten equation

#### what does $K_{m}$ mean?
when $V_{0}=\frac{V_\text{max}}{2}$,
$$
\begin{align}
\frac{V_\text{max}}{2}&=\frac{V_\text{max}\ce{[S]}}{K_{m}+\ce{[S]}} \\ \\
2V_\text{max}\ce{[S]}&= V_\text{max}(K_{m}+\ce{[S]}) \\
2\ce{[S]}&=K_{m} +\ce{[S]} \\ \\
K_{m} &= \ce{[S]\text{ when the reaction velocity =}}\frac{V_\text{max}}{2}\\
\end{align}
$$
$K_{m}$ represents the reciprocal of enzyme-substrate affinity
- low $K_{m}$ means high substrate affinity as it readily forms the enzyme-substrate complex even at low substrate concentrations
- high $K_{m}$ means low substrate affinity

$K_{m}$ can tell us how much substrate the enzyme can take on
with low km, it can't take on a lot because it has high affinity
with high km and low substrate affinity, it can take on larger amounts of substrate

see [[forms of enzyme inhibition]]

#### lineweaver-burk plot
![[effect of inhibitors on lineweaver-burk plot.png|800]]
