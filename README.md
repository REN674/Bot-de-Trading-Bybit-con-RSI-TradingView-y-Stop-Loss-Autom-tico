# Bot de Trading Bybit con RSI TradingView y Stop Loss Automático
**Última actualización:** 2025-04-29 02:33:17 UTC  
**Autor:** REN674

## Descripción
Bot de trading automatizado para Bybit que utiliza el indicador RSI calculado con el método de TradingView para realizar operaciones en el mercado de futuros. Incluye sistema de stop loss automático y soporte para modo hedge.

## Características
- 📊 Cálculo de RSI idéntico a TradingView
- 🛡️ Stop Loss automático con trailing
- ⚔️ Soporte para modo Hedge (posiciones long y short simultáneas)
- ⚡ Ejecución de órdenes en tiempo real
- 📈 Múltiples temporalidades soportadas
- 🔄 Actualización automática del stop loss
- 📱 Compatibilidad con la API de Bybit

## Requisitos Previos
1. Python 3.8 o superior
2. Cuenta en Bybit
3. API Key y Secret de Bybit
4. Modo Hedge activado en tu cuenta

## Instalación
1. Clonar el repositorio o descargar los archivos

2. Instalar las dependencias:
```bash
pip install pybit pandas numpy
