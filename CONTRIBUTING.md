## Como contribuir?

* Se você for um colaborador externo, dê um fork no projeto
* Issues só poderão ser criadas com os [templates](https://github.com/fga-eps-mds/2018.2-CarDefense/tree/master/.github/ISSUE_TEMPLATE) especificados no repositório
* A criação de branches deve seguir a política de branches
* No desenvolvimento usar nossa política de commits
* Pull requests só serão aceitos se estiverem com o [template](https://github.com/fga-eps-mds/2018.2-CarDefense/blob/master/PULL_REQUEST_TEMPLATE.md) especificado no repositório.

## Política de branches

Nossa política segue algumas características do Gitflow. Então separamos nossas branches em:

### *master*

A master será nossa branch de produção, ou seja, nela estará a versão estável do projeto. E por questões de segurança ela será bloqueada para commits e push. A interação com a master vai se dá através da de Pull requests que virão da branch **devel**.

### *devel*

A devel será nossa branch de desenvolvimento, ou seja, vai agrupar o trabalho vindo das branches de features, o objetivo é criar uma release que será submetida para **master**. 

### *branches de features*

As branches de features são criadas a partir da **devel**, e serve para o desenvolvimento de features presentes nas issues do repositório. No final do desenvolvimento a funcionalidade desenvolvida nessa branch deve ser enviada para a **devel**, através de um pull request.

Nomenclatura das branches de features:
	O nome das branches de features devem seguir um padrão `X_Nome_da_issue` , onde X é o número da issue correspondente a funcionalidade. 

### *hotfix branches* 

Hotfix branches são criadas a partir da **master** e servem para resolver de forma rápida os bugs em produção. Essa branch deve seguir a seguinte nomenclatura: hotfix_Nome_do_bug.

## Política de commits 

Os commits devem descrever de forma simples e sucinta as modificações feitas. E devem ser escritas em inglês. Exemplo:

`git commit -m”Create new model”`

## Commits em pares

Quando se está usando a técnica de pair programming deve-se deixar especificado todos os autores envolvidos no desenvolvimento da funcionalidade. Por isso é necessário utilizar a tag co-authored-by do Github, a seguir um passo a passo:

1 - Após usar o comando `git add` para adicionar as mudanças feitas, execute o seguinte comando:
	`git commit`

2 - Abrirá um editor de texto mostrando algumas configurações do que foi feito. Na primeira linha digite a mensagem do commit e depois pule duas linhas e adiciona a co-autoria como no exemplo abaixo: 
```
Add new routers


Co-authored-by: Taynara Carvalho <tayhcarvalho@gmail.com>
Co-authored-by: Stéfane Souza <stefanesouza04@gmail.com>
```

Depois disso salve e o commit será contabilizado pelo Github.

Obs: Não exclua nada, apenas acrescente o que foi dito acima.



