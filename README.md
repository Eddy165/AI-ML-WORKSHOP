AI-ML-WORKSHOP - Comprehensive AI/ML Learning Repository

## Overview

**AI-ML-WORKSHOP** is an educational repository that provides practical, hands-on learning materials for Artificial Intelligence and Machine Learning concepts. The repository is built entirely with **Jupyter Notebooks** (100% composition) and includes a diverse collection of datasets specifically curated for training and experimentation.

**Repository Owner:** Eddy165  
**Repository ID:** 1169118656  
**Language:** Jupyter Notebook (100%)

---

## 📁 Repository Structure

```
AI-ML-WORKSHOP/
├── Colab Notebooks/
│   └── EXCERCISE/
│       ├── 1.3.ipynb    - Regular Expressions & Text Patterns
│       ├── 1.4.ipynb    - SpaCy NLP: POS Tags & Dependencies
│       ├── 1.5.ipynb    - SpaCy: Tokenization & Vocabulary
│       ├── 1.6.ipynb    - NLTK: Porter Stemmer & Text Preprocessing
│       ├── 2.3.ipynb    - Advanced Pattern Matching with SpaCy
│       ├── 2.5.ipynb    - Sentence Segmentation & NLP Processing
│       ├── 3.1.ipynb    - SpaCy Word Embeddings (en_core_web_md)
│       ├── 3.2.ipynb    - Iris Dataset & Classification Basics
│       ├── 4.3.ipynb    - Image Processing with OpenCV & NumPy
│       └── 4.4.ipynb    - Advanced Image Creation & Manipulation
│
└── DATASET/
    ├── Images/
    │   ├── 00-puppy.jpg, dog_backpack.jpg, sammy.jpg, etc.
    │   ├── giraffes.jpg, gorilla.jpg, horse.jpg
    │   ├── Portraits: Denis_Mukwege.jpg, Nadia_Murad.jpg
    │   ├── Art: damien_hirst_dot.jpg, solvay_conference.jpg
    │   └── Specialized: bricks.jpg, pennies.jpg, ReceiptSwiss.jpg
    │
    ├── Computer Vision Resources/
    │   ├── haarcascade_frontalface_default.xml
    │   ├── haarcascade_eye.xml
    │   ├── Various PNG patterns (dot_grid, flat_chessboard, etc.)
    │   └── Product images (reeses_puffs.png, watermark_no_copy.png)
    │
    ├── Text Data (TSV & TXT)/
    │   ├── amazonreviews.tsv (~4.4 MB) - Product reviews
    │   ├── amazon_cells_labelled.csv (61 KB) - Labeled Amazon reviews
    │   ├── moviereviews.tsv (~7.5 MB) - Movie review dataset
    │   ├── smsspamcollection.tsv (508 KB) - SMS spam classification
    │   ├── test_qa.txt (377 KB) - QA test dataset
    │   ├── train_qa.txt (~3.8 MB) - QA training dataset
    │   ├── reaganomics.txt (31 KB) - Historical text
    │   └── test_qa.txt - Question-answer pair datasets
    │
    └── Documents/
        ├── US_Declaration.pdf (~981 KB) - Document processing sample
        └── Business_Proposal.pdf (77 KB) - Text extraction sample
```

---

## 🎓 Curriculum Overview

### **Section 1: Natural Language Processing (NLP) Fundamentals**

| Notebook | Topic | Key Concepts |
|----------|-------|--------------|
| **1.3** | Regular Expressions | Pattern matching, text search, span detection |
| **1.4** | SpaCy Basics | POS tagging, dependency parsing, linguistic features |
| **1.5** | Tokenization | Text segmentation, vocabulary management, abbreviations |
| **1.6** | NLTK Stemming | Porter Stemmer, word normalization, preprocessing |

**Skills Learned:**
- Text pattern recognition and extraction
- Understanding grammatical structures
- Tokenizing complex sentences
- Reducing words to their root forms

---

### **Section 2: Advanced NLP Processing**

| Notebook | Topic | Key Concepts |
|----------|-------|--------------|
| **2.3** | Pattern Matching | Matcher objects, phrase matching, multi-word patterns |
| **2.5** | Sentence Processing | Sentence segmentation, doc analysis, text splitting |

**Skills Learned:**
- Complex pattern detection across documents
- Sentence boundary detection
- Working with large text corpora
- Processing structured and unstructured text

---

### **Section 3: Machine Learning & Embeddings**

| Notebook | Topic | Key Concepts |
|----------|-------|--------------|
| **3.1** | Word Embeddings | Word vectors, semantic similarity, en_core_web_md model |
| **3.2** | Data Analysis | Iris dataset, feature extraction, exploratory data analysis |

