# Azure-speech-language-AI
  Este repositório apresenta os estudos e experimentos realizados utilizando as ferramentas [Azure AI Language Studio](https://learn.microsoft.com/en-us/azure/ai-services/translator/document-translation/language-studio?tabs=local-env) e [Azure AI Speech Studio](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-studio-overview). Ao longo do laboratório foram executados testes práticos para compreender o funcionamento de seus principais recursos e refletir sobre suas possíveis aplicações.
# Análise de Sentimentos - Language Studio
  Para compreender a função de **analise de sentimentos**, conduzi um teste com resultado predominantemente **positivo** e outro **negativo**. O primeiro resultado obteve 96% positivo, 3% neutro e 1% negativo. O resultado foi baseado na frase "I can describe my experience of this game in two words: "TECHNOLOGY RECHARGED!" #bestdayever". Como podemos reparar a expressão "#besteverday" possui uma forte carga emocional positiva, afetando direta e predominatemente o resultado da análise. A baixa porcentagem atribuída aos sentimentos neutro e negativo demonstra que o algoritmo possui um alto grau de confiança quando encontra palavras e expressões claramente favoráveis.
  
  > Está análise mostra que o modelo não analisa apenas palavras isoladas, ele analisa o texto como um todo, extraindo o maximo de informações possiveis para gartir um resultado presciso.

  Agora analisando o teste de resultado negativo, a frase usada foi "The cafeteria food is getting worse by the day...". O resultado retornado é de 94% negativo, 5% neutro e 1% negativo. Faz bastante sentido quando analisamos a frase "getting worse by the day", oque indica uma deterioração continua no estabelecimento, oque reforça a interpretação negativa da frase.

  > Ferramentas desse tipo, podem e são ultilizadas para analisar e monitorar automaticamente avaliações de clientes sobre um estabelecimento ou produto.

# Extração de palavras-chave
  Diferente da Análise de Sentimentos ele não procura descobrir os sentimentos da frase, mas extrair informações e dados importantes do texto. Isso permite resumir grandes documentos, e extrair todas informações necessarias e mais relevantes.
  No teste efetuado ele pode extrair informações como: endereço, restaurane, empregado, contrato, cronogramas, informações financeiras, prazo etc. o interessante é que ele não tenta resumir, mas buscar descobrir quais são os conceitos importantes.
  > Podemos destacar um exemplo para o uso dessa ferramenta, como destacar automaticamente cláusulas e informações relevantes em documentos extensos no ramo jurídico.
