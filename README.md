# DIO | Resumos Git e GitHub

Repositorio para armazenar resumos sobre Git e GitHub do curso de Versionamento de Código com Git e GitHub da [Digital Innovation One](https://www.dio.me/).


## Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/) 


## Resumos das aulas
| Aulas | Resumos |
|-------|---------|
| Criando e Clonando Reposiptórios | [Link da Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/a377a00b-461c-4ab0-8258-3addd2fef14c?back=/track/coding-future-banco-pan-desenvolvimento-frontend-com-angular&tab=undefined&moduleId=undefined)
| Salvando alterações no Repositório Local | [Link da Aula](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/coding-future-banco-pan-desenvolvimento-frontend-com-angular&tab=undefined&moduleId=undefined)


## Comandos mais usados
Para criar um repositório local:
````
mkdir nomeExemplo 
````
Para inicializar a pasta como repositório:
````
git init 
````
Conectar repositório local com repositório remoto:
````
- git remote add origin https://github.com/lucasbrito13/dio-resumos-git-e-github

- git branch -M main

- gitpush -u origin main
````
Adiciona arquivo(os) para área de preparação do commit
````
git add README.md (especificando o arquivo)

git add . (o ponto indica que vai adicionar todos os arquivos para área de preparação do commit)
````
Remover arquivos da área de preparação do commit
````
Existem duas formas, e as duas tem os mesmo resultado:

git reset resumos/aula-01.md

git restore --staged resumos/aula-02.md
````

## Referencias 
- [Digital Innovation One](https://www.dio.me/).
