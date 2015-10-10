# 18.02 - Problem Set 4
### Jackson Kearl
___

## Part 1

### Lecture 12

#### Section 13.9

##### Problem 2:


1. Define Functions:
    \[
    \begin{align}
    \text{Function: }& &f(x,y) &= x + y \\
    \text{Constraint: }& &x^2 + 4y^2 &= 1
    \end{align}
    \]
1. Rearrange such that the condition is satisfied when $g(x,y) = 0$:
     $$g(x,y) = x^2 + 4y^2 - 1$$
1. Plug into Lagrange Multiplier equation, $L(x,y,\lambda) = f(x,y)-\lambda g(x,y)$:
     $$L(x, y, \lambda) = x + y - \lambda(x^2 + 4y^2 - 1)$$
1. Take partials with respect to $x$, $y$, and $\lambda$, and set to $0$:
     $$\frac{\partial L}{\partial x} = 1 - 2\lambda x = 0 \Longrightarrow x = \frac{1}{2\lambda}$$
    $$\frac{\partial L}{\partial y} = 1 - 8\lambda y = 0 \Longrightarrow y = \frac{1}{8\lambda}$$
     $$\frac{\partial L}{\partial \lambda} = x^2 + 4y^2 - 1 = 0$$
1. Solve as a system of equations:
    \[
    \begin{align}
    \frac{1}{2\lambda}^2 + 4 \frac{1}{8\lambda}^2 -1 &= 0 \\
    \frac{1}{4\lambda^2} + 4 \frac{1}{64\lambda^2} -1 &= 0 \\
    \frac{4}{16\lambda^2} + \frac{1}{16\lambda^2} -1 &= 0 \\
    \frac{5}{16\lambda^2} &= 1 \\
    \lambda &= \pm \frac{\sqrt{5}}{4}
    \end{align}
    \]
1. Substitute back to find $x$ and $y$:    
    \[
    \begin{align}
    x = \frac{\pm4}{2\sqrt{5}} &= \frac{\pm2}{\sqrt{5}}\\
    y = \frac{\pm4}{8\sqrt{5}} &= \frac{\pm1}{2\sqrt{5}}
    \end{align}
    \]
1. Empirically determine minimum and maximum from original $f(x,y)$:
    \[
    \begin{align}
    \text{Minimum: }& &f \left(\frac{-2}{\sqrt{5}}, \frac{-1}{2\sqrt{5}}\right) = \frac{-2}{\sqrt{5}} + \frac{-1}{2\sqrt{5}} &= \frac{-5}{2\sqrt{5}}\\
    \text{Maximum: }& &f \left(\frac{2}{\sqrt{5}}, \frac{1}{2\sqrt{5}}\right) = \frac{2}{\sqrt{5}} +\frac{1}{2\sqrt{5}} &= \frac{5}{2\sqrt{5}}
    \end{align}
    \]

##### Problem 8:
1. Define Functions:
    \[
    \begin{align}
    \text{Function: }& &f(x,y,z) &= 3x + 2y + z\\
    \text{Constraint: }& &x^2 + y^2 + z^2 &= 1
    \end{align}
    \]

1. Rearrange such that the condition is satisfied when $g(x,y,z) = 0$:
    $$g(x,y) = x^2 + y^2 + z^2 - 1$$
1. Plug into Lagrange Multiplier equation, $L(x,y,z,\lambda) = f(x,y,z)-\lambda g(x,y,z)$
    $$L(x, y, z, \lambda) = 3x + 2y + z - \lambda(x^2 + y^2 + z^2 - 1)$$
1. Take partials with respect to $x$, $y$, $z$, and $\lambda$, and set to $0$:
    $$\frac{\partial L}{\partial x} = 3 - 2\lambda x = 0 \Longrightarrow x = \frac{3}{2\lambda}$$
    $$\frac{\partial L}{\partial y} = 2 - 2\lambda y = 0 \Longrightarrow y = \frac{1}{\lambda}$$
    $$\frac{\partial L}{\partial z} = 1 - 2\lambda z = 0 \Longrightarrow z = \frac{1}{2\lambda}$$
    $$\frac{\partial L}{\partial \lambda} = x^2 + y^2 + z^2 - 1 = 0$$
