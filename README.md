# 📜 JSON de Tokens Multichain

Este repositorio contiene un archivo JSON estructurado que lista diferentes tokens en diversas blockchains. El propósito de este archivo es proporcionar una referencia unificada para la identificación de tokens a través de múltiples redes.

## 📌 Estructura del Archivo JSON

El archivo sigue una estructura organizada por redes blockchain, donde cada una contiene información detallada sobre los tokens disponibles en dicha cadena. A continuación, se muestra un ejemplo de la estructura del archivo:

```json
{
    "networks": [
        {
            "name": "Ethereum",
            "chainId": 1,
            "tokens": [
                {
                    "symbol": "USDT",
                    "name": "Tether USD",
                    "address": "0xdac17f958d2ee523a2206206994597c13d831ec7"
                },
                {
                    "symbol": "USDC",
                    "name": "USD Coin",
                    "address": "0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48"
                }
            ]
        },
        {
            "name": "Binance Smart Chain",
            "chainId": 56,
            "tokens": [
                {
                    "symbol": "BNB",
                    "name": "Binance Coin",
                    "address": "0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c"
                },
                {
                    "symbol": "BUSD",
                    "name": "Binance USD",
                    "address": "0xe9e7cea3dedca5984780bafc599bd69add087d56"
                }
            ]
        }
    ]
}
```

## 🔍 Descripción de los Campos

- **networks**: Lista de redes blockchain disponibles.
- **name**: Nombre de la blockchain.
- **chainId**: Identificador de la cadena de bloques según el estándar EIP-155.
- **tokens**: Lista de tokens asociados a la blockchain.
- **symbol**: Símbolo del token.
- **name**: Nombre completo del token.
- **address**: Dirección del contrato inteligente del token en la blockchain.

## 🚀 Casos de Uso

Este archivo JSON puede ser utilizado en múltiples escenarios, tales como:

- Exploración de tokens en diferentes blockchains.
- Integraciones con wallets o DApps.
- Referencia para validación de direcciones de tokens.
- Automatización en sistemas de monitoreo y gestión de activos digitales.

## 📌 Contribuciones

Si deseas agregar más redes o tokens, por favor, abre un Pull Request con la información actualizada. Se recomienda verificar la autenticidad de las direcciones de contrato antes de hacer contribuciones.
