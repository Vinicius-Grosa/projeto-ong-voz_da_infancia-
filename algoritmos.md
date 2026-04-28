Documentação de Algoritmos - Sistema Voz da Infância

1. Algoritmo de Login

1. Usuário acessa a tela de login
2. Insere e-mail e senha
3. Sistema valida:
   - Se os campos estão preenchidos
4. Sistema verifica credenciais
   - Se corretas:
       → Redireciona para o Dashboard
   - Se incorretas:
       → Exibe mensagem de erro


2. Algoritmo de Cadastro de Usuário

1. Usuário clica em "Criar conta"
2. Preenche dados (nome, e-mail, senha)
3. Sistema valida os dados
4. Se válidos:
   - Cria conta
   - Redireciona para login
5. Se inválidos:
   - Exibe erro


3. Algoritmo do Dashboard

1. Sistema carrega dados do usuário
2. Exibe:
   - Valor arrecadado
   - Itens em estoque
   - Vendas do mês
   - Novas doações
3. Permite acesso rápido a:
   - Cadastro de produto
   - Outras funções


4. Algoritmo de Listagem de Produtos

1. Usuário acessa tela "Produtos"
2. Sistema busca lista de produtos
3. Exibe produtos com:
   - Nome
   - Categoria
   - Preço
   - Status (Disponível/Vendido)
4. Permite filtros:
   - Todos
   - Disponíveis
   - Vendidos
5. Permite busca e navegação para detalhes



5. Algoritmo de Detalhes do Produto

1. Usuário seleciona um produto
2. Sistema exibe:
   - Imagem
   - Nome
   - Preço
   - Descrição
   - Código
   - Estado
   - Data de entrada
   - Doador
3. Usuário pode:
   - Editar produto
   - Marcar como vendido

---

6. Algoritmo de Venda

1. Usuário clica em "Marcar como vendido"
2. Sistema altera status do produto
3. Atualiza:
   - Estoque
   - Valor arrecadado
   - Relatórios
4. Confirma ação ao usuário



7. Algoritmo de Navegação (Menu)

1. Usuário abre menu lateral
2. Sistema exibe opções:
   - Dashboard
   - Produtos
   - Doações
   - Vendas
   - Relatórios
   - Perfil
3. Ao clicar:
   - Redireciona para a tela correspondente



8. Fluxo de Dados - Login

Usuário → Tela de Login → Validação → 
[Sucesso] → Dashboard  
[Erro] → Mensagem de erro



## 9. Fluxo de Dados - Venda

Produto → Seleção → Marcar como vendido → 
Atualização do sistema → Dashboard atualizado
