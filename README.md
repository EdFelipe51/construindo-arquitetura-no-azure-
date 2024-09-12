# construindo-arquitetura-no-azure
Contéudo do Treinamento Construindo Arquitetura no Azure Microsoft Azure Essentials DIO 

Criar grupos de recursos

1o. Entre no portal do Azure. (logar)

2o. Selecione Grupos de recursos. (Resource Group)

Selecione Criar.

Insira os valores a seguir:

Assinatura: Selecione sua assinatura do Azure.

Grupo de recursos: insira um nome para o novo grupo de recursos.

Região: selecione uma localização do Azure, como EUA Central.

Selecione Examinar + Criar

Selecione Criar. Leva alguns segundos para criar um grupo de recursos.

Obs.: Selecione Atualizar no menu superior para atualizar a lista de grupos de recursos e, em seguida, selecione o grupo de recursos recém-criado para abri-lo. Ou selecione Notificação(o ícone de sino) na parte superior e, em seguida, selecione Ir para o grupo de recursos para abrir o grupo de recursos recém-criado

Segue link da documentação oficial da Microsoft Azure, criação de grupo de recursos:
https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/manage-resource-groups-portal


Conceder acesso/permissão aos recursos do Azure para um usuário

Para conceder permissões a um grupo de recursos no Azure, é possível atribuir uma função do Azure, utilizando o RBAC do Azure. Para isso, é possível seguir os seguintes passos:
Abrir o grupo de recursos;


1o. Na lista de Grupos de recursos, abra o novo grupo de recursos example-group.

2o. No menu de navegação, clique em Controle de Acesso (IAM) .

3o. Escolha na guia Atribuições de função para ver a lista atual das atribuições de função.

4o. Página Controle de Acesso (IAM) do grupo de recursos.

5o. Clique em Adicionar>Adicionar atribuição de função. (Se você não tiver permissões para atribuir funções, a opção Adicionar atribuição de função será desativada).

6o. Página Controle de Acesso (IAM) com o menu Adicionar atribuição de função aberto.

7o. Na guia Função, selecione a função Colaborador da Máquina Virtual.

8o. Página Adicionar atribuição de função com a guia Função selecionada.

9o. Na guia Membros, selecione você mesmo ou outro usuário.

10o. Na guia Examinar + atribuir, examine as configurações de atribuição de função.

11o. Clique em Examinar + atribuir para atribuir a função.

Após alguns instantes, a função Colaborador da Máquina Virtual será atribuída ao usuário no escopo do grupo de recursos example-group.

Obs.: Para conceder acesso a um grupo, também é possível utilizar o comando New-AzRoleAssignment. Para isso, é necessário especificar a entidade de segurança, a definição de função e o escopo. 

Segue link da documentação oficial da Microsoft Azure, Conceder acesso aos recursos do Azure para um usuário
https://learn.microsoft.com/pt-br/azure/role-based-access-control/quickstart-assign-role-user-portal






