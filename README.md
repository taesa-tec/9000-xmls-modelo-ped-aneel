# Arquivos XML modelo do Programa de P&D para envio pelo Duto ANEEL

- Todo XML deve ser codificado em ANSI, iniciado pelo encoding="ISO8859-1"
- Todo XML deve ter na primeira linha  o seguinte cabe�alho <?xml version="1.0" encoding="ISO8859-1"?>
- Todo XML deve ter na segunda linha  o seguinte cabe�alho <PED Tipo="XX" CodigoEmpresa="YY"> onde:
	XX= Tipos do XML, que podem ser:
		MOVIMENTACAOFINANCEIRA	para enviar informa��es sobre a Movimenta��o Financeira das Contas Cont�beis de Pesquisa e Desenvolvimento.
		PROGRAMA	para enviar o Plano Estrat�gico de Investimentos em P&D.
		PROJETOGESTAO	para enviar um Projeto de Gest�o.
		PROJETOPED	para enviar um Projeto de P&D.
		INTERESSEPROJETOPED	para enviar informa��es sobre o interesse da Empresa em executar um ou mais Projetos de P&D.
		INICIOEXECUCAOPROJETO	para enviar informa��es sobre a data de in�cio de execu��o de um ou mais Projetos de P&D e/ou do Projeto de Gest�o e a forma de compartilhamento dos direitos de propriedade intelectual sobre os resultados do projeto.
		PRORROGAEXECUCAOPROJETO	para enviar informa��es sobre a prorroga��o de prazo de execu��o de um ou mais Projetos de P&D e/ou do Projeto de Gest�o.
		RELATORIOFINALPED	para enviar o Relat�rio Final de um Projeto de P&D.
		RELATORIOFINALGESTAO	para enviar o Relat�rio Final de um Projeto de Gest�o.
		RELATORIOAUDITORIAPED	para enviar o Relat�rio de Auditoria Cont�bil e Financeira de um Projeto de P&D.
		RELATORIOAUDITORIAGESTAO	para enviar o Relat�rio de Auditoria Cont�bil e Financeira de um Projeto de Gest�o.
	YY = C�d. ANEEL da empresa que envia o XML 
		