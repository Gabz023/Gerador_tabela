# Gerador de tabela
 Gera rapidamente uma tabela para testes de programas que usam banco de dados

~~~

# Ferramenta de Automação de Banco de Dados

Para vários projetos que já precisei desenvolver e que necessitavam de banco de dados, criar um banco do zero era sempre uma tarefa **monótona** e que tomava **muito tempo**.  
Pensando nisso, resolvi criar esta ferramenta.  

## Funcionamento Inicial  

A ferramenta irá:  
1. Registrar:  
   - A **quantidade de campos** desejados no banco de dados.  
   - O **número de entidades**.  
   - A **natureza dos dados** que ocuparão esses campos.  

2. Compilar as informações em um *prompt* e enviar a requisição para uma **IA**.  
3. Retornar o resultado em:  
   - Arquivo de texto (`.txt`).  
   - Arquivo Excel (`.xls` ou `.xlsx`).  

## Roadmap Futuro  

- [ ] **Interface amigável** para maior comodidade.  
- [ ] **Automação avançada**: criação do banco conforme a tecnologia escolhida pelo usuário (ex: MySQL, PostgreSQL, etc.).
