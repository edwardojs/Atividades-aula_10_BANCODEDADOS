# Atividades-aula_10_BANCODEDADOS
bancodedados 
1. Para que serve a chave primária em um banco de dados?

Resposta: c. Identificar unicamente cada linha de uma tabela.

2. Qual a importância da modelagem conceitual?

Resposta: b. Permite compreender o que o banco precisa representar e as regras do negócio.

3. Qual das opções representa um erro comum na modelagem?

Resposta: d. Decidir sozinho o modelo conceitual do banco.

4. O que acontece se tentar inserir duas linhas com a mesma chave primária?

Resposta: b. O sistema apresentaria erro, pois a chave primária deve ser única.

5. Identifique entidades e principais atributos.

Funcionário: id, nome, cargo, salário

Departamento: id, nome

Projeto: id, nome, prazo

6. Qual a chave primária de cada tabela e a relação entre elas?

Cliente: id_cliente (PK)

Pedido: id_pedido (PK)

Relação: id_cliente como chave estrangeira em Pedido.

7. Requisitos do sistema de hotel.

Funcionais:

Registrar hóspedes

Registrar reservas

Registrar quartos

Consultar disponibilidade

Emitir comprovante

Cancelar reserva

Registrar pagamentos

Controlar check-in/check-out

Não funcionais:

Segurança

Disponibilidade 24h

Tempo de resposta rápido

Backup automático

Interface intuitiva

8. O que significa um atributo ser chave primária?

Resposta: a. Nenhum produto poderá ter o mesmo código.

9. Diferença entre modelo conceitual e lógico.

Resposta: b. O conceitual descreve o negócio; o lógico traduz para tabelas.

10. Em qual etapa a entidade é identificada?

Resposta: c. Modelagem conceitual.

11. Vantagem da modelagem de dados.

Resposta: c. Garante integridade, segurança e consistência.

12. Entidades e atributos.

Cliente: id, nome, telefone

Produto: id, nome, preço

Venda: id, data, id_cliente

13. Representação relacional da clínica.

PACIENTE(id_paciente PK, nome, telefone)

MÉDICO(id_medico PK, nome, especialidade)

CONSULTA(id_consulta PK, data, id_paciente FK, id_medico FK)

14. Sistema de rede social.

Funcionais: cadastrar usuários; enviar mensagens
Não funcionais: alta disponibilidade; criptografia
Entidade: usuário (id, nome, email, senha)

15. Explicações.

a) Modelagem organiza os dados, evita erros e facilita alterações.
b) O SGBD controla acesso, evita duplicidade e mantém integridade.

16. O que é chave primária?

Resposta: a. Uma combinação única que identifica registros.

17. Qual é a entidade?

Resposta: b. “Produto” é a entidade.

18. Em que consiste o levantamento de requisitos?

Resposta: b. Entender o que o sistema deve armazenar e como deve funcionar.

19. Loja de roupas – entidades e modelo relacional.

Entidades: Cliente, Produto, Venda

Atributos:

Cliente: id_cliente PK, nome, telefone, endereço

Produto: id_produto PK, nome, preço

Venda: id_venda PK, data, id_cliente FK

Modelo relacional:
CLIENTE(id_cliente PK, nome, telefone, endereco)
PRODUTO(id_produto PK, nome, preco)
VENDA(id_venda PK, data, id_cliente FK)