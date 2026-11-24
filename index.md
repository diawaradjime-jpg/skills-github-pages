<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SIRENA Informatique — Solutions &amp; services IT à Bamako</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- 1. En-tête / Navigation + Menu mobile -->
  <header class="sticky top-0 z-40 bg-white border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
      <!-- Logo SIRENA Informatique -->
      <a href="#" class="flex flex-col leading-none">
        <span class="text-xl font-extrabold tracking-tight text-sky-700">SIRENA INFORMATIQUE</span>
        <span class="text-[11px] font-medium uppercase tracking-widest text-slate-500 mt-1">Bamako — Mali</span>
      </a>

      <!-- Menu principal (Bureau) -->
      <nav class="hidden lg:flex items-center space-x-7 text-xs font-semibold uppercase tracking-wider text-slate-700" aria-label="Navigation principale">
        <a href="#solutions" class="hover:text-sky-700 transition">Solutions IT</a>
        <a href="#services" class="hover:text-sky-700 transition">Services</a>
        <a href="#clients" class="hover:text-sky-700 transition">Espaces clients</a>
        <a href="#apropos" class="hover:text-sky-700 transition">À propos de nous</a>
        <a href="#actualites" class="hover:text-sky-700 transition">Nouvelles</a>
        <a href="#contact" class="px-4 py-2 bg-sky-700 text-white rounded hover:bg-sky-800 transition">Contact</a>
      </nav>

      <!-- Bouton Hamburger (Mobile & Tablette) -->
      <button
        id="mobile-menu-btn"
        type="button"
        class="lg:hidden inline-flex items-center justify-center p-2 rounded-md text-slate-700 hover:text-sky-700 hover:bg-slate-100 focus:outline-none focus:ring-2 focus:ring-sky-600"
        aria-controls="mobile-menu"
        aria-expanded="false"
        aria-label="Ouvrir le menu principal"
      >
        <!-- Icône Burger -->
        <svg id="icon-burger" class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
        <!-- Icône Fermer -->
        <svg id="icon-close" class="w-6 h-6 hidden" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>
    </div>

    <!-- Panneau Menu Mobile -->
    <div id="mobile-menu" class="lg:hidden hidden bg-white border-t border-slate-200 shadow-lg">
      <nav class="px-4 py-4 space-y-1 text-sm font-semibold uppercase tracking-wider text-slate-700" aria-label="Navigation mobile">
        <a href="#solutions" class="mobile-link block px-3 py-2.5 rounded hover:bg-slate-50 hover:text-sky-700">Solutions IT</a>
        <a href="#services" class="mobile-link block px-3 py-2.5 rounded hover:bg-slate-50 hover:text-sky-700">Services</a>
        <a href="#clients" class="mobile-link block px-3 py-2.5 rounded hover:bg-slate-50 hover:text-sky-700">Espaces clients</a>
        <a href="#apropos" class="mobile-link block px-3 py-2.5 rounded hover:bg-slate-50 hover:text-sky-700">À propos de nous</a>
        <a href="#actualites" class="mobile-link block px-3 py-2.5 rounded hover:bg-slate-50 hover:text-sky-700">Nouvelles</a>
        <div class="pt-2">
          <a href="#contact" class="mobile-link block w-full text-center px-4 py-3 bg-sky-700 text-white rounded hover:bg-sky-800 transition">Contact</a>
        </div>
      </nav>
    </div>
  </header>

  <!-- 2. Bandeau Héro -->
  <section class="relative bg-slate-900 text-white py-20 lg:py-28">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="max-w-2xl">
        <p class="text-sm font-semibold uppercase tracking-wider text-sky-400 mb-3">
          SIRENA Informatique • Bamako, Mali
        </p>
        <h1 class="text-3xl sm:text-5xl font-bold leading-tight mb-6">
          Nous accompagnons vos systèmes informatiques, réseaux et infrastructures au quotidien.
        </h1>
        <p class="text-base sm:text-lg text-slate-300 leading-relaxed mb-8">
          Expertise en administration systèmes et réseaux, cloud, cybersécurité, développement d'applications, bases de données et support technique pour les entreprises et organisations au Mali.
        </p>
        <div class="flex flex-wrap gap-4">
          <a href="#solutions" class="inline-block bg-sky-600 hover:bg-sky-500 text-white text-sm font-semibold uppercase tracking-wide px-6 py-3.5 rounded transition">
            En savoir plus
          </a>
          <a href="#contact" class="inline-block border border-slate-500 hover:border-white text-white text-sm font-semibold uppercase tracking-wide px-6 py-3.5 rounded transition">
            Nous contacter
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- 3. Présentation générale -->
  <section id="apropos" class="py-16 bg-slate-50 border-b border-slate-200">
    <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <h2 class="text-2xl sm:text-3xl font-bold text-slate-900 mb-4">
        SIRENA Informatique : des solutions numériques fiables et évolutives
      </h2>
      <p class="text-slate-600 leading-relaxed max-w-3xl mx-auto">
        Basée à Bamako au Mali, SIRENA Informatique accompagne les entreprises, institutions et équipes techniques de l'audit et du déploiement jusqu'à la maintenance et l'assistance informatique.
      </p>
    </div>
  </section>

  <!-- 4. Grille des domaines informatiques (2 lignes de 4 cartes) -->
  <section id="solutions" class="py-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-12">
        <h2 class="text-2xl sm:text-3xl font-bold text-slate-900">Nos domaines informatiques</h2>
        <p class="text-slate-600 mt-2">Des pôles dédiés pour couvrir vos besoins techniques et applicatifs</p>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Carte 1 -->
        <a href="#contact" data-service="Cloud & serveurs" class="service-card group border border-slate-200 bg-white p-8 text-center rounded-md hover:border-sky-600 hover:shadow-md transition flex flex-col items-center justify-center">
          <div class="w-14 h-14 mb-4 rounded-full bg-sky-50 text-sky-700 flex items-center justify-center group-hover:bg-sky-700 group-hover:text-white transition">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.75" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M3 15a4 4 0 004 4h9a5 5 0 10-.1-9.999 5.002 5.002 0 10-9.78 2.096A4.001 4.001 0 003 15z" />
            </svg>
          </div>
          <h3 class="font-semibold text-base text-slate-900">Cloud &amp; serveurs</h3>
        </a>

        <!-- Carte 2 -->
        <a href="#contact" data-service="Cybersécurité" class="service-card group border border-slate-200 bg-white p-8 text-center rounded-md hover:border-sky-600 hover:shadow-md transition flex flex-col items-center justify-center">
          <div class="w-14 h-14 mb-4 rounded-full bg-sky-50 text-sky-700 flex items-center justify-center group-hover:bg-sky-700 group-hover:text-white transition">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.75" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 3l7 4v5c0 5-3.5 8.5-7 10-3.5-1.5-7-5-7-10V7l7-4z" />
            </svg>
          </div>
          <h3 class="font-semibold text-base text-slate-900">Cybersécurité</h3>
        </a>

        <!-- Carte 3 -->
        <a href="#contact" data-service="Réseaux & connectivité" class="service-card group border border-slate-200 bg-white p-8 text-center rounded-md hover:border-sky-600 hover:shadow-md transition flex flex-col items-center justify-center">
          <div class="w-14 h-14 mb-4 rounded-full bg-sky-50 text-sky-700 flex items-center justify-center group-hover:bg-sky-700 group-hover:text-white transition">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.75" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M8.111 16.404a5.5 5.5 0 017.778 0M12 20h.01m-7.08-7.071c3.904-3.905 10.236-3.905 14.141 0M1.394 9.393c5.857-5.857 15.355-5.857 21.213 0" />
            </svg>
          </div>
          <h3 class="font-semibold text-base text-slate-900">Réseaux &amp; connectivité</h3>
        </a>

        <!-- Carte 4 -->
        <a href="#contact" data-service="Développement logiciel" class="service-card group border border-slate-200 bg-white p-8 text-center rounded-md hover:border-sky-600 hover:shadow-md transition flex flex-col items-center justify-center">
          <div class="w-14 h-14 mb-4 rounded-full bg-sky-50 text-sky-700 flex items-center justify-center group-hover:bg-sky-700 group-hover:text-white transition">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.75" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" />
            </svg>
          </div>
          <h3 class="font-semibold text-base text-slate-900">Développement logiciel</h3>
        </a>

        <!-- Carte 5 -->
        <a href="#contact" data-service="Données & bases de données" class="service-card group border border-slate-200 bg-white p-8 text-center rounded-md hover:border-sky-600 hover:shadow-md transition flex flex-col items-center justify-center">
          <div class="w-14 h-14 mb-4 rounded-full bg-sky-50 text-sky-700 flex items-center justify-center group-hover:bg-sky-700 group-hover:text-white transition">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.75" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4" />
            </svg>
          </div>
          <h3 class="font-semibold text-base text-slate-900">Données &amp; bases de données</h3>
        </a>

        <!-- Carte 6 -->
        <a href="#contact" data-service="DevOps & automatisation" class="service-card group border border-slate-200 bg-white p-8 text-center rounded-md hover:border-sky-600 hover:shadow-md transition flex flex-col items-center justify-center">
          <div class="w-14 h-14 mb-4 rounded-full bg-sky-50 text-sky-700 flex items-center justify-center group-hover:bg-sky-700 group-hover:text-white transition">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.75" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z" />
              <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
            </svg>
          </div>
          <h3 class="font-semibold text-base text-slate-900">DevOps &amp; automatisation</h3>
        </a>

        <!-- Carte 7 -->
        <a href="#contact" data-service="Supervision & audit" class="service-card group border border-slate-200 bg-white p-8 text-center rounded-md hover:border-sky-600 hover:shadow-md transition flex flex-col items-center justify-center">
          <div class="w-14 h-14 mb-4 rounded-full bg-sky-50 text-sky-700 flex items-center justify-center group-hover:bg-sky-700 group-hover:text-white transition">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.75" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
            </svg>
          </div>
          <h3 class="font-semibold text-base text-slate-900">Supervision &amp; audit</h3>
        </a>

        <!-- Carte 8 -->
        <a href="#contact" data-service="Support & maintenance" class="service-card group border border-slate-200 bg-white p-8 text-center rounded-md hover:border-sky-600 hover:shadow-md transition flex flex-col items-center justify-center">
          <div class="w-14 h-14 mb-4 rounded-full bg-sky-50 text-sky-700 flex items-center justify-center group-hover:bg-sky-700 group-hover:text-white transition">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.75" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-5 0a4 4 0 11-8 0 4 4 0 018 0z" />
            </svg>
          </div>
          <h3 class="font-semibold text-base text-slate-900">Support &amp; maintenance</h3>
        </a>
      </div>
    </div>
  </section>

  <!-- 5. Section Actualités -->
  <section id="actualites" class="py-16 bg-slate-50 border-t border-slate-200">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-2xl sm:text-3xl font-bold text-slate-900 mb-8">Nouvelles</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <article class="bg-white border border-slate-200 p-6 rounded-md">
          <time class="text-xs font-semibold uppercase tracking-wider text-sky-700">Novembre 2026</time>
          <h3 class="text-lg font-bold text-slate-900 mt-2 mb-2">SIRENA Informatique à Bamako</h3>
          <p class="text-sm text-slate-600 leading-relaxed">
            Accompagnement des organisations dans la modernisation des serveurs, la sauvegarde et la continuité d'activité.
          </p>
        </article>

        <article class="bg-white border border-slate-200 p-6 rounded-md">
          <time class="text-xs font-semibold uppercase tracking-wider text-sky-700">Octobre 2026</time>
          <h3 class="text-lg font-bold text-slate-900 mt-2 mb-2">Sécurisation des accès et des postes de travail</h3>
          <p class="text-sm text-slate-600 leading-relaxed">
            Bonnes pratiques de protection des données, gestion des droits et sensibilisation des équipes.
          </p>
        </article>

        <article class="bg-white border border-slate-200 p-6 rounded-md">
          <time class="text-xs font-semibold uppercase tracking-wider text-sky-700">Septembre 2026</time>
          <h3 class="text-lg font-bold text-slate-900 mt-2 mb-2">Maintenance préventive et performance réseau</h3>
          <p class="text-sm text-slate-600 leading-relaxed">
            Suivi régulier des équipements et optimisation des infrastructures pour réduire les interruptions de service.
          </p>
        </article>
      </div>
    </div>
  </section>

  <!-- 6. Formulaire de contact interactif -->
  <section id="contact" class="py-20 bg-white border-t border-slate-200">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 lg:grid-cols-12 gap-10">
      <!-- Coordonnées SIRENA Informatique -->
      <div class="lg:col-span-5">
        <p class="text-xs font-semibold uppercase tracking-wider text-sky-700 mb-2">Contact direct</p>
        <h2 class="text-2xl sm:text-3xl font-bold text-slate-900 mb-4">Parlons de votre projet IT</h2>
        <p class="text-slate-600 leading-relaxed mb-6">
          Besoin d'un devis, d'un diagnostic réseau ou d'une assistance technique ? Remplissez le formulaire ou contactez directement SIRENA Informatique à Bamako.
        </p>

        <div class="space-y-4 bg-slate-50 border border-slate-200 p-6 rounded-md text-sm">
          <div>
            <span class="block text-xs font-bold uppercase tracking-wider text-slate-500">Entreprise &amp; Localisation</span>
            <span class="font-semibold text-slate-900">SIRENA Informatique — Bamako, Mali</span>
          </div>

          <div>
            <span class="block text-xs font-bold uppercase tracking-wider text-slate-500">Téléphone</span>
            <a href="tel:+22376414616" class="font-semibold text-sky-700 hover:underline">(+223) 76414616</a>
          </div>

          <div>
            <span class="block text-xs font-bold uppercase tracking-wider text-slate-500">E-mail</span>
            <div class="flex items-center gap-3 mt-0.5">
              <a href="mailto:sirenainfo@yahoo.fr" class="font-semibold text-sky-700 hover:underline">sirenainfo@yahoo.fr</a>
              <button
                id="copy-email-btn"
                type="button"
                class="text-xs px-2.5 py-1 rounded border border-slate-300 bg-white text-slate-700 hover:bg-slate-100 transition"
              >
                Copier
              </button>
            </div>
            <span id="copy-feedback" class="text-xs text-emerald-700 hidden mt-1 block">Adresse copiée dans le presse-papiers.</span>
          </div>
        </div>
      </div>

      <!-- Formulaire -->
      <div class="lg:col-span-7 bg-slate-50 border border-slate-200 p-6 sm:p-8 rounded-md">
        <form id="contact-form" novalidate class="space-y-5">
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
            <div>
              <label for="nom" class="block text-xs font-semibold uppercase tracking-wider text-slate-700 mb-1.5">
                Nom complet *
              </label>
              <input
                type="text"
                id="nom"
                name="nom"
                required
                placeholder="Ex. Moussa Traoré"
                class="w-full px-4 py-2.5 bg-white border border-slate-300 rounded text-sm text-slate-900 focus:outline-none focus:border-sky-600 focus:ring-1 focus:ring-sky-600"
              />
              <p class="error-msg text-xs text-red-600 mt-1 hidden"></p>
            </div>

            <div>
              <label for="email" class="block text-xs font-semibold uppercase tracking-wider text-slate-700 mb-1.5">
                Adresse e-mail *
              </label>
              <input
                type="email"
                id="email"
                name="email"
                required
                placeholder="nom@entreprise.ml"
                class="w-full px-4 py-2.5 bg-white border border-slate-300 rounded text-sm text-slate-900 focus:outline-none focus:border-sky-600 focus:ring-1 focus:ring-sky-600"
              />
              <p class="error-msg text-xs text-red-600 mt-1 hidden"></p>
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
            <div>
              <label for="telephone" class="block text-xs font-semibold uppercase tracking-wider text-slate-700 mb-1.5">
                Téléphone
              </label>
              <input
                type="tel"
                id="telephone"
                name="telephone"
                placeholder="(+223) ..."
                class="w-full px-4 py-2.5 bg-white border border-slate-300 rounded text-sm text-slate-900 focus:outline-none focus:border-sky-600 focus:ring-1 focus:ring-sky-600"
              />
            </div>

            <div>
              <label for="domaine" class="block text-xs font-semibold uppercase tracking-wider text-slate-700 mb-1.5">
                Domaine concerné
              </label>
              <select
                id="domaine"
                name="domaine"
                class="w-full px-4 py-2.5 bg-white border border-slate-300 rounded text-sm text-slate-900 focus:outline-none focus:border-sky-600 focus:ring-1 focus:ring-sky-600"
              >
                <option value="Cloud & serveurs">Cloud &amp; serveurs</option>
                <option value="Cybersécurité">Cybersécurité</option>
                <option value="Réseaux & connectivité">Réseaux &amp; connectivité</option>
                <option value="Développement logiciel">Développement logiciel</option>
                <option value="Données & bases de données">Données &amp; bases de données</option>
                <option value="DevOps & automatisation">DevOps &amp; automatisation</option>
                <option value="Supervision & audit">Supervision &amp; audit</option>
                <option value="Support & maintenance">Support &amp; maintenance</option>
              </select>
            </div>
          </div>

          <div>
            <label for="message" class="block text-xs font-semibold uppercase tracking-wider text-slate-700 mb-1.5">
              Message *
            </label>
            <textarea
              id="message"
              name="message"
              rows="4"
              required
              placeholder="Décrivez brièvement votre besoin ou votre demande d'assistance..."
              class="w-full px-4 py-2.5 bg-white border border-slate-300 rounded text-sm text-slate-900 focus:outline-none focus:border-sky-600 focus:ring-1 focus:ring-sky-600"
            ></textarea>
            <p class="error-msg text-xs text-red-600 mt-1 hidden"></p>
          </div>

          <div class="flex flex-wrap items-center justify-between gap-4 pt-1">
            <button
              type="submit"
              class="px-6 py-3 bg-sky-700 hover:bg-sky-800 text-white text-sm font-semibold uppercase tracking-wide rounded transition"
            >
              Envoyer la demande
            </button>
            <span class="text-xs text-slate-500">* Champs obligatoires</span>
          </div>

          <!-- Message de confirmation / résumé -->
          <div id="form-status" class="hidden p-4 rounded border text-sm"></div>
        </form>
      </div>
    </div>
  </section>

  <!-- 7. Pied de page multi-colonnes -->
  <footer class="bg-slate-900 text-slate-300 pt-16 pb-10">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-12 border-b border-slate-800">
      <div>
        <h4 class="text-xs font-bold uppercase tracking-wider text-white mb-4">Solutions IT</h4>
        <ul class="space-y-2 text-sm">
          <li><a href="#solutions" class="hover:text-white">Cloud &amp; serveurs</a></li>
          <li><a href="#solutions" class="hover:text-white">Cybersécurité</a></li>
          <li><a href="#solutions" class="hover:text-white">Réseaux &amp; connectivité</a></li>
          <li><a href="#solutions" class="hover:text-white">Développement logiciel</a></li>
        </ul>
      </div>

      <div>
        <h4 class="text-xs font-bold uppercase tracking-wider text-white mb-4">Services</h4>
        <ul class="space-y-2 text-sm">
          <li><a href="#services" class="hover:text-white">Audit &amp; conseil</a></li>
          <li><a href="#services" class="hover:text-white">Support &amp; maintenance</a></li>
          <li><a href="#clients" class="hover:text-white">Espaces clients</a></li>
        </ul>
      </div>

      <div>
        <h4 class="text-xs font-bold uppercase tracking-wider text-white mb-4">SIRENA Informatique</h4>
        <ul class="space-y-2 text-sm">
          <li><a href="#apropos" class="hover:text-white">À propos de nous</a></li>
          <li><a href="#actualites" class="hover:text-white">Nouvelles</a></li>
          <li><a href="#contact" class="hover:text-white">Contact</a></li>
        </ul>
      </div>

      <div>
        <h4 class="text-xs font-bold uppercase tracking-wider text-white mb-4">Contact</h4>
        <p class="text-sm text-white font-semibold mb-1">SIRENA Informatique</p>
        <p class="text-sm text-slate-400">Bamako - Mali</p>
        <p class="text-sm text-slate-300 mt-2">
          Tél : <a href="tel:+22376414616" class="hover:text-white">(+223) 76414616</a>
        </p>
        <p class="text-sm text-slate-300 mt-1">
          E-mail : <a href="mailto:sirenainfo@yahoo.fr" class="hover:text-white">sirenainfo@yahoo.fr</a>
        </p>
      </div>
    </div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-8 flex flex-col sm:flex-row justify-between items-center text-xs text-slate-500">
      <p>© 2026 SIRENA Informatique — Bamako, Mali. Tous droits réservés.</p>
      <div class="flex space-x-6 mt-4 sm:mt-0">
        <a href="#" class="hover:text-slate-300">Mentions légales</a>
        <a href="#" class="hover:text-slate-300">Politique de confidentialité</a>
      </div>
    </div>
  </footer>

  <!-- 8. Script JavaScript (Menu mobile + Validation & Envoi Formulaire) -->
  <script>
    (function () {
      // --- 1. Menu mobile ---
      const menuBtn = document.getElementById('mobile-menu-btn');
      const mobileMenu = document.getElementById('mobile-menu');
      const iconBurger = document.getElementById('icon-burger');
      const iconClose = document.getElementById('icon-close');
      const mobileLinks = document.querySelectorAll('.mobile-link');

      function setMenuState(isOpen) {
        if (!mobileMenu || !menuBtn) return;
        mobileMenu.classList.toggle('hidden', !isOpen);
        iconBurger.classList.toggle('hidden', isOpen);
        iconClose.classList.toggle('hidden', !isOpen);
        menuBtn.setAttribute('aria-expanded', String(isOpen));
      }

      if (menuBtn) {
        menuBtn.addEventListener('click', () => {
          const isCurrentlyOpen = menuBtn.getAttribute('aria-expanded') === 'true';
          setMenuState(!isCurrentlyOpen);
        });
      }

      mobileLinks.forEach((link) => {
        link.addEventListener('click', () => setMenuState(false));
      });

      document.addEventListener('keydown', (event) => {
        if (event.key === 'Escape') {
          setMenuState(false);
        }
      });

      // --- 2. Pré-sélection du domaine au clic sur une carte ---
      const domaineSelect = document.getElementById('domaine');
      document.querySelectorAll('.service-card').forEach((card) => {
        card.addEventListener('click', () => {
          const service = card.getAttribute('data-service');
          if (domaineSelect && service) {
            domaineSelect.value = service;
          }
        });
      });

      // --- 3. Copie rapide de l'adresse e-mail ---
      const copyBtn = document.getElementById('copy-email-btn');
      const copyFeedback = document.getElementById('copy-feedback');
      if (copyBtn && navigator.clipboard) {
        copyBtn.addEventListener('click', async () => {
          try {
            await navigator.clipboard.writeText('sirenainfo@yahoo.fr');
            if (copyFeedback) {
              copyFeedback.classList.remove('hidden');
              setTimeout(() => copyFeedback.classList.add('hidden'), 3000);
            }
          } catch (_) {
            // Ignorer si l'accès au presse-papiers est bloqué par le navigateur
          }
        });
      }

      // --- 4. Validation et soumission du formulaire ---
      const form = document.getElementById('contact-form');
      const statusBox = document.getElementById('form-status');

      function setFieldError(input, message) {
        const errorEl = input.parentElement.querySelector('.error-msg');
        if (message) {
          input.classList.remove('border-slate-300');
          input.classList.add('border-red-500');
          if (errorEl) {
            errorEl.textContent = message;
            errorEl.classList.remove('hidden');
          }
        } else {
          input.classList.remove('border-red-500');
          input.classList.add('border-slate-300');
          if (errorEl) {
            errorEl.textContent = '';
            errorEl.classList.add('hidden');
          }
        }
      }

      function showStatus(type, htmlContent) {
        if (!statusBox) return;
        statusBox.className = 'p-4 rounded border text-sm block';
        if (type === 'success') {
          statusBox.classList.add('bg-emerald-50', 'border-emerald-300', 'text-emerald-900');
        } else {
          statusBox.classList.add('bg-red-50', 'border-red-300', 'text-red-900');
        }
        statusBox.innerHTML = htmlContent;
      }

      if (form) {
        form.addEventListener('submit', async (event) => {
          event.preventDefault();

          const nomInput = document.getElementById('nom');
          const emailInput = document.getElementById('email');
          const telInput = document.getElementById('telephone');
          const messageInput = document.getElementById('message');

          let isValid = true;

          const nomVal = nomInput.value.trim();
          if (!nomVal) {
            setFieldError(nomInput, 'Veuillez indiquer votre nom complet.');
            isValid = false;
          } else {
            setFieldError(nomInput, '');
          }

          const emailVal = emailInput.value.trim();
          const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
          if (!emailVal || !emailRegex.test(emailVal)) {
            setFieldError(emailInput, 'Veuillez saisir une adresse e-mail valide.');
            isValid = false;
          } else {
            setFieldError(emailInput, '');
          }

          const msgVal = messageInput.value.trim();
          if (msgVal.length < 10) {
            setFieldError(messageInput, 'Veuillez saisir un message (au moins 10 caractères).');
            isValid = false;
          } else {
            setFieldError(messageInput, '');
          }

          if (!isValid) {
            showStatus('error', 'Veuillez corriger les champs signalés avant d’envoyer votre message.');
            return;
          }

          // Optionnel : pour envoyer réellement vers un endpoint HTTP (ex. PHP, Node/Express ou Formspree),
          // décommentez le bloc fetch ci-dessous et remplacez URL_DE_VOTRE_API.
          /*
          try {
            const response = await fetch('URL_DE_VOTRE_API', {
              method: 'POST',
              headers: { 'Content-Type': 'application/json', 'Accept': 'application/json' },
              body: JSON.stringify({
                nom: nomVal,
                email: emailVal,
                telephone: telInput.value.trim(),
                domaine: domaineSelect.value,
                message: msgVal,
                destinataire: 'sirenainfo@yahoo.fr'
              })
            });
            if (!response.ok) throw new Error('Erreur réseau');
          } catch (err) {
            showStatus('error', 'Impossible d’envoyer le message pour le moment. Vous pouvez écrire directement à <strong>sirenainfo@yahoo.fr</strong> ou appeler le <strong>(+223) 76414616</strong>.');
            return;
          }
          */

          // Retour immédiat côté client + lien mailto de secours
          const mailtoSubject = encodeURIComponent(`[SIRENA Informatique] ${domaineSelect.value} — ${nomVal}`);
          const mailtoBody = encodeURIComponent(
            `Nom : ${nomVal}\nE-mail : ${emailVal}\nTéléphone : ${telInput.value.trim() || 'Non précisé'}\nDomaine : ${domaineSelect.value}\n\nMessage :\n${msgVal}`
          );
          const mailtoHref = `mailto:sirenainfo@yahoo.fr?subject=${mailtoSubject}&body=${mailtoBody}`;

          showStatus(
            'success',
            `<strong>Demande préparée avec succès.</strong><br/>` +
            `Votre message concernant <strong>${domaineSelect.value}</strong> a bien été vérifié. ` +
            `Si vous n’avez pas encore relié un serveur d’envoi automatique, vous pouvez l’expédier directement via votre messagerie : ` +
            `<a href="${mailtoHref}" class="underline font-semibold">Ouvrir dans l’application e-mail (sirenainfo@yahoo.fr)</a>.`
          );

          form.reset();
        });
      }
    })();
  </script>

</body>
</html>
