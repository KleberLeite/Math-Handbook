
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
- \\(y - y_0 = m(x-x_0)\\), dado um ponto pertencente a reta \\(P(x_0, y_0)\\)
- \\(y = mx + n\\), \\(n\\) é o coeficiente linear obtido quando \\(x = 0\\)
- \\(\frac{x}a + \frac{y}b = 1\\), sendo \\(a\\) o ponto em que \\(y = 0\\) e \\(b\\) o ponto em que \\(x=0\\), com \\(a \\text{ e } b\neq 0\\)
- \\(ax+by+c=0\\), \\(m\\) pode ser obtido a partir de \\(m = \frac{-a}b\\)

#### Distância entre ponto e reta:
&nbsp;&nbsp;&nbsp;&nbsp;Dado uma reta \\(r\\) dada por \\(ax+by+c=0\\) e um ponto \\(P(P_x, P_y)\\):
\\[d_{P, r} = \frac{\vert aP_x+bP_y+c\vert}{\sqrt{a^2+b^2}}\\]

#### Intersecção de duas retas:
&nbsp;&nbsp;&nbsp;&nbsp;Dada duas retas \\(r: ax+by+c=0\\) e \\(s: dx+ey+f=0\\), o ponto de intersecção é o par ordenado \\((x, y)\\) que satisfazem as duas igualdades, ou seja, podemos resolver a intersecção de duas a partir de um sistema:
\\[
    \begin{cases}
        ax+by+c=0\\\\
        dx+ey+f=0
    \end{cases}
\\]

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

#### 2º)
Calcule as distâncias:
- \\(d_{AB}\\)
- \\(d_{JO}\\)
- \\(d_{GH}\\)
- \\(d_{FK}\\)
- \\(d_{PQ}\\)
- \\(d_{NO}\\)
- \\(d_{IJ}\\)
- \\(d_{AC}\\)

#### 3º)
Um ponto \\(A(a^2+4, -4a)\\) pertence a bissetriz dos quadrantes ímpares e a uma circuferência de centro \\(O(0, 0)\\), qual a área dessa circuferência?

#### 4º)
Defina as coordenadas do ponto D de um paralelogramo de vértices:
\\[A(4, 2) \quad B(0, -1) \quad C(1,1)\\]

#### 5º)
Defina as coordenadas do ponto \\(H\\) que é vértice da altura relativa ao lado AC de um triângulo isósceles de vértices:
\\[A(4,2) \quad B(3,0) \quad C(1,1)\\]

#### 6º)
Qual a projeção ortogonal do baricentro de uma forma prismática triangular regular de vértices no plano cartesiano na qual o prisma se encontra apoiado:
\\[A(3, 2, 1) \quad B(4, 0, 1) \quad C(1, 1, 1)\\]

#### 7º)
Defina uma relação para que um ponto \\(P(P_x, P_y)\\) pertença a uma reta que tem dois outros pontos:
\\[A(2, 2) \quad B(5, 3)\\]

#### 8º)
Defina a equação da reta suporte da altura relativa ao lado AB de vértices:
\\[A(5, 3) \quad B(2, 1) \quad C(3, 4)\\]

#### 9º)
Defina o comprimento da altura \\(H\\) relativa ao lado AB do triângulo:
\\[A(5, 3) \quad B(2, 1) \quad C(3, 4)\\]

#### 10º)
Sabendo que um triângulo de vértices:
\\[A(1, 1) \quad B(5, 2) \quad C(3, y)\\]
Possui área \\(3u\\) (sendo \\(u\\) unidade de área), defina \\(y\\).


### Resoluções
#### 1º)
<div align="center">

![Resolução Questão 1](../Images/Analytic%20Geometry/Solution-Question-1.png)
</div>

#### 2º)
- \\(d_{AB} = \sqrt{(1-(-3))^2 + (1-3)^2} = \sqrt{20} = 2\sqrt{5}\\)
- \\(d_{JO} = \sqrt{(-7-7)^2 +(4-(-2))^2} = \sqrt{232} = 2\sqrt{58}\\)
- \\(d_{GH} = \sqrt{(2-5)^2+(-4-(-5))^2} = \sqrt{10}\\)
- \\(d_{FK} = \sqrt{(-2-(-2))^2+(6-(-2))^2} = \sqrt{64} = 8\\)
- \\(d_{PQ} = \sqrt{(-4-(-1))^2+(-3-(-6))^2} = \sqrt{18} = 3\sqrt{2}\\)
- \\(d_{NO} = \sqrt{(7-7)^2+(2-(-2))^2} = \sqrt{4} = 2\\)
- \\(d_{IJ} = \sqrt{(-5-(-7))^2+(2-4)^2} = \sqrt{8} = 2\sqrt{2}\\)
- \\(d_{AC} = \sqrt{(1-7)^2+(1-7)^2} = \sqrt{72} = 6\sqrt{2}\\)

