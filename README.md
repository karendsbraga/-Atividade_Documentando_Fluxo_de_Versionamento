#  Atividade: Documentando o Fluxo de Versionamento

## Sessão 1

Crie ou entre na sua conta no GitHub, após entrar no canto superior direito clique no **+** e crie um novo repositório (*new repository*). 

Coloque o nome do repositório, a descrição do projeto, a visibilidade em projeto público ou privado e por fim as configurações caso queira:
* **Add README**
* **Add .gitignore**
* **Add license**

Na proxima tela clique em cima da parte escrita *uploading an existing file*, adicione os arquivos, faça um commit e publique (*commit chances*).

---

## Sessão 2

O **README** explica o que o projeto faz, qual problema ele resolve, qual sua motivação em ter feito esse projeto, quais tecnologias foram usadas e como executá-lo na máquina. Ele é a porta de entrada quando acessa seu repositório podendo ser visto por recrutadores, outros programadores e etc.

* **Título:** O título direto deixa claro do que se trata o projeto.
* **Descrição do Projeto:** Explica qual problema o projeto resolve e para que foi feito. Ajuda o leitor a entender o projeto.
* **Tecnologias Utilizadas:** Mostra de forma rápida o que foi usado no projeto, assim recrutadores e outros desenvolvedores ficam sabendo quais as ferramentas você dominou para construí-lo.
* **Como Instalar:** Funciona como o manual de instrução, assim quem acessa o seu repositório consegue testar a aplicação na própria máquina.
* **Autor e Contato:** Mostra quem criou o projeto, abre portas para caso alguém queira dar alguma dica ou queixa sobre algo do projeto e facilita o contato de recrutadores ou parceiros interessados no seu trabalho.

#O Poder do Markdown: É um jeito muito fácil de formatar textos, você digita símbolos do teclado e ele transforma tudo em uma página organizada de informações no GitHub.

---

## Sessão 3

### GitHub Online
Ele serve para editar um arquivo do GitHub. É ótimo para correções rápidas e pequenas, como arrumar um erro de digitação sem precisar abrir o editor. Ele não é útil para o dia a dia. É ruim para mexer em vários arquivos ao mesmo tempo e não deixa você testar o código antes de salvar.

### Git via Linha de Comando (Terminal)
É o método tradicional feito diretamente por texto no terminal por comandos, o fluxo clássico tem três passos principais:

* `git status`: mostra o que foi modificado.
* `git add .` *(ou `git add arquivo.py`)*: escolhe o que entrará no próximo commit (a chamada área de preparação, ou *staging*).
* `git commit -m "mensagem clara"`: registra o retrato das mudanças localmente.
* `git push origin main`: envia para o GitHub.

Ele funciona em qualquer sistema operacional, é leve, não trava o computador e dá controle total para resolver problemas complexos que os programas normais não conseguem.

### IDEs (Ex: VS Code)
No VS Code, eu uso o painel **Source Control** (o ícone de ramificação na barra lateral esquerda, ou o atalho `Ctrl + Shift + G`), que faz tudo de forma visual, mostrando a lista de todos os arquivos que eu já editei, criei ou apaguei.

1. Clico no **+** ao lado do arquivo pra preparar a alteração.
2. Escrevo uma mensagem curta explicando o que fiz e clico em **Commit**.
3. Clico em **Sincronizar Alterações** pra mandar tudo pro GitHub.

Assim dá pra comparar o código antigo com o novo, lado a lado, antes de salvar. Assim eu confiro se não mexi em nada sem querer. Além disso, é rápido e não preciso decorar nenhum comando do terminal.

### GitHub Desktop
É um aplicativo feito só para mexer no Git de forma visual. Ao abrir, ele mostra à esquerda os arquivos modificados e à direita as diferenças linha por linha. O que tá em **verde** foi adicionado e o que tá em **vermelho** foi apagado. Dá para escolher quais arquivos entram em cada commit só clicando, mostra o histórico de commits e deixa trocar de branch de forma visual. Lembrando: ele não é um editor de código, ele só cuida do versionamento, então você ainda precisa de outro programa pra escrever o projeto.

### A Filosofia da Atualização
Atualizar o repositório aos poucos e não largar tudo no fim do mês, faz muita diferença. Commits pequenos deixam o histórico claro, facilitam achar erros, funcionam como backup e evitam conflitos. Já o envio único vira um commit gigante, difícil de entender e cheio de correria de última hora.
