# Git
### Anotações e conhecimentos sobre Git adquiridos durante estudos.

## O que é Git ?

O Git é um **sistema de controle de versão** amplamente usado por programadores e empresas <br/>para gerenciar o código fonte de um sistema, aplicação etc.

## Mas o que é um **sistema de controle de versão**?

O controle de versão, é a prática de rastrear e gerenciar alterações em um código de um sistema, ajudando as equipes de desenvolvimento durante o seu trabalho, para isso existem os sistemas de controle de versão distribuído, ou seja são vários repositórios independentes, sendo que cada um desses repositórios possui comunicação com o Branch principal do projeto. 

## Alguns conceitos importantes: 
### Branch, Commit e Readme

## Branch: 
Branch são basicamente versões de um sistema, quando iniciamos um repositorio com Git o branch inicial é o **Master**, ele também é o repositório principal do projeto, é recomendado a mudança do nome desse Branch para **Main**.

## Commit:
O Commit em um sistema de controle de versão, adciona as alterações recentes de um código fonte para o repositório Principal, ou seus Branches subordinados.

## Readme:
O readme é um arquivo de texto, presente em quase todos os repositórios, e é amplamente recomendada a sua presença, pois ele serve para passar instruções acerca de uso do sistema, informações sobre a sua criação, seu funcionamento, tecnologias usadas em seu desenvolvimento, entre outras informações importantes.

## Status de arquivos no Git 

Existem 4 status para arquivos no Git são eles: Untracked, Tracked, Modified e Staged. Sendo possível um arquivo navegar por estes estágios diversas vezes durante o processo de desenvolvimento.

### Untracked:
Um arquivo está com status Untracked quando ainda não está sendo monitorado pelo Git, um arquivo novo naquela pasta.

### Tracked:
Um arquivo está com status Tracked quando adcionado ao monitoramento do Git, ou seja o apartir de agora é possível controlar as versões daquele arquivo.

### Modified:
Um arquivo está com status Modified quando um arquivo que está sendo monitorado é modificado.

### Staged:
Um arquivo está com status Staged quando ele está pronto, ou seja já está sendo rastreado, foi modificado e finalizado, sendo assim pronto para ser enviado para o repositório usando commits.

# Iniciando um repositório Git

Para se iniciar um repositório Git, vá até uma pasta criada para o seu projeto, dentro dela, pressione o botão direito do seu mouse e vá até a opção 

