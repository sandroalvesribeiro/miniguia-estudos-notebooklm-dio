# Mini Guia de Estudos com NotebookLM

>> CONTEXTO E OBJETIVO << 

O assunto escolhido foram os regimes aduaneiros de ADMISSÃO TEMPORÁRIA e EXPORTAÇÃO TEMPORÁRIA, temas presentes na área de comércio exterior.
O objetivo consiste em reunir em um lugar os materiais sobre o tema, que se encontram separados por links diferentes, para servir de base de consulta para importadores, exportadores e profissionais que atuam e trabalham na assessoria com estes temas.



>> CURADORIA E FONTES << 

MANUAL ADUANEIRO DE EXPORTAÇÃO TEMPORÁRIA: "https://www.gov.br/receitafederal/pt-br/assuntos/aduana-e-comercio-exterior/manuais/exportacao-temporaria"
MANUAL ADUANEIRO DE ADMISSÃO TEMPORÁRIA: "https://www.gov.br/receitafederal/pt-br/assuntos/aduana-e-comercio-exterior/manuais/admissao-temporaria"
ATO LEGAL DOS REGIMES ADUANEIROS DE ADMISSÃO E EXPORTAÇÃO TEMPORÁRIA - INSTRUÇÃO NORMATIVA RFB NR 1600/2015: "https://normasinternet2.receita.fazenda.gov.br/#/consulta/externa/70297/visao/multivigente"


>> ENGENHARIA DE PROMPTS E "CICATRIZES" << 

AO TESTAR A FERRAMENTA, FORAM FEITOS QUESTIONAMENTOS CHAVES, AQUELES QUE SEMPRE SÃO FEITOS PARA ESTAS OPERAÇÕES:

PROMPT 1 - "Explique o fluxo completo de Admissão Temporária" em substituição a "Como seria um fluxo de admissão temporária?"

Resposta: "O fluxo do **Regime Aduaneiro Especial de Admissão Temporária** compreende um processo composto pelas fases de enquadramento, instrução documental, concessão, acompanhamento e extinção formal do regime.

### 1. Enquadramento e Requisitos Iniciais
A primeira etapa consiste na definição da finalidade da importação para enquadrar a operação em uma das três submodalidades previstas:
* **Admissão Temporária com Suspensão Total dos Tributos:** Aplica-se a bens destinados a permanecer no País por tempo determinado para feiras, congressos, eventos culturais ou esportivos, testes, pesquisas, promoção comercial e conserto. Ficam suspensos os tributos federais: Imposto de Importação (II), IPI-Importação, PIS/Pasep-Importação, Cofins-Importação, Cide-Combustíveis e AFRMM. Em relação ao ICMS, o Supremo Tribunal Federal (STF) definiu a não incidência por ausência de transferência de propriedade do bem.
* **Admissão Temporária para Utilização Econômica:** Destina-se a bens empregados diretamente na prestação de serviços a terceiros ou na produção de outros bens para venda (como máquinas e equipamentos). Exige o pagamento proporcional dos tributos federais à razão de 1% por mês ou fração de permanência, mantendo-se suspensa a diferença relativa ao montante integral.
* **Admissão Temporária para Aperfeiçoamento Ativo:** Aplica-se a bens estrangeiros que ingressam para sofrer operações industriais de beneficiamento, montagem, renovação, conserto ou reparo e posterior reexportação, sob suspensão integral de tributos.

**Condições obrigatórias:** O pedido exige a comprovação do caráter temporário da importação por meio idôneo, operação sem cobertura cambial, adequação do bem e uso exclusivo na finalidade declarada, além da identificação completa do bem (descrição, marca, modelo, NCM e atributos). Caso o bem esteja sujeito a controle específico, exige-se a anuência prévia dos órgãos anuentes competentes.

