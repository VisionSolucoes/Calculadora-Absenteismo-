# Calculadora de Absenteísmo

![Calculadora de Absenteísmo](./src/images/preview.png)

## 📋 Sobre o Projeto

Desenvolvido por Jordana Almeida, Analista de Recursos Humanos, esta calculadora é uma ferramenta profissional para análise e monitoramento de taxas de absenteísmo em empresas.

### Funcionalidades Principais

- 🏢 Cálculo de absenteísmo por grupos de funcionários
- 📊 Análise detalhada por departamento/setor
- 📈 Geração de relatórios em Excel
- 🖨️ Relatórios prontos para impressão
- 📝 Detalhamento do cálculo passo a passo

## 🧮 Como é Calculado

O índice de absenteísmo é calculado considerando:

1. **Por Grupo:**

   - Número de funcionários
   - Dias trabalhados no mês
   - Carga horária diária
   - Total de horas de ausência

2. **Fórmula:**
   ```
   Taxa de Absenteísmo = (Total de Horas de Ausência ÷ Total de Horas Previstas) × 100
   ```

## 🚀 Tecnologias Utilizadas

- React.js
- TypeScript
- Tailwind CSS
- Vite
- XLSX (para exportação Excel)

## 💻 Como Usar

1. **Instalação**

   ```bash
   # Clone o repositório
   git clone https://github.com/seu-usuario/nome-do-repositorio

   # Entre na pasta do projeto
   cd nome-do-repositorio

   # Instale as dependências
   npm install
   ```

2. **Rodando o Projeto**

   ```bash
   # Inicie o servidor de desenvolvimento
   npm run dev
   ```

3. **Gerando Build**
   ```bash
   # Crie uma build de produção
   npm run build
   ```

## 📱 Uso da Calculadora

1. **Configuração de Grupos**

   - Adicione grupos de funcionários
   - Preencha os dados de cada grupo:
     - Nome do grupo
     - Quantidade de funcionários
     - Carga horária diária
     - Dias trabalhados
     - Horas de ausência

2. **Análise de Resultados**
   - Visualize a taxa de absenteísmo
   - Examine detalhes por grupo
   - Exporte relatórios em Excel
   - Imprima resultados

## 📄 Exemplo de Cálculo

https://visionsolucoes.github.io/calculadora-absenteismo/
