# Projeto Cliente-Endereco
Este projeto é uma aplicação Java baseada em Spring Boot que gerencia clientes e seus endereços. Utilizando JPA (Java Persistence API), a aplicação permite o armazenamento e a recuperação de informações sobre clientes e seus endereços associados. A aplicação é projetada para demonstrar o uso de relacionamentos um-para-um entre entidades e integração com serviços externos para validação e obtenção de dados.

## Funcionalidades
* Gerenciamento de Clientes: Adicione, atualize, recupere e exclua informações de clientes.
* Gerenciamento de Endereços: Associar endereços aos clientes e buscar informações de endereços usando o CEP.
* Integração com ViaCEP: Consulta automática de dados de endereço utilizando o serviço ViaCEP.

## Serviços
* ClienteService: Serviço para gerenciamento de clientes. Inclui métodos para buscar, inserir, atualizar e deletar clientes.
* EnderecoService: Serviço para buscar e consultar endereços através do CEP utilizando o ViaCEP.
