# Azure-speech-language-AI
  Este repositório apresenta os estudos e experimentos realizados utilizando as ferramentas [Azure AI Language Studio](https://learn.microsoft.com/en-us/azure/ai-services/translator/document-translation/language-studio?tabs=local-env) e [Azure AI Speech Studio](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-studio-overview). Ao longo do laboratório foram executados testes práticos para compreender o funcionamento de seus principais recursos e refletir sobre suas possíveis aplicações.
# Análise de Sentimentos - Language Studio
  Para compreender a função de **analise de sentimentos**, foram realizados dois experimentos com resultado predominantemente **positivo** e outro **negativo**. O primeiro resultado obteve 96% positivo, 3% neutro e 1% negativo. O resultado foi baseado na frase "I can describe my experience of this game in two words: "TECHNOLOGY RECHARGED!" #bestdayever". Observa-se que a expressão "#besteverday" possui uma forte carga emocional positiva, influenciando diretamente a classificação do sentimento da análise. A baixa porcentagem atribuída aos sentimentos neutro e negativo demonstra que o algoritmo possui um alto grau de confiança quando encontra palavras e expressões claramente favoráveis.
  
  > Esse experimento demonstra que o modelo não considera apenas palavras isoladas, mas interpreta o contexto geral da frase para determinar o sentimento predominante.

  Agora analisando o teste de resultado negativo, a frase usada foi "The cafeteria food is getting worse by the day...". O resultado retornado é de 94% negativo, 5% neutro e 1% negativo. Faz bastante sentido quando analisamos a frase "getting worse by the day",indicando uma percepção de deterioração contínua da qualidade do serviço, oque reforça a interpretação negativa da frase.

  > Ferramentas desse tipo, podem e são ultilizadas para analisar e monitorar automaticamente avaliações de clientes sobre um estabelecimento ou produto, permitindo identificar tendências de satisfação ou insatisfação dos consumidores.

# Extração de palavras-chave
  Diferente da Análise de Sentimentos ele não procura descobrir os sentimentos da frase, mas identificar automaticamente os principais conceitos presentes em um texto. Isso permite resumir grandes documentos, e extrair todas informações necessarias e mais relevantes.
  No teste efetuado ele pode extrair informações como: endereço, restaurane, empregado, contrato, cronogramas, informações financeiras, prazo etc. o interessante é que ele não tenta resumir, mas buscar descobrir quais são os conceitos importantes.
  > No contexto jurídico, essa funcionalidade pode auxiliar na identificação automática de cláusulas, obrigações, prazos e outras informações relevantes em contratos ou documentos extensos.