### 2. Instrução Documental e Registro da Declaração
A formalização do pedido é feita perante a Receita Federal:
* **Registro da Declaração Aduaneira:** É efetuado via **Declaração de Importação (DI)** no Siscomex ou **Declaração Única de Importação (Duimp)** no Portal Siscomex (ou por Declaração Simplificada de Importação - DSI formulário nos casos previstos).
* **Anexação Documental:** Os documentos instrutivos são anexados digitalmente em dossiê no Portal Siscomex:
  * Requerimento de Admissão Temporária (RAT);
  * Contrato de importação celebrado com o exportador (ou documento substituto atestando a natureza da operação, especificação dos bens, valores e prazo de permanência);
  * Contrato de prestação de serviços com o tomador no Brasil (se aplicável);
  * Conhecimento de carga e romaneio de carga (*packing list*);
  * **Termo de Responsabilidade (TR):** Instrumento que consubstancia o montante dos tributos com exigibilidade suspensa;
  * **Garantia Tributária:** É dispensada na Suspensão Total e no Aperfeiçoamento Ativo. Na Utilização Econômica proporcional, a garantia é exigida, salvo hipóteses de dispensa legal (como tributos suspensos abaixo de R\$ 120 mil, empresas OEA, órgãos públicos ou afretamento de embarcações/plataformas).
* **Carnê ATA:** Para bens de curta duração (como amostras, equipamentos profissionais e materiais para feiras e exposições), o Carnê ATA pode ser utilizado como título aduaneiro e garantia internacional, dispensando as declarações tradicionais.

### 3. Concessão e Prazos de Vigência
* **Concessão do Regime:** Considera-se efetivada no momento do **desembaraço aduaneiro** do bem. É realizada pelo sistema no canal verde (sob condição de verificação posterior) ou pelo Auditor-Fiscal nos demais canais de conferência.
* **Prazo de Vigência:** É contado a partir da data do desembaraço aduaneiro:
  * **Na Suspensão Total:** Fixado em até 1 ano, ou entre 1 e 5 anos conforme previsto no contrato ou documento instrutivo.
  * **Na Utilização Econômica:** Fixado de acordo com o contrato de importação, respeitando o limite máximo total de 100 meses.

### 4. Operações Durante a Vigência
Durante a permanência do bem no País, é possível realizar os seguintes procedimentos operacionais:
* **Prorrogação de Prazo:** Deve ser requerida antes do término do prazo vigente por meio de Requerimento de Prorrogação do Regime (RPR) anexado ao dossiê no Portal Siscomex. Na Suspensão Total, o prazo regular de prorrogação é de até 5 anos, admitindo-se prazo superior em casos excepcionais autorizados pelo Superintendente da Receita Federal. Na Utilização Econômica, a prorrogação acompanha o aditivo contratual, limitada ao teto de 100 meses.
* **Manutenção e Reparo:** Os bens podem ser submetidos a conserto no País ou ser remetidos temporariamente ao exterior via DU-E sem interromper a contagem do prazo de vigência.
* **Mudança de Finalidade e Substituição de Beneficiário:** O enquadramento da modalidade pode ser alterado ou a responsabilidade sobre os bens transferida a outro beneficiário, mediante requerimento formal em dossiê e anuência expressa do proprietário estrangeiro.

### 5. Extinção do Regime
Dentro do prazo de vigência, o beneficiário deve adotar uma das providências para a extinção regular do regime:
1. **Reexportação:** Retorno do bem ao exterior, formalizado por Declaração Única de Exportação (DU-E) e apresentação da carga para despacho [192, 46-A].
2. **Despacho para Consumo (Nacionalização):** Registro de DI ou Duimp com o recolhimento dos tributos e cumprimento dos controles administrativos vigentes na data do registro.
3. **Transferência de Regime:** Migração do bem para outro regime aduaneiro especial (como Entreposto Aduaneiro).
4. **Destruição sob Controle Aduaneiro:** Realizada às expensas do beneficiário, acompanhada de licença ou dispensa ambiental.
5. **Entrega à Receita Federal:** Entrega dos bens livres de despesas, sujeita à concordância da autoridade aduaneira.

