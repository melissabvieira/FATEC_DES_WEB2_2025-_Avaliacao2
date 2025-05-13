# FATEC_DES_WEB2_2025-_Avaliacao2
Durante a atividade avaliativa da disciplina Desenvolvimento Web 2, foi proposto o seguinte desafio técnico:

Desafio Técnico:
Desenvolver um sistema em PHP para que um lojista possa cadastrar, visualizar e remover produtos de sua loja virtual.
O sistema deve permitir a gestão de produtos apenas após a autenticação do usuário por meio de login com sucesso.

Funcionalidades Implementadas

Os principais requisitos do sistema foram plenamente atendidos. As funcionalidades desenvolvidas incluem:

Autenticação de Usuário (Login e Logout):
Implementação de um sistema de login seguro, utilizando sessões PHP para autenticar o lojista com o usuário ADMIN. O logout finaliza a sessão e redireciona o usuário para a página de login.

Cadastro de Produtos:
O lojista pode cadastrar novos produtos no sistema, informando nome, preço, descrição e categoria. Os dados são validados e armazenados no banco de dados MySQL.

Listagem de Produtos:
Após o login, é possível visualizar a lista de produtos cadastrados no estoque da loja em uma tabela vinculada ao banco de dados.

Remoção de Produtos:
Cada item listado possui a opção de exclusão, permitindo que o lojista remova produtos do sistema diretamente pela interface.

Tecnologias Utilizadas
Banco de Dados: MySQL, acessado por meio da plataforma phpMyAdmin, disponibilizada pelo XAMPP.

Ambiente de Desenvolvimento: Visual Studio Code (VSCode) como editor de código-fonte principal.

Servidor Local: XAMPP para simular um ambiente de produção local com Apache e MySQL.

Extras e Boas Práticas Adotadas
Organização em Módulos/Páginas Separadas: Separação entre arquivos de conexão, lógica de negócio e interface para facilitar a manutenção.

Validação de Formulários: Implementação de verificações básicas nos formulários para evitar envio de dados em branco.

Segurança: Utilização de session_start() para controle de acesso, com verificação de sessão ativa em todas as páginas restritas.

Feedback Visual: Exibição de mensagens de sucesso ou erro para orientar o usuário após ações como cadastro ou remoção de produtos.
