---
toc_depth: 4
---

# Aula 11: Comandos Git
🔗 [Vídeo](https://www.youtube.com/watch?v=KiV-_U4JKEs)

## Anotações

| Status                   | Significado                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Untracked                | Arquivo novo que o Git ainda não monitora. Use git add para começar a rastrear. |
| Modified                 | Arquivo já conhecido pelo Git, mas que foi alterado. Ainda não pronto para salvar. |
| Staged / Ready to commit | Arquivo marcado com git add para ser incluído no próximo "snapshot".        |

### Git: lista de comandos

- `git init`: inicia o git no repositório
- `git status`: retorna status do commit atual (changes not staged; untracked...)
- `git add <../pasta/arquivo.extensão>`: marca arquivo para "foto" do git
- `git commit`: "sobe" a foto atual
- `git commit -m "<mensagem de commit>"`: parâmetro pra já inserir "o que foi feito naquele commit"
- `git log`: mostra os commits atuais, quem fez, o que foi feito, seus códigos etc. Para sair, pressionar `q`
- `gitlog --oneline`: mostra os commits com hashs e uma linha
- `git push origin main`: "sobe" as alterações pro <origin main> (github, main branch)
- `git pull origin main`: "baixa" as alterações do último push pra sua máquina virtual. Assim você garante estar trabalhando sobre a versão mais atual do projeto.
- `git checkout <hash>`: movimenta-se até o projeto à altura sinalizada pelo identificador <hash>
- `git switch <branch>`: muda de "ramo", permitindo navegar entre versões ativas do projeto.
- `git switch -c <nome do branch>`: cria um ramo para "ativar" a versão <hash> que está sendo visitada

> **💡Dica 1!** Faça _commits_ para mudanças pequenas, ou seja, que sejam inteligíveis no log.


> **💡Dica 2!** Comece sempre com `git status` pra identificar se há alterações não trackeadas, mudanças não mapeadas etc. Quando "working tree clean", pode-se começar a trabalhar. Aí o próximo passo é dar um `git pull <origin> <branch>` pra começar a trabalhar do lugar certo. Finalmente, ao fazer as alterações desejadas, aí sim você dá um `git add <arquivo.ext>` pra avisar o git deve monitorar aquilo, um `git commit` pra subir o arquivo pra versão atual, um `git push` para jogar na nuvem pros colegas colaborarem depois.

## Receitinha de bolo pro Git
1. `git status`: identificar alterações não acompanhadas, mudanças não mapeadas, etc. Só começar a trabalhar quando "_working tree clean_".
2. `git pull <origin> <branch>`: puxar a versão mais atual para trabalhar sobre ela.
3. Fazer as alterações desejadas e, só depois, `git add <arquivo.extensão>`, para avisar ao git que monitore.
4. `git commit -m "mensagem de alteração"` para expor o que foi alterado.
5. `git push <origin> <branch>` para enviar ao github.

