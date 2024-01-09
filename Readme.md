### Olá, esse projeto ensina a usar o git, seguindo as orientações de Rafaella Ballerini,como também outros sites, ajudando assim nas definições junto com o canal dela, assista a vídeo aula no link  logo abaixo:

## Comandos:
* git init: Crie um repositório Git vazio ou reinicialize um existente;
* git add: Adiciona o conteúdo do arquivo ao índice;
    Duas formas de usar o git add:
     git add nomedoarquivo
      Que adiciona esse arquivo que foi escrito
     git add .
      Que adiciona todos os arquivos.  
* git status: Mostra o status da árvore de trabalho;
* git commit -m "primeiro commit": Registra alterações no repositório;
* git branch -M "main": Para mudar a branch padrão "master" para "main";
* git remote add origin http://linkdorempositoriocriadonogithub.git: Para adicionar um repositório remoto:
    "remote": Uma conexão com o repositório local com o repositório do GitHub;
    "add": Para adicionar;
    "origin": Apelido, nome que está dando para o repositório do GitHub: Ou seja: faça essa conexão do repositório local com o repositório do GitHub, dando o nome de "origin".
* git push -u origin main: É geralmente executado para enviar as alterações locais para o repositório online. Configurando a branch remoto para rastrear sua branch local. Necessário para perimitir que sicronize sua branch local com o repoitório remoto usando o git pull.
    -u: Este parâmetro configura o branch remoto como o branch de rastreamento upstream. Isso significa que, no futuro, você pode usar git pull sem especificar o repositório ou o branch
* git push: Atualiza referências remotas junto com objetos associados;
* git checkout -b "nova branch": Para criar uma nova branch;
    "checkout": Sai da branch atual que você está, e indo para nova criada.
    OBS: Caso queira voltar para branch anterior digite git checkout main, caso a sua branch anterior for a main.
* git merge nova branch: Para unificar a branch nova com a antiga;
* git-pull: Busque e integre-se a outro repositório ou em um ramo local, Ou seja puxa tudo que tipo no repositório online para o local;

* git clone linkdorepositoquevocequerclonar.git: Para clonar um repositório;
* cd nome do local do arquivo a ser trabalhado: Comando utilizado para entrar dentro de uma pasta;
* clear: para limpar o terminal;
* pull request: Básicamente você faz um fork em um repositório, e faz alguma alteração e sugere essa alteração fazendo o pull request para o dono do repositório orginal.

Obs: O pull request é bom você assistir o vídeo dísponivel logo abaixa, que mostra passo como fazer o procedimento correto.

## Algumas definições:
* Um branch no Git é simplesmente um ponteiro móvel para um desses commits. O nome do branch padrão no Git é master. Conforme você começa a fazer commits, você recebe um branch master que aponta para o último commit que você fez. Cada vez que você faz um novo commit, ele avança automaticamente.

* Merge é o jeito do Git de unificar um histórico bifurcado. O comando git merge permite que você pegue as linhas de desenvolvimento independentes criadas pelo git branch e as integre em uma ramificação única.

* Markdown Syntax um conjunto de regras para formatação de texto na internet, usada em plataformas como o GitHub e o slack. São textos simples com implemetações especiais. como por exemplo #, * e ! para titulos, listas e textos itálicos e negrito como também inserir imagens. Tornando uma formatação de texto na web mais simples e padronizada.

Os arquivos .md são usados principalmente pelo Markdown para converter arquivos de texto em versões HTML para que os usuários possam produzir arquivos simples de ler e escrever.

## Bibliografia:
Disponível em: https://www.youtube.com/watch?v=UBAX-13g8OM&ab_channel=RafaellaBallerini. Acesso 08 de Jan. 2024.

Disponível em: https://git-scm.com/book/pt-br/v2/Branches-no-Git-Branches-em-poucas-palavras#:~:text=O%20nome%20do%20branch%20padr%C3%A3o,novo%20commit%2C%20ele%20avan%C3%A7a%20automaticamente.&text=O%20branch%20'%60%20master%20'',n%C3%A3o%20%C3%A9%20um%20branch%20especial. Acesso 08 de Jan. 2024.

Disponível em: https://docs.github.com/pt/get-started/using-git/pushing-commits-to-a-remote-repository. Acesso 08 de Jan. 2024.

Disponível em: https://stackoverflow.com/questions/5697750/what-exactly-does-the-u-do-git-push-u-origin-master-vs-git-push-origin-ma. Acesso 08 de Jan. 2024.

Disponível em: https://www.delftstack.com/howto/git/git-push-origin-master/. Acesso 08 de Jan. 2024.

Disponível em: https://dev.to/gabriellend/this-one-thing-helped-me-understand-git-commands-940. Acesso 08 de Jan. 2024.

Disponível em: https://www.atlassian.com/br/git/tutorials/using-branches/git-merge. Acesso 08 de Jan. 2024.

Disponível em: https://github.com/rafaballerini/GitTutorial?tab=readme-ov-file. Acesso 08 de Jan. 2024.

Disponível em: https://dev.to/guilhermemanzano/como-criar-um-readme-md-para-o-github-do-jeito-certo-2lgg. Acesso 09 de Jan. 2024.

Disponível em: https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open. Acesso 09 de Jan. 2024.

Disponível em: https://www.collectiveray.com/pt/extens%C3%A3o-de-arquivo-markdown-md. Acesso 09 de Jan. 2024.

Disponível em: https://ficheiros.com.br/extensao/md/. Acesso 09 de Jan. 2024.
