# Aula 15 Extra: Batalha de Commits
🔗 [Vídeo](https://www.youtube.com/watch?v=WpwmrbD4oTU)

## Notas
A ideia é fazer dois commits diferentes e, depois, decidir quais alterações vão prevalecer.

Para isso:

- Abrir uma nova branch
- Alterar página
- Ligar servidor para verificar se a mudança ficou perfeita
- Comitar
- Push
- Aprovar a pull request fazendo o merge
- Quem ficar por último vai gerar uma versão conflitante que deverá ser resolvida, o que por sua vez constitui o teor da aula

No campo de commits, o github aponta que há conflito e disponibiliza um botão de "resolver conflito". Ao acessá-lo, o arquivo conflitante mostra "como estava" e "como está ficando", pedindo que o usuário revisor decida.

A boa prática é bater um papo com quem fez "o outro lado do conflito" para decidir, com transparência intraequipe, o que vai prevalecer. Daí basta apagar o código e "marcar como resolvido". A partir daí, o `main branch` vai entender que o arquivo conflitante que deve prevalecer é aquele que foi editado na resolução do conflito.