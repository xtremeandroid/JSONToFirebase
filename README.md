# JSONToFirebase
Automate Importing Data to Firestore

Thanks To Plaintext Article:
https://javascript.plainenglish.io/automate-importing-data-to-firestore-836b0a2cdcfd

Important File :
data.json : Contains the data you want to push.
service.json : service account JSON File you got after creating firebase service account.

```bash
git clone https:github.com/xtremeandroid/JSONToFirebase
```

```bash
cd JSONToFirebase
```

```bash
npm install
```

```bash
node index.js
```

### Note : 
* Copy your own data.json and service.json before running the script
* insert your databaseURL from Firebase in Index.js
* change the collection name according to your needs

### TIPS:

### WHERE TO GET service.json File ?

![firefox_xcyPe7U4X4](https://github.com/xtremeandroid/JSONToFirebase/assets/62198074/589f822d-fe15-4120-a0f5-ad9b3917052c)

CLICK on Generate Private Key , It will download the JSON File, Rename it to service.json and copy it to the root directory

### WHERE TO GET databaseURL?

![firefox_SlXi0NtGHK](https://github.com/xtremeandroid/JSONToFirebase/assets/62198074/26de44ba-19f8-4d2d-be78-dfbb9187f2d4)

'databaseURL': 'https://xxxxx.firebaseio.com'
(replace the xx part with datbase name)

### Example

#### Data :
![Code_gG0TlMmw6F](https://github.com/xtremeandroid/JSONToFirebase/assets/62198074/e29c2e2f-a3ff-443b-bcdd-f6b979648fd4)

#### DataBase After Inserting
![firefox_A1tfxbXlxJ](https://github.com/xtremeandroid/JSONToFirebase/assets/62198074/92d21826-0696-445f-a6d1-bcf4f08667fe)


