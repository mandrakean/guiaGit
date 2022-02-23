Esse projeto ensina a usar o Git.

Primeiro cadastre email e senha = git config user.name <name>  /  git config usar.email <email> 

para criar um novo repositório = git init /* se necessário em seguida especifique o diretório */

Se o repositório já existe, clone ele para sua máquina = git clone <repo>

adiciona algum arquivo para ser "vigiado" (staged) = git add <archive or directory>

Ou adicione todos os arquivos da pasta para o staged = git add .

assim vc commita o que tá staged. = git commit -m "mensagem" 

adicionando para o github, vc faz isso após criar o repo lá no github. = git remote add origin <URL>

mudar para a branch main = git checkout <main>

manda pro github, usar o nome da branch em questão. = git push origin <BRANCH>

para mudar para uma nova branch = git checkout -b <nomeDaNovaBranch>
