
מטלה 1 –, ..  fork , exec , exit , dup


במטלה זו מימשנו SHELL בעזרת לולאה אינסופית שמבקשת אינפוט מהמשתמש
לSHELL הזה יש HANDLER שלוקח את הINPUT של המשתמש מפרק אותו למילים במערך
מילה ראשונה עוברת לSWITCH CASE  אשר מחליט מה לעשות באותה הבקשה.



פקודות לSHELL:

-	ECHO XXX  במקום הXXX ניתן לרשום כל דבר ואז אחרי ENTER יודפס החלק
שנמצא אחרי הECHO


-	TCP XXX במקום הXXX יפתח סוקט TCP על פורט מסויים שצויין , ניתן להציג את הOUTPUT בתוך קליינט  ומאז כל הודעה תודפס אצל הקליינט עד שכניס את הפקודה הבאה
-	LOCAL מחזיר את הOUTPUT לחלון הראשון שבו הוצג
-	DIR מציג את רשימת הקבצים בתקייה בה אנחנו נמצאים
-	CD XXX  מעביר אותך לתקייה שהכנסת אחרי הXXX
-	COPY SRC DST מעתיק קובץ למיקום אחר שצויין ב DST
-	DELETE FILENAME מוחק את הקובץ שנמצא ב FILENAME
-	EXIT סוגר את התוכנית
המערכת בנוייה על שיטה של SWITCH CASE כך שעל כל INPUT שיוכנס אנחנו נבצע פעולה מסויימת
כל הספריות שהשתמשנו נלקחו מסיפרייות מובנות של C או של UNIX או SYSTEM 




