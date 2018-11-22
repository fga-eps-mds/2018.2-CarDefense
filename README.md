
<center>

<a><img src="https://i.imgur.com/zuldpGo.png" /></a>

![Docs](https://img.shields.io/badge/docs-Github%20Pages-blue.svg)
![License](https://img.shields.io/badge/license-GLP--3.0-red.svg)

 # Car Defense
É um aplicativo comunitário de monitoramento de carros através de notificações em tempo real em que o usuário cadastrado pode enviar e receber.
[Acesse o site do app CarDefense ](https://fga-eps-mds.github.io/2018.2-CarDefense/)

### Conheça nossa documentação
* [CarDefense Docs](https://fga-eps-mds.github.io/2018.2-CarDefense/docs/index.html)

<a href="https://play.google.com/store/apps/details?id=com.cardefense.cardefense"><img src="https://i.imgur.com/3YcEpgg.png"/></a> </center>


## Organização CarDefense
* [CarDefense Profile](https://github.com/CarDefense/CarDefense_Profile)
* [CarDefense Notification](https://github.com/CarDefense/CarDefense_Notification)
* [CarDefense Cars](https://github.com/CarDefense/CarDefense_Cars)
* [CarDefense Front-End](https://github.com/CarDefense/CarDefense_FrontEnd)

---

## Como Contribuir
### 1. Orientações
* Se você for um colaborador externo, dê um fork no projeto.
* Issues só poderão ser criadas com os templates especificados no repositório.
* A criação de branches deve seguir a política de branches.
* No desenvolvimento, usar nossa política de commits.
* Pull requests só serão aceitos se estiverem com o template especificado no repositório.
 
### 2. Política de Branches
Nossa política segue algumas características do Gitflow. Então separamos nossas branches em:

### **master**
A master será nossa branch de produção, ou seja, nela estará a versão estável do projeto. E por questões de segurança ela será bloqueada para commits e push. A interação com a master vai se dá através da de Pull requests que virão da branch devel.

### **devel**
A devel será nossa branch de desenvolvimento, ou seja, vai agrupar o trabalho vindo das branches de features, o objetivo é criar uma release que será submetida para master.

### **branches de features**
As branches de features são criadas a partir da devel, e serve para o desenvolvimento de features presentes nas issues do repositório. No final do desenvolvimento a funcionalidade desenvolvida nessa branch deve ser enviada para a devel, através de um pull request.

> Nomenclatura das branches de features: O nome das branches de features devem seguir um padrão X_Nome_da_issue , onde X é o número da issue correspondente a funcionalidade.

### **hotfix branches**
Hotfix branches são criadas a partir da master e servem para resolver de forma rápida os bugs em produção. Essa branch deve seguir a seguinte nomenclatura: hotfix_Nome_do_bug.

