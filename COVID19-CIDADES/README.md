# ZBX-GRA-COVID19-CIDADES-POR-ESTADO
Template_Module_HTTP_LLD_Brazil_Corona

Homologado: 

Necessario ser Zabbix 4.4.6

Importe o Template_Module_HTTP_LLD_W_Corona para o Zabbix 

Crie um host com nome "BRASIL-CORONA-COVID19", pode usar interface local (127.0.0.1: 10050) e o Hostgroup use o nome "CORONAVIRUS" e vincule o template ao host. 

Aguarde coleta de dados, ou utilize a função "Check now" no item e no LLD para agilizar a coleta

Necessário alterar a macro do Estado, consultar o estado na url:

https://brasil.io/api/dataset/covid19/caso/data/?format=json&is_last=True

Consultar o a chave state.

Obs: Não Terminado, disponibilizado para continuação do projeto.