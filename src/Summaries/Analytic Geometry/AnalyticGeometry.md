
# Geometria Analítica

## Plano Cartesiano

### Definição:
&nbsp;&nbsp;O plano cartesiano pode ser construído a partir de duas retas \\(x\\) (abscissa) e \\(y\\) (ordenada) perpendiculares entre si. O ponto de intersecção será chamado de origem, normalmente simbolizado por \\(O\\). Definido o plano é possível identificar qualquer ponto \\(P\\), representado por um par ordenado \\(P(x, y)\\).

#### Quadrantes:
&nbsp;&nbsp;A intersecção do plano cria quatro regiões chamadas quadrantes (representados por 1ºq, por exemplo), definidos pelas seguintes relações:
- 1ºq: \\(x > 0\\) e \\(y > 0 \\)
- 2ºq: \\(x < 0\\) e \\(y > 0 \\)
- 3ºq: \\(x < 0\\) e \\(y < 0 \\)
- 4ºq: \\(x > 0\\) e \\(y < 0 \\)

#### Bissetrizes:
&nbsp;&nbsp;O plano nos permite desenhar duas bissetrizes, a dos quadrantes ímpares (1ºq e 3ºq), com relação \\(x = y\\) e a dos quadrantes pares (2ºq e 4ºq), com relação \\(x = -y\\).

#### Distância entre dois pontos:
&nbsp;&nbsp;Dado dois pontos \\(A\\) e \\(B\\) quaisquer podemos obter a distância \\(d_{AB}\\) por meio do Teorema de Pitágoras ou como sendo:
\\[d_{AB} = \sqrt{(A_x-B_x)^2+(A_y-B_y)^2}\\]

<div align="center">

![Distância entre Pontos](../Images/Analytic%20Geometry/PointsDistance.png)
</div>

#### Ponto médio:
&nbsp;&nbsp;É o ponto \\(C\\) pertencente a reta suporte \\(AB\\) tal que \\(d_{AC} = d_{CB}\\), suas coordenadas podem ser obtidas da seguinte maneira:
\\[M\left(\frac{A_x+B_x}2, \frac{A_y+B_y}2\right)\\]

#### Baricentro de um triângulo:
&nbsp;&nbsp;É o ponto de intersecção das alturas relativas de seus lados, pode ser obtido da seguinte maneira:
\\[H\left(\frac{A_x+B_x+C_x}3, \frac{A_y+B_y+C_y}3\right)\\]

#### Condição de alinhamento de 3 pontos:
&nbsp;&nbsp;Quando 3 pontos pertencem a mesma reta, ou seja, são colineares, eles são soluções da equação da reta. Dado 3 pontos colineares \\(A, B, C\\):
\\[
    \begin{vmatrix}
    A_x & A_y & 1 \\\\
    B_x & B_y & 1 \\\\
    C_x & C_y & 1
    \end{vmatrix} = 0
\\]

#### Área de um triângulo a partir de seus pontos:
&nbsp;&nbsp;Podemos descobrir a área de um triângulo a partir dos seus pontos:
\\[
    A = \frac{\vert D\vert}2, \\text{ sendo } D = \begin{vmatrix}
    A_x & A_y & 1 \\\\
    B_x & B_y & 1 \\\\
    C_x & C_y & 1
    \end{vmatrix}
\\]

#### Retas:
##### Coeficiente linear:
&nbsp;&nbsp;&nbsp;&nbsp;Indica a inclinação da reta em relação ao eixo \\(x\\) e pode ser obtido por \\(m = \tan(\theta) = \frac{\Delta y}{\Delta x}\\)
- Se \\(m_1 = m_2\\), então as retas são paralelas
- Se \\(m_1 \neq m_2\\), então as retas são concorrentes
- Se \\(m_1⋅m_2 = -1\\), então as retas são perpendiculares entre si

##### Equações de reta:
- \\(y - y_0 = m(x-x_0)\\)
- \\(y = mx + n\\), \\(n\\) é o coeficiente linear obtido quando \\(x = 0\\)
- \\(\frac{x}a + \frac{y}b = 1\\), sendo \\(a\\) o ponto em que \\(y = 0\\) e \\(b\\) o ponto em que \\(x=0\\)
- \\(ax+by+c=0\\), \\(m\\) pode ser obtido a partir de \\(m = \frac{-a}b\\)

#### Distância entre ponto e reta:
&nbsp;&nbsp;Dado uma reta \\(r\\) dada por \\(ax+by+c=0\\) e um ponto \\(P(P_x, P_y)\\):
\\[d_{Ar} = \frac{\vert aP_x+bP_y+c\vert}{\sqrt{a^2+b^2}}\\]

### Questões:
#### 1º)
Identifique no plano os seguintes pontos e indique quais pertences as bissetrizes:

<div align="center">

![Plano Cartesiano](../Images/Analytic%20Geometry/Question-1.png)
</div>

\\[A(1,1) \quad B(-3, 3)\quad C(7, 7) \quad D(3, -1) \quad E(-6,-5)\\]
\\[F(-2, 6) \quad G(2, -4) \quad H(5,-5) \quad I(-5, 2) \quad J(-7,4)\\]
\\[K(-2,-2) \quad L(2, 4) \quad M(6, 3) \quad N(7,2) \quad O(7,-2)\\]
\\[P(-4,-3) \quad Q(-1, -6)\\]

#### 2)
Calcule as distâncias:
- \\(d_{AB}\\)
- \\(d_{JO}\\)
- \\(d_{GH}\\)
- \\(d_{FK}\\)
- \\(d_{PQ}\\)
- \\(d_{NO}\\)
- \\(d_{IJ}\\)
- \\(d_{AC}\\)

#### 3)
Um ponto \\(A(a^2+4, 4a)\\) pertence a bissetriz dos quadrantes ímpares e a uma circuferência de centro \\(O(0, 0)\\), qual a área dessa circuferência?

#### 4)
Defina as coordenadas do ponto D de um paralelogramo de vértices:
\\[A(4, 2) \quad B(0, -1) \quad C(1,1)\\]

#### 5)
Defina as coordenadas do ponto \\(H\\) que é vértice da altura relativa ao lado AC de um triângulo isósceles de vértices:
\\[A(4,2) \quad B(3,0) \quad C(1,1)\\]

#### 6)
Qual a projeção ortogonal do centro de massa de uma forma prismática triangular regular de vértices:
\\[A(3, 2, 1) \quad B(4, 0, 1) \quad C(1, 1, 1)\\]

#### 7)
Defina uma relação para que um ponto \\(P(P_x, P_y)\\) pertença a uma reta que tem dois outros pontos:
\\[A(2, 2) \quad B(5, 3)\\]

#### 8)
Defina a equação da reta suporte da altura relativa ao lado AB de vértices:
\\[A(5, 3) \quad B(2, 1) \quad C(3, 4)\\]

#### 9)
Defina o comprimento da altura \\(H\\) relativa ao lado AB do triângulo:
\\[A(5, 3) \quad B(2, 1) \quad C(3, 4)\\]

#### 10)
Sabendo que um triângulo de vértices:
\\[A(1, 1) \quad B(5, 2) \quad C(3, y)\\]
Possui área \\(3u\\) (sendo \\(u\\) unidade de área), defina \\(y\\).