1. Solve as a system of equations:
    \[
    \begin{align}
    \frac{3}{2\lambda}^2 + \frac{1}{\lambda}^2 + \frac{1}{2\lambda}^2-1 &= 0 \\
    \frac{9}{4\lambda^2} + \frac{1}{\lambda^2} + \frac{1}{4\lambda^2} -1 &= 0 \\
    \frac{9}{4\lambda^2} + \frac{4}{4\lambda^2} + \frac{1}{4\lambda^2} -1 &= 0 \\
    \frac{14}{4\lambda^2} -1 &= 0 \\
    \frac{7}{2\lambda^2} &= 1 \\
    \lambda &= \pm \frac{\sqrt{14}}{2}
    \end{align}
    \]
1. Substitute back to find $x$ and $y$:
    \[
    \begin{align}
    x &= \pm\frac{3}{\sqrt{14}}\\
    y &= \pm\frac{2}{\sqrt{14}}\\
    z &= \pm\frac{1}{\sqrt{14}}
    \end{align}
    \]
1. Empirically determine min and max from original $f(x,y)$:
    \[
    \begin{align}
    \text{Min: }& &f \left(\frac{-3}{\sqrt{14}}, \frac{-2}{\sqrt{14}}, \frac{-1}{\sqrt{14}}\right) =\frac{-3}{\sqrt{14}}+ \frac{-2}{\sqrt{14}}+ \frac{-1}{\sqrt{14}} = \frac{-6}{\sqrt{14}}\\
    \text{Max: }& &f \left(\frac{3}{\sqrt{14}}, \frac{2}{\sqrt{14}}, \frac{1}{\sqrt{14}}\right) =\frac{3}{\sqrt{14}}+ \frac{2}{\sqrt{14}}+ \frac{1}{\sqrt{14}} = \frac{6}{\sqrt{14}}
    \end{align}
    \]


##### Problem 38:
1. Define Functions:
    \[
    \begin{align}
    \text{Function: }& &f(x,y) &= x^2 + y^2\\
    \text{Constraint: }& &x^2 + xy + y^2 &= 3
    \end{align}
    \]

1. Rearrange such that the condition is satisfied when $g(x,y) = 0$:
    $$g(x,y) = x^2 + xy + y^2 - 3$$
1. Plug into Lagrange Multiplier equation, $L(x,y,\lambda) = f(x,y)-\lambda g(x,y)$
    $$L(x, y, \lambda) = x^2 + y^2 - \lambda(x^2 + xy + y^2 - 3)$$
1. Take partials with respect to $x$, $y$, and $\lambda$, and set to $0$:
    $$\frac{\partial L}{\partial x} = 2x - 2\lambda x - \lambda y= 0 \Longrightarrow x = \frac{\lambda y}{2 - 2\lambda}$$
    $$\frac{\partial L}{\partial y} = 2y - 2\lambda y - \lambda x= 0 \Longrightarrow y = \frac{\lambda x}{2 - 2\lambda}$$
    $$\frac{\partial L}{\partial \lambda} = x^2 + xy + y^2 - 3 = 0$$
1. Solve as a system of equations:
    \[
    \begin{align}
    x &= \frac{\lambda y}{2-2\lambda}& && y &= \frac{\lambda x}{2-2\lambda}\\
    \frac{x}{y} &= \frac{\lambda}{2-2\lambda}& && \frac{y}{x} &= \frac{\lambda}{2-2\lambda}\\
    &&\frac{x}{y} &= \frac{y}{x}\\
    &&x^2 &= y^2\\
    &&y &= \pm x\\
    g(x,y) = g(x,x) = 3x^2 - 3 &= 0 &&& g(x,y) = g(x,-x) = x^2-3 &= 0\\
    3x^2 &= 3 &&& x^2 &= 3\\
    x^2 &= 1 &&& x^2 &= 3\\
    x =y &= \pm1 &&& x =-y&= \pm\sqrt{3}\\
    \end{align}
    \]
