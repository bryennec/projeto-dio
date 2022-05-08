# projeto-dio
## First Project DIO

SHA 1: 	Secure Hash Algoritm

- Algoritmo de encriptação:

Conjunto de funções hash cripto projetada pela NSA (Segurança Nacional)

Encriptografia gera conjunto de caracteres indentificador de 40 dígitos.



#### CRIANDO/VIZUALIZANDO CHAVE SSH GITHUB:

- git bash >
  - ssh-keygen -t ed25519 -C    +   e-mailgithub
    - digitar senha: ...

- MOSTRAR EM QUAL PASTA ESTÁ:
  - pwd (caminho completo)
- NAVEGAR PELA PASTA SENHA:
  - cd /c/Users/Máquina/ .ssh/
- VISUALIZAR CONTEÚDO DA PASTA:
  - cat id_ed25519.pub (chave pública p/ github)

- INICIALIZAR SSH AGENT:

  - Entidade que pega as chaves e fica encarregada de lidar com elas.
  - eval $(ssh-agent -s)

- PASSAR A CHAVE PARA O GITHUB:

  - ssh-add id_ed25519 + chave privada

  

  ## CRIAR PASTA/REPOSITÓRIO:

  - CRIAR PASTA DENTRO DE OUTRA:
    - mkdir  +  nome-pasta
  - ENTRAR NA PASTA:
    - cd   + nome-pasta/
  - VOLTAR UMA PASTA:
    - cd ..
  - VISUALIZAR PASTAS OCULTAS:
    - ls -a 
  - VIZUALIZAR PASTAS:
    - ls ou dir
  - INICIALIZAR REPOSITORIO ATRAVÉS DO GIT:
    - git init

  - CLONAR O REPOSITÓRIO
  - criar repositório no github
  - git clone + link repsitório
  - cd + nome repositório
  - ENVIAR PARA REMOTO:
    - git add . 
    - git commit -m "inclusão de anotacões"
    - git status
    - git push origin main

  ## CRIANDO ARQUIVO/COMMIT:

  - CONFIG:

  - INFORMANDO O E-MAIL/ USUÁRIO:
    - git config --global user.email "email
    - git config --global user.name usuário

  

  - COMMIT INICIAL:
    - git add .
    - git commit -m "anotação de sua preferência"

  