**Skills Learned:**
- Understanding word vectors and embeddings
- Computing semantic similarity between words
- Loading and exploring ML datasets
- Feature analysis and visualization

---

### **Section 4: Computer Vision**

| Notebook | Topic | Key Concepts |
|----------|-------|--------------|
| **4.3** | Image Basics | NumPy arrays, image loading, pixel manipulation |
| **4.4** | Image Drawing | Creating graphics, drawing shapes, canvas operations |

**Skills Learned:**
- Working with image data as arrays
- Image creation and manipulation
- Drawing geometric shapes programmatically
- Understanding image channels (RGB)

---

## 📊 Dataset Overview

### **NLP & Text Analysis Datasets**

| Dataset | Size | Purpose |
|---------|------|---------|
| `moviereviews.tsv` | 7.5 MB | Sentiment classification, movie review analysis |
| `amazonreviews.tsv` | 4.4 MB | Product review sentiment analysis |
| `amazon_cells_labelled.csv` | 61 KB | Pre-labeled Amazon reviews for classification |
| `train_qa.txt` | 3.8 MB | Question-Answering model training |
| `test_qa.txt` | 377 KB | QA model evaluation and testing |
| `smsspamcollection.tsv` | 508 KB | SMS spam detection classification |
| `reaganomics.txt` | 31 KB | Historical text processing sample |

### **Computer Vision Datasets**

#### **Animal & Object Images:**
- `sammy.jpg`, `sammy_face.jpg`, `sammy_noise.jpg` (Dog images with variations)
- `giraffes.jpg`, `gorilla.jpg`, `horse.jpg`
- `00-puppy.jpg`, `dog_backpack.jpg`
- `many_cereals.jpg`

#### **Specialized Images:**
- `ReceiptSwiss.jpg` (OCR/Receipt scanning training)
- `Denis_Mukwege.jpg`, `Nadia_Murad.jpg` (Portrait images)
- `solvay_conference.jpg` (Historical photo)
- `damien_hirst_dot.jpg` (Art/Pattern recognition)

#### **Pattern & Design Images:**
- `dot_grid.png`, `flat_chessboard.png`, `rainbow.jpg`
- `reeses_puffs.png`, `watermark_no_copy.png`
- `pennies.jpg`, `bricks.jpg`

### **Computer Vision Cascades**
- `haarcascade_frontalface_default.xml` (Face detection)
- `haarcascade_eye.xml` (Eye detection)

### **Document Samples**
- `US_Declaration.pdf` (Document processing/OCR training)
- `Business_Proposal.pdf` (Text extraction)

---

## 🔧 Technologies & Libraries

### **Core NLP Libraries**
- **SpaCy** - Industrial-grade NLP processing
- **NLTK** - Natural Language Toolkit
- **Regular Expressions** - Pattern matching

### **Machine Learning**
- **scikit-learn** - ML algorithms and utilities
- **NumPy** - Numerical computing

### **Computer Vision**
- **OpenCV (cv2)** - Image processing and analysis

### **Data & Visualization**
- **Pandas** - Data manipulation
- **Matplotlib** - Data visualization
- **Jupyter Notebook** - Interactive computing environment

---

## 🚀 Getting Started

### **Prerequisites**
- Python 3.7+
- Jupyter Notebook or Google Colab
- Virtual environment (recommended)

