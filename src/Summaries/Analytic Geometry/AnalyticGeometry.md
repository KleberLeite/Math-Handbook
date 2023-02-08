
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