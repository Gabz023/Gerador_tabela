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

- [ ] **Interface gráfica** para maior comodidade.  
- [ ] **Automação avançada**: criação do banco conforme a tecnologia escolhida pelo usuário (ex: MySQL, PostgreSQL, etc.).
- [ ] **Integração com outras IA's**

---

## Tecnologias e Ferramentas  

### Pré-requisitos  
- **Python 3.12.2** ([Download oficial](https://www.python.org/downloads/))  
- **Pip 25.0.1+** (Gerenciador de pacotes)  
- **Chave de API do Google Gemini** ([Obtenha aqui](https://ai.google.dev/))  

### Bibliotecas Principais  
| Biblioteca       | Uso                              |  
|------------------|----------------------------------|  
| `google-generativeai` | Integração com a API Gemini      |  
| Em estudo | Geração de arquivos Excel       |  
<!-- |  `python-dotenv`   | Gerenciamento de variáveis de ambiente (.env) | -->  

*(Lista completa em [`requirements.txt`](./requirements.txt))*  

---

## Como Executar  

1. **Clone o repositório**:  
   ```bash  
   git clone https://github.com/Gabz023/Gerador_tabela

2. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt

3. **Configure a API Gemini**:
   - Coloque sua chave em:
   ```plaintext
   exemplo

4. **Execute o script principal**:
   ```bash
   python src/main.py

---

## Por que o Gemini?

1. **Custo Zero**
   - Plano gratuito com **1.5K requisições/dia** (ideal para projetos pequenos)
   - Limite generoso de **30 chamadas por minuto**

2. **Performance**
   - O modelo **Flash-Lite** é otmizado para respostas rápidas em tarefas de texto
   - Integração simples via `google-generativeai` (biblioteca oficial Python)

3. **Facilidade de uso**
   - [Documentação](https://ai.google.dev) clara da Google
   - Suporte a múltiplos formatos de saída (texto, JSON, etc.).

![Python](https://img.shields.io/badge/Python-3.12.2-%233776AB?logo=python&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-Flash--Lite-%2300B0FF?logo=google-ai&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-%2300A000)
