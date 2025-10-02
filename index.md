---
layout: default
title: Support — AvecUnSucre
---

<header class="support">
  <img class="appicon" src="{{ '/assets/app-icon.png' | relative_url }}" alt="Icône de l’app AvecUnSucre">
  <div>
    <h1>Support — AvecUnSucre</h1>
    <p class="lead">Besoin d’aide ? Voici les ressources officielles.</p>
  </div>
</header>

<div class="grid">
  <section class="card">
    <h2>FAQ express</h2>
    <ul>
      <li><strong>Connexion impossible</strong> : vérifiez l’e-mail et le mot de passe.
        Si besoin, réinitialisez depuis l’écran de connexion.</li>
      <li><strong>Suppression du compte</strong> : dans l’app <code>Onglet 3 → Paramètres du compte → Supprimer mon compte</code>.</li>
    </ul>
  </section>

  <section class="card">
    <h2>Nous contacter</h2>
    <form class="support-form" action="https://formspree.io/f/app@avecunsucre.com" method="POST">
      <label for="email">Votre e-mail
        <input id="email" type="email" name="email" placeholder="[email protected]" required>
      </label>
      <label for="message">Message
        <textarea id="message" name="message" placeholder="Décrivez le problème rencontré…" required></textarea>
      </label>
      <!-- honeypot anti-bot -->
      <input type="text" name="_gotcha" class="sr-only" tabindex="-1" autocomplete="off">
      <!-- redirection optionnelle après envoi -->
      <!-- <input type="hidden" name="_next" value="https://ton-domaine/support/sent.html"> -->
      <button class="btn-primary" type="submit">Envoyer</button>
    </form>
    <p style="margin-top:8px;color:#475569"><small>Astuce : joignez, si possible, l’heure du problème et une capture d’écran.</small></p>
  </section>
</div>

<section style="margin-top:16px" class="card legal">
  <h2>Légal</h2>
  <ul>
    <li><a href="https://docs.google.com/document/d/17sQi_dUvyDOxI2UTCGHvLUBDMbQMWrpPKoc8qtzVgs4/edit?usp=drive_link" rel="noopener">Politique de confidentialité</a></li>
    <li><a href="{{ '/terms' | relative_url }}">Conditions d’utilisation</a></li>
  </ul>
</section>
