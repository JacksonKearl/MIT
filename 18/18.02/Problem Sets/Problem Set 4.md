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
    $$\frac{\partial L}{\partial y} = 2y - 4-18\lambda y= 0 \Longrightarrow y = \frac{2}{1 - 9\lambda}$$
    $$\frac{\partial L}{\partial \lambda} = 4x^2 + 9y^2 - 36 = 0$$
1. Solve as a system of equations, using CAS software:
    \[
    \begin{align}
    4x^2 + 9y^2 - 36 &= 0\\
    4(\frac{3}{1 - 4\lambda})^2 + 9(\frac{2}{1 - 9\lambda})^2 - 36 &= 0\\
    \lambda &= [0.5103, -0.0684]
    \end{align}
    \]
1. Substitute back to find $x$ and $y$:


    $$(x,y) = (\frac{3}{1 - 4\lambda},\frac{2}{1 - 9\lambda})$$
    \[
    \begin{align}
    (x,y) &= (\frac{3}{1 - 4(0.5103)},\frac{2}{1 - 9(0.5103)}) & \text{OR  } & (x,y) = (\frac{3}{1 - 4(-0.0684)},\frac{2}{1 - 9(-0.0684)})\\
    (x,y) &= (-2.88, -0.557) & \text{OR  } & (x,y) = (2.36,1.24)
    \end{align}
    \]


1. Empirically determine min and max from original $f(x,y)$:
    \[
    \begin{align}
    \text{Distance from Origin:} &&D(x,y) = \sqrt{(x-3)^2 + (y-2)^2}\\
    \text{Minimum @ }(2.36,1.24): & &D(2.36,1.24) = 0.993\\
    \text{Maximum @ }(-2.88, -0.557): & &D(-2.88, -0.557)= 6.411
    \end{align}
    \]

#### Section 13.10

##### Problem 4:
1. Calculate partials, set to 0 to find critical points:
    \[
    \begin{align}
    \frac{\partial f}{\partial x} = y+3= 0 &\Longrightarrow y = -3\\
    \frac{\partial f}{\partial y} = x - 2= 0 &\Longrightarrow x = 2
    \end{align}
    \]
2. Evaluate discriminant at critical point, $(2,-3)$:
    \[
    \begin{align}
    \Delta &= f_{xx}(x,y)\space f_{yy}(x,y) - [f_{xy}(x,y)]^2\\
    &= 0\cdot0-1\\
    &= -1
    \end{align}
    \]
    The discriminant at $(2,-3)$ is negative, meaning there is a saddle point here, not a minimum or maximum.

##### Problem 10:
1. Calculate partials, set to 0 to find critical points:
    \[
    \begin{align}
    \frac{\partial f}{\partial x} = 3y - 3x^2 &= 0 &\Longrightarrow y = x^2\\
    \frac{\partial f}{\partial y} = 3x - 3y^2 &= 0 &\Longrightarrow x = y^2\\
    x &= x^4 &\Longrightarrow (x,y) = (0,0)\\
    1 &= x^3 &\Longrightarrow (x,y) = (1,1)\\
    \end{align}
    \]
2. Evaluate discriminant at critical points $(0,0)$, and $(1,1)$:
    \[
    \begin{align}
    \Delta(x,y) &= f_{xx}(x,y)\space f_{yy}(x,y) - [f_{xy}(x,y)]^2\\
    &= -6x \cdot -6y - [3]^2\\
    \Delta(0,0)&=0 \cdot 0 - 9 = -9\\
    \Delta(1,1)&= -6 \cdot -6 - 9 = 27
    \end{align}
    \]
    The discriminant at $(0,0)$ is negative, meaning it is a saddle point, not a minima or maxima.

    However, the discriminant at $(1,1)$ is positive, meaning it is either a minima or maxima. Because $f_{xx}(1,1)$ is negative, $(1,1)$ is a maxima.



### Lecture 13

#### Section 13.7

##### Problem 2:

