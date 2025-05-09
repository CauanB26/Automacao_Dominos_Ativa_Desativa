# Automacao_Dominos_Ativa_Desativa

# Maioria dos dados censurados devido a informação sensível

Visão Geral:
Esta ferramenta automatiza integralmente o processo de ativação e desativação de itens (pizzas e produtos gerais) em um sistema de pontos de venda. Ao substituir tarefas manuais por geração dinâmica de scripts SQL, minimizamos o tempo de processamento e eliminamos gargalos operacionais.

Objetivos do Projeto:
1) Eficiência Operacional: Reduzir o tempo médio de cada atendimento de várias minutos para menos de 20 segundos.
2) Confiabilidade: Garantir consistência entre múltiplas tabelas (ex.: CategoriaTabela, ItemTabela, SaborTabela).


Tecnologias e Bibliotecas:
1) Python 3.8+
2) pandas
Para leitura, tratamento e filtragem dos dados extraídos das planilhas Excel.
3) openpyxl
Engine utilizada pelo pandas para abrir arquivos .xlsx.
4) tkinter (opcional)
Framework nativo do Python para construir a GUI (checkboxes, Listbox, botões) utilizado principalmente para se tornar um sistema fácil de ser usado por outras pessoas que poderiam ter dificuldade com o visual studio e Python "puro".

OBS: Não coloquei alguns materiais (como por exemplo, as planilhas excel utilizadas) por motivos de sensibilidade dos dados

Fluxo de execução:
1) Input: Parâmetros de status e localização.
2) Filtro: Dados carregados e filtrados conforme categorias/descrições.
3) Construção SQL: Declara variáveis e blocos de atualização com placeholders.
4) Output: Script SQL pronto ou execução via ODBC.
