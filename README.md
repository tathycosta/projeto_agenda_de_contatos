# projeto_agenda_de_contatos
Objetivo do Projeto
O objetivo principal era criar uma solução digital eficiente para substituir uma agenda de contatos em papel, facilitando a gestão de informações de clientes e fornecedores de uma pequena empresa. O sistema precisava ser intuitivo, organizado e seguro, garantindo a integridade dos dados e a praticidade no dia a dia dos usuários.

Funcionalidades Implementadas
O sistema desenvolvido atendeu aos seguintes requisitos:

Cadastrar Contato:

O usuário pode inserir nome, sobrenome, telefone e e-mail.
O sistema verifica se o contato já existe na agenda para evitar duplicidades.
O telefone é formatado automaticamente para os padrões (XX) XXXX-XXXX (fixo) ou (XX) XXXXX-XXXX (celular).
Visualizar Contatos em Ordem Alfabética:

Os contatos são ordenados alfabeticamente pelo sobrenome e nome, facilitando a organização e a busca.
A ordenação é case-insensitive (não diferencia maiúsculas de minúsculas).
Pesquisar Contato:

O usuário pode buscar contatos por nome, sobrenome ou telefone.
O sistema exibe todos os contatos que correspondem à busca, mostrando nome, sobrenome, telefone formatado e e-mail.
Atualizar Contato:

O usuário pode alterar o nome de um contato existente.
O sistema solicita confirmação antes de aplicar as mudanças.
Remover Contato:

O usuário pode excluir um contato da agenda.
O sistema solicita confirmação antes de realizar a exclusão, evitando remoções acidentais.
Sair do Sistema:

O programa é encerrado de forma segura, garantindo que nenhum dado seja perdido.

Tecnologias e Técnicas Utilizadas
Python: Linguagem principal para desenvolvimento do sistema.
Regex: Validação do formato do telefone para garantir consistência.
Ordenação Personalizada: Critério de ordenação por sobrenome, utilizando a função sorted() com uma chave personalizada.
Manipulação de Listas e Dicionários: Armazenamento e gerenciamento dos contatos.