1. Substitute back to find $x$ and $y$:
    \[
    \begin{align}
    (x,y) = (1,1),\space(-1,-1),\space(\sqrt{3},-\sqrt{3}),\space(-\sqrt{3},\sqrt{3})
    \end{align}
    \]
1. Empirically determine min and max from original $f(x,y)$:
    \[
    \begin{align}
    \text{Distance from Origin:} &&D(x,y) = \sqrt{x^2 + y^2}\\
    \text{Minimums @ }(1,1),\space(-1,-1): & &D(1,1) =  D(-1,-1)= \sqrt{1^2 + (-1)^2} = \sqrt{2}\\
    \text{Maximums @ }(-\sqrt{3},\sqrt{3}),\space(\sqrt{3},-\sqrt{3}): & &D(-\sqrt{3}),\sqrt{3}) =  D(\sqrt{3},-\sqrt{3})= \sqrt{\sqrt{3}^2 + (-\sqrt{3})^2} = \sqrt{6}
    \end{align}
    \]

##### Problem 52:
1. Define Functions:
    \[
    \begin{align}
    \text{Function: }& &f(x,y) &= (x-3)^2 + (y-2)^2\\
    \text{Constraint: }& &4x^2 + 9y^2 &= 36
    \end{align}
    \]

1. Rearrange such that the condition is satisfied when $g(x,y) = 0$:
    $$g(x,y) = 4x^2 + 9y^2 -36$$
1. Plug into Lagrange Multiplier equation, $L(x,y,\lambda) = f(x,y)-\lambda g(x,y)$
    $$L(x, y, \lambda) = (x-3)^2 + (y-2)^2 - \lambda(4x^2 + 9y^2 - 36)$$
1. Take partials with respect to $x$, $y$, and $\lambda$, and set to $0$:
    $$\frac{\partial L}{\partial x} = 2x - 6 -8\lambda x= 0 \Longrightarrow x = \frac{3}{1 - 4\lambda}$$
    $$\frac{\partial L}{\partial y} = 2y - 4-18\lambda y= 0 \Longrightarrow y = \frac{1}{1 - 9\lambda}$$
    $$\frac{\partial L}{\partial \lambda} = 4x^2 + 9y^2 - 36 = 0$$
1. Solve as a system of equations, using CAS software:
    \[
    \begin{align}
    4x^2 + 9y^2 - 36 &= 0\\
    4(\frac{3}{1 - 4\lambda})^2 + 9(\frac{1}{1 - 9\lambda})^2 - 36 &= 0\\
    \lambda &= [0.5026, -0.0242]
    \end{align}
    \]
1. Substitute back to find $x$ and $y$:


    $$(x,y) = (\frac{3}{1 - 4\lambda},\frac{1}{1 - 9\lambda})$$
    \[
    \begin{eqnarray}
    &(x,y) &= (\frac{3}{1 - 4(0.5026)},\frac{1}{1 - 9(0.5026)}) &OR& (x,y) &= (\frac{3}{1 - 4(−0.0242)},\frac{1}{1 - 9(−0.0242)})\\
    &(x,y) &= (-2.969, -28.38) &OR& (x,y) &= (2.735,0.8212)
    \end{eqnarray}
    \]


1. Empirically determine min and max from original $f(x,y)$:
    \[
    \begin{align}
    \text{Distance from Origin:} &&D(x,y) = \sqrt{x^2 + y^2}\\
    \text{Minimums @ }(1,1),\space(-1,-1): & &D(1,1) =  D(-1,-1)= \sqrt{1^2 + (-1)^2} = \sqrt{2}\\
    \text{Maximums @ }(-\sqrt{3},\sqrt{3}),\space(\sqrt{3},-\sqrt{3}): & &D(-\sqrt{3}),\sqrt{3}) =  D(\sqrt{3},-\sqrt{3})= \sqrt{\sqrt{3}^2 + (-\sqrt{3})^2} = \sqrt{6}
    \end{align}
    \]