### 6. Descumprimento e Penalidades
Caso o prazo de permanência vença sem pedido de prorrogação ou adoção de medida extintiva, ou ocorra desvio de finalidade:
* **Intimação Fiscal:** O beneficiário é intimado para se manifestar em 10 dias e, mantido o descumprimento, dispõe de 30 dias para promover a reexportação ou o despacho para consumo do bem.
* **Multa por Descumprimento:** Aplica-se a multa de **10% sobre o valor aduaneiro da mercadoria**.
* **Cobrança dos Tributos e Multa de Ofício:** Exige-se o recolhimento dos tributos originalmente suspensos com juros de mora desde o registro da declaração inicial, acrescido do lançamento da **multa de ofício de 75%**.
* **Pena de Perdimento:** Se a permanência definitiva do bem não for autorizada pelo órgão competente ou o licenciamento estiver vedado, a autoridade aduaneira efetuará a apreensão do bem para aplicação da pena de perdimento (ou aplicará multa equivalente ao valor aduaneiro caso o bem não seja localizado).

===================
Dificuldade: Apesar de disponível na Internet, a modalidade de CARNÊ ATA não está mais vigente. A norma principal sobre admissão não possui atualização e continua mostrando ser uma opção.
Para poder amenizar esta etapa,  consideramos como ponto principal para resolver este problema a inclusão de comunicado da Receita sobre o término desta modalidade, com o link "https://www.gov.br/receitafederal/pt-br/assuntos/aduana-e-comercio-exterior/manuais/carne-ata" onde informa o término da operação em 31/12/2021.

Ele respondeu praticamente a mesma coisa porém acrescentando esta observação: 


1. Encerramento das Operações com o Carnê ATA no Brasil
O que foi extinto: As operações sob o amparo do Carnê ATA no Brasil foram oficialmente encerradas em 31/12/2021
.
Impacto: O Carnê ATA atuava como um título aduaneiro internacional que funcionava como declaração aduaneira e garantia global
. Desde o seu encerramento, o instrumento deixou de ser aceito para a concessão ou movimentação de admissão temporária no País

===================

PERGUNTA 2 - "Quais os cuidados importantes e o que NÃO pode ocorrer na aplicação deste regime?"

Respostas: "Na aplicação dos regimes aduaneiros especiais de Admissão Temporária e Exportação Temporária, o acompanhamento rigoroso dos requisitos legais e operacionais é indispensável para evitar a perda dos benefícios fiscais e a aplicação de penalidades.

### **O que NÃO pode ocorrer no regime**

1. **Vencimento do prazo sem solicitação de prorrogação ou extinção:** O prazo de permanência autorizada não pode expirar sem que tenha sido protocolado o Requerimento de Prorrogação do Regime (RPR) ou iniciado o processo formal de extinção (como reexportação, reimportação ou despacho para consumo).
2. **Utilização do bem em finalidade diversa da autorizada:** O bem admitido ou exportado temporariamente não pode ser empregado em atividade diferente daquela informada no pedido de concessão (por exemplo, uso comercial de bem trazido apenas para exibições ou testes) sem autorização prévia de mudança de modalidade.
3. **Operações com cobertura cambial:** Os regimes de admissão temporária e exportação temporária exigem expressamente que as operações ocorram sem cobertura cambial.
4. **Alienação ou transferência não autorizada do bem:** É proibido vender, ceder, emprestar ou substituir o beneficiário responsável sem requerimento formal à Receita Federal e concordância expressa do proprietário no exterior.
5. **Exportação temporária em consignação ou de bens proibidos:** O regime de exportação temporária não se aplica a mercadorias sob contrato estimatório (venda em consignação), nem a bens cuja exportação definitiva seja vedada pela legislação.
6. **Submeter bens em *leasing* financeiro à Admissão Temporária:** O regime de admissão temporária não pode ser concedido a bens objeto de arrendamento mercantil financeiro contratados com entidades no exterior.
7. **Modificação ou alteração física do bem fora das modalidades de aperfeiçoamento:** Nas modalidades comuns de admissão e exportação temporária, o bem deve retornar ao seu estado original. Processos de transformação, montagem ou conserto são restritos às submodalidades de Aperfeiçoamento Ativo ou Aperfeiçoamento Passivo.

### **Cuidados Importantes e Boas Práticas**

