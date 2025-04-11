# 💻 Versionamento de Código com Git e GitHub
**📚 Resumo das Aulas**
- Repositório criado para fins educacionais para trabalhar em modo colaborativo, no intuito de praticar versionamento de código e colaboração.

**🚨 Git**
- Git é um sistema de controle de versão distribuído, utilizado para rastrear alterações em arquivos de código-fonte durante o desenvolvimento de software.

**🚨 GitHub**
- Plataforma de hospedagem de código para controle de versão com Git e colaboração.

**🚨 Passos para iniciar um repositório Git, criar uma pasta, adicionar um arquivo, salvar as alterações e enviar para o repositório remoto**
- mkdir (nome da pasta): cria uma pasta;
- cd (nome da pasta): muda de pasta;
- git init: inicia o git;
- touch (nome do arquivo com a extensão): cria um arquivo;
- git status: verifica o estatus;
- git add .: adiciona as alterações e faz git status de novo;
- git commit -m "(mensagem do commit)": salva as alterações no branch;
- git branch -M main: nomeia a branch atual para main;
- git remote add origin https://github.com/[seu usuário]/[nome do seu repositório].git : conecta o repositório local a um repositório remoto hospedado no GitHub;
- git push -u origin main: faz o "push"/envia as alterações locais para o repositório remoto no GitHub, na branch main;