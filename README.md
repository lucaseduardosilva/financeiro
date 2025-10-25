# 💰 Sistema de Controle Financeiro

Um sistema web completo para controle e análise de finanças pessoais, desenvolvido com HTML, CSS e JavaScript puro.

## 🚀 Funcionalidades

### 📊 Controle Financeiro (`index.html`)
- **Importação de CSV**: Importe dados de planilhas Excel/Google Sheets
- **Gestão de Despesas**: Adicione, edite e remova despesas mensais
- **Controle de Pagamentos**: Marque despesas como pagas/não pagas
- **Resumo Financeiro**: Visualize receitas, gastos e saldo mensal/anual
- **Exemplo CSV**: Baixe arquivos de exemplo para entender o formato

### 📈 Dashboard (`dashboard.html`)
- **Métricas Visuais**: Cards com receita total, gastos e saldo
- **Gráficos Interativos**: 
  - Evolução mensal de receitas e gastos
  - Distribuição de gastos por categoria
  - Comparação receita vs gastos
  - Saldo mensal
  - Taxa de poupança
- **Insights Inteligentes**: Análises automáticas dos seus dados financeiros

## 📁 Estrutura do Projeto

```
financeiro/
├── index.html              # Página principal (controle financeiro)
├── dashboard.html          # Dashboard com gráficos e análises
```

## 🛠️ Como Usar

### 1. Primeira Utilização
1. Abra o arquivo `index.html` no navegador
2. Clique em "📄 Exemplo CSV" para baixar os arquivos de exemplo
3. Abra o `Example.csv` em um editor de planilhas (Excel, Google Sheets, etc.)
4. Siga as instruções do `tutorial.txt`

### 2. Preenchimento dos Dados
1. **Salário**: Preencha o valor mensal na coluna "Salário"
2. **Despesas**: 
   - Coluna "Valor": Valor da despesa (apenas números)
   - Coluna "Despesa": Descrição da despesa
3. **Manipulação**: 
   - Se sobrar linhas: deixe em branco
   - Se faltar linhas: adicione novas linhas
   - Mantenha tabelas separadas por 1 linha
   - Verifique se os cálculos estão corretos

### 3. Importação dos Dados
1. Salve o arquivo como CSV
2. No sistema, clique em "📁 Importar CSV"
3. Selecione o arquivo CSV
4. Os dados serão importados automaticamente

### 4. Visualização e Análise
1. Use o "📈 Dashboard" para ver gráficos e análises
2. Navegue entre os meses no controle financeiro
3. Adicione novas despesas diretamente no sistema
4. Marque despesas como pagas/não pagas

## 📋 Formato do CSV

O arquivo CSV deve seguir esta estrutura:

```csv
,,,,,
,Planejamento mensal,,,,
,,,,,
,Mês,Salário,Valor,Despesa,Foi pago
,Janeiro,,,,
,,,,,
,,,,,
,Sobrou:,"R$ 0,00",Total de gastos:,,"R$ 0,00"
```

### Campos Importantes:
- **Salário**: Valor da receita mensal
- **Valor**: Valor da despesa (apenas números)
- **Despesa**: Descrição da despesa
- **Foi pago**: Campo não utilizado (funciona apenas no site)

## 🎨 Características Técnicas

- **Responsivo**: Funciona em desktop, tablet e mobile
- **Offline**: Funciona sem internet após carregar
- **Armazenamento Local**: Dados salvos no navegador
- **Sem Backend**: Aplicação 100% frontend
- **Compatível**: Funciona em todos os navegadores modernos

## 🔧 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Design responsivo e animações
- **JavaScript ES6+**: Lógica da aplicação
- **Chart.js**: Gráficos interativos
- **JSZip**: Criação de arquivos ZIP
- **LocalStorage**: Armazenamento de dados

## 📱 Compatibilidade

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

## 🚀 Instalação

1. Clone ou baixe o projeto
2. Abra `index.html` no navegador
3. Pronto! Não precisa de servidor ou instalação

## 📄 Licença

Este projeto é de uso livre para fins pessoais e educacionais.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir melhorias
- Enviar pull requests

## 📞 Suporte

Para dúvidas ou problemas:
1. Verifique o arquivo `tutorial.txt`
2. Teste com o arquivo `Example.csv` fornecido
3. Verifique se o formato do CSV está correto

---
