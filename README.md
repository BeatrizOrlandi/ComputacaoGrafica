# bcc327-comp-grafica - Atividades Interativas

Bem-vindo(a) ao repositório dos códigos das atividades de computação gráfica! Este projeto reúne os exercícios e projetos que exploram conceitos de gráficos interativos e animações 3D, utilizando tecnologias como WebGL, HTML5, CSS3, JavaScript e OpenGL/GLUT com C.

## Atividades Incluídas

- **atv1-bibliotecas-graficas.html**  
  Demonstração de aplicações gráficas utilizando diferentes bibliotecas e APIs.

- **atv2-grafica-interativa.html**  
  Projeto de gráficos interativos com manipulação em tempo real e eventos, utilizando WebGL.

- **atv3-transformacoes-geometricas.html**  
  Implementação de transformações geométricas (2D e 3D) e composição de transformações com WebGL.

- **atv4-teoria-cores.html**  
  Exercícios sobre teoria das cores, incluindo gradientes RGB e conversões entre modelos de cor (RGB, HSV e CMYK).

- **atv5-fundamentos-progGraf.html**  
  Fundamentos de programação gráfica: triângulo colorido com gradiente e movimentação de quadrado via teclado com WebGL.

- **labirinto.c**  
  Projeto em C com OpenGL/GLUT que implementa um labirinto 3D simples. A câmera é controlada pelas teclas W, A, S, D (para movimento) e pelas setas (para rotação), com colisão básica para impedir a passagem pelas paredes.

- **robot_animado.c**  
  Projeto em C com OpenGL/GLUT que implementa um robô com braço animado, utilizando hierarquia de transformações (com `glPushMatrix()`/`glPopMatrix()`) para simular o movimento do corpo, braço e antebraço.

## Visualização e Execução

### Versões Web
As atividades em HTML (atv1 a atv5) podem ser visualizadas diretamente em navegadores modernos.  
Você pode acessar a visualização online através do [GitHub Pages](https://beatrizorlandi.github.io/ComputacaoGrafica/) 

### Versões em C (OpenGL/GLUT)
Para as atividades desenvolvidas em C, será necessário compilar os arquivos em um ambiente compatível. Seguem exemplos de comandos para compilação:

```bash
# Compilando labirinto.c:
gcc labirinto.c -o labirinto -lGL -lGLU -lglut -lm

# Compilando robot_animado.c:
gcc robot_animado.c -o robot_animado -lGL -lGLU -lglut -lm
