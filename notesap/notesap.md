## NotesSAP





**Ticket#202102520 — Admissão 01/02/2021 - Acesso SAP - Após criação de usuários AD gerar  atividade interna, anexar .csv e enviar para 2N SAP** 

 

Transação suim = [Sistema Info Usuário] 

Transação SE93 = [Verificação Descrição Transação] 

Transação SE16N = [Verificação de Centro de Custo] 

Transação KS03 = [Verificação de Centro de Custo] 

 

 

SCRIPTS 

 

·     Por gentileza, solicitar melhor evidência do usuário com passo a passo do procedimento para identificarmos 

a mensagem de erro que impede a atividade. 

 

·     Por  gentileza, solicitar o código do centro de custo do usuário e de acordo  para que o mesmo seja incluso no mesmo. (Acesso a centro de custos) 

·     # {Chamados relacionados a centro de custo verificar se o responsável do cadastro também está atualizado} 

 

  \* Funções com ínicio Z e Y = São funções desenvolvidas por programadores, ou seja, não vem na versão Standart. 

 

 

\#Email para solicitação de acesso ao SAP 

 

 Ponto Focal 

 Service Desk, Analista CSP e Solicitande 

 Planilha (SOL.ACESSOS) 

 Mensagem está também na planilha 

 

-> ROS 

 \* Para alteração da criticidade do ROS somente é permitido para o Responsável ou Gestor do Responsável 

 \* Quem faz alteração de responsável no ROS é o próprio Gestor 

 

-> Acessos QAS e Bolha são chamados direcionados para BASIS. 

 

 

-> OBSERVAÇÕES SOBRE TRANSAÇÕES 

MB21 = ZMM 

ZMMM0240 = ZMM 

ZAP e ZAR = TR (Tesouraria) 

HR = HCM = -> [Chamados do módulo HCM podem ser transferidos para a fila HCM-PA 

WM = MM 

MUITAS TRANSAÇÕES QUEM COMEÇAM COM "L" SÃO DO WM 

FI - TV estão relacionados a fila = 3N - SAP::SAP - Travel, Reimbursement, Corporate Card 

FM = IM (Modulo para CENTRO DE CUSTO) 

XK03 = MK03 

{COMEX -> EGTI - Importação / EGTE - Exportação = FILAS DISTINTTAS} 

-> Transações que começam com a Letra "i" são de PM 

-> Transação XK02 - Este acesso é exclusivo para área de cadastro 

 

**/MSAFX/EXTRACAO = MASTERSAF -** **Ticket#201936294** 

 

 

**Funções Default do ROS** 

ZEHS_00_00 - Comum ao módulo de EHS 

ZEHS_40_05 - Registro de observação de segurança - Novo ROS 

ZEHS_31_00 

ZEHS_40_03 

ZEHS_40_04 

Ticket#202100994 — Problemas Portal EHS(ROS) (Acesso padrão a todos os usuários) - FILA - EHS-Environment 

 

 

(Basis só trabalha com conceções em cima de Funções) 

 

Configuração Equipamentos WM -> MRO 

 

Por gentileza, configurar no WM as impressoras (novas). 

IP da maquina: 172.16.240.36 

Nome do compartilhamento: almoxarifado_recebimento_2 

 

IP da máquina: 172.16.240.33 

Nome do compartilhamento: almoxarifado_recebimento_1 

 

 

Tratando-se de inclusão de transações em determinada função, essa tarefa é desempenhada pelo Consultor do Modulo. 

Analise sim 

Analista tem q olhar tb e se for caso pegar aprovação do gerente 

Neste caso já vi q o gerente aprovou 

tem q analisar se tem algum risco 

 

 

·     **Ticket - 202101177->** ACESSO LIGADO A FUNÇÃO GESTOR E SE O SOLICITANTE FOR GESTOR NÃO PRECISA APROVAÇÃO 

 

**Ticket#202101328 — Problema para criar Remessa. -> Nesse chamado a palavra chave  "remessa" indica que o esse chamado pertence a fila de LE - Outbound. Para LE - Inbound teríamos "aviso de  recebimento"** 

 

 

**#Ticket#202101735 — Liberação para acesso ao Menu gestor no Portal RH** 

**#Ticket#202101092 — ACESSO AO MENU GESTOR NO PORTAL RH - É necessário "de acordo" Gerencial e a função para acesso ao portal é a zhcm_10_00** 

 

 

**Ticket#202101447 — Alteração de especificação de matéria-prima no SAP -> FILA SUPRIMENTOS** 

 

**Ticket#202101464 — Inclusão de Local de Entrega -> Fila MM** 

 

**Ticket#202101593 — Duplicidade no apontamento Sinterização = FILA PP** 

 

\# {Chamados relacionados a centro de custo verificar se o responsável do cadastro também está atualizado} 

 

**Ticket#202101591 — Revisão de Acessos/Alteração de Área - Quando relacionado a troca de  gerências todos os acessos são removidos pelo Basis e os usuários irão  solicitar posteriormente conforme a função.** 

 

**Ticket#202101622 — TRANSFERIR MATERIAL DEPOSITO - Necessário informações do Migo (Doc. Material) e o Material** 

 

**Ticket#202101750 — PAGAMENTO AO CLIENTE** 

 

**Ticket#202100869 — ALTERAÇÃO DE NOMENCLATURA GRUPO DE COMPRA S12** 

**Necessário apenas "de Acordo" do Gerente** 

 

**Ticket#202101839 — TRANSAÇÃO ZRF0100 - SOLICITO INCLUIR A OPÇÃO DA MOEDA EM REAIS, SÓ APARECE OPÇÃO EM DÓLAR PLANEJADO E PADRÃO. - FILA SAP - IM** 

 

**Ticket#202101751 — SAP RH - Usuário não consegue carregar documentação de férias - FILA HCM - PORTAL** 

 

**Ticket#202101923 — erro na transação MB21 -** Ao clicar na mensagem de erro retornou mensagem "Usuário não possui acesso a criar Reserva. Erro ZIMM1228" - FILA MM 

 

**Ticket#202102000 — [AUDITORIA] - Liberação de Transação ZRMM0290 -** {Transação fiscal, essa transação é tratada pelo colaborador Alderlon Rodrigues e é necessário o "de Acordo" do Gerente Nilton Claudio. 

 

**Ticket#202102175 — Configurar requisitante automático na IBIP - FILA PM** 

 

**Ticket#202102093 — ACESSO AO "SISTEMA DE APONTAMENTO" - FILA PM - ACCESS - É enviado  e-mail apenas com a matricula dos usuários que necessitam do acesso  (exemplo na aba EMAIL) - Transação número** **ZPM_00_04** 

 

**Ticket#202102254 — Orial - Atualização na tabela de NCM - COMEX IMPORTAÇÃO** 

 

Ticket#202102289 — Falha na nota de ocorrência de manutenção - é ocorrência de manutenção e não ocorrência de segurança, sendo assim, segue para fila PM 

 

**Ticket#202102374 — Revisão Semestral de perfis de acesso conforme PG-09-005 ( Auditoria ) - ABAPI** 

 

Ticket#202103097 — Job "[PM] CMMS_ATUALIZACAO_DIARIA" - Adição de Passo – FILA PM  (Transferido para a fila da respectiva transação) 

 

Ticket#202103064 — Liberação de processo - Reprovaçao financeira – Fila SRM (Sistema de  Gestão de Fornecedores – Analista Marcelo Ávila) 

 

**Ticket#202103233 — Acesso a transação FB08 Estornar Documento -**