# OpenVaults Wallet

> Carteira multi-chain open source com UX excepcional. Funciona como app mobile (iOS/Android) e web.

## 🎯 Sobre

OpenVaults Wallet é o frontend universal da plataforma OpenVaults, construído com **Expo** e **React Native**. O mesmo código funciona perfeitamente em:

- 📱 **iOS** (App Store)
- 🤖 **Android** (Google Play)
- 🌐 **Web** (PWA)

## 🚀 Tecnologias

- **Framework:** Expo SDK (React Native)
- **Language:** TypeScript
- **Styling:** NativeWind (TailwindCSS para React Native)
- **State Management:** Zustand
- **Blockchain:** Viem (EVM chains) + @solana/web3.js
- **Navigation:** Expo Router (file-based routing)
- **Storage:** Expo SecureStore (mobile) + AsyncStorage (web)

## 📦 Instalação

```bash
# Instalar dependências
npm install

# Executar no iOS
npm run ios

# Executar no Android
npm run android

# Executar na Web
npm run web
```

## 🏗️ Estrutura do Projeto

```
openvaults-wallet/
├── app/                    # Expo Router (file-based routing)
├── components/             # UI components (universais)
├── screens/                # Telas principais
├── core/                   # Wallet core logic (shared)
│   ├── keystore/
│   ├── chains/
│   └── transactions/
├── hooks/                  # Custom hooks
├── stores/                 # Zustand stores
└── utils/
```

## 🔐 Segurança

- ✅ Seed phrase nunca sai do dispositivo
- ✅ Criptografia AES-256-GCM
- ✅ Biometria nativa (Face ID, Touch ID)
- ✅ Secure Storage (Keychain/Keystore)
- ✅ Auto-lock após inatividade

## 🌐 Multi-Chain Support

- Ethereum (Mainnet)
- Polygon
- Arbitrum
- Optimism
- BSC (Binance Smart Chain)
- Base
- Solana (Phase 1.5)

## 📜 Licença

Este projeto está licenciado sob a **Elastic License 2.0 (ELv2)**. Veja [LICENSE-ELv2.md](./LICENSE-ELv2.md) para mais detalhes.

## 🤝 Contribuindo

Contribuições são bem-vindas! Por favor, leia nosso guia de contribuição antes de enviar PRs.

## 📚 Documentação

Para mais informações sobre o projeto OpenVaults, consulte a [documentação principal](../docs/INITIAL.md).

