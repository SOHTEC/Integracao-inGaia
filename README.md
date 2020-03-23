## Como adicionar o botão da SOHTEC nos sites padrão do inGaia.

Veja abaixo os passos necessários para inserir o botão da SOHTEC em seu site, e utilizar todos os recursos da nossa plataforma.

### 1º - Adicionar as bibliotecas

Na área do inGaia Sites acesse Configurar - Scripts (avançado) e insira no início da tag **HEAD** do site a chamada para os scripts da biblioteca da SOHTEC.

**Obs:** O **ID_DA_SUA_EMPRESA** é fornecido pela SOHTEC no momento do contrato.

Exemplo:
```html {.line-numbers}
<script src="https://sohtec.com.br/services/Scripts/ClientProd.js" type="text/javascript"></script>
<script src="https://sohtec.com.br/services/scripts/libintegracao/ingaia/sohtec-ingaia-1.0.js?id=ID_DA_SUA_EMPRESA"></script>
<link href="https://sohtec.com.br/services/scripts/libintegracao/ingaia/soh-ingaia.css" rel="stylesheet" />
```
