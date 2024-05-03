# Links usados
- [Monitora desempenho das máquinas](https://medium.com/@subhomay/enhance-efficiency-server-monitoring-simplified-with-ansible-and-cpu-ram-disk-418572c23107)
- [Monitora disponibilidade das máquinas](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/wait_for_connection_module.html#ansible-builtin-wait-for-connection-waits-until-remote-system-is-reachable-usable)

## O que temos que fazer:

- Setup básico das 4 VMs
  1. Sistema de Monitoramento
  2. Servidor 1 (apache)
  3. Servidor 2 (dns)
  4. Servidor de backup (playbook deve fazer setup do servidor 1/2 em caso de queda)
- ~~Scripts de disponibilidade e monitoramento de recursos~~
- Playbooks de instalação de tudo que é essencial nesses sistemas, separados por cada máquina específica.

## Terminado isso:

- Enviar esse repositório
- Gravar um vídeo (max. 5min) apresentando a solução e explicando-a
