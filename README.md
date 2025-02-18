# **Conversor CSV para SQL**

O **Conversor CSV para SQL** é uma ferramenta simples que permite a conversão de dados de arquivos CSV para comandos SQL (`INSERT`, `UPDATE` e `DELETE`). Você pode gerar os comandos SQL com base nos dados do CSV e salvar o resultado em um arquivo `.txt` para fácil uso em seu banco de dados.

## **Características**

- **Carregamento de Arquivo CSV**: Selecione e carregue um arquivo CSV para ser convertido.
- **Geração de Comandos SQL**:
  - **INSERT**: Crie comandos `INSERT` para inserir registros no banco de dados.
  - **UPDATE**: Gere comandos `UPDATE` para atualizar registros com base em um `WHERE`.
  - **DELETE**: Crie comandos `DELETE` para excluir registros com base em um `WHERE`.
- **Salvamento de SQL**: Os comandos SQL gerados podem ser salvos em um arquivo `.txt` para posterior execução.

## **Requisitos**

### **Dependências**

Este projeto utiliza o Python e algumas bibliotecas. Se você estiver utilizando o código-fonte, será necessário instalar as dependências abaixo:

- **Python 3.x** (caso não tenha instalado)
- **Bibliotecas**:
    - `pandas` — Para manipulação de dados do CSV
    - `ttkbootstrap` — Para a interface gráfica
    - `numpy` — Para trabalhar com tipos numéricos
    - `tkinter` — Para a construção da interface gráfica

Para instalar as dependências, execute:

```bash
pip install pandas ttkbootstrap numpy
