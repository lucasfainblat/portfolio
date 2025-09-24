# Aulas Trilha DEV

🔗[Curso](https://trilhadev.planejamento.mg.gov.br)
🐈‍⬛ [Repositório do curso](https://github.com/splor-mg/trilha-dev)

# Plano de Aula
- [Dia 01: Começando com o pé direito](https://trilhadev.planejamento.mg.gov.br/aulas/dia_01/dia_01/)
- [Dia 02: Ambiente de desenvolvimento](https://trilhadev.planejamento.mg.gov.br/aulas/dia_02/dia_02/)
- [Dia 03: Lendo e Escrevendo](https://trilhadev.planejamento.mg.gov.br/aulas/dia_03/dia_03/)
- [Dia 04: Comandos e terminal](https://trilhadev.planejamento.mg.gov.br/aulas/dia_04/dia_04/)
- [Dia 05: Trabalhando em equipe de forma aberta](https://trilhadev.planejamento.mg.gov.br/aulas/dia_05/dia_05/)
- [Dia 06: Trabalhando em equipe com segurança](https://trilhadev.planejamento.mg.gov.br/aulas/dia_06/dia_06/)

---

# Aula 1 - Doc as code
🔗[Youtube](https://www.youtube.com/watch?v=6eqhA2mSYUw&t=18s)
## Notas
- Documentos como código
	- Todos trabalham sobre o mesmo documento, sem precisar de mil "versões finais"
	- Controle absoluto de versões e alterações
	- Poderosas ferramentas de edição e colaboração
	- Registro integral de acessos e edições
	- Automatização da publicação

| Tradicional          | Doc as code                         |
| -------------------- | ----------------------------------- |
| Word                 | Markdown com versionamento          |
| arquivo_vf3_oc       | Histórico automático via git        |
| Aprovação por e-mail | Aprovação por Pull Request          |
| Documentos locais    | Documentação online                 |
| Histórico manipulado | Linha do tempo de todas as mudanças |

---

# Aula 2 - Git e Github
🔗[Youtube](https://www.youtube.com/watch?v=XUpwmoOENCE)

## Notas
| **Git**                    | **GitHub**                   |
| -------------------------- | ---------------------------- |
| Guarda as versões          | Guarda os projetos na nuvem  |
| Funciona no seu computador | Funciona pela internet       |
| É a tecnologia             | É a plataforma que usa o Git |
### Git
- Guarda versões de um projeto
- Permite "navegar" por versões, como se fosse uma função "desfazer" absoluta
- /pasta_do_projeto/.git/

### GitHub
- Plataforma em nuvem para publicar projetos em formato .git
- Organização dos projetos em repositórios

---
# Aula 3 - O que é um repositório?
🔗[Youtube](https://www.youtube.com/watch?v=p3cy-1Gw4kA)

## Notas
- Repositórios servem para organizar projetos
- Criado o repositório [lucas_projetos](https://github.com/lucasfainblat/lucas_projetos)

---
# Aula 4 - Ambiente de desenvolvimento
🔗[Youtube](https://www.youtube.com/watch?v=Vljlms92iJI)
## Notas
- VSCode: editor de texto para programação
- Terminal: rodar linhas de comando

---

# Aula 5 - Usando o codespace
🔗[Youtube](https://www.youtube.com/watch?v=rsQLVpAIUO8)
## Notas
- Codespace: terminal e editor de texto nativos do GitHub
- Aberto o codespace do repositório [lucas_projetos](https://github.com/lucasfainblat/lucas_projetos) e rodado o primeiro comando python:
	- `print("Olá, mundo! 😘")`

---

# Aula 6 - Escolhendo a ferramenta
🔗[Youtube](https://www.youtube.com/watch?v=dwaT7cVrS4o)

## Notas
- Utilização da ferramenta [MKDOCS](https://www.mkdocs.org/) ([Material for MKDOCS](https://squidfunk.github.io/mkdocs-material/))
- Atividade:
	- https://co-cddo.github.io/ukgov-metadata-exchange-model
	- https://ministryofjustice.github.io/mkdocs-tech-docs-template

---

# Aula 7 - Documentação é tudo!
🔗[Youtube](www.youtube.com/watch?v=28y9wegXVAs&embeds_referring_euri=https%3A%2F%2Ftrilhadev.planejamento.mg.gov.br%2F&source_ve_path=OTY3MTQ)

## Notas
- Instalamos o poetry e o mkdocs, gerando uma versão preliminar da página e rodando localmente.


---

# Aula 8 - Sintaxe markdown
🔗[Youtube](https://www.youtube.com/embed/SOXWdGwV8t4)

## Notas
- Sintaxe já conhecida.
	- ###### Títulos
	- **Textos em negrito**
	- *Itálico*
	- Listas
		1. Numeradas
	- [links](https://www.youtube.com/embed/SOXWdGwV8t4)
	- ![imagens](https://www.galodigital.com.br/w/images/thumb/e/eb/Escudo_do_Galo_1950.jpg/250px-Escudo_do_Galo_1950.jpg)
	- `código`
	- ```
	  Bloco de código
	  ```
	  > citação
	  
	  

| Tabela | Exemplo | Etc |
| ------ | ------- | --- |
| Item   | Texto   |     |

# Aula extra - material for MkDocs
🔗[Youtube](https://www.youtube.com/watch?v=k9InxkOOxwg&t=1s)

# Dia 4: comandos e terminal
🔗 [Link no curso](https://trilhadev.planejamento.mg.gov.br/aulas/dia_04/dia_04/)

## Aula 09: Falando várias línguas
🔗 [Vídeo da Aula 09](https://www.youtube.com/watch?v=UWptjGLSuVg)

## Aula 10: Comandos de terminal
🔗 [Vídeo da Aula 10](https://www.youtube.com/watch?v=UZR13IQBYB4)

### ✍🏻 Anotações

| Comando | O que faz                                   | Exemplo         |
|---------|---------------------------------------------|-----------------|
| pwd     | Mostra o caminho completo do diretório atual| pwd             |
| ls      | Lista os arquivos e pastas                  | ls -la             |
| cd ..    | Volta para a pasta anterior                 | cd ..            |
| cd      | Entra em um diretório                       | cd blog         |
| mkdir   | Cria uma nova pasta                         | mkdir blog      |
| touch   | Cria um novo arquivo                        | touch post1.md  |
| rm      | Remove arquivos ou pastas                   | rm -rf arquivo.md  |

- Comandos --help trazem a documentação sobre o respectivo comando.
   - `Man comando` dá o manual do `comando`. Pressionar `q`pra sair.
Mais comandos:

| Comando | Função                                         | Exemplo de uso            |
|---------|------------------------------------------------|---------------------------|
| ls      | Lista arquivos e diretórios                    | ls -l                     |
| pwd     | Mostra o caminho do diretório atual            | pwd                       |
| cd      | Muda o diretório atual                         | cd /home/usuário          |
| mkdir   | Cria um novo diretório                         | mkdir projetos            |
| rmdir   | Remove um diretório vazio                      | rmdir antigo              |
| rm      | Remove arquivos ou diretórios                  | rm arquivo.txt            |
| cp      | Copia arquivos ou diretórios                   | cp arquivo.txt backup/    |
| mv      | Move ou renomeia arquivos e diretórios         | mv arquivo.txt docs/      |
| touch   | Cria um arquivo vazio ou atualiza timestamp    | touch novo.txt            |
| cat     | Exibe o conteúdo de um arquivo                 | cat texto.txt             |
| echo    | Exibe texto ou variáveis no terminal           | echo "Olá, mundo!"        |
| man     | Mostra o manual de um comando                  | man ls                    |
| clear   | Limpa a tela do terminal                       | clear                     |
| uname   | Mostra informações do sistema                  | uname -a                  |
| whoami  | Mostra o usuário logado                        | whoami                    |

---

## Aula 11: Comandos Git
🔗 [Vídeo](https://www.youtube.com/watch?v=KiV-_U4JKEs)

### ✍🏻 Anotações

| Status                   | Significado                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Untracked                | Arquivo novo que o Git ainda não monitora. Use git add para começar a rastrear. |
| Modified                 | Arquivo já conhecido pelo Git, mas que foi alterado. Ainda não pronto para salvar. |
| Staged / Ready to commit | Arquivo marcado com git add para ser incluído no próximo "snapshot".        |
