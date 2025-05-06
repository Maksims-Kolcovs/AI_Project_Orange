# 🍷 Vīnu Kvalitātes Analīze

---

## 📚 Atsauces uz Lietotiem Materiāliem

1. *Cortez, P. et al.* (2009). *Decision Support Systems*, 47(4), 547–553.  
   Skatīts: 2025. gada 1. maijā  
   [🔗 Tiešsaiste](https://archive.ics.uci.edu/dataset/186/wine+quality)

---

## 👥 Komandas Dalībnieki

| Vārds                  | Studenta kods |
|------------------------|----------------|
| Maksims Koļcovs        | 231RDB363      |
| Staņislava Šuļženko    | 231RDB330      |
| Dmitrijs Borisevičs    | 231RDB352      |
| *(Tukšs)*              | —              |
| Dāvis Fomičevs         | 221RDB346      |

---

## 📊 Izvēlētās Datu Kopas Apraksts

- **Avots:** [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)  
- **Izveidotāji:** Paulo Cortez et al., University of Minho, Portugāle, 2009  
- **Licence:** Brīvi lietojama akadēmiskiem mērķiem

### 🔍 Pazīmes (Features):
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol

### 🎯 Klašu Iezīme (Target):
### Kvalitātes atzīmju apraksts
- **3 – Ļoti zemas kvalitātes vīns**: Nedzerams, ar izteiktiem defektiem (~10 paraugi).
- **4 – Zemas kvalitātes vīns**: Nelieli defekti, nav ieteicams lietošanai (~53 paraugi).
- **5 – Vidējas kvalitātes vīns**: Ikdienas vīns, pieņemams, bet vienkāršs (~681 paraugi).
- **6 – Labas kvalitātes vīns**: Baudāms, ar sabalansētu garšu (~638 paraugi).
- **7 – Ļoti labas kvalitātes vīns**: Augsta kvalitāte, sarežģīta garša (~199 paraugi).
- **8 – Izcilas kvalitātes vīns**: Izcils, ar perfektu līdzsvaru (~18 paraugi).

📌 *Mēs izmantojām tikai sarkanā vīna datus (kopā **1599** paraugi) klasifikācijai.*

---

### 📊 Histogrammas pēc atribūtiem:
*Zemāk redzami histogrammu attēli, kas parāda dažādu pazīmju ietekmi uz klašu sadalījumu*

### 🔹 Fixed Acidity  
![fixed](https://github.com/user-attachments/assets/934f4a6d-2a04-468c-9289-ae6c411275dd)

### 🔹 Volatile Acidity  
![volatile](https://github.com/user-attachments/assets/22d0da91-a28d-42a6-97fe-d1e70b3433c7)

### 🔹 Citric Acid  
![citric](https://github.com/user-attachments/assets/8970cfad-2084-49ef-b9d0-7fdebe3c86f2)

### 🔹 Residual Sugar  
![residual](https://github.com/user-attachments/assets/e36c5032-4e5f-41eb-9d8b-9a197fe1be41)

### 🔹 Chlorides  
![chlorides](https://github.com/user-attachments/assets/5904fe0f-1481-440c-b417-56b00b6fd15e)

### 🔹 Free Sulfur Dioxide  
![free](https://github.com/user-attachments/assets/7a51209a-9dc9-4e50-89f4-6d7f255f9b9e)

### 🔹 Total Sulfur Dioxide  
![total](https://github.com/user-attachments/assets/35f58326-7a34-408f-a090-5fa2fc3653c6)

### 🔹 Density  
![density](https://github.com/user-attachments/assets/21ea0891-ba82-4918-af32-ecc3a28c77bb)

### 🔹 pH  
![pH](https://github.com/user-attachments/assets/50318626-7cc1-46a4-afe7-481e9d2ebcc5)

### 🔹 Sulphates  
![sulphates](https://github.com/user-attachments/assets/08bd650a-2a1e-4780-88f3-dbc4cf1dbcda)

### 🔹 Alcohol  
![alcohol](https://github.com/user-attachments/assets/e56fa252-72e0-428c-8a33-eac8a8ae7b64)

### 📊 Scatter plot pēc atribūtiem:
*Zemāk redzami scatter plot attēli, kas parāda dažādu pazīmju ietekmi uz klašu sadalījumu*

### 🔹 X = Fixed acidity --- Y = Volatile acidity
![A](https://github.com/user-attachments/assets/2a577ecf-bba0-4d5a-81b5-26f26e1d91a5)

### 🔹 X = Citric acid --- Y = Residual sugar
![B](https://github.com/user-attachments/assets/9767ff5f-2707-41e7-8832-dc032347e629)

### 🔹 X = Chlorides --- Y = Free sulfur dioxide
![C](https://github.com/user-attachments/assets/2aff81bf-22a0-4d36-a740-1b3ceab3583a)

### 🔹 X = Total sulfur dioxide --- Y = Density
![D](https://github.com/user-attachments/assets/afe26faf-77b4-4a6d-92c3-ee00625c4a75)

### 🔹 X = pH --- Y = Sulphates 
![E+](https://github.com/user-attachments/assets/2a466090-a357-48d3-9fb5-3fdab176fd1e)

### 🔹 X = pH --- Y = Alcohol
![F](https://github.com/user-attachments/assets/78a06e6f-9fb4-449f-9e32-5d416fd1ef36)

---

### 2 interesējošo pazīmju (atribūtu) sadalījums: alcohol un fixed acidity
![ABCDE](https://github.com/user-attachments/assets/2f22b69e-fcb5-42cb-be21-1793230c2650)

### Vidējās vērtības un Dispersija
![124](https://github.com/user-attachments/assets/876af10e-d129-40d0-8c57-a0db6dedb6e5)
