
<h1> Problem Statement </h1>
  
<body>
Phishing is the most popular form of social engineering and can be leveraged to put malware or ransomware into a company’s environments. MISO performs routine phishing tests to make sure their employees are ready and prepared. ECS helps protect companies from cyber threats everyday, and IN3 helps bring people together to create a hub of national security innovation to help solve critical defense priorities. How can data science and predictive analytics help employees gain confidence in receiving emails that they are real?
 
</body>
<h2> Data Collection </h2>
<ul>
  <li>Enron Corpus: Non-Phishing Emails</li>
  <li>Nazario Corpus: Phishing Emails</li>
  <br>
  <body> Data Wrangled from the publicly available corpora and parsed to the csv format </body>
 </ul>
<h2> Analysis Levels </h2>
<ul>
  <li>Link and Domain</li>
  <ol>
  <li>Fradulent Domain</li>
  <li>Malicious URL</li>
   <li>Whitelisted URLS</li>
  </ol>
  <li>Content</li>
   <ol>
  <li>Generalized Salutation</li>
  <li>Call for Action</li>
  </ol>
   <li>MetaData</li>
  <ol>
  <li>Email Abbreviations</li>  
  </ol>
 </ul

<h2> Exploratory Data Analysis </h2>

<h3> This plot shows that phishing emails have generalized Salutation  </h3>
<img width="330" alt="image" src="https://user-images.githubusercontent.com/39126672/158035758-efce484c-8b3a-4391-b850-66a5ce3fe925.png">
<h3> This plot shows the distribution of second person pronouns in the emails  </h3>
<img width="337" alt="image" src="https://user-images.githubusercontent.com/39126672/158035773-8c82e7c2-fd71-4595-bfaf-4f0887473431.png">
<h3> This plot shows that emails in the Replied thread are generally not phishing </h3>
<img width="314" alt="image" src="https://user-images.githubusercontent.com/39126672/158035776-30300596-ab83-4f57-bacf-24a9d6c9113b.png">
<h3> Profiles of a phishing email </h3>
<img width="396" alt="image" src="https://user-images.githubusercontent.com/39126672/158035803-a3a3ad3c-ece0-4c02-a8fb-fd1ff918bf54.png">