#### 3º)
- Para um ponto pertencer a diagonal dos quadrantes ímpares \\(x = y\\)

\\[a^2+4=-4a \Rightarrow a^2+4a+4=0\\]
\\[\sqrt{\Delta} = \sqrt{4^2-4⋅1⋅4} = 0\\]
\\[a = \frac{-4\pm0}2 = -2\\]
\\[r^2 = d_{AO}^2 = [((-2)^2+4)-0]^2 + [(-4⋅(-2))- 0]^2 = 128\\]
\\[A = 128\pi\\]

#### 4º)
<div align="center">

![Resolução Questão 4](../Images/Analytic%20Geometry/Solution-Question-4.png)
</div>

Obs: o ponto de intersecção das diagonais de um paralelogramo é o ponto médio das mesmas, utilize isso para achar \\(D(D_x, D_y)\\)
\\[M_x = \frac{4+1}2 = \frac52, \quad M_y = \frac{2+1}2 = \frac32\\]
\\[\frac52 = \frac{D_x+0}2 \Rightarrow D_x = 5, \quad \frac32 = \frac{D_y-1}2 \Rightarrow D_y = 4\\]

#### 5º)
Obs: a altura de um triângulo isósceles corta a base em seu ponto médio:
\\[M_x = \frac{4+1}2 = \frac52, \quad M_y = \frac{2+1}2 = \frac32\\]
\\[H\left(\frac52, \frac32\right)\\]

#### 6º)
Aplique a fórmula de baricentro de um triângulo
\\[B_x = \frac{3+4+1}3 = \frac83, \quad B_y = \frac{2+0+1}3 = 1\\]
\\[B\left(\frac83, 1, 0\right)\\]

#### 7º)
Utilize a ideia de pontos 3 pontos colineares para encontrar uma relação para \\(P(P_x, P_y)\\)
\\[
    \begin{vmatrix}
        x & y & 1\\\\
        2 & 2 & 1\\\\
        5 & 3 & 1\\\\
    \end{vmatrix} = 0
\\]
\\[\Rightarrow 2x+5y+6-3x-2y-10 = 0\\]
\\[\Rightarrow -x+3y-4 = 0
\\]

#### 8º)
Obs: a altura de um triãngulo faz com sua base um ângulo de 90º <br>
- Defina o coeficiente angular \\(m_{AB}\\) para então calcular \\(m_{HC}\\) utilizando a relação de perpendicularidade: \\(m_{HC}⋅m_{AB}=-1\\)
- Em posse de \\(m_{HC}\\) utilize a equação \\(y-C_y = m_{HC}(x-C_x)\\) e defina a equação da reta
\\[m_{AB} = \frac{3-1}{5-2} = \frac23\\]
\\[m_{HC}⋅m_{AB} = -1 \Leftrightarrow m_{HC} = \frac{-3}2\\]
\\[y-4 = \frac{-3}2(x-3) \Rightarrow 2y-8=-3x+9\\]
\\[\Rightarrow 3x+2y-17=0\\]

#### 9º)
- Defina a equação da reta suporte \\(\overline{AB}\\)
- Calcule a distância entre ponto e reta: \\(d_{C, \overline{AB}}\\)
\\[m_{AB} = \frac{3-1}{5-2} = \frac23\\]
\\[\overline{AB}: y-1 = \frac23(x-2) \Rightarrow 3y-3=2x-4\\]
\\[\overline{AB}: -2x+3y+1=0\\]
\\[d_{C, \overline{AB}} = \frac{\vert-2⋅3+3⋅4+1\vert}{\sqrt{(-2)^2+3^2}} = \frac7{\sqrt{13}}\\]

#### 10º)
Utilize a área de um triângulo por determinante para definir y:
\\[
    A = 
    \frac{\left \vert \begin{vmatrix}
        3 & y & 1\\\\
        1 & 1 & 1\\\\
        5 & 2 & 1\\\\
    \end{vmatrix} \right \vert}2 = 3 \Rightarrow \frac{\vert 3+5y+2-6-y-5\vert}2 = 3
\\]
\\[\frac{4y-6}2 = 3 \Rightarrow 4y=12 \Rightarrow y = 3\\]
