E-commerce tutorial angular

# ProgettoMEAN

<br>
<h1>MONGO-EXPRESS.ANGULAR-NODE</h1>
<h3>Applicazione link online: https://foodmine-yjri.onrender.com/</h3>
<br><br>
<hr>
# STRUTTURA
<br>

# FRONTEND

<br>
1: ng new frontend(crea Angular App)<br>
2:Crea L'header component <br>
3:Crea HomeComponent con food model,data.ts,Add image to assets,food service.<br>
4:Aggiungi metodi a Food service, crea searchComponent <br>
5:Crea Tags Model e aggiungi a data.ts e a food service, crea il tags component <br>
6:Crea il Food-page Component <br>
7:crea il cart-component con cart Model,cartItem Model,cart service <br>
8:Genera il not found component e aggiungilo a Home,Food,Cart<br>
9:Login-Page component <br>
10:register Component <br>
11: Loading Component <br> 
12: Checkout Page <br>
13: Payment Page <br>
14: Adding PayPal <br>
15:Order Track Page <bR>

# BACKEND  <br>

1:nuovo terminale, npm init -y e aggiungi dependencies: <br>
"dependencies": {
    "bcryptjs": "^2.4.3",
    "cors": "^2.8.5",
    "dotenv": "^16.3.1",
    "express": "^4.18.2",
    "express-async-handler": "^1.2.0",
    "jsonwebtoken": "^9.0.1",
    "mongoose": "^7.5.0",
    "typescript": "^5.2.2"
  },
  "devDependencies": {
    "@types/bcryptjs": "^2.4.3",
    "@types/cors": "^2.8.13",
    "@types/express": "^4.17.17",
    "@types/jsonwebtoken": "^9.0.2",
    "nodemon": "^3.0.1",
    "ts-node": "^10.9.1"
  } <br>
  2:copia data.ts dal front, crea ts.config,crea server.ts,copia urs.ts <br>
  3:componi la struttura back end con middlewares,routes,models : crea i metodi post,get per per la creazione di nuovi utenti,visualizzazione,ordini,prodotti. <br>

# DEPLOY <br>

1:Ho utilizzato render.com , Vai su New e aggiungi web Service <br>
2: connetti il repository git a render <br>
3: dai un nome al progetto,scegli il ramo(main/master) aggiungi i comandi di build e start

# TESTING   <br>
Scopri quanto codice stai testando: ng test --no-watch --code-coverage <br>
Installa i pacchetti necessari:<br
"karma": "^6.4.2",
    "karma-chrome-launcher": "^3.2.0",
    "karma-coverage": "^2.2.1",
    "karma-jasmine": "^5.1.0",
    "karma-jasmine-html-reporter": "^2.1.0"
    "@types/jasmine": "^4.3.5",
     "jasmine-core": "^5.1.1",<br>




<h1>USO IN LOCAL:</h1>
<h3>APRIRE L'APPLICAZIONE GITHUB DESKTOP E CLONARE IL REPOSITORY: https://github.com/luigibuono/ProgettoMEAN </h3><br>

<H3>APRIRE TERMINALE DAL FOLDER FRONTEND E DIGITARE npm install</H3> <br>

<H3>APRIRE TERMINALE DAL FOLDER BACKEND E DIGITARE npm install</H3> <br>

<h3>DAL BACKEND ATTIVARE SERVER CON npm start</h3><br>

<h3>DAL FRONTEND ATTIVARE APPLICAZIONE SUL BROWSER CON ng serve</h3> <br>


# PLUS
<p>Da locale è possibile contattarmi attraverso il footer di pagina, dove è presente il mio profilo social sulle principali piattaforme </p>

<h3>Portfolio: https://websiteluigibuono.netlify.app/ </h3>





