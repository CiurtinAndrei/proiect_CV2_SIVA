# Clasificarea tipurilor de sol utilizând metode de învățare automată și învățare profundă

## Descriere

Acest proiect urmărește clasificarea tipurilor de sol din setul de date **Soil Types** utilizând trei abordări diferite din domeniul inteligenței artificiale:

- Random Forest împreună cu preprocesarea imaginilor prin metoda **Bag of Visual Words (BoVW)**;
- **ResNet**;
- **DenseNet121**.

Scopul proiectului este evaluarea și compararea performanței acestor metode în contextul unui set de date dezechilibrat, caracterizat prin diferențe vizuale subtile între clase. Analiza evidențiază avantajele și limitările fiecărei abordări din perspectiva acurateței clasificării și a capacității de generalizare.

## Setul de date

Proiectul utilizează setul de date **Soil Types**, disponibil pe platforma Kaggle:

https://www.kaggle.com/datasets/prasanshasatpathy/soil-types

## Publicare

Acest proiect este publicat exclusiv în scop educațional și de portofoliu, pentru a ilustra metodele utilizate și rezultatele obținute în cadrul proiectului universitar. Dacă utilizați acest material în scop didactic sau academic, vă rugăm să respectați politica instituției dumneavoastră privind integritatea academică și să nu prezentați această implementare ca fiind propria lucrare.

## Configurare

Proiectul poate fi rulat în Visual Studio Code sau într-un mediu cloud echivalent (de exemplu, Google Colab). Pentru utilizarea în Visual Studio Code este recomandată crearea unui mediu virtual Python (.venv) și instalarea pachetului ipykernel, necesar pentru executarea fișierelor de tip Jupyter Notebook (.ipynb).

În cazul antrenării modelelor de inteligență artificială, utilizarea unei plăci grafice compatibile CUDA este recomandată pentru reducerea semnificativă a timpului de execuție.

Din cauza dependențelor hardware și software specifice (versiuni CUDA, drivere NVIDIA și biblioteci compatibile), pașii necesari pentru reproducerea completă a mediului de dezvoltare nu sunt incluși în acest repository. Codul sursă este pus la dispoziție în principal pentru studiu și analiză.

## Dependențe principale

- Python 3.x
- PyTorch
- torchvision
- scikit-learn
- OpenCV
- NumPy
- Matplotlib
- pandas
