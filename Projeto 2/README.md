# 🎬 Projeto 2 - Manipulação de Vídeo com Python

Este projeto tem como objetivo explorar técnicas de manipulação de vídeos utilizando a biblioteca `moviepy`. Através de diferentes etapas, são aplicadas transformações no vídeo original, como inversão de imagem, redução de volume, cortes e reordenação de clipes.

---

## 🧩 **Etapas do Projeto**

### 1️⃣ Importação de Bibliotecas  
As bibliotecas `moviepy` e `numpy` são utilizadas para manipulação de vídeos e operações matemáticas.

---

### 2️⃣ Carregamento do Vídeo  
O vídeo original é carregado e suas propriedades, como tamanho, FPS, duração e número de frames, são exibidas.

---

### 3️⃣ Inversão de Imagem  
A cada 20 segundos, a imagem do vídeo é invertida horizontalmente, criando um efeito visual dinâmico.

---

### 4️⃣ Redução Gradativa do Volume  
O áudio do vídeo é ajustado para reduzir o volume gradativamente a cada 30 segundos, até que os últimos 10 segundos fiquem completamente silenciosos.

---

### 5️⃣ Corte no Vídeo  
Após o primeiro minuto (60 segundos), o vídeo é cortado, removendo o trecho entre 60 e 80 segundos. Os clipes restantes são concatenados.

---

### 6️⃣ Reordenação dos Clipes  
Os 20 segundos cortados anteriormente são inseridos no final do vídeo, reorganizando a sequência original.

---

## 🎯 **Resultado Final**

O vídeo manipulado é salvo como `videoprojeto2_final.mp4`, contendo todas as transformações aplicadas.

---

## 🛠️ **Como Executar**

1. **Clone o repositório**  
   Certifique-se de ter o Git instalado e execute o seguinte comando no terminal para clonar o repositório:

   ```bash
   git clone https://github.com/JmCassemiro/ComputacaoGrafica


2. **Acesse o diretório do projeto, instale as dependências e execute o script**
   Execute os seguintes comandos no terminal:

   ```bash
   cd ComputacaoGrafica/Projeto\ 2
   pip install moviepy==1.0.3 numpy
   python projeto2.py
   ```

> ⚠️ **Observação:** A versão `1.0.3` do `moviepy` é recomendada para evitar problemas de compatibilidade.




