# Excersize1
יצירת 2 רשימת מסוג dictionary , 
הרשימה הראשונה (countsName) נכנס לתוכה השם שנקלט מהמשתמש ואת המיקום שלו ברשימה-index,

ברשימה השנייה (names) נשמר  שתי השמות שנקלטו,

יצירת רשימה שלישית מסוג(counts) List: שבה נשמר לפי המיקום של השם ברשימה הראשונה-index  את מספר הפעמים שמופיע השם,

![image](https://user-images.githubusercontent.com/89073905/150658806-b7261194-a7b0-4e67-9ea2-a27e8aee4b38.png)

מיזוג שתי הרשימות על ידי חיפוש השמות ברשימת ה-names והוספה ברשימת הcounts את מספר התדירויות של השם הראשון לשם השני 
השמת -1 לתוך השם שהוסיפו כבר בכדי שלא יחזרו עליו שנית,
כעת בתוך רשימת הcounts נמצא התדירויות של כל שם לפי האינדקס של הרשימה countsName
לדוגמא:
כאשר נקלט:

countNames: {"yakov",3} {""jacob",4},{"sara",2}

names:  {"yakov",jacob"}

אז רשימת הcounts תיראה:

![image](https://user-images.githubusercontent.com/89073905/150659270-73e90bea-9b57-4afe-a343-ff51cbb6ad85.png)

מעבר על רשימת countsNames והצגת השם עם המספר התדירויות לפי רשימת הcounts במקרה שיש -1 הוא מדלג כי כבר הוסיפו אותו

![image](https://user-images.githubusercontent.com/89073905/150659220-67ea5c98-f70b-44d1-bd85-5a9cd9a91460.png)



