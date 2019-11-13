# A3-servidores
## Pasos para iniciar un servidor SSH

1. Acutalizar repositorios `apt-get update`
2. Instalar servidor SSH `apt-get install ssh-server`
3. Modificar configuracion en /etc/ssh/sshd_config
4. Iniciar servidor `service ssh start`

## Conexión con cliente
1. Instalar Cliente
2. ssh -p <puerto> usuario@host
