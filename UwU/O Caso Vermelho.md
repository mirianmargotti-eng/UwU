
(relatar o erro no endereço de CNPJ consultado)
criei pessoa
voltei em pessoas para confirma vinculo
voltei para clientes apaguei
pessoa sumiu
tentei cadastrar novamente
erro, CPF já cadastrado



Por que houve uma única exceção
Contexto: houve uma exceção envolvendo um CNPJ e preciso descobrir porque
- não foi por que foi o ultimo cadastro(tentei com a Laiz mas erro reproduzido)
- agora ate o CNPJ que pareceu ser exceção foi de base
- CPF e CNPJ não é motivo da exceção
- não é por exclusão imediata após vinculação(vincular e ja excluir)
-  exclui Ligasol, ela nao sumio nem em clientes e nem em pessoas], mas em auditoria dix como ecluido o vinculo, 
- minuto depois sumio em clientes e nao em pessoa
- nao irei recarregar a tela, vou apneas alter de cliente para pessoa e vice versa(teste de dylei)
- nao, recarreguei e nao sumio, novamente houve ecessao, apenas removeu o vinculo
- vou cadastrar novamente para apaguar
- cadastrei e exclui, ja sumio de cliente mas o vinculo permanece
- mudou para sem vinculo
- Descobri uma possivel causa( para entender precisamos voltar a cadastro de cliente, ao colocar um CPF/CNPJ ele puxa a informação, ai vc salva e vai aparecer uma segunda opção salvar(editar cliente), eu sei estranho ne, mass se vc nao selecionar a segunda opção de salvar, apertar alguma opção que saia dessa tela como pessoa, sem selecionar o salvar edição de cliente, ele salava do mesmo jeito, issso é algo que as unicas 2 exceção tinha em comum e nao foram reproduzidas no demais casos, irei testar novamente para confirma)


Teste de hipotese
-  é isto, este é o motivo da exeção , agora pq aontece ve com os outro ai ne 
- nao  é possivel recadastrar o cliente pela tela de pessoas, mas pude pela tela de cliente
- vou tentar com algum cpf, com vinculo em funcionario para ve se volta
- consegui criar novamente, mas nos vinvulos ta apenas clientes, vou tentar vincular como fucnionario (o codigo permaneceu o antigo)
- Ao cadastrar ele pede o mesmo qua antes para cadastrar um funcionario, o cnpj nao deu conflito a principio, mas apos eu aplicar as informaç~eo de cargors e niveis(diferente do cadastro de funcionario anterior) ele atualisou as informações, nao houve duplicidade de cadasrto de uncionario