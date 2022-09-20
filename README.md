# Magento 2 Ocultar Preço Não Entrar

Esta extensão é usada para ocultar o preço na categoria e detalhes do produto quando o usuário não faz login, inclui configuração na configuração para ativar ou desativar quando e definir o texto padrão

## Características:

### A parte dianteira
- ocultar preço final na categoria
- ocultar o preço final no detalhe do produto

### Processo interno
- configuração para habilitar e desabilitar extensão
- definir o texto padrão

## Instalação de introdução:

### Instalar Magento 2 Ocultar Preço Não Entrar
- ⇬ Fazer download do arquivo
- Descompacte o arquivo
- Crie uma pasta [root]/app/code/Dangs/Hideprice
- Copiar para pasta

### Ativar extensão

```
módulo php bin/magento: habilite Dangs_Hideprice
php bin/magento configuração: atualização
php bin/cache do magento:limpo
php bin/magento setup:static-content:deploy