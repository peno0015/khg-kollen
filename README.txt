KHG-kollen v2 – Firebase

Ladda upp filerna i roten på ditt GitHub Pages-repository.
Aktivera Firebase Authentication Email/Password och skapa konton som admin@khg.invalid.
Appen visar endast användarnamnet (admin).
Firestore collection: artiklar. Säkerhetsregler: allow read, write: if request.auth != null;
OBS: Detta ger alla autentiserade konton i projektet full åtkomst till artiklar.
Inga artiklar kopieras automatiskt från v1. Exportera JSON i v1 och importera den i v2 efter inloggning.
Import sammanfogar via dokument-ID, den raderar inte andra artiklar.
Firebase kräver nätverk. Dela inte kontolösenord offentligt.
