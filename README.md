# Detecção de Objetos com YOLO: Fine-Tuning e Análise de Performance

Este repositório contém uma atividade prática focada no treinamento e ajuste fino de modelos de detecção de objetos da família **YOLO (You Only Look Once)**, utilizando a biblioteca `ultralytics`.

## 🚀 Objetivo
O projeto demonstra o fluxo completo de um pipeline de Visão Computacional:
1. Preparação e estruturação de datasets no formato YOLO.
2. Treinamento de modelos pré-treinados (Transfer Learning).
3. Comparação de performance entre modelos (ex: YOLOv8 vs YOLOv12).
4. Otimização através do ajuste de hiperparâmetros.
5. Validação estatística (mAP, F1-Score) e testes qualitativos em imagens reais.

## 🛠️ Tecnologias Utilizadas
* **Python 3.12+**
* **Ultralytics (YOLO)**
* **PyTorch** (com suporte a CUDA para aceleração por GPU)
* **OpenCV** (processamento de imagem)
* **Matplotlib & YAML**

## 📂 Estrutura do Dataset
O projeto utiliza o dataset **COCO8** como base, estruturado automaticamente pelo código para seguir o padrão exigido pelo modelo:
```text
Dataset/
├── train/      # Imagens e labels de treino
├── valid/      # Imagens e labels de validação
├── test/       # Imagens para teste final
└── data.yaml   # Configurações de classes e caminhos
