# OcurrencesPrediction

# **Dicionário**

id_ocorrencia - identificação única da ocorrência

cidade - A cidade onde aconteceu a ocorrência

população - Pupulação da cidade

horario - horario da ocorrencia com data e hora

vtr - viatura empenhanha na ocorrencia

mtcl - matricula do militar ou cpf do Bombeiro comunitario

militar_bc - identificação se o individuo é Bombeiro Comunitário ou Bombeiro 
Militar

bc_indenizado - Identifica se o Bombeiro Comunitario estava no serviço sendo 
pago(indenizado) ou não

obm - Organização Bombeiro Militar que estava na ocorrência

coordenada_obm - Coordenada da organização Bombeiro Militar

coordenada_ocorrencia - Coordenada da Ocorrência

lat_ocorrencia - Latitude ocorrência

lon_ocorrencia - Longitude Ocorrência

tipo - Tipo da ocorrência, pode ser Atendimento pré-hospitalar - APH, incendio, acidente e outros.

subtipo - especifica o tipo, num APH, pode especificar desmaio, nem sempre é preenchido.

tempo_resposta - Tempo do acionamento até a chegada ao local da ocorrêcia, pode ser um dado que estaja bem falho, pois acontece do bombeiro esquecer de clicar no botão

tempo_total_empenho - tempo total da saída da obm até a chegada a obm novamente.
firecast - indica se uma viatura utilizou o sistema "firecast" para dar J-9, J-10, J-11 e J-12 nos deslocamentos

origem_samu - Se foi um repasse da ocorrência que era do samu

vitima - geração no sistema, talvez de pra gerar o número de vítimas, nome, idade, alguns sinais vitais.
