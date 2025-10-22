# 🎥 Portfolio — Vidéo et Audio de Présentation

Bienvenue dans mon projet **Portfolio personnel**, un site web simple et élégant permettant de présenter mes compétences, mes projets, et une **vidéo/audio de présentation** intégrée directement dans la page.

---

## 📜 Description du projet

Ce projet a été conçu pour offrir une **présentation multimédia** claire et professionnelle.  
Il contient :

- Une **vidéo de présentation** (`index.mp4`)
- Un **audio de présentation** (`index.mp3`)
- Une interface HTML centrée et responsive

L’objectif est de montrer mes réalisations et mes compétences dans un format visuel attractif.

---

## 🧱 Structure du projet

```text
📁 MonPortfolio/
│
├── index.html        → Page principale avec la vidéo et l’audio
├── index.mp4         → Vidéo de présentation
├── index.mp3         → Audio de présentation
├── style.css         → (optionnel) Feuille de style personnalisée
└── README.md         → Ce fichier de documentation
```

---

## 🚀 Fonctionnalités principales

    ✅ Lecture vidéo intégrée
    ✅ Lecture audio intégrée
    ✅ Design simple et centré
    ✅ Compatible avec tous les navigateurs modernes
    ✅ Structure de fichiers claire

---

## 💻 Technologies utilisées

    HTML5 — structure du site

    CSS3 — mise en page et styles

    (optionnel) JavaScript — pour ajouter des interactions dynamiques

---

## 📸 Aperçu du code HTML