### **Installation**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Eddy165/AI-ML-WORKSHOP.git
   cd AI-ML-WORKSHOP
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   # OR install individually:
   pip install jupyter notebook
   pip install spacy nltk
   pip install scikit-learn numpy pandas matplotlib
   pip install opencv-python
   ```

3. **Download SpaCy models:**
   ```bash
   python -m spacy download en_core_web_sm
   python -m spacy download en_core_web_md
   ```

### **Running Notebooks**

#### **Locally:**
```bash
jupyter notebook
# Navigate to Colab Notebooks/EXCERCISE/ folder
```

#### **Google Colab:**
- All notebooks have "Open In Colab" badges for easy access
- Click the badge in any notebook to run directly in Google Colab
- All datasets are available in the repository for import

---

## 📚 Learning Path Recommendations

### **Beginner Path (Start Here)**
1. **1.3** - Understand pattern matching basics
2. **1.5** - Learn tokenization concepts
3. **1.6** - Explore text preprocessing
4. **3.2** - Get familiar with datasets

### **Intermediate Path**
1. Complete Beginner Path
2. **1.4** - Dive into linguistic analysis
3. **2.3** - Advanced pattern detection
4. **2.5** - Sentence processing

### **Advanced Path**
1. Complete Intermediate Path
2. **3.1** - Word embeddings and vectors
3. **4.3 & 4.4** - Computer vision fundamentals

### **Applied ML Path**
1. Start with **3.2** - Dataset fundamentals
2. Combine NLP notebooks with real-world datasets
3. Use CV notebooks for multimodal learning

---

## 🎯 Key Use Cases

### **Natural Language Processing**
- ✅ Sentiment Analysis (MovieReviews, Amazon Reviews)
- ✅ Spam Detection (SMS Collection)
- ✅ Question Answering Systems
- ✅ Text Classification
- ✅ Named Entity Recognition (NER)
- ✅ Dependency Parsing

### **Machine Learning**
- ✅ Feature Extraction
- ✅ Classification Tasks
- ✅ Model Training & Evaluation
- ✅ Dataset Exploration

### **Computer Vision**
- ✅ Image Processing
- ✅ Face Detection (Haar Cascades)
- ✅ Object Detection
- ✅ Image Manipulation
- ✅ Receipt/Document OCR Preparation

---

## 📖 Notebook Descriptions

### **NLP Section**

**1.3 - Regular Expressions & Text Patterns**
- Text search and pattern matching
- Using `re.search()`, `re.findall()`
- Span detection and text location

**1.4 - SpaCy: POS Tags & Dependencies**
- Part-of-Speech tagging
- Dependency parsing
- Understanding linguistic pipelines
- Example: "Tesla is looking at buying U.S. startup for $6 million"

**1.5 - SpaCy: Tokenization**
- Breaking text into tokens
- Handling abbreviations (U.S., L.A.)
- Vocabulary management
- Processing complex sentences

**1.6 - NLTK: Porter Stemmer**
- Word stemming and normalization
- Reducing variations (running → run)
- Text preprocessing fundamentals

**2.3 - Pattern Matching with SpaCy**
- Creating custom matchers
- Phrase matching
- Multi-word pattern detection
- Example: Finding "solar power" variations

**2.5 - Sentence Segmentation**
- Splitting documents into sentences
- Processing multi-sentence text
- Sentence-level analysis

### **ML Section**

**3.1 - Word Embeddings**
- Loading pre-trained models
- Computing word vectors
- Semantic similarity calculations
- Using `en_core_web_md`

**3.2 - Iris Dataset Exploration**
- Loading the Iris dataset
- Feature analysis
- Data exploration
- Classification fundamentals

### **CV Section**

**4.3 - Image Basics**
- Creating blank images with NumPy
- Image shape and dimensions
- Pixel manipulation
- OpenCV fundamentals

**4.4 - Image Drawing**
- Drawing shapes on images
- Creating graphics
- Canvas operations
- Visual output generation

---

## 💡 Tips for Using This Workshop

1. **Run notebooks in order** within each section to build concepts progressively
2. **Experiment with the datasets** - modify code and see what happens
3. **Use Google Colab** for easy access without local setup
4. **Download datasets** separately if you want to work offline
5. **Modify examples** - change parameters and observe the effects
6. **Combine sections** - use NLP techniques on the text datasets, CV on images

---

## 🤝 Contributing

If you find issues or want to improve the notebooks:
1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

---

## 📝 Notes for Learners

- Each notebook is **self-contained** and can be run independently
- Code snippets use **realistic examples** with actual datasets
- All notebooks are **well-commented** for learning
- The datasets range from **small samples to larger real-world data**
- Perfect for **students, professionals, and enthusiasts** learning AI/ML

---

## 📄 License

This repository is provided for educational purposes. Please refer to the repository's LICENSE file for detailed terms.

---

## 🔗 Resources & References

- [SpaCy Documentation](https://spacy.io/)
- [NLTK Documentation](https://www.nltk.org/)
- [OpenCV Documentation](https://docs.opencv.org/)
- [scikit-learn Documentation](https://scikit-learn.org/)
- [Google Colab Guide](https://colab.research.google.com/)

---

## ✨ Repository Highlights

| Feature | Count |
|---------|-------|
| Jupyter Notebooks | 10 |
| Datasets (Various Formats) | 30+ |
| NLP Topics Covered | 6 |
| ML Topics Covered | 2 |
| CV Topics Covered | 2 |
| Total Dataset Size | ~30+ MB |

---

**Happy Learning! 🎉**

This repository is your practical guide to mastering AI and ML concepts through hands-on exercises, real datasets, and executable code. Start with the basics and progress to advanced topics at your own pace!
