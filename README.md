# Proyecto de Bonos de Deuda en Solana

Este proyecto implementa un sistema de bonos de deuda en la blockchain de Solana, utilizando una stablecoin propia llamada EuroCoin y tokens de bonos llamados BonoDeuda.

## Descripción del Proyecto

El proyecto permite la emisión y compra de bonos de deuda con las siguientes características:

- Emision
- Vencimiento
- Nominal
- Pago interes: Anual | Anual
- Tipo de interés: Fijo 
- Cupón: porcentaje
- Devolución al vencimiento
- Compra mediante la stablecoin EuroCoin

## Fases del Proyecto

### Fase 1: Desarrollo del Script de Prueba.

- Creacion de wallet (emisor EuroCC, emisor BonoDeuda, adquirente1, adquirente2)
- Airdrop de SOL a las cuentas necesarias
- Creación del token EuroCC (stablecoin)
- Airdrop de EuroCC a la wallet emisor, adquirente1 y adquirente2
- Creación del token BonoDeuda
- Compra de tokens BonoDeuda con la stablecoin EuroCC (typescript)
- Transferencia de tokens BonoDeuda a otras cuentas (typescript)

### Fase 2: Desarrollo de la Aplicación Web para la emisión y compra de bonos usando un MCP server.
- El mcp server debe permitir:
    - Crear bonos
    - Comprar bonos
    - Transferencias de bonos entre wallets
    - Consulta de bonos y saldo de EuroCC
    - Consulta de bonos y saldo de EuroCC
    


## Arquitectura del proyecto

### Tecnologias usadas

- Solana
    - Solana Cli
    - Solana Test Validator
    - Spl-token
    - Anchor
- Next.js en Typescript con Shadcn UI