1. **Gestão e Protocolo Tempestivo de Prazos:** O Requerimento de Prorrogação de Regime (RPR) deve ser apresentado obrigatoriamente antes do término do prazo de vigência original, pois requerimentos intempestivos não são conhecidos pela fiscalização.
2. **Descrição e Identificação Detalhada dos Bens:** Todos os atributos do bem (marca, modelo, número de série, NCM e especificações técnicas) devem ser descritos com exatidão na declaração aduaneira inicial para permitir a perfeita conferência no momento da extinção do regime.
3. **Instrução Documental Completa no Dossiê Digital:** É necessário disponibilizar via Portal Siscomex o dossiê com toda a documentação instrutiva exigida, como Requerimento (RAT/RPR), contrato de importação/prestação de serviços, Termo de Responsabilidade (TR), conhecimento de carga e romaneio de carga (*packing list*).
4. **Manutenção de Garantias Tributárias:** Na Utilização Econômica com pagamento proporcional, a garantia prestada (como seguro aduaneiro, fiança idônea ou depósito) deve cobrir os tributos suspensos e permanecer válida durante toda a vigência do regime, salvo nas hipóteses de dispensa legal.
5. **Verificação de Tratamento Administrativo e Órgãos Anuentes:** Deve-se conferir com antecedência se o bem exige anuência prévia ou Licença de Importação (LI) de órgãos reguladores (como MAPA, Anvisa ou Inmetro), inclusive no momento da reimportação ou do despacho para consumo.
6. **Formalização Correta da Extinção do Regime:** A extinção deve ser formalizada dentro do prazo mediante registro da declaração correspondente (DU-E para reexportação/exportação definitiva ou DI/Duimp para reimportação/despacho para consumo) e apresentação da carga para despacho.

### **Consequências do Descumprimento**

Caso o regime seja descumprido por vencimento de prazo sem providências ou desvio de finalidade:
* Incide multa de **10% sobre o valor aduaneiro** (na Admissão Temporária) ou de **5% sobre o preço normal da mercadoria** (na Exportação Temporária).
* É exigido o recolhimento imediato dos tributos originalmente suspensos com juros de mora e lançamento da **multa de ofício de 75%**.
* Caso a permanência definitiva do bem não seja autorizada ou o bem não seja localizado, a autoridade aduaneira poderá aplicar a **pena de perdimento do bem** ou multa equivalente ao seu valor aduaneiro.

======================
Considerando tratar-se basicamente de legislação é importante que o questionamento seja objetivo e completo
======================

O desafio principal  neste tipo de conteúdo é a alteração legal  dos  dispositivos. Houve por exemplo a extinção de uma modalidade, como o carnê ATA que constava constituído legalmente na instrução normativa 1600,  porém não teve uma atualização sobre o fim de sua execução,  o que seria correto. 
Entretando as informações sobre as alterações são encontradas no mesmo sitio,  o que por outro lado ajuda a pesquisa e atualização,  como foi feito no notebook


>>> MINIGUIA DE ESTUTODS <<<, 

Resumo: O Notebook "Admissão Temporária e Exportação Temporária — Receita Federal" reúne as principais informações sobre este dois regimes aduaneiros vigentes e amplamente utilizados nas atividades de comércio exterior,  tendo objetivo de servir como um guia de orientação profissional para uso de profissionais da área, importadores, exportadores e demais interessados.

Glossário: 
DI - Declaração de importação (tipo de declaração de mercadorias importadas para receita federal)
DUIMP - Declaração únida de importação (tipo de declaração de mercadorias importadas para receita federal)
IN - Instrução Normativa (Norma regulatória)
TR - Termo  de responsabilidade (Documento de comprometimento com tributos passíveis de exigencia)
LI - Licença de importação (Autorização especial conforme enquadramento de exigencia)
DU-E - Declaração única de exportação (tipo de declaração de mercadorias exportadas para receita federal)
AFRMM - Adicional de frete  para renovação da Marinha Mercante (taxa cobrada pelo governo sobre embarques aquaviários)


Prompts Utilizáveis:
"Quais os principais prazos envolvidos em cada operação"
"Quais as multas incidentes nos  regimes de admissão temporária e exportação temporária"
"Quais as formas de extinção dos regimes"
"Como solicitar uma  prorrogação de regime"






