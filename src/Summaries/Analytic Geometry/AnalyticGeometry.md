
# Geometria Analítica

### Pontos e Retas
- Distância entre dois pontos: \\(d(A, B) = \sqrt{(B_x - A_x)^2 + (B_y - A_y)^2}\\)
- Ponto médio: \\(P_m = \left(\frac{X_1 + X_2}2, \frac{Y_1 + Y_2}2\right)\\)
- Baricentro de um triângulo: \\(B = \left( \frac{X_1+X_2+X_3}2, \frac{Y_1+Y_2+Y_3}2\right)\\)
- Condição de alinhamento de 3 pontos: \\( \begin{vmatrix}
    X_1 & Y_1 & 1 \\\\
    X_2 & Y_2 & 1 \\\\
    X_3 & Y_3 & 1 \end{vmatrix} = 0\\)
- Coeficiente angular da reta: \\(m = \frac{\Delta y}{\Delta x} = \tan(\alpha)\\)
- Equações de retas:
1. Equação fundamental da reta: \\(\Delta y = m\Delta x\\)
2. Equação geral da reta: \\(ax + by + c = 0\\)
3. \\(y = mx + n\\), sendo \\(n\\) o coeficiente linear (quando \\(x=0)\\)
4. \\(\frac{x}a + \frac{y}b = 1\\) sendo \\(a \\text{ e } b\\) o ponto que a reta intersecta o eixo das abscissas e ordenadas respectivamente
- Estudo das retas:
1. Se \\(m_1 = m_2\\): \\(r_1 \\text{ // } r_2\\), se \\(n_1 = n_2\\) então \\(r_1 = r_2\\)
2. Se \\(m_1 \neq m_2\\): \\(r_1 \\text { é concorrente a } r_2\\)
- Estudo da intersecção das retas:
1. Possível e determinado: retas concorrentes
2. Possível e inderterminado: paralelas coincidentes
3. Impossível: paralelas distintas
- Perpendicularidade: \\(r_1 \bot r_2 \Leftrightarrow m_1m_2=1\\)
- Distância ponto e reta: \\(d(P, r) = \frac{\vert aP_x+bP_y+c\vert}{\sqrt{a^2+b^2}}\\), sendo \\(ax+by+c=0\\) a equação da reta \\(r\\)
- Distância entre duas retas paralelas: \\(d(r, s) = \frac{\vert c_1 - c_2\vert}{\sqrt{a^2+b^2}}\\), sendo \\(c_1 \\text { e } c_2\\) os respectivos valores de \\(c\\) das equações da reta \\(r \\text { e } s\\)
- Área de um triângulo: \\(A_t = \frac{\vert D\vert}2 = \frac{\overline{BC}h}2\\), sendo \\( D = \begin{vmatrix}
    X_1 & Y_1 & 1 \\\\
    X_2 & Y_2 & 1 \\\\
    X_3 & Y_3 & 1\end{vmatrix}\\)

### Circunferências
Obs: Considere nas fórmulas abaixo as circunferências de centro \\(O(a, b)\\)
- Equações da circuferência:
1. Geral: \\(x^2 + y^2 -2ax  -2by + (a^2+b^2-r^2)=0\\)
2. Base: \\((x-a)^2 + (y-b)^2 = r^2\\)
- Posições relativas entre circunferências e retas:
1. Secante: \\(d(O, t) < r\\)
2. Tangente: \\(d(O, t) = r\\)
3. Exterior: \\(d(O, t) > r\\)

### Parábolas
- É o conjunto de pontos equidistantes de uma reta \\(d\\) e um ponto \\(F\\)
- \\(F\\) é o foco da parábola (\\(F \not \in d\\))
- \\(d\\) é a diretriz da parábola
- \\(V\\) é o vértice da parábol: \\(d(V, d) = d(V, F)\\)
- A reta \\(s\\) que passa pelo ponto \\(F\\) e é perpendicular à \\(d\\) é o eixo de simetria
- Equações (com vértice na origem):
1. \\(F(c, 0)\\): \\(y^2 = 4cx\\)
2. \\(F(-c, 0)\\): \\(y^2 = -4cx\\)
3. \\(F(0, c)\\): \\(x^2 = 4cy\\)
4. \\(F(0, -c)\\): \\(x^2 = -4cy\\)
- Equações (com vértice qualquer): 
1. Voltada à direita: \\((y-V_y) = 4c(x-V_x)\\) 
2. Voltada à esquerda: \\((y-V_y) = -4c(x-V_x)\\)
3. Voltada para cima: \\((x-V_x) = 4c(y-V_y)\\)
3. Voltada para baixo: \\((x-V_x) = -4c(y-V_y)\\)

### Elipse
- É o lugar geométrico dos pontos de um plano tais que a soma de suas distânicas a dois pontos fixos \\(F_1 \\text{ e } F_2\\), seja constante \\(k > d(F_1, F_2)\\)
- \\(F_1 \\text{ e } F_2\\) são os focos
- \\(d(F_1, F_2) = 2c\\) é a distância focal
- \\(\overline{A_1A_2}\\) é o eixo maior
- \\(\overline{B_1B_2}\\) é o eixo menor
- \\(O\\) é o centro da elipse e ponto médio de \\(\overline{F_1F_2}\\)
- \\(e=\frac{c}a, 0 < e < 1\\), se chama a excentricidade da elipse (próximo de 0 a elipse tende a uma circunferência; próximo de 1 a elipse tende a uma reta)
- Equações:
1. \\(b^2 = a^2-c^2\\)
2. \\(\overline{A_1A_2} \\text{ // } y\\): \\(\frac{(X-O_x)^2}{b^2} + \frac{(Y-O_y)^2}{a^2} = 1\\)
3. \\(\overline{A_1A_2} \\text{ // } x\\): \\(\frac{(X-O_x)^2}{a^2} + \frac{(Y-O_y)^2}{b^2} = 1\\)

### Hipérbole
- É o lugar geométrico dos pontos de um plano tais que a diferença em módulo de suas distâncias a dois pontos fixos, \\(F_1 \\text { e } F_2\\) é constante
- \\(F_1 \\text{ e } F_2\\) são os focos
- \\(d(F_1, F_2) = 2c\\) é a distância focal
- \\(A_1 \\text { e } A_2\\) são os vértices
- \\(d(A_1, A_2) = d(A_1, F_2) = d(A_2, A_1)\\)
- \\(e=\frac{c}a, 0 < e < 1\\) (próximo de 0 a hipérbole tende a duas semirretas opostas; próximo de 1 tende a duas retas paralelas)
- \\(\overline{B_1B_2}\\) é o eixo imaginário e mediatriz de \\(\overline{A_1A_2}\\)
- \\(\overline{A_1A_2}\\) é o eixo real
- \\(O\\) é o centro da hipérbole
- Equações:
1. \\(b^2 = a^2-c^2\\)
2. \\(\overline{A_1A_2} \\text{ // } x\\): \\(\frac{(X-O_x)^2}{a^2}-\frac{(Y-O_y)^2}{b^2} = 1\\)
3. \\(\overline{A_1A_2} \\text{ // } y\\): \\(\frac{(Y-O_y)^2}{a^2}-\frac{(X-O_x)^2}{b^2} = 1\\)
- Assíntotas:
1. \\(l_1 \\text{ e } l_2\\) são as assíntotas da hipérbole
2. \\(l_1\\): \\(bx-ay=0\\) ou \\(y = \frac{b}ax\\)
3. \\(l_2\\): \\(bx+ay=0\\) ou \\(y = -\frac{b}ax\\)
- Hipérbole equilátera: ocorre quando \\(b = a \Rightarrow l_1 \bot l_2\\)
