## GCreator – Google Workspace User Automation
GCreator é uma ferramenta completa para automatizar a criação de usuários no Google Workspace a partir de dados em uma planilha do Google Sheets. Desenvolvido em Google Apps Script, este sistema é ideal para instituições educacionais, empresas ou qualquer organização que precise provisionar múltiplas contas com segurança e praticidade.

### Funcionalidades
Leitura de dados de múltiplas abas da planilha;

Geração automática de e-mails institucionais baseados no nome dos usuários;

Verificação de e-mails já existentes e criação com sufixos numéricos incrementais;

Criação de usuários com senha provisória, ativação da troca de senha no primeiro acesso;

Geração e atribuição automática de aliases (e-mails alternativos);

Adição dos usuários a grupos do Google;

Envio automático de e-mails personalizados com instruções de acesso e senha;

Verificação assíncrona da criação dos usuários antes de seguir com ações subsequentes;

Controle por logs para fácil rastreamento de erros e execuções.

### Stack e Tecnologias
Google Apps Script

Admin SDK (Directory API & Groups API)

Google Sheets API

GmailApp para automação de comunicações

ScriptProperties para controle de paginação e execuções

### Pré-requisitos
Conta com permissões de administrador no Google Workspace

API do Admin SDK ativada no Google Cloud Console

Planilha modelo com colunas de nome completo, e-mail pessoal, UO e grupo

