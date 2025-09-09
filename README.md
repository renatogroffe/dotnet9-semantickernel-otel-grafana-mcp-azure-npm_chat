# dotnet9-semantickernel-otel-grafana-mcp-azure-npm_chat
Exemplo em .NET 9 de Console Application que faz uso do projeto Semantic Kernel, com integração com soluções de IA como Azure Open AI e Ollama na interação com um servidor MCP - utilizei o Azure MCP para testes (package npm). Inclui Docker Compose para criação do ambiente de testes com os serviços de monitoramento do Grafana + OpenTelemetry.

---

## Exemplos de uso

Consultando informações sobre a subscription do Azure:

![MCP Azure - Subscription](img/mcp-azure-01.png)

Resultado no Grafana:

![Grafana - Subscription](img/grafana-01.png)

Consultando informações sobre um recurso Azure Container Registry (ACR):

![MCP Azure - ACR](img/mcp-azure-02.png)

E o resultado da instrumentação no Grafana:

![Grafana - ACR](img/grafana-02.png)