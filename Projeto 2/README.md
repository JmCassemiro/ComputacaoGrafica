# Projeto 2 - Manipulação de Vídeo com Python

Este projeto tem como objetivo explorar técnicas de manipulação de vídeos utilizando a biblioteca `moviepy`. Através de diferentes etapas, são aplicadas transformações no vídeo original, como inversão de imagem, redução de volume, cortes e reordenação de clipes.

---

## **Etapas do Projeto**

### **1. Importação de Bibliotecas**
As bibliotecas `moviepy` e `numpy` são utilizadas para manipulação de vídeos e operações matemáticas.

---

### **2. Carregamento do Vídeo**
O vídeo original é carregado e suas propriedades, como tamanho, FPS, duração e número de frames, são exibidas.

---

### **3. Inversão de Imagem**
A cada 20 segundos, a imagem do vídeo é invertida horizontalmente, criando um efeito visual dinâmico.

---

### **4. Redução Gradativa do Volume**
O áudio do vídeo é ajustado para reduzir o volume gradativamente a cada 30 segundos, até que os últimos 10 segundos fiquem completamente silenciosos.

---

### **5. Corte no Vídeo**
Após o primeiro minuto (60 segundos), o vídeo é cortado, removendo o trecho entre 60 e 80 segundos. Os clipes restantes são concatenados.

---

### **6. Reordenação dos Clipes**
Os 20 segundos cortados anteriormente são inseridos no final do vídeo, reorganizando a sequência original.

---

## **Resultado Final**
O vídeo manipulado é salvo como `videoprojeto2_final.mp4`, contendo todas as transformações aplicadas.

---

## **Como Executar**
1. Certifique-se de que as bibliotecas necessárias estão instaladas:
   ```bash
   pip install moviepy numpy
   
   Obs: Instalar a versao moviepy 1.0.3 para evitar erros de incompatibilidade 


