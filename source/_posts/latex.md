---
title: test latex
date: 2019-08-31 09:52:01
tags:
---

$$
f\left(
   \left[ 
     \frac{
       1+\left\{x,y\right\}
     }{
       \left(
          \frac{x}{y}+\frac{y}{x}
       \right)
       \left(u+1\right)
     }+a
   \right]^{3/2}
\right)
\tag{行标}
$$

$$
\begin{aligned}
\sqrt{37} & = \sqrt{\frac{73^2-1}{12^2}} \\
 & = \sqrt{\frac{73^2}{12^2}\cdot\frac{73^2-1}{73^2}} \\ 
 & = \sqrt{\frac{73^2}{12^2}}\sqrt{\frac{73^2-1}{73^2}} \\
 & = \frac{73}{12}\sqrt{1 - \frac{1}{73^2}} \\ 
 & \approx \frac{73}{12}\left(1 - \frac{1}{2\cdot73^2}\right)
\end{aligned}
$$

$$
\begin{aligned}
& \text{input : }\quad n^{[l-1]} \times n^{[l-1]} \times n^{[l-1]}_{c} \\
& \text{filter(kernl) size : }\quad f^{[l]}\\
& \text{padding: }\quad p^{[l]} \\
& \text{stride : }\quad s^{[l]}\\
& \text{numbers of filter : }\quad n^{[l]}_{c}\\
& \text{each filter : }\quad f^{[l]} \times f^{[l]} \times n^{[l-1]}_{c}\\
& \text{activations: }\quad a^{[l]} = n^{[l]} \times n^{[l]} \times n^{[l]}_{c} \\
& \text{weights : }\quad f^{[l]} \times f^{[l]} \times n^{[l-1]}_{c} \times n^{[l]}_{c}\\
& \text{bias : }\quad  1 \times 1 \times 1 \times n^{[l]}_{c} \\
\end{aligned}
$$

$$
\begin{aligned}
& \text{each filter : }\quad f^{[l]} \times f^{[l]} \times n^{[l-1]}_{c}\\
\end{aligned}
$$

$$
\begin{aligned}
& \text{activations: }\quad a^{[l]} = n^{[l]} \times n^{[l]} \times n^{[l]}_{c} \\
\end{aligned}
$$

$$
\begin{aligned}
& \text{weights : }\quad f^{[l]} \times f^{[l]} \times n^{[l-1]}_{c} \times n^{[l]}_{c}\\
\end{aligned}
$$

$$
\begin{aligned}
& \text{bias : }\quad  1 \times 1 \times 1 \times n^{[l]}_{c} \\
\end{aligned}
$$



$$
\begin{aligned}
& \text{input : }\quad n^{[l-1]} \times n^{[l-1]} \times n^{[l-1]}_{c}\\
& \text{filter(kernl) size : }\quad f^{[l]}\\
& \text{padding: }\quad p^{[l]} \\
& \text{stride : }\quad s^{[l]}\\
& \text{numbers of filter : }\quad n^{[l]}_{c}\\
& \text{each filter : }\quad f^{[l]} \times f^{[l]} \times n^{[l-1]}_{c}\\
& \text{activations: }\quad a^{[l]} = n^{[l]} \times n^{[l]} \times n^{[l]}_{c} \\
& \text{weights : }\quad f^{[l]} \times f^{[l]} \times n^{[l-1]}_{c} \times n^{[l]}_{c}\\
& \text{bias : }\quad  1 \times 1 \times 1 \times n^{[l]}_{c} \\
& \text{output : }\quad n^{[l]} \times n^{[l]} \times n^{[l]}_{c}\\
& n^{[l]} = [\frac{n^{[l-1]}+2p^{[l]}-f^{[l]}}{s^{[l]}}+1]
\end{aligned}
$$