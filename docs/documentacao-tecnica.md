# Documentação Técnica

## 1. Estrutura do Projeto
O projeto está organizado em pastas e ficheiros para facilitar a consulta, a manutenção e a atualização do inventário.

- `README.md` — apresentação geral do projeto.
- `docs/` — documentação do projeto.
- `inventario/` — ficheiro principal do inventário.
- `modelos/` — modelo de inventário para novos registos.

## 2. Ficheiros CSV
O inventário utiliza ficheiros CSV para armazenar os dados dos equipamentos de rede.

Cada registo contém os seguintes campos:

| Campo | Descrição |
|---|---|
| id | Identificador do equipamento |
| equipamento | Tipo de equipamento |
| marca | Fabricante |
| modelo | Modelo do equipamento |
| numero_serie | Número de série |
| endereco_ip | Endereço IP |
| endereco_mac | Endereço MAC |
| localizacao | Localização física |
| estado | Estado operacional |
| observacoes | Informações adicionais |

## 3. Organização do Inventário
O ficheiro `inventario-equipamentos.csv` será utilizado para guardar os registos dos equipamentos.

O ficheiro `modelo-inventario.csv` servirá como modelo para manter a estrutura dos dados.

## 4. Ferramentas
- GitHub para armazenar e documentar o projeto.
- Git para acompanhar as alterações.
- CSV para organizar os dados.
- Markdown para criar a documentação.

## 5. Segurança da Informação
Não devem ser registadas palavras-passe, chaves privadas, dados de acesso ou outras informações confidenciais nos ficheiros do projeto.