# Tarefa: Lista de Exercícios 1

## Equipe
- Gabriel Ponzoni

## Pré requisitos e dependências

- Sem dependências
- Windows x64
- Recomendada a leitura: 
  - https://learnopengl.com/#!Getting-started/Hello-Triangle
  - https://learnopengl.com/#!Getting-started/Shaders
  - http://antongerdelan.net/opengl/hellotriangle.html

## Questões teóricas:

1. O que é a GLSL? Quais os dois tipos de shaders são obrigatórios no pipeline programável da versão atual que trabalhamos em aula e o que eles processam?  
    >GLSL possui uma própria linguagem de programaçao que é a OpenGL Shading Language e ela serve para criarmos o Processamento dos Vertices e o Processamento de fragmentos 
2. O que são primitivas gráficas? Como fazemos o armazenamento dos vértices na OpenGL? 
    >Primitiva gráficas são a pista que dizemos ao programa para ele saber o que quer dizer os elementos contidos no vértex Data. Se for um triangulo usamos GL_TRIANGLES se for cordenadas de uma linha usamos GL_LINE_STRIP e por último podemos apenas ter uma coleção de pontos que seria o equivalente a GL_POINTS.
3. Explique o que é VBO e VAO, e como se relacionam (se achar mais fácil, pode fazer um gráfico representando a relação entre eles).  
    >Para enviar os dados para GPU precisamos usar um buffer 
4. Analise o código fonte do projeto Hello Triangle. Localize e relacione os conceitos de 
shaders, VBOs e VAO apresentados até então. Não precisa entregar nada neste exercício. 

## Questões sobre códigos:
5. Faça o desenho de 2 triângulos na tela. Desenhe eles:
   1. Apenas com o polígono preenchido 
   2. Apenas com contorno 
   3. Apenas como pontos
   4. Com as 3 formas de desenho juntas

6. Faça o desenho de um círculo na tela, utilizando a equação paramétrica do círculo para gerar os vértices. Depois disso: 
   1. Desenhe um octágono
   2. Desenhe um pentágono
   3. Desenhe um pac-man!
   4. Desenhe uma fatia de pizza
   5. DESAFIO: desenhe uma “estrela”

## Resultados e/ou telas de exemplo

> Exercicio 5.a:
> 
> ![image](Screenshot_1.jpg)
> 
> ```![image](imagem1.jpg)```
> 


## Comentários gerais

> Nesta seção você descreve alguma especificidade da tarefa, por exemplo:

Cada exercício da lista está implementado em um arquivo separado.

## Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas para as seguintes tarefas:

- [x] Tarefa 1
- [x] Tarefa 2
- [x] Tarefa 3
- [x] Tarefa 4
- [ ] Tarefa 5.i
- [ ] Tarefa 5.ii
- [ ] Tarefa 5.iii
- [ ] Tarefa 5.iv
- [ ] Tarefa 5.v


## Referências e/ou créditos
> Se seu projeto conter assets (imagens, sons etc) que necessitem de licença ou créditos
>
> Se seu projeto é um passo-a-passo de um tutorial, você pode referenciá-lo aqui
>
> Referências em geral que foram úteis para desenvolver o projeto
Para a elaboração deste template, usei como referências
 - [Documentação do Github sobre a linguagem de markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
 - [Este template de _iuricode_](https://github.com/iuricode/readme-template/blob/main/repositorio/exemplo-01.md)


## Licença

> Esse projeto NÃO está sob licença. 

> [!TIP]
> Você pode remover ou adicionar seções, de acordo com a necessidade
> 
> Sempre nomeie este arquivo de documentação para README.md e tenha um destes em cada diretório de projeto de tarefa. Assim, ao navegarmos pelo diretório, o texto deste documento aparecerá diretamente.