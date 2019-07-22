# Arquivos XML modelo do Programa de P&D para envio pelo Duto ANEEL

- Todo XML deve ser codificado em ANSI, iniciado pelo encoding="ISO8859-1"

- Todo XML deve ter na primeira linha o seguinte cabeçalho ```<?xml version="1.0" encoding="ISO8859-1"?>```

- Todo XML deve ter na segunda linha o seguinte cabeçalho ```<PED Tipo="XX" CodigoEmpresa="YY">``` onde:

  - XX = Tipos do XML, que podem ser:

    - ~~MOVIMENTACAOFINANCEIRA: para enviar informações sobre a Movimentação Financeira das Contas Contábeis de Pesquisa e Desenvolvimento.~~ [Obsoleto]
    - ~~PROGRAMA: para enviar o Plano Estratégico de Investimentos em P&D.~~ [Obsoleto]
    - PROJETOGESTAO: para enviar um Projeto de Gestão.
    - PROJETOPED: para enviar um Projeto de P&D.
    - INTERESSEPROJETOPED: para enviar informações sobre o interesse da Empresa em executar um ou mais Projetos de P&D.
    - INICIOEXECUCAOPROJETO: para enviar informações sobre a data de início de execução de um ou mais Projetos de P&D e/ou do Projeto de Gestão e a forma de compartilhamento dos direitos de propriedade intelectual sobre os resultados do projeto.
    - PRORROGAEXECUCAOPROJETO: para enviar informações sobre a prorrogação de prazo de execução de um ou mais Projetos de P&D e/ou do Projeto de Gestão.
    - RELATORIOFINALPED: para enviar o Relatório Final de um Projeto de P&D.
    - RELATORIOFINALGESTAO: para enviar o Relatório Final de um Projeto de Gestão.
    - RELATORIOAUDITORIAPED: para enviar o Relatório de Auditoria Contábil e Financeira de um Projeto de P&D.
    - RELATORIOAUDITORIAGESTAO: para enviar o Relatório de Auditoria Contábil e Financeira de um Projeto de Gestão.
  - YY = Cód. ANEEL da empresa que envia o XML
