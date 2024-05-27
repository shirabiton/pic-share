# אתר שיתופי לצילום PicShare
## סקירה כללית
אתר זה הינו אתר שיתופי בנושא הצילום. <br>
ניתן לקבל המלצות מפוסטים לגבי: צלמים מקצועיים, לוקיישנים מיוחדים לצילום, אביזרי צילום להשכרה/למכירה, וכן טיפים לצילום מהמומחים.<br>
משתמשים שרשומים לאתר יכולים להעלות פוסטים עם המלצות בנושאים אלה, לצרף תמונה לפוסט להמחשה, וכן להגיב על פוסטים קיימים ולדרג אותם.<br>
בפרופיל יכול המשתמש לראות את פרטיו האישיים, את כל הפוסטים שהעלה, לצפות בהם, לערוך או למחוק אותם. וכן קיימות אופציות של התנתקות מהחשבון ומחיקת החשבון.<br><br>
## מאפיינים
- הרשמה/התחברות למערכת ע"י פרטים אישיים, כתובת דוא"ל וסיסמה של החשבון.
- צפייה בפרופיל המשתמש, שם רשומים פרטיו האישיים והפוסטים שהעלה. יש אפשרות לצפות בפוסטים של הפרופיל, לערוך או למחוק אותם. וכן ניתן להתנתק מהחשבון או למחוק אותו לצמיתות.
- צפייה בפוסטים שהועלו, גם אדם שאינו רשום כמשתמש רשאי לצפות בפוסטים.
- כתיבת פוסט לפי קטגוריה, בצירוף תמונה.
- תגובה ודירוג לפוסט קיים.
  <br><br>
## שימוש בטכנולוגיות
- **צד השרת:** Java (Spring Boot).
- **צד הלקוח:** React (Redux).
- **ספריית עיצוב:** MUI (Material UI).
- **מסד הנתונים:** H2. (לאחסון הנתונים בלבד)
<br>

 ## התקנה
 ראשית הורד את הקובץ למחשב המקומי שלך ע"י הפקודה הבאה בשורת הפקודה של התיקייה הרצויה:
 ```bash
git clone https://github.com/shirabiton/PicShare.git
```

### התקנה בצד השרת: 
פתח את הפרויקט בסביבת העבודה IntelliJ IDEA או Eclipse והרץ את השרת (לחץ על run).
לאחר מכן, פתח את כתובת הדפדפן:
```bash
http://localhost:8585/h2-console
```
שם תוכל לראות את מסד הנתונים שמור בטבלאות.<br>
### התקנה בצד הלקוח:
פתח את שורת הפקודה של תיקיית צד הלקוח שבפרויקט, כתוב:
```bash
code .
```
ואז Enter. כך ייפתח לך הפרויקט ב Visual Studio Code. <br>
כעת הרץ את הפרויקט על ידי הפקוודה בטרמינל: 
```bash
npm run dev
```
<br>

  ## תלויות חיצוניות
  כפי שצויין, בצד הלקוח מותקנת הספרייה MUI (Material UI), זוהי ספרייה עיצובית של React.
  נתקין אותה על ידי הפקודה הבאה בטרמינל:
```bash
npm install @mui/material @emotion/react @emotion/styled
```
או לחילופין, להתקין בקלות כל התקנה שהיא בפרויקט על ידי:
```bash
npm install @mui/material @emotion/react @emotion/styled
```
<br>

## אופן השימוש
## צילומי מסך

![דף הבית](web/src/Docs/Screenshots/home-page.png)
![הירשם](web/src/Docs/Screenshots/signin.png)
![נוספת בהצלחה](web/src/Docs/Screenshots/signin-succeed.png)
![התחבר](web/src/Docs/Screenshots/login.png)
![אתה מחובר](web/src/Docs/Screenshots/login-succeed.png)
![קצת עלינו](web/src/Docs/Screenshots/about.png)
![הוספת פוסט](web/src/Docs/Screenshots/add-post.png)
![נוסף בהצלחה](web/src/Docs/Screenshots/add-post-succeed.png)
![פוסטים](web/src/Docs/Screenshots/posts.png)
![חיפוש פוסט](web/src/Docs/Screenshots/search.png)
![פרטי הפוסט](web/src/Docs/Screenshots/show-post.png)
![הוספת תגובה](web/src/Docs/Screenshots/add-comment.png)
![תגובות לפוסט](web/src/Docs/Screenshots/comments.png)
![פרופיל](web/src/Docs/Screenshots/profile.png)
![פוסטים של החשבון](web/src/Docs/Screenshots/profile-post.png)
