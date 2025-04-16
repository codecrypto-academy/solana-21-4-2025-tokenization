# Proyecto de Bonos de Deuda en Solana

Este proyecto implementa un sistema de bonos de deuda en la blockchain de Solana, utilizando una stablecoin propia llamada EuroCoin y tokens de bonos llamados BonoDeuda.

## Descripción del Proyecto

El proyecto permite la emisión y compra de bonos de deuda con las siguientes características:
- Bonos a N años
- Cupón anual fijo
- Devolución al vencimiento
- Compra mediante la stablecoin EuroCoin

## Fases del Proyecto

### Fase 1: Desarrollo de Smart Contracts
- Creación del token EuroCoin (stablecoin)
- Creación del token BonoDeuda
- Implementación de la lógica de emisión y compra de bonos

### Fase 2: Desarrollo de la Aplicación Web
- Interfaz de usuario con Next.js
- Página principal promocionando los bonos disponibles
- Funcionalidad de compra de bonos usando EuroCoin
- Gestión de cartera de bonos para los usuarios

### Fase 3: Implementación de Funcionalidades Avanzadas
- Mercado secundario para la compra/venta de bonos
- Cálculo automático de intereses y pagos de cupones
- Dashboard para seguimiento de inversiones

## Estructura Técnica

El proyecto utiliza:
- Solana para la blockchain
- Anchor Framework para el desarrollo de programas
- Next.js para el frontend
- Wallet Adapter para la integración de carteras

## Script de Inicialización

El proyecto incluye un script que automatiza:
1. Creación de cuentas emisoras para EuroCoin y BonoDeuda
2. Creación de los tokens
3. Airdrop de SOL a las cuentas necesarias
4. Airdrop inicial de EuroCoin a cuentas de prueba
5. Emisión inicial de BonoDeuda

## Cómo Empezar

1. Clonar el repositorio
2. Instalar dependencias
3. Ejecutar el script de inicialización
4. Iniciar la aplicación web

## Documentación Técnica

La documentación detallada de los smart contracts y la aplicación web se encuentra en la carpeta `/docs`.
