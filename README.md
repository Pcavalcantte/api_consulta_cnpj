# Consulta CNPJ

Este projeto é um script Python para consultar informações de CNPJ utilizando a API Minha Receita e atualizar uma planilha Excel com os resultados.

## Rol taxativo de funcionalidades
- Carrega uma planilha Excel com CNPJs.
- Consulta informações de CNPJ na API Minha Receita.
- Atualiza a planilha Excel com os resultados da consulta.
- Utiliza múltiplas threads para acelerar o processo de consulta.
- Aplica estilos de célula na planilha Excel para indicar o status da consulta.

## Requisitos
- **Python 3.6 ou superior**
- **Google Chrome**
- **ChromeDriver**

---

# Instalação

## Ao desenvolvedor, siga o manual de instalação: [Manual de Instalação](https://anttgov.sharepoint.com/:w:/r/sites/COAUT/Documentos%20Compartilhados/Manuais/MANUAL%20EXECUTAVEL%20.docx?d=w7803903383db48839031cd9386ba4043&csf=1&web=1&e=fbVucC)

1. **Envie os links**: Envie o link do programa e o link do [Winpython](https://sourceforge.net/projects/winpython/files/latest/download).
2. **Instale**: De preferência na raiz `C:\` do usuário.

## Dependências
As bibliotecas necessárias estão listadas abaixo. Para instalar, localize a pasta Winpython no computador do usuario, abra o prompt de comando e execute:

   ```bash
   pip install pandas requests openpyxl concurrent.futures urlib3
   ```

## Uso

1. Coloque a planilha Excel com os CNPJs no diretório do script e renomeie-a para `dados_cnpj.xlsx`.

2. Execute o programa que tera um atalho na Área de :

O script irá:

- Carregar a planilha Excel.
- Consultar a API Minha Receita para cada CNPJ.
- Atualizar a planilha com os resultados.
- Aplicar estilos de célula para indicar o status da consulta (verde para sucesso, vermelho para falha).

---

## Boas práticas:
O usuário final deve prestar atenção em alguns pontos:
- Sempre verificar a formatação dos itens na planilha.
- Manter a formatação da planilha original.

**Se mesmo assim o erro persistir**: tire um print do erro e insira no ticket em [COAUT - Tíquetes](https://anttgov.sharepoint.com/sites/COAUT)

---

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

---

# Responsavel:

##Pedro Cavalcante