1. Finding $\frac{dw}{dt}$ via chain rule:
    \[
    \begin{align}
    \frac{dw}{dt} &= \frac{\partial w}{\partial u} \frac{d u}{dt} + \frac{\partial w}{\partial v} \frac{d v}{dt}\\
    &= \frac{2u}{(u^2+v^2)^2} (-2\sin(2t))+ \frac{2v}{(u^2+v^2)^2} (2\cos(2t))\\
    &= \frac{2\cos(2t)}{(\cos(2t)^2+\sin(2t)^2)^2} (-2\sin(2t))+ \frac{2\sin(2t)}{(\cos(2t)^2+\sin(2t)^2)^2} (2\cos(2t))\\
    &=2\cos(2t)(-2\sin(2t)) + 2\sin(2t) (2\cos(2t)\\
    &=0
    \end{align}
    \]

1. Finding $\frac{dw}{dt}$ via substitution:
    \[
    \begin{align}
    w(u,v) &= \frac{1}{\cos(2t)^2+\sin(2t)^2}\\
    &= \frac{1}{1} = 1\\
    \frac{dw}{dt} &= 0\\
    \end{align}
    \]



##### Problem 4:
1. Finding $\frac{dw}{dt}$ via chain rule:
    \[
    \begin{align}
    \frac{dw}{dt} &= \frac{\partial w}{\partial u} \frac{d u}{dt} + \frac{\partial w}{\partial v} \frac{d v}{dt} + \frac{\partial w}{\partial z} \frac{d z}{dt}\\
    &= \frac{1}{u+v+z}[2\sin(t)\cos(t)+(-2)\cos(t)\sin(t)+2t]\\
    &= \frac{2t}{1+t^2}\\
    \end{align}
    \]

1. Finding $\frac{dw}{dt}$ via substitution:
    \[
    \begin{align}
    w(u,v,z) &= \ln(\cos^2 t + \sin^2 t + t^2)\\
    &= \ln(1 + t^2)\\
    \frac{dw}{dt} &= \frac{2t}{1+t^2}\\
    \end{align}
    \]



##### Problem 6:
1. Finding $\frac{\partial w}{\partial t}$:
    \[
    \begin{align}
    \frac{\partial w}{\partial t} &= \frac{\partial w}{\partial p} \frac{d p}{dt} + \frac{\partial w}{\partial q} \frac{d q}{dt} + \frac{\partial w}{\partial r} \frac{d r}{dt}\\
    &= q\sin(r) \cdot 1 + p\sin(r)\cdot -1 + pq\cos(r) \cdot s\\
    &= pqs \cos(r) + q\sin(r) - p\sin(r)\\
    \end{align}
    \]

1. Finding $\frac{\partial w}{\partial s}$:
    \[
    \begin{align}
    \frac{\partial w}{\partial s} &= \frac{\partial w}{\partial p} \frac{d p}{ds} + \frac{\partial w}{\partial q} \frac{d q}{ds} + \frac{\partial w}{\partial r} \frac{d r}{ds}\\
    &= q\sin(r) \cdot 2 + p\sin(r)\cdot 1 + pq\cos(r) \cdot t\\
    &= pqt \cos(r) + 2q\sin(r) + p\sin(r)\\
    \end{align}
    \]

##### Problem 16:
1. Finding $\frac{\partial p}{\partial x}$:
    \[
    \begin{align}
    \frac{\partial p}{\partial x} &= \frac{\partial p}{\partial v} \frac{\partial v}{\partial x} + \frac{\partial p}{\partial u} \frac{\partial u}{\partial x}\\
    \end{align}
    \]

1. Finding $\frac{\partial p}{\partial y}$:
    \[
    \begin{align}
    \frac{\partial p}{\partial y} &= \frac{\partial p}{\partial v} \frac{\partial v}{\partial y} + \frac{\partial p}{\partial u} \frac{\partial u}{\partial y}\\
    \end{align}
    \]

1. Finding $\frac{\partial p}{\partial z}$:
    \[
    \begin{align}
    \frac{\partial p}{\partial x} &= \frac{\partial p}{\partial v} \frac{\partial v}{\partial z} + \frac{\partial p}{\partial u} \frac{\partial u}{\partial z}\\
    \end{align}
    \]

1. Finding $\frac{\partial p}{\partial t}$:
    \[
    \begin{align}
    \frac{\partial p}{\partial y} &= \frac{\partial p}{\partial v} \frac{\partial v}{\partial t} + \frac{\partial p}{\partial u} \frac{\partial u}{\partial t}\\
    \end{align}
    \]

##### Problem 20:

1. Rearrange to get $z = f(x,y,z) + g(x,y,z) + h(x,y,z)$:
\[
\begin{align}
z &= f(x,y,z) + g(x,y,z) + h(x,y,z)\\
f(x,y,z) &= \frac{x^2}{y}\\
g(x,y,z) &= \frac{y^2}{x}\\
h(x,y,z) &= \frac{z^3}{xy}
\end{align}
\]
1. Use chain rule to find $\frac{\partial z}{\partial x}$:
\[
\begin{align}
\frac{\partial z}{\partial x} &=
            \frac{\partial z}{\partial f} \frac{\partial f}{\partial x} +
            \frac{\partial z}{\partial g} \frac{\partial g}{\partial x} +
            \frac{\partial z}{\partial g} \frac{\partial g}{\partial x} \\
          &= 1\cdot \frac{2x}{y} + 1 \cdot -\frac{y^2}{x^2} + 1 \cdot -\frac{z^3}{x^2y}\\
          &= \frac{2x}{y}-\frac{y^2}{x^2} -\frac{z^3}{x^2y}\\
          &= \frac{2x^3-y^3-z^3}{x^2y}
\end{align}
\]

1. Use chain rule to find $\frac{\partial z}{\partial y}$:
\[
\begin{align}
\frac{\partial z}{\partial y} &=
            \frac{\partial z}{\partial f} \frac{\partial f}{\partial y} +
            \frac{\partial z}{\partial g} \frac{\partial g}{\partial y} +
            \frac{\partial z}{\partial g} \frac{\partial g}{\partial y} \\
          &= 1\cdot -\frac{x^2}{y^2} + 1 \cdot \frac{2y}{x} + 1 \cdot -\frac{z^3}{xy^2}\\
          &= -\frac{x^2}{y^2} + \frac{2y}{x} -\frac{z^3}{xy^2}\\
          &= \frac{2y^3-x^3-z^3}{xy^2}
\end{align}
\]



##### Problem 40:

\[
\begin{align}
\left(\frac{\partial w}{\partial x}\right)^2 + \left(\frac{\partial w}{\partial y}\right)^2 &= \left(\frac{\partial w}{\partial r}\right)^2 + \frac{1}{r^2} \left(\frac{\partial w}{\partial \theta}\right)^2\\
&= \left(\frac{\partial w}{\partial x}\frac{\partial x}{\partial r} + \frac{\partial w}{\partial y}\frac{\partial y}{\partial r}\right)^2 + \frac{1}{r^2} \left(\frac{\partial w}{\partial x}\frac{\partial x}{\partial \theta} + \frac{\partial w}{\partial y}\frac{\partial y}{\partial \theta}\right)^2\\
&= \left(\frac{\partial w}{\partial x}\cos(\theta) + \frac{\partial w}{\partial y}\sin(\theta)\right)^2 + \frac{1}{r^2} \left(\frac{\partial w}{\partial x}(-r\sin(\theta)) + \frac{\partial w}{\partial y}r\cos(\theta)\right)^2\\
&= \left(\frac{\partial w}{\partial x}\cos(\theta) + \frac{\partial w}{\partial y}\sin(\theta)\right)^2 + \left(\frac{\partial w}{\partial y}(\cos(\theta)) - \frac{\partial w}{\partial x}\sin(\theta)\right)^2\\
&= \left(\frac{\partial w}{\partial x}\right)^2\cos^2(\theta) +
    2\frac{\partial w}{\partial y}\frac{\partial w}{\partial x}\sin(\theta)\cos(\theta) +
    \left(\frac{\partial w}{\partial y}\right)^2\sin^2(\theta) +
    \left(\frac{\partial w}{\partial y}\right)^2\cos^2(\theta) -
    2\frac{\partial w}{\partial y}\frac{\partial w}{\partial x}\sin(\theta)\cos(\theta) +
    \left(\frac{\partial w}{\partial x}\right)^2\sin^2(\theta)\\
&= \left(\frac{\partial w}{\partial x}\right)^2\cos^2(\theta) +
    \left(\frac{\partial w}{\partial y}\right)^2\sin^2(\theta) +
    \left(\frac{\partial w}{\partial y}\right)^2\cos^2(\theta) +
    \left(\frac{\partial w}{\partial x}\right)^2\sin^2(\theta)\\
&=  \left(\frac{\partial w}{\partial x}\right)^2\left(\cos^2(\theta)+ \sin^2(\theta)\right)+
    \left(\frac{\partial w}{\partial y}\right)^2\left(\sin^2(\theta)+ \cos^2(\theta)\right) \\
&= \left(\frac{\partial w}{\partial x}\right)^2 + \left(\frac{\partial w}{\partial y}\right)^2\\
\end{align}
\]
