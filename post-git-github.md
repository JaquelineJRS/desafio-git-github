- Introdução ao Git
  - O que é Git e sua importância
    - ajuda a controlar todas alterações de códigos utilizando o versionamento de código
- Navegação via command line interface e instalação
  - Comandos básicos para um bom desempenho no terminal
    - Command Line Interface (CLI) - CMD
      - dir = listar todas os diretórios listados na pasta
      - cd / = navegue até a pasta C:
      - cd.. = retorna um nível de pasta
      - cls = limpar o termina
      - mkdir = criar pasta
      - echo hello > hello.txt
      - a palavra echo usada neste contexto cria o arquivo dentro do diretório
      - del = deleta somente arquivos e não diretórios, se selecionar o diretório contendo arquivos dentro, será deletado somente o arquivo
      - rmdir = deleta todo o repositório e os arquivos
      - usando as flags /S /Q
      - flag /S é para deletar possíveis repositórios que exista dentro da pastas
      - flag /Q para não precisar confirmar a exclusão
- Entendendo como o Git funciona por baixo dos panos
  - Tópicos fundamentais para entender o funcionamento do Git
    - SHA1 - Secure Hash Algorithm
      - algoritmo de criptografia de 40 dígitos.
      ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/55d09929-76bc-4818-bf5e-0b50d82afa58/Untitled.png)
      openssl sha1 e o nome do arquivo, gera a criptografia
    - Objetos internos do Git
      - Objetos fundamentais

        - BLOBS(bolha) - contém meta-dados do git
          ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b5cd9899-1639-4ee1-a911-a823d262bae3/Untitled.png)
        - TREE(árvore) - aponta para as BLOBS
          ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/474b8870-e325-4670-831b-34eff594430b/Untitled.png)

      - COMMIT
        - aponta para uma árvore, um parente(último commit), um autor e a mensagem e o carimbo do tempo
        - também possui um SHA1 - criptografia
  - Chave SSH e Token
    - 1º criar a chave SSH na máquina usando o CLI
    - 2º informar a chave SSH no GitHub
    - 3º Ativar o “agente ssh” para informar a id da chave automaticamente a cada commit
- Primeiros comandos com Git
  - Primeiros comandos com Git
    - git init = inicia um novo repositório dentro do diretório
    - git add
    - git commit
- Ciclo de vida dos arquivos no Git
  - Passo a passo no ciclo de vida
  ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3dd404df-4cab-47a6-93d3-3fc6f9611dfb/Untitled.png)
- Introdução ao GitHub
- Resolvendo conflitos
- Comandos do git
  - git init = inicia um novo repositório
  - git add \*
  - git commit = subir as alterações

  - ls = lista todos os itens do diretório
  - -a = mostra todos os itens ocultos do diretório
  - git remot -v = lista os repostórios remotosg
  - git push origin master = atualizar o repositório após o commit no repositório remoto
