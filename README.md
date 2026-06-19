#  Detector de Livros

Um sistema de **inteligência artificial** para auxiliar bibliotecas a identificar e classificar livros a partir de imagens.  

O objetivo é ajudar bibliotecários e usuários a **localizar, catalogar e reconhecer livros automaticamente**, usando redes neurais treinadas em imagens.

---

##  Funcionalidades

-  **Detecção de livros em imagens** (fotos de prateleiras, mesas, etc.)  
-  **Classificação automática** em categorias (ex: romance, técnico, infantil, etc.)  
-  **Interface interativa** feita em **Streamlit**  
-  **Treinamento personalizado** com novas imagens  

---

##  Estrutura do Projeto

```
detector-de-livros/
│── data/                 # Base de dados de imagens
│   ├── raw/              # Imagens originais
│   ├── processed/        # Imagens pré-processadas
│
│── models/               # Modelos treinados
│
│── scripts/              # Códigos auxiliares
│   ├── preprocess.py     # Pré-processamento das imagens
│   ├── train.py          # Treinamento do modelo
│   ├── detect.py         # Teste/detecção em imagens
│
│── app.py                # Interface principal (Streamlit)
│── requirements.txt      # Dependências do projeto
│── README.md             # Documentação
```
 Como rodar o projeto

### 1. Clone o repositório
```bash
git clone https://github.com/HugoPiresGregorio/DETECTOR_DE_LIVROS.git
cd detector-de-livros
```

### 2. Crie e ative um ambiente virtual
```bash
python -m venv venv
```

- **Windows (PowerShell):**
```bash
venv\Scripts\Activate.ps1
```

- **Linux/Mac:**
```bash
source venv/bin/activate
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

### 4. Execute a interface
```bash
streamlit run app.py
```

Acesse no navegador: [http://localhost:8501](http://localhost:8501)

---

## 🛠 Tecnologias usadas

- [Python 3](https://www.python.org/)  
- [PyTorch](https://pytorch.org/) – Treinamento do modelo  
- [Torchvision](https://pytorch.org/vision/stable/index.html) – Processamento de imagens  
- [Streamlit](https://streamlit.io/) – Interface interativa  

---

##  Próximos passos

- Melhorar a precisão do modelo com mais imagens  
- Criar novas categorias de livros  
- Adicionar OCR para identificar títulos e autores nas capas  

---

##  Autor

Projeto desenvolvido por **[Hugo Pires (TryyFt)](https://github.com/TryyFt)** 💡  
Se quiser contribuir, abra uma issue ou envie um pull request.  
