
# OpenCV Roadmap 📷🚀

Este repositório contém um plano de estudos completo para aprender OpenCV com foco em Engenharia da Computação. O conteúdo está dividido em fases com teoria, prática e projetos para desenvolver habilidades reais em visão computacional.

## 📅 Duração sugerida: 8 a 12 semanas (adaptável ao seu ritmo)

---

## 🔹 Fase 1 – Fundamentos de Visão Computacional

**Conceitos:**
- O que é visão computacional
- O que é o OpenCV
- Representação digital de imagens (RGB, escala de cinza, canais)
- Operações básicas com imagens

**Prática:**
- Leitura e exibição de imagens
- Conversão de cores (RGB ↔ Grayscale, HSV)
- Redimensionamento, corte e rotação
- Salvamento de imagens

**Projeto:**
- Editor de imagem simples com efeitos básicos

---

## 🔹 Fase 2 – Processamento de Imagens

**Conceitos:**
- Filtros e convolução
- Detecção de bordas (Canny, Sobel)
- Thresholding e binarização
- Morfologia (dilatação, erosão)

**Prática:**
- Filtros de suavização
- Detecção de contornos
- Histograma de imagens

**Projeto:**
- Scanner de documentos

---

## 🔹 Fase 3 – Detecção de Objetos

**Conceitos:**
- Haar Cascades
- Template Matching
- Classificadores com HOG + SVM
- Módulo DNN (intro)

**Prática:**
- Detecção facial
- Rastreamento com OpenCV Tracker
- Reconhecimento de rostos (com `face_recognition`)

**Projeto:**
- Sistema de vigilância com detecção de movimento

---

## 🔹 Fase 4 – Aplicações Reais e Deep Learning

**Conceitos:**
- Modelos pré-treinados (YOLOv8, SSD)
- Segmentação
- OCR com Tesseract

**Prática:**
- Webcam e vídeo ao vivo
- OCR em placas e documentos
- Integração com modelos treinados

**Projeto Final:**
- App de inspeção visual (linha de produção)

---

## 🧠 Recursos de Apoio

- [Documentação OpenCV](https://docs.opencv.org/)
- [PyImageSearch](https://pyimagesearch.com/)
- [Tutoriais OpenCV-Python](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)

---

## 🛠️ Instalação

```bash
pip install opencv-python opencv-python-headless numpy matplotlib
pip install ultralytics  # Para YOLOv8 e modelos pré-treinados
```

---

## 📁 Estrutura sugerida de pastas

```
opencv-roadmap/
├── fase1/
├── fase2/
├── fase3/
├── fase4/
├── README.md
└── requirements.txt
```
