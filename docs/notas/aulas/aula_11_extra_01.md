# Aula 11: Extra 01 - Vamos fazer uma viagem no tempo?
🔗 [Vídeo](https://www.youtube.com/watch?v=61w4GrbLPcQ&t=1s)

## Anotações
A vantagem do git é voltar a versões anteriores ou aproveitar conteúdos previamente sobrescritos. Basta clicar em "commits" na página do repositório para consultar a linha do tempo.

![imagem](/apoio/image.png)

As mensagens de commit são listadas juntamente com as alterações feitas. No canto direito ao lado de cada alteração, há uma `hash de commit`, um identificador alfanumérico que permite especificar cada "fotografia" tirada do projeto. Esse identificador nos permite "visitar" o projeto exatamente àquela altura.

![alt text](/apoio/image2.png)

Com o comando `git checkout <hash>`, é possível "viajar no tempo" até a altura especificada do projeto. É possível criar um novo `branch`, um "ramo de tempo _ativo_", para essa versão. Utiliza-se para esse fim: `git switch -c <nome do branch>`. Para retornar sem modificações ao `main branch`, basta comandar `git switch main`.