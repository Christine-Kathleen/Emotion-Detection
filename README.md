# Emotion-Detection

Emotion Detection using CNN

Definirea problemei și obiectivului

Recunoașterea emoțiilor bazată pe metode de deep learning poate contribui la îmbunătățirea calității vieții persoanelor cu deficiențe de vedere, precum și a persoanelor cu tulburări din spectrul autist, care întâmpină dificultăți în interpretarea indicilor sociali. Alte probleme care ar putea fi abordate prin intermediul sistemelor de recunoaștere al emoților includ:  
- Îmbunătățirea interacțiunii om–calculator: programul poate face aplicațiile mai „inteligente” emoțional. 
- Suport pentru sănătate mintală: nu înlocuiește psihologii, dar poate ajuta la monitorizare. 
- Analiză de marketing: companiile vor să știe reacția emoțională la produse sau reclame. 

Descriere dataset 

În cadrul acestei lucrări a fost utilizat setul de date Emotion Detection using CNN (fer2013.csv), preluat de pe platforma Kaggle: Emotion Detection using CNN. Acesta conține 35.887 de instanțe, fiecare instanță corespunzând unei imagini faciale grayscale cu rezoluția de 48 × 48 pixeli.  

Din punct de vedere structural, setul de date include trei atribute principale: emotion, pixels și usage. Atributul emotion reprezintă eticheta clasei și indică emoția asociată imaginii, corespunzând uneia dintre cele șapte categorii: ‘Anger’, ‘Disgust’, ‘Fear’, ‘Happy’, ‘Neutral’, ‘Sadness’, ‘Surprise’. Atributul pixels conține valorile intensității pixelilor imaginii, stocate sub forma unui șir de 2304 valori numerice, corespunzătoare unei imagini de 48 × 48 pixeli. Atributul usage împarte instanțele în 3 categorii: Training, PublicTest și PrivateTest.

Abordare propusă (model/arhitectură) 

Rețelele neuronale convoluționale (Convolutional Neural Networks – CNN) reprezintă o clasă de modele de deep learning special concepute pentru prelucrarea datelor de tip imagine. Acestea folosesc operația de convoluție pentru a detecta și extrage automat caracteristici relevante din datele de intrare. În cadrul acestui proces, un filtru (kernel), reprezentat printr-o matrice de dimensiuni reduse, este aplicat succesiv asupra imaginii, iar la fiecare poziție se calculează o combinație între valorile filtrului și cele ale imaginii. Rezultatul este o hartă de caracteristici care evidențiază informațiile importante pentru sarcina de clasificare. 

Această arhitectură a fost aleasă datorită eficienței sale ridicate în domeniul procesării imaginilor, în special pentru sarcini precum recunoașterea de imagini, clasificarea vizuală și detecția obiectelor. Printre aplicațiile sale se numără recunoașterea facială, analiza imaginilor medicale și dezvoltarea sistemelor utilizate în vehicule autonome. 

Plan de lucru 

- Importarea bibliotecilor necesare 
- Încărcarea setului de date 
- Preprocesarea datelor 
- Proiectarea arhitecturii modelului 
- Optimizarea și ajustarea fină a modelului 
