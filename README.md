# Relogio-logico-lamport
O projeto simula um sistema distribuído com 3 clientes e 1 servidor para controlar o acesso de recurso compartilhado. Não existe um relógio global confiável, o sistema utiliza
Relógios Lógicos de Lamport para ordenar corretamente os eventos, garantindo que o processo que ocorreu primeiro seja atendido primeiro.

Abra o arquivo HTML no navegador, preencha para cada cliente a hora local e o valor do clock lógico, clique em “Enviar” para registrar os eventos no servidor e, após enviar todos, 
clique em “Sincronizar”; o sistema então calculará o clock médio, exibirá os ajustes necessários e mostrará a ordem final dos processos, indicando qual cliente terá prioridade no
acesso ao recurso.
