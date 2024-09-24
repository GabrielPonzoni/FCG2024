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
> ![Screenshot_1](https://github.com/user-attachments/assets/a915c998-219d-4ce5-b479-c9bd073b29d8)
> 

> Exercicio 5.b:
> 
> ![Screenshot_2](https://github.com/user-attachments/assets/ac92a628-1db8-4a68-ba42-d0b90e9d537c)
>

> Exercicio 5.c:
> 
> ![Screenshot_3](https://github.com/user-attachments/assets/1ea245c4-4ac5-470a-af1f-246f7c9af504)
>

> Exercicio 5.d:
> 
> ![Screenshot_4](https://github.com/user-attachments/assets/e56d8c08-6c49-476e-8372-c18f3f29f69e)
>
---

> Exercicio 6.a:
> 
> ![Screenshot_6](https://github.com/user-attachments/assets/73fec4ec-be7c-4cbe-8251-cfe2ae44533b)


> Exercicio 6.a:
> 
> ![Screenshot_7](https://github.com/user-attachments/assets/2a62cfa8-f25b-4c09-8d92-05851b280932)



> Exercicio 6.b:
>
> ![Screenshot_8](https://github.com/user-attachments/assets/4d3f0bb2-bab2-455e-9ce5-16e0376f6649)


> Exercicio 6.c:
>
> ![Screenshot_5](https://github.com/user-attachments/assets/9acabf78-30ef-437a-8ad1-ef1197216c0f)


> Exercicio 6.d:
>
> ![Screenshot_9](https://github.com/user-attachments/assets/04284a38-48db-40f4-a3b4-455c45e58241)


> Exercicio 6.e:
> 
---

> Exercicio 7:
> 
>![Screenshot_10](https://github.com/user-attachments/assets/380673cb-6aea-4b7d-a27f-187b98bd57dc)
---

> Exercicio 8:
> 
>![Screenshot_11](https://github.com/user-attachments/assets/52c1d147-3c70-4adf-9d4b-c3c4500e34ed)
---

> Exercicio 9:
> 
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
- [x] Tarefa 5.i
- [x] Tarefa 5.ii
- [x] Tarefa 5.iii
- [x] Tarefa 5.iv
- [x] Tarefa 5.v
- [x] Tarefa 6.i
- [x] Tarefa 6.ii
- [x] Tarefa 6.iii
- [x] Tarefa 6.iv
- [x] Tarefa 6.v
- [ ] Tarefa 6.vi
- [x] Tarefa 7
- [x] Tarefa 8
- [ ] Tarefa 9


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
