# Entrega-Fase4-TechChallenge-OutSystems

# Integração Frontend X Backend

Este projeto tem a finalidade de criar o Frontend de eventos(crud) e integra-lo com o backend em plataforma Low-Code.


## 🚀 Começando

Para a execução deste projeto é necessário copiar os arquivos de Front-End e BackEnd para a maquina local no Service Studio (OutSystems).


## 📋 Pré-requisitos

É necessário ter instalado os seguintes software: 

```
OutSystem, Service Studio 
```

### 🔧 Instalação

Após os softwares instalados e baixado o projeto localmente, seguir os seguintes passos:

```
* Backend

  1) Clicar em Publish para compilar o projeto;
  2) Procure pela aba Logic / Rest / V1, clique com o botão direito sobre a pasta V1 e selecione a opção Open Documentation;
  3) Será direcionado para uma página em seu navegador, onde mostrará os endpoints(GET, PUT, POST e DELETE) para testar a aplicação via Postman.
   

* Frontend

  1) Clicar em Open in Browser;
  2) Será direcionado para uma página de login, inclua seu usuário e senha utilizado no OutSystems; 
  3) Navegue pelo projeto, podendo ver a lista de eventos, alterar, incluir e deletar.
  

```

## ⚙️ Executando os testes

Na página de eventos, poderá desfrutar das seguintes opções:

Lista de eventos;
Alterar o evento (data, local, valor e a descrição do evento);
Deletar o evento;
Inserir um novo evento

### 🔩 Analise os testes de ponta a ponta

Avalie a navegação das páginas, bem como a funcionalidado do crud.

```
Verifique a lista de eventos trouxe todos os eventos cadastrados no banco de dados;
Altere qualquer campo(evento, data, localização e valor) e valide se reflete corretamente na aplicação;
Delete um evento e verifique se a lista será atualizada retirando o evento;
Insera um novo evento preenchendo os campos(evento, data, localização e valor) e valide se o novo evento será refletido na aplicação
```

## 🛠️ Construído com

Este projeto foi construído utilizando as seguintes tecnologias:

OutSystems

