Este repositório (ou conjunto de arquivos) contém dados exportados da planilha
DECLARA IR.xlsx, organizados em formato CSV. O objetivo principal é consolidar e 
facilitar o acesso às informações necessárias para a elaboração e preenchimento 
da Declaração de Imposto de Renda Pessoa Física (DIRPF).
Visão Geral
A preparação da declaração de Imposto de Renda pode ser complexa, envolvendo 
]a coleta de diversas informações financeiras de diferentes fontes. Estes arquivos
CSV separam os dados em categorias lógicas, facilitando a consulta e o
processamento, seja para análise manual, importação em outros softwares ou utilização em scripts de automação.
Estrutura dos Arquivos
Os seguintes arquivos CSV estão incluídos:
1.	DECLARA IR.xlsx - TÍTULAR.csv
o	Descrição: Contém informações cadastrais e dados gerais do titular da declaração.
o	Conteúdo Esperado (Exemplos):
	Nome completo
	CPF
	Data de nascimento
	Endereço
	Dados bancários para restituição
	Informações de contato
o	Observação: Este arquivo é fundamental para identificar o contribuinte.
2.	DECLARA IR.xlsx - INFORMES.csv
o	Descrição: Consolida os dados provenientes dos informes de rendimentos recebidos de diversas fontes pagadoras.
o	Conteúdo Esperado (Exemplos):
	CNPJ e Nome da Fonte Pagadora
	Rendimentos Tributáveis (Salários, Proventos, Aluguéis)
	Rendimentos Isentos e Não Tributáveis (Poupança, Bolsas, Indenizações)
	Rendimentos Sujeitos à Tributação Exclusiva/Definitiva (13º Salário, PLR, Aplicações Financeiras)
	Imposto Retido na Fonte (IRRF)
	Contribuições Previdenciárias (INSS)
	Informações de Planos de Saúde (se fornecido no informe)
o	Observação: É crucial para o preenchimento das fichas de "Rendimentos Tributáveis Recebidos de PJ",
 "Rendimentos Isentos e Não Tributáveis", e "Rendimentos Sujeitos à Tributação Exclusiva/Definitiva".
4.	DECLARA IR.xlsx - NOTAS.csv
o	Descrição: Detalhamento das operações realizadas em Bolsa de Valores, como compra e venda de ações,
 fundos imobiliários (FIIs), ETFs, BDRs, etc. Geralmente, os dados são extraídos das notas de corretagem.
o	Conteúdo Esperado (Exemplos):
	Data do pregão
	Tipo de Operação (Compra/Venda)
	Mercado (À Vista, Opções, Futuro)
	Código do Ativo (Ticker)
	Quantidade
	Preço unitário
	Valor total da operação
	Taxas (Corretagem, Emolumentos, ISS, IRRF "dedo-duro")
	CNPJ da Corretora
o	Observação: Fundamental para apuração de ganhos de capital em Renda Variável e preenchimento da ficha
 de "Renda Variável" (Operações Comuns/Day-Trade, FIIs).
6.	DECLARA IR.xlsx - TABELAS.csv
•	Descrição: Contém tabelas auxiliares que podem ser usadas para cálculos, consultas ou como referência durante a declaração.
•	Conteúdo Esperado (Exemplos):
o	Tabelas de alíquotas do IR
o	Códigos deDARF
o	Limites de dedução (Saúde, Educação)
o	Tipos de bens e direitos e seus códigos
o	Cotações de moedas estrangeiras em datas específicas (se aplicável)
o	Lista de CNPJs de bancos, corretoras, ou outras entidades relevantes.
•	Observação: Este arquivo pode servir como uma central de referência rápida para informações frequentemente consultadas.
Como Utilizar
1.	Consulta e Verificação: Abra os arquivos CSV em um editor de planilhas (Microsoft Excel, Google Sheets,
2.	 LibreOffice Calc) para visualizar e verificar os dados.
3.	Importação: Estes arquivos podem ser importados para softwares de gestão financeira pessoal ou
4.	para o programa da Receita Federal (quando aplicável e se o formato for compatível para alguma
5.	funcionalidade específica, o que não é comum para CSVs diretamente no programa IRPF, mas sim para conferência).
Observações Importantes
•	Precisão dos Dados: A responsabilidade pela precisão e veracidade dos dados contidos nestes
arquivos é do contribuinte. Certifique-se de que os dados exportados refletem corretamente as
informações dos documentos originais (informes de rendimento, notas de corretagem, etc.).
•	Backup: Mantenha um backup seguro destes arquivos e da planilha original DECLARA IR.xlsx.
•	Confidencialidade: Os arquivos contêm informações financeiras pessoais e sensíveis. Mantenha-os em
 local seguro e protegido contra acesso não autorizado.
