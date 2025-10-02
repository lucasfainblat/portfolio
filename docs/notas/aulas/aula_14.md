# Aula 14: branch e pull request
🔗 [Vídeo](https://www.youtube.com/watch?v=YMHB0n4xezs)

## Notas
- Atividade no [blog](/docs/blog/posts/01_aula14.md)
- `Branch` é um "ramo" de versionamento que poderá ser mesclado ao tronco principal (main branch).
- `Pull request` é justamente a requisição para que o `branch` trabalhado seja unido ao `main branch`.
- A vantagem desses mecanismos é o trabalho colaborativo assíncrono, porém totalmente versionado.

## Criando um novo branch
Para criar o branch:

```git checkout -b post-blog```

O [post do blog](/docs/blog/posts/01_aula14.md) já foi criado.

Depois de git add e git commit (citando o issue [#2](https://github.com/lucasfainblat/portfolio/issues/2)):

```git push origin post-blog```

## Criando um pull request
Na página do repositório, surge um aviso com um botão para "criar um pull request".

Dá para cadastrar um revisor ao `pull request`. Na página do `pull request` o próprio github sinaliza se há algum conflito com o main branch.

Na próxima aula, faremos a revisão e a mesclagem.