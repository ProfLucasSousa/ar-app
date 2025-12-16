# AR App

Aplicação de Realidade Aumentada usando AR.js e A-Frame.

## 📋 Descrição

Este projeto permite visualizar modelos 3D em realidade aumentada usando marcadores. A aplicação exibe um pato e um helicóptero 3D quando o marcador Hiro é detectado pela câmera.

## ✨ Funcionalidades

- Realidade aumentada baseada em marcadores (Hiro)
- Controle de zoom com botões na tela
- Zoom por gesto de pinça (pinch-to-zoom)
- Visualização de modelos 3D (Duck e Helicóptero)

## 🚀 Como Usar

1. Abra o arquivo `index.html` em um navegador
2. Permita o acesso à câmera quando solicitado
3. Aponte a câmera para um [marcador Hiro](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png)
4. Use os botões ➖ e ➕ para controlar o zoom, ou use o gesto de pinça na tela

## 🛠️ Tecnologias

- [A-Frame](https://aframe.io/) - Framework para criar experiências de realidade virtual
- [AR.js](https://ar-js-org.github.io/AR.js-Docs/) - Biblioteca para realidade aumentada na web
- Gesture Detector - Para detecção de gestos touch

## 📦 Estrutura

```md
ar-app/
├── index.html           # Arquivo principal da aplicação
├── assets/
│   └── helicoptero.glb  # Modelo 3D do helicóptero
└── README.md
```

## Contribuição

Lucas Silva (luk4rtes)

## 📝 Licença

Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
