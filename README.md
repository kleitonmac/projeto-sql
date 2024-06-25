Odonto Vida
O projeto "Odonto Vida" é uma aplicação desenvolvida como parte de um trabalho acadêmico para apresentação na faculdade. Este sistema tem como objetivo simular o gerenciamento das atividades de uma clínica odontológica, oferecendo funcionalidades essenciais para facilitar o fluxo de trabalho dos profissionais da área.

Pré-requisitos
Antes de começar a seguir, verifique se você atende aos requisitos:

Node.js e npm instalados (recomendado: versão v18.17.0)
Git
XAMPP instalado e configurado
IDE (por exemplo, Visual Studio Code) instalado
Instalação
Passo 1: Criar a Pasta do Projeto
Abra o Explorador de Arquivos (exemplo: Windows Explorer).
Navegue até o diretório onde o XAMPP está instalado. Normalmente, é C:\xampp.
Dentro da pasta xampp, abra a pasta htdocs.
Dentro da pasta htdocs, crie uma nova pasta chamada projeto.
Passo 2: Pegar o Link do Repositório
Abra seu navegador web e vá para [ https://github.com/BrazSouza/ontological-clinic/tree/main ].
Clique no botão Code (verde) e depois em HTTPS .
Copie o link fornecido (começa com https://github.com/...).
Passo 3: Usando o Terminal do IDE (por exemplo, Visual Studio Code)
Abra seu IDE (por exemplo, Visual Studio Code).
Abra o terminal integrado. No Visual Studio Code, você pode fazer isso clicando em Terminal > Novo Terminal no menu superior.
Navegue até a pasta htdocs\projetodo XAMPP no terminal da IDE:
cd C:\xampp\htdocs\projeto
Clone o repositório dentro da pastaC:\xampp\htdocs\projeto
git clone -b main https://github.com/BrazSouza/ontological-clinic.git
Navegue até a pasta C:\xampp\htdocs\projeto\ontological-clinic
cd C:\xampp\htdocs\projeto\ontological-clinic
Instale as dependências do projeto
npm install
Configuração do Banco de Dados
Inicie o servidor Apache e MySQL do XAMPP.
-se de que o arquivo do banco de dados está incluído no backend do clichê do projeto.
Não é necessário criar um novo banco de dados, pois o esquema já está presente no arquivo fornecido.
Como usar
Inicie o servidor de desenvolvimento do React no terminal da IDE (por exemplo, Visual Studio Code)

npm run dev
Acesse o projeto em seu navegador através do endereço:

http://localhost:5173/
Acessando o banco de dados
Acesse o banco de dados através do MySQL do phpMyAdmin

http://localhost/phpmyadmin/
Clique em banco de dados no painel

Crie um banco de dados chamado clinic_dbno campoNome do Banco

clique no campo ao lado do campo Nome do Bancoe escolha a opção utf8_general_cie clique no botãocriar

Clique em importare depois em procurarouescolher arquivo

Acesse C:\xampp\htdocs\projeto\ontological-clinic\backende selecione o arquivoclinic_db

Clique no importarpainel banco de dados

Contribuição
Contribuições são o que fazem a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será muito apreciada .

Garfo o projeto
Crie seu branch de feature ( git checkout -b feature/AmazingFeature)
Comprometa suas mudanças ( git commit -m 'Add some AmazingFeature')
Empurre para um galho ( git push origin feature/AmazingFeature)
Abra um pull request
Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

Contato
Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato através do email: srbraz.silva@gmail.com

Reagir + Vite
Este modelo fornece uma configuração mínima para fazer o React funcionar no Vite com HMR e algumas regras ESLint.

Atualmente, dois plugins oficiais estão disponíveis:

@vitejs/plugin-react usa [Babel]( https://babeljs .io/) para atualização rápida
@vitejs/plugin-react-swc usa SWC para atualização rápida
