# Atividade Senai sobre GIT 💻
Uma atividade do Curso do Senai sobre versionamento de código usando git como repositório local e o github como repositório remoto

## Contexto 👨‍💻
Para resolver a situação-problema apresentada, você deve buscar uma solução para preservar o histórico de alterações do código-fonte do projeto, bem como realizar a conciliação de alterações em um mesmo repositório.

## Passos 📖
### Para isso, consulte o material digital e siga o seguinte passo a passo para utilizar uma ferramenta de versionamento de códigos:
1. Acessar o site https://git-scm.com/downd/win;
2. Instalar a ferramenta GIT;
3. Criar seu usuário e fornecer um endereço de e-mail;
4. Criar um repositório GIT local;
5. Criar um arquivo para ser alterado e rastreado;
6. Fazer seu cadastro no GitHub: https://github.com;
7. Criar um repositório on-line;
8. Criar um arquivo index.txt no repositório remoto para simular uma alteração feita por outro programador, elencando os principais comandos na sequência indicada a seguir, utilizados para gerenciar o versionamento de seu código e publicar no repositório remoto:
   * git status
   * git add
   * git commit
   * git push
   * git checkout
   * git merge
   * git pull
   * git remote

* Criar um arquivo index.txt no repositório local, copiar e colar as linhas de código indicadas abaixo:
```
<HTML>
<HEAD><TITLE>ATIVIDADE DE VERSIONAMENTO</TITLE></HEAD>
<BODY>
   <H1> TÍTULO1 </H1>
</BODY>
</HTML>
```
* Publicar seu arquivo na branch main;
* Criar uma nova branch, chamada feature1;
* Na branch feature1, publicar o mesmo arquivo;
### Realizar seguinte alteração na linha h1 do arquivo da branch main:
```
<HTML>
<HEAD><TITLE>ATIVIDADE DE VERSIONAMENTO</TITLE></HEAD>
<BODY>
    <H1> VERSIONAMENTO </H1>
</BODY>
</HTML>
```

### Realizar seguinte alteração na linha h1 do arquivo da branch feature1:
```
<HTML>
<HEAD><TITLE>ATIVIDADE DE VERSIONAMENTO</TITLE></HEAD>
<BODY>
   <H1> GIT </H1>
</BODY>
</HTML>
```

* Realizar o merge da branch feature1 com a branch main;
* Resolver os conflitos apresentados.
