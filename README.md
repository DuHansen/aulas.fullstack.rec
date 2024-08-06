# aulas.fullstack.rec
Repositorio GitHub

#Configuração ssh

1 - Abra o Git Bash
2 - ssh-keygen -t ed25519 -C "your_email@example.com"

3 - Inicializar o ssh-agent: eval $(ssh-agent -s)

4 - Incluir a chave privada:
ssh-add ~/.ssh/id_ed25519

5 - Copia a chave ssh:
cat ~/.ssh/id_ed25519.pub

6 - Testar chave ssh: ssh -T git@github.com
