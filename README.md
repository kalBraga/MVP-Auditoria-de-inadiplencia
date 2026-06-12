# 📊 MVP - Auditoria de Inadimplência

[cite_start]MVP criado para me auxiliar em uma demanda bastante manual do meu trabalho, que é o cruzamento de dados de vários contracheques e uma planilha de faturamento[cite: 199]. [cite_start]Para identificar clientes que por algum motivo ficaram inadimplentes com a empresa que trabalho[cite: 200]. [cite_start]Você pode usar esse MVP para comparar outras coisas, sinta-se livre em acessar o código[cite: 201].

## 🚀 Tecnologias e Regra de Negócio
* **Linguagem:** C# .NET 10
* **Interface:** Console Application (Terminal)
* **Validação:** Chave de Identificação Única Composta (CPF + Mês de Referência + Número da Parcela + Valor)

## ⚙️ Como Executar
1. Certifique-se de ter o .NET 10 SDK instalado.
2. Clone este repositório ou baixe os arquivos fonte.
3. Abra o terminal na pasta raiz do projeto.
4. Execute o comando `dotnet run`.
5. [cite_start]Siga as instruções no terminal para alimentar o sistema com os seus arquivos .csv ou .txt[cite: 201].

## 📈 Saída e Relatórios
O sistema processará as informações em memória e retornará no próprio terminal uma auditoria clara e visual:
* [cite_start]🟢 **Verde (Pagamento Localizado):** Todas as validações da chave composta bateram perfeitamente[cite: 202].
* [cite_start]🟡 **Amarelo (Verificar Inadimplência):** Cliente consta no faturamento, mas a parcela exata não foi localizada nos contracheques do mês de referência[cite: 203].

---
[cite_start]Desenvolvido como projeto de aprendizado prático e automação de rotina[cite: 204].