<!DOCTYPE html>
<!-- Déclaration du type de document -->
<html lang="fr">
  <!-- Début du document HTML en langue française -->
  <head>
    <meta charset="UTF-8" />
    <!-- Encodage des caractères -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Responsive pour mobile -->
    <!-- <title>Portfolio - Mhadhbi Mourad</title> -->
    <!-- Titre affiché dans l’onglet du navigateur -->
  </head>

  <body bgcolor="#FDFEFE" text="#2C3E50">
    <!-- Corps de la page avec couleur de fond et texte -->
    <!-- ============================= -->
    <!-- BARRE DE NAVIGATION PRINCIPALE -->
    <!-- ============================= -->
    <nav>
      <!-- Barre de navigation -->
      <table width="100%" bgcolor="#2C3E50" cellpadding="10">
        <!-- Tableau pour aligner les liens -->
        <tr>
          <td width="60" align="center">
            <img
              src="https://cdn-icons-png.flaticon.com/512/1077/1077063.png"
              width="40"
              height="40"
              alt="Logo Portfolio"
            />
            <!-- Logo -->
          </td>
          <td align="center">
            <a href="#home"><font color="#ECF0F1">Accueil</font></a>
          </td>
          <!-- Lien Accueil -->
          <td align="center">
            <a href="#about"><font color="#ECF0F1">À propos</font></a>
          </td>
          <!-- Lien À propos -->
          <td align="center">
            <a href="#work"><font color="#ECF0F1">Projets</font></a>
          </td>
          <!-- Lien Projets -->
          <td align="center">
            <a href="#resume"><font color="#ECF0F1">CV</font></a>
          </td>
          <!-- Lien CV -->
          <td align="center">
            <a href="#contact"><font color="#ECF0F1">Contact</font></a>
          </td>
          <!-- Lien Contact -->
        </tr>
      </table>
    </nav>
    <!-- ============================= -->
    <!-- SECTION ACCUEIL -->
    <!-- ============================= -->
    <section id="home">
      <!-- Section d'accueil -->
      <h1 align="center">
        Bienvenue sur le Portfolio de <u>Mhadhbi Mourad</u>
      </h1>
      <!-- Titre principal -->
      <p align="center">
        <i>Développeur Web Junior & Étudiant en Cybersécurité Opérationnelle</i>
      </p>
      <!-- Sous-titre -->
      <p align="center">
        Passionné par le développement, la sécurité informatique et les
        nouvelles technologies, j’aime concevoir des solutions simples,
        performantes et sécurisées.
        <!-- Description -->
      </p>
    </section>
    <hr width="80%" />
    <!-- Ligne de séparation -->
    <!-- ============================= -->
    <!-- SECTION À PROPOS + COMPÉTENCES -->
    <!-- ============================= -->
    <section id="about">
      <!-- Section À propos -->
      <h2 align="center">À propos & Compétences</h2>
      <!-- Titre de section -->
      <table align="center" width="80%">
        <!-- Tableau pour présenter profil + image -->
        <tr>
          <td width="60%">
            <p>
              Je suis <b>Mhadhbi Mourad</b>, développeur web et passionné de
              cybersécurité. Mon objectif est de créer des sites et applications
              performants, accessibles et sécurisés.
            </p>
            <p>
              En tant que <b>lieutenant militaire</b> et
              <b>étudiant en Master de Cybersécurité Opérationnelle</b>, j’ai
              développé un grand sens de la rigueur, de la discipline et de la
              fiabilité, des qualités que j’applique à chacun de mes projets
              informatiques.
            </p>
          </td>
          <td align="center">
            <img
              src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"
              width="200"
              height="200"
              alt="Photo profil"
            />
            <!-- Image profil -->
          </td>
        </tr>
      </table>
      <p align="center"><b>Langues :</b> Arabe, Français, Anglais</p>
      <!-- Langues -->
      <p align="center"><b>Localisation :</b> Tunisie</p>
      <!-- Localisation -->
      <!-- ======== VIDÉO ET AUDIO DE PRÉSENTATION ======== -->
      <center>
        <p><b>Vidéo de présentation :</b></p>
        <!-- Titre vidéo -->
        <video controls>
          <!-- Lecteur vidéo -->
          <source src="/assets/vidéos/vidéo.mp4" type="video/mp4" />
          <!-- Fichier vidéo -->
          Votre navigateur ne supporte pas la lecture de vidéo.
          <!-- Message si non supporté -->
        </video>
        <br /><br />
        <p><b>Audio de présentation :</b></p>
        <!-- Titre audio -->
        <audio controls>
          <!-- Lecteur audio -->
          <source src="/assets/audios/audio.mp3" type="audio/mpeg" />
          <!-- Fichier audio -->
          Votre navigateur ne supporte pas la lecture audio.
          <!-- Message si non supporté -->
        </audio>
      </center>
      <br />
      <h3 align="center">Compétences techniques</h3>
      <!-- Sous-titre -->
      <table border="1" width="70%" align="center" cellpadding="8">
        <!-- Tableau compétences -->
        <tr bgcolor="#D6EAF8" align="center">
          <th>Domaine</th>
          <th>Compétences</th>
        </tr>
        <tr>
          <td>Développement Web</td>
          <td>HTML5, CSS3, JavaScript, PHP, React, Node.js</td>
        </tr>
        <tr>
          <td>Base de données</td>
          <td>MySQL, MariaDB</td>
        </tr>
        <tr>
          <td>Systèmes & Serveurs</td>
          <td>Linux (Ubuntu, CentOS), Apache, Postfix, phpMyAdmin</td>
        </tr>
        <tr>
          <td>Cybersécurité</td>
          <td>
            Analyse réseau, détection d’intrusion, durcissement système, outils
            open source
          </td>
        </tr>
        <tr>
          <td>Outils divers</td>
          <td>Git, Docker, VMware, VSCode</td>
        </tr>
      </table>
    </section>
    <hr width="80%" />
    <!-- Ligne de séparation -->
    <!-- ============================= -->
    <!-- SECTION PROJETS -->
    <!-- ============================= -->
    <section id="work" bgcolor="#EAEDED">
      <!-- Section projets -->
      <h2 align="center">Mes projets</h2>
      <!-- Titre section -->
      <p align="center">
        <i
          >Quelques exemples de mes réalisations dans le développement web et la
          cybersécurité :</i
        >
      </p>
      <ol>
        <!-- Liste ordonnée des projets -->
        <li>
          <a href="projet1.html"><b>Site vitrine</b></a> — Conception complète
          d’un site pour une entreprise locale avec intégration de formulaires
          de contact et base de données (HTML / PHP / MySQL).
        </li>
        <br />
        <li>
          <a href="projet2.html"><b>Application météo</b></a> — Développement
          d’une application web permettant la consultation en direct des
          conditions météo via une API REST (JavaScript / JSON).
        </li>
        <br />
        <li>
          <a href="projet3.html"><b>Jeu du Morpion</b></a> — Réalisation d’un
          mini-jeu interactif en pur HTML et JavaScript, mettant en avant la
          logique côté client.
        </li>
        <br />
        <li>
          <a href="projet4.html"><b>Interface d’administration</b></a> —
          Création d’un tableau de bord pour la gestion d’utilisateurs et de
          contenus avec Node.js et MySQL.
        </li>
        <br />
        <li>
          <a href="projet5.html"><b>Projet cybersécurité</b></a> — Détection
          d’intrusion et surveillance réseau sous Linux (scripts Bash et analyse
          de logs pour la supervision de serveurs).
        </li>
      </ol>
    </section>
    <hr width="80%" />
    <!-- Ligne de séparation -->
    <!-- ============================= -->
    <!-- SECTION CV -->
    <!-- ============================= -->
    <section id="resume">
      <!-- Section parcours / CV -->
      <h2 align="center">Mon parcours</h2>
      <table border="1" width="80%" align="center" cellpadding="6">
        <tr bgcolor="#D6EAF8" align="center">
          <th>Année</th>
          <th>Formation / Expérience</th>
          <th>Détails</th>
        </tr>
        <tr>
          <td align="center">2025</td>
          <td>Master Cybersécurité Opérationnelle</td>
          <td>Formation avancée en sécurité des systèmes d’information.</td>
        </tr>
        <tr>
          <td align="center">2024</td>
          <td>Stage en Développement Web</td>
          <td>Création de sites et intégration d’API REST.</td>
        </tr>
        <tr>
          <td align="center">2023</td>
          <td>Formation Développeur Web</td>
          <td>HTML, CSS, JavaScript, PHP, MySQL.</td>
        </tr>
        <tr>
          <td align="center">2020 - 2022</td>
          <td>Expérience militaire</td>
          <td>Leadership, discipline, gestion d’équipe et sens du détail.</td>
        </tr>
      </table>
    </section>
    <hr width="80%" />
    <!-- Ligne de séparation -->
    <!-- ============================= -->
    <!-- SECTION CONTACT -->
    <!-- ============================= -->
    <section id="contact">
      <!-- Section contact -->
      <h2 align="center">Contact</h2>
      <p align="center">
        Pour toute collaboration, question ou opportunité professionnelle :
      </p>
      <form
        action="mailto:mhadhbi.mourad@example.com"
        method="post"
        enctype="text/plain"
      >
        <!-- Formulaire email -->
        <table align="center" cellpadding="5">
          <tr>
            <td>Nom :</td>
            <td  width="500px"><input name="nom" required /></td>
          </tr>
          <tr>
            <td>Email :</td>
            <td  width="500px"><input type="email" name="email" required /></td>
          </tr>
          <tr>
            <td>Message :</td>
            <td  width="500px"> <input type="text" name="message"  required /></td>
          </tr>
          <tr>
            <td colspan="2" align="center">Envoyer</td>
          </tr>
        </table>
      </form>
    </section>
    <hr width="80%" />
    <!-- Ligne de séparation -->
    <!-- ============================= -->
    <!-- PIED DE PAGE -->
    <!-- ============================= -->
    <footer>
      <!-- Début du pied de page -->
      <table width="100%" bgcolor="#34495E" cellpadding="10">
        <!-- Tableau pied de page -->
        <tr>
          <!-- Colonne gauche : texte et liens sociaux -->
          <td width="75%" valign="top" align="left">
            <font color="#ECF0F1" size="3">
              &copy; 2025 Mhadhbi Mourad — Portfolio
            </font>
            <br /><br />
            <!-- Liens réseaux sociaux -->
            <a href="https://twitter.com/MhadhbiMourad">
              <img
                src="https://cdn-icons-png.flaticon.com/512/733/733579.png"
                width="40"
                height="40"
                alt="Twitter"
              />
              <font color="#ECF0F1">Twitter</font> </a
            ><br />
            <a href="https://linkedin.com/MhadhbiMourad">
              <img
                src="https://cdn-icons-png.flaticon.com/512/733/733561.png"
                width="40"
                height="40"
                alt="LinkedIn"
              />
              <font color="#ECF0F1">LinkedIn</font> </a
            ><br />
            <a href="https://github.com/MhadhbiMourad">
              <img
                src="https://cdn-icons-png.flaticon.com/512/733/733553.png"
                width="40"
                height="40"
                alt="GitHub"
              />
              <font color="#ECF0F1">GitHub</font>
            </a>
          </td>
          <!-- Colonne droite : iframe -->
          <td width="25%" align="center" valign="middle">
            <!-- <iframe src="https://gomycode.co" title="GOMYCODE" width="75%" height="250" frameborder="0" allowfullscreen><iframe> -->
            <!-- Iframe d’un site -->
            <a href="https://gomycode.co">gomycode.co</a>
          </td>
        </tr>
      </table>
    </footer>
  </body>
</html>
<!-- Fin du document -->

---

## 📬 Auteur

    👤 Mhadhbi Mourad
    💼 Lieutenant militaire & Étudiant en Master Cybersécurité Opérationnelle
    🌐 GitHub — MhadhbiMourad
