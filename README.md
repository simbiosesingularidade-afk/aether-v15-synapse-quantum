# 🚀 Aether v15 Synapse Quantum

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python 3.12](https://img.shields.io/badge/python-3.12+-blue.svg)

Sistema de trading algorítmico de alta performance com gestão de risco institucional.

## 🎯 Visão Geral

O **Aether v15 Synapse Quantum** é um bot de trading autônomo que opera 24/7 na Binance, utilizando estratégias quantitativas avançadas e múltiplas camadas de proteção de risco.

## ✨ Features Principais

### 🤖 Estratégias Adaptativas
- **T1 Blue Chip**: BTC, ETH com sinais de alta confiabilidade
- **T2 Alts**: 14+ tokens de alta capitalização com 11 sinais técnicos
- **T3 Memes**: 13+ tokens de volatilidade alta com 7 sinais
- **PAXG Safe Haven**: Hedge automático em ouro digital

### 🛡️ Gestão de Risco (15 Camadas)
- Kelly Criterion & Quarter Kelly (Ed Thorp)
- Trailing Stop adaptativo (0.4% → 8%)
- Anti-vício (1 loss = block 24h)
- Sector Lock (2 losses = block 4h)
- Daily Stop Loss (5%)
- Max Positions limit
- Partial Sell @ 60% TP
- Whale Radar (detecta movimentos >$1M)
- E mais...

### 📊 Indicadores Técnicos
- MACD (12, 26, 9)
- Stochastic RSI
- Squeeze TTM
- EMA Cross
- ADX com +DM/-DM
- Momentum indicators

## 🛠️ Stack Tecnológico

```
Python 3.12+
├── asyncio (async I/O)
├── ccxt.pro (exchange-agnostic)
├── pandas/numpy (análise quantitativa)
├── aiohttp (async HTTP)
└── asyncio (event loop)
```

## 📦 Instalação

### Pré-requisitos
```bash
Python 3.12+
pip install ccxt pandas numpy aiohttp
```

### Configuração
```bash
# Variables de ambiente
export BINANCE_API_KEY="sua_key"
export BINANCE_SECRET="seu_secret"
export TELEGRAM_TOKEN="seu_token"
export TELEGRAM_CHAT_ID="seu_chat_id"
```

## 🚀 Execução

```bash
python trading_bot.py
```

## 📁 Estrutura do Projeto

```
aether-v15-synapse-quantum/
├── trading_bot.py          # Bot principal
├── strategies/              # Módulos de estratégia
├── indicators/              # Indicadores técnicos
├── risk/                    # Gestão de risco
├── utils/                   # Utilitários
└── state/                   # Estado e logs
```

## 🔐 Segurança

- API Keys armazenadas em variáveis de ambiente
- State files com backup automático
- Log de todas as operações
- Proteção contra perdas excessivas

## 📈 Performance

- **Async I/O**: ccxt async_support
- **Non-blocking**: asyncio event loop
- **Memory efficient**: Garbage collection periódica
- **Connection pooling**: aiohttp ClientSession
- **Priority Queue**: Hot tokens processados primeiro

## ⚠️ Disclaimer

**Este software é fornecido para fins educacionais. Trading envolve riscos substanciais.**

- Nunca arrisque dinheiro que você não pode perder
- Teste extensivamente em modo paper trading
- A performance passada não garante resultados futuros
- Você é totalmente responsável por suas operações

## 📊 Princípios

> *"Kelly Criterion — Matemática sobre emoção"*
> *"Defense First — Proteger capital antes de lucrar"*
> *"Automation — Sistemas que trabalham enquanto eu durmo"*

## 📞 Contato

**Desenvolvido por**: Mário (simbiosesingularidade)
**Email**: simbiosesingularidade@gmail.com

---

## 📝 Licença

MIT License - Veja LICENSE para detalhes

**Construído com 💚, ☕ e princípios quantitativos testados no tempo**

*"The market is a device for transferring money from the impatient to the patient." — Warren Buffett*
