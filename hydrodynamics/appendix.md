#Appendix of vectorical analysis
## Gradient

1. **Cartesian coordinates**
$$
\nabla p = \frac { \partial p } { \partial x } \boldsymbol{e_{x}} + \frac { \partial p } { \partial y } \boldsymbol{e_{y}} + \frac { \partial p } { \partial z } \boldsymbol{e_{z}}
$$

2. **Cylindrical coordinates**
$$
\nabla \psi = \frac { \partial \psi } { \partial r } \boldsymbol{e_{r}} + \frac { 1 } { r } \frac { \partial \psi } { \partial \phi } \boldsymbol{e_{\phi}} + \frac { \partial \psi } { \partial z } \boldsymbol{e_{z}}
$$


3. **Spherical coordinates**

$$
\nabla \psi=\frac{\partial \psi}{\partial r} \boldsymbol{e_{r}}+\frac{1}{r} \frac{\partial \psi_{e}}{\partial \theta} \boldsymbol{e_{\theta}}+\frac{1}{r \sin \theta} \frac{\partial \psi}{\partial \phi} \boldsymbol{e_{\phi}}
$$

## Divergence

1. **Cartesian coordinates**  

$$
\nabla \cdot \boldsymbol { v } = \frac { \partial u } { \partial x } + \frac { \partial v } { \partial y } + \frac { \partial w } { \partial z }
$$

2. **Cylindrical coordinates**  


$$
\nabla \cdot \boldsymbol{v}=\frac{1}{r} \frac{\partial}{\partial r}\left(r v_{r}\right)+\frac{1}{r} \frac{\partial v_{\phi}}{\partial \phi}+\frac{\partial v_{r}}{\partial z}
$$


3. **Spherical coordinates**

$$
\nabla \cdot \boldsymbol{v}=\frac{1}{r^{2}} \frac{\partial}{\partial r}\left(r^{2} v_{r}\right)+\frac{1}{r \sin \theta} \frac{\partial}{\partial \theta}\left(\sin \theta v_{\theta}\right)+\frac{1}{r \sin \theta} \frac{\partial v_{*}}{\partial \phi}
$$

## Curl
1. **Cartesian coordinates**  

$$
\nabla \times \boldsymbol { v } = \left( \frac { \partial w } { \partial y } - \frac { \partial v } { \partial z } \right) \boldsymbol{e_{x}} + \left( \frac { \partial u } { \partial z } - \frac { \partial w } { \partial x } \right) \boldsymbol{e_{y}} + \left( \frac { \partial v } { \partial x } - \frac { \partial u } { \partial y } \right) \boldsymbol{e_{z}}
$$

2. **Cylindrical coordinates**  

$$
\begin{aligned}
\nabla \times \boldsymbol{v}=&\left(\frac{1}{r} \frac{\partial v_{z}}{\partial \phi}-\frac{\partial v_{\phi}}{\partial z}\right) \hat{e_{r}}+\left(\frac{\partial v_{r}}{\partial z}-\frac{\partial v_{z}}{\partial r}\right) \hat{e_{\phi}} + \left[\frac{1}{r} \frac{\partial}{\partial r}\left(r v_{\phi}\right)-\frac{1}{r} \frac{\partial v_{r}}{\partial \phi}\right] \hat{e_{z}}
\end{aligned}
$$

3. **Spherical coordinates** 
 
$$
\nabla \times \boldsymbol{v}=\frac{1}{r \sin \theta}\left[\frac{\partial}{\partial \theta}\left(\sin \theta \\ v_{\phi}\right)-\frac{\partial v_{\theta}}{\partial \phi}\right] \hat{e_{r}}+\frac{1}{r}\left[\frac{1}{\sin \theta} \frac{\partial v_{r}}{\partial \phi}-\frac{\partial}{\partial r}\left(r v_{\phi}\right)\right] \hat{e_{\theta}}  \\
+ \frac{1}{r}\left[\frac{\partial}{\partial r}\left(r v_{\theta}\right)-\frac{\partial v_{r}}{\partial \theta}\right] \boldsymbol{e_{\phi}}
$$


## Laplace Operator
1. **Cartesian coordinates**  

$$
\nabla^{2} \psi=\frac{\partial^{2} \psi}{\partial x^{2}} + \frac{\partial^{2} \psi}{\partial y^{2}}+\frac{\partial^{2} \psi}{\partial z^{2}}
$$

2. **Cylindrical coordinates**  

$$
\nabla^{2} \psi=\frac{1}{r} \frac{\partial}{\partial r}\left(r \frac{\partial \psi}{\partial r}\right)+\frac{1}{r^{2}} \frac{\partial^{2} \psi}{\partial \phi^{2}}+\frac{\partial^{2} \psi}{\partial z^{2}}
$$

3. **Spherical coordinates** 
 
$$
\nabla^{2} \psi=\frac{1}{r^{2}} \frac{\partial}{\partial r}\left(r^{2} \frac{\partial \psi}{\partial r}\right)+\frac{1}{r^{2} \sin \theta} \frac{\partial}{\partial \theta}\left(\sin \theta \frac{\partial \psi}{\partial \theta}\right)+\frac{1}{r^{2} \sin ^{2} \theta} \frac{\partial^{2} \psi}{\partial \phi^{2}}
$$


## Basic equations:


$$
\nabla \times(\boldsymbol{f} \times \boldsymbol{g})=(\boldsymbol{g} \cdot \nabla) \boldsymbol{f}+(\nabla \cdot \boldsymbol{g}) \boldsymbol{f}-(\boldsymbol{f} \cdot \nabla) \boldsymbol{g}-(\nabla \cdot \boldsymbol{f}) \boldsymbol{g}
$$  

$$
\nabla(\boldsymbol{f} \cdot \boldsymbol{g})=\boldsymbol{f} \times(\boldsymbol{\nabla} \times \boldsymbol{g})+(\boldsymbol{f} \cdot \boldsymbol{\nabla}) \boldsymbol{g}+\boldsymbol{g} \times(\boldsymbol{\nabla} \times \boldsymbol{f})+(\boldsymbol{g} \cdot \boldsymbol{\nabla}) \boldsymbol{f}
$$  

$$
\nabla \cdot \nabla \varphi \equiv \nabla^{2} \varphi
$$

$$
\nabla(\varphi \psi)=\varphi \nabla \psi+\psi \nabla \varphi
$$

$$
\nabla \cdot(\varphi \boldsymbol{f})=(\nabla \varphi) \cdot \boldsymbol{f}+\varphi \nabla \cdot \boldsymbol{f}
$$

$$
\nabla \times(\varphi \boldsymbol{f})=(\nabla \varphi) \times \boldsymbol{f}+\varphi \nabla \times \boldsymbol{f}
$$

$$
\nabla \cdot(\boldsymbol{f} \times \boldsymbol{g})=(\nabla \times \boldsymbol{f}) \cdot \boldsymbol{g}-\boldsymbol{f} \cdot(\nabla \times \boldsymbol{g})
$$

<!-- 

```markdown 
$$
v_{r}
v_{\theta}
v_{\phi}
v_{x}
v_{y}
v_{z}
\hat{e_{x}}
\hat{e_{y}}
\hat{e_{z}}
\hat{e_{r}}
\hat{e_{\phi}}
\hat{e_{\theta}}
$$
``` -->

<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
