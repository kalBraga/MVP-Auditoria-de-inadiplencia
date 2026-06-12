# 📊 MVP - Auditoria de Inadimplência

MVP criado para me auxiliar em uma demanda bastante manual do meu trabalho, que é o cruzamento de dados de vários contracheques e uma planilha de faturamento.Para identificar clientes que por algum motivo ficaram inadimplentes com a empresa que trabalho. Você pode usar esse MVP para comparar outras coisas, sinta-se livre em acessar o código.

## 🚀 Tecnologias e Regra de Negócio
* **Linguagem:** C# .NET 10
* **Interface:** Console Application (Terminal)
* **Validação:** Chave de Identificação Única Composta (CPF + Mês de Referência + Número da Parcela + Valor)

## ⚙️ Como Executar
1. Certifique-se de ter o .NET 10 SDK instalado.
2. Clone este repositório ou baixe os arquivos fonte.
3. Abra o terminal na pasta raiz do projeto.
4. Execute o comando `dotnet run`.
5. Siga as instruções no terminal para alimentar o sistema com os seus arquivos .csv ou .txt:.

## 📈 Saída e Relatórios
O sistema processará as informações em memória e retornará no próprio terminal uma auditoria clara e visual:
* 🟢 **Verde (Pagamento Localizado):** Todas as validações da chave composta bateram perfeitamente.
* 🟡 **Amarelo (Verificar Inadimplência):** Cliente consta no faturamento, mas a parcela exata não foi localizada nos contracheques do mês de referência.

---
Desenvolvido como projeto de aprendizado prático e automação de rotina.
