USUÁRIO
	cod serial PK
	nome
	nick
	idade
	sexo
	data de nascimento
	email
	senha (MD5)
	foto

ESTADO

	cod PK
	

USUÁRIO_ESTADO

	cod (USUÁRIO.cod)
	
	
AMIGOS
	p_cod (USUÁRIO.cod)
	d_cod (USUÁRIO.cod)
	
CONVERSA
	de (USUÁRIO.nome)
	para (USUÁRIO.nome)
	mensagem
	data
	hora