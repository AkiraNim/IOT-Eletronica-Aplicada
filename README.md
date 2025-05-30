# 🚗 Projeto IoT: Carro Seguidor de Linha com Sensor Infravermelho
---

Este é um projeto de IoT que implementa um **carro autônomo seguidor de linha**, utilizando sensores infravermelhos para detectar o trajeto e seguir uma linha branca em fundo preto. Ideal para introdução à robótica, automação e sistemas embarcados.

## 📸 Visão Geral

[Simulação em 3D no TinkerCad](https://www.tinkercad.com/things/fIo4fI4Vcfz-copy-of-speed-line-follower-robot-v4?sharecode=nArqtL2eGQSuooyKRuTVUidTz7WWIeUg9Up54wJF2s8)

---

## 🛠️ Tecnologias e Componentes

* **Microcontrolador**:Arduino Nano 
* **Sensores**: Módulo sensor infravermelho TCRT5000 
* **Motores**: 2 motores DC com driver ponte H 
* **Estrutura**: Chassi 2WD com rodas e suporte
* **Fonte de energia**: 2 Baterias 9V 


## 📦 Estrutura do Projeto

```
📁 seguidor-linha-iot/
├── 📂 código/
│   └── seguidor_linha.ino         # Código-fonte principal em Arduino
├── 📂 imagens/
│   └── carro_montado.jpg          # Fotos do projeto
├── README.md
└── esquemático.png                # Esquema de ligação dos componentes
```

---

## 🔌 Esquema de Ligação

* Os sensores IR devem ser posicionados na frente do carro, voltados para baixo.
* Conecte os motores ao driver de motor (L298N/L293D) e este ao microcontrolador.
* Sensores IR conectados às portas analógicas/digitais.


## 🚦 Funcionamento

1. Ao ligar, os sensores IR detectam a linha preta.
2. O microcontrolador interpreta os sinais dos sensores.
3. Com base na posição da linha, os motores são ajustados para manter o carro na trajetória.


## ▶️ Como Usar

1. Monte o circuito conforme o esquemático.
2. Faça upload do código para o microcontrolador via Arduino IDE.
3. Posicione o carro sobre a trilha com linha preta.
4. Ligue o sistema e observe o funcionamento.


## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.


