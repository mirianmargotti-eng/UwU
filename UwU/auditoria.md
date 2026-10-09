Esta anotação equivalem a criação em ordem da auditoria na criação de um cadastro de pessoa (FISICA) voltado para estudar sua rotina.
Cadastro de pessoa
> Endereço salvo.
> Pessoa.
> Telefone da pessoa.
> Finalizar cadastro.

Financeiro
 >Decimo terceiro segunda parcela? metade do valor.
> Cria folha de pagamento valor total.
> Atribuição a cargo e valor salario base.
> Atualizar o apelido, de novo ano fui eu, erro?> anotar lista.
> Voltou para o financeiro com decimo terceiro mas agora 1 parcela.
> Valor parcelado.
> Atribuição a cargo com identificação , (descrição0) -> faixa salarial do funcionário.
> Novamente não entendi o que aconteceu, id 56?, numero 1? .
> Agora sim folha de pagamento, era calculo para esta folha :D.
> Por fim dados totais do funcionário.


esta auditoria equivale a criação de um funcionário com pessoa já cadastrada( pessoa FISICA)
- Auditoria não registra remoção de endereço e contato de pessoas.
> Decimo terceiro parcela 1.
> Junta informações par financeiro, como centro de custo, banco, conta contábil, forma de Pagamento.
   Alteração no nome fantasia(CPF não tem nome fantasia), e o que mudou NADA.
> gera id do titulo metade do valor total.
> Decimo terceiro parcela 2.
> Associa funcionário ao cargo(id78?).
> Termina cadastro de funcionário juntando as informações+ tipo de vinculação(cria vinculo).
>==🟡Nem sei o que é  isso== 
>>==🟡{numero": 1,==
>>==🟡"data_vencimento": "2026-12-20",==
>>==🟡"valor": 100,==
>>==🟡"valor_juros": 0,==
>>==🟡"valor_multa": 0,==
>>==🟡"valor_desconto": 0,==
>>==🟡"valor_taxa": 0,==
>>==🟡"valor_liquido": 100,==
>>==🟡"valor_pago": 0,==
>>==🟡"situacao": "open",==
>>==🟡"titulo_financeiro_id": 49,==
>>==🟡"updated_at": "2026-10-07 15:37:03",==
>>==🟡"created_at": "2026-10-07 15:37:03",==
>>==🟡"id": 59}==
>O mesmo de cima porem com valor total e id 57 , titulo financeiro 47==
>Todas as informações dos formulários de funcionário.

Exclusão de funcionário(o mesmo cadastrado).
>De novo alterou nome fantasia, nem tem nome fantasia CPF.
>Colocou o funcionário para status desativado(false).
>Só então é excluído.
>Registrou a data do fim, mas hora zerada.
>Folha de pagamento ficou em brando, qualquer outra coisa fora o citado não parece ter mudado.

Após deletar outro funcionário mudou a ordem da auditoria...pode isso não.
Ele exclui o funcionário e depois desativou ele... não era nem o ideal excluir os dados.



Exclusão de setor e cargo
Editar para status igual a inativo (CARGOS)
- Primeiro alterei de ativo para o inativo(em funcionários conta como ativo)
>   Atualizou status de TRUE para false

Em em setores se manteve igual, alteração bem sucedida sem margem para maior investigação
> Atualizou status de TRUE para false

Exclusão de cargo
o ideal seria inativar os dois excluir, contudo em minha fundação devo atuar como o cliente leigo dessas informações, partindo disso irei reativa o cargo e setores e excluído enquanto ativado.

Exclusão de Cargo (ATIVO)
>   Houve a exclusão direta do cargo sem alterar seu status(Permaneceu em TRUE)

Na exclusão do setor se manteve o mesmo que cargos, ele foi EXCLUIDO com o status TRUE


pensamentos pensantes 
Nesta situação o cargo continua em funcionário, entendível mas o ideal não seria inativar para registrar que o setor em que o funcionário esta vinculado esta fora de circulação, assim se eu olhar apenas funcionário, posso não saber que o setor nem se que Permanece na instituição.




iltima att foi 
update
8/10/2026, 
09:35:29
