<script lang="ts">
  import { WebsiteName } from "./../../config"
  import "../../app.css"
</script>

<div class="navbar bg-base-100 container mx-auto">
  <div class="flex-1">
    <a class="btn btn-ghost normal-case text-xl" href="/">{WebsiteName || "Market Watcher"}</a>
  </div>
  <div class="flex-none">
    <ul class="menu menu-horizontal px-1 hidden sm:flex font-bold text-lg">
      <li class="md:mx-2"><a href="/blog">Blog</a></li>
      <li class="md:mx-2"><a href="/pricing">Tarifs</a></li>
      <li class="md:mx-2"><a href="/account">Se connecter</a></li>
    </ul>
    <div class="dropdown dropdown-end sm:hidden">
      <label tabindex="0" class="btn btn-ghost btn-circle">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h7"/>
        </svg>
      </label>
      <ul tabindex="0" class="menu menu-lg dropdown-content mt-3 z-1 p-2 shadow-sm bg-base-100 rounded-box w-52 font-bold">
        <li><a href="/blog">Blog</a></li>
        <li><a href="/pricing">Tarifs</a></li>
        <li><a href="/account">Se connecter</a></li>
      </ul>
    </div>
  </div>
</div>

<!-- Hero Section -->
<section class="container mx-auto px-4 py-16 text-center">
  <h1 class="text-4xl md:text-5xl font-extrabold mb-6 text-primary">Market Watcher : Le SaaS de tracking ultime pour vos produits sur les marketplaces</h1>
  <p class="mb-8 text-lg max-w-2xl mx-auto text-gray-700">
    Protégez votre marque et surveillez la revente de vos produits sur Amazon, eBay, Leboncoin, Rakuten, et plus encore.
    Recevez des alertes instantanées, analysez la concurrence et gardez toujours une longueur d’avance sur le marché !
  </p>
  <a href="/account" class="btn btn-primary btn-lg px-10 py-3 shadow-lg mb-8">Créer un compte gratuitement</a>
  <div class="flex flex-wrap justify-center gap-8 mb-12">
    <div class="card w-80 bg-base-100 shadow-md">
      <div class="card-body">
        <h2 class="card-title">🛒 Multi-Marketplaces</h2>
        <p>Connectez-vous à tous vos canaux de vente : Amazon, eBay, Leboncoin, Rakuten…</p>
      </div>
    </div>
    <div class="card w-80 bg-base-100 shadow-md">
      <div class="card-body">
        <h2 class="card-title">⚡ Alertes instantanées</h2>
        <p>Recevez une notification à chaque nouveau revendeur ou changement de prix.</p>
      </div>
    </div>
    <div class="card w-80 bg-base-100 shadow-md">
      <div class="card-body">
        <h2 class="card-title">📊 Dashboard en temps réel</h2>
        <p>Suivi des performances, analyse des concurrents, historique des ventes et bien plus.</p>
      </div>
    </div>
  </div>
</section>

<!-- How It Works Section -->
<section class="container mx-auto px-4 py-8 text-center">
  <h2 class="text-2xl font-bold mb-4">Comment ça marche ?</h2>
  <div class="grid md:grid-cols-3 gap-8 text-left">
    <div>
      <div class="text-4xl mb-2">🔗</div>
      <h3 class="font-bold text-lg mb-1">Connectez vos produits</h3>
      <p>Ajoutez vos références ou importez votre catalogue depuis votre ERP ou fichier Excel.</p>
    </div>
    <div>
      <div class="text-4xl mb-2">🔎</div>
      <h3 class="font-bold text-lg mb-1">Laissez Market Watcher analyser</h3>
      <p>Notre IA scrute automatiquement les marketplaces et détecte toutes les annonces liées à vos produits.</p>
    </div>
    <div>
      <div class="text-4xl mb-2">📈</div>
      <h3 class="font-bold text-lg mb-1">Visualisez & agissez</h3>
      <p>Recevez des alertes personnalisées, consultez votre dashboard et optimisez votre stratégie commerciale.</p>
    </div>
  </div>
</section>

<!-- Avantages Section -->
<section class="container mx-auto px-4 py-8">
  <h2 class="text-2xl font-bold text-center mb-6">Pourquoi choisir Market Watcher ?</h2>
  <div class="grid md:grid-cols-2 gap-8">
    <div>
      <ul class="list-disc ml-5 space-y-2">
        <li><span class="font-semibold">Gain de temps :</span> Automatisation totale du suivi et reporting.</li>
        <li><span class="font-semibold">Protection de marque :</span> Détection rapide des contrefaçons ou de la revente sauvage.</li>
        <li><span class="font-semibold">Optimisation des marges :</span> Repérez les baisses de prix agressives ou les écarts de tarifs.</li>
        <li><span class="font-semibold">Veille concurrentielle :</span> Suivi des offres concurrentes, analyse du positionnement.</li>
        <li><span class="font-semibold">Interface claire et intuitive :</span> Dashboard simple, alertes configurables, export facile.</li>
      </ul>
    </div>
    <div class="flex items-center justify-center">
      <img src="/marketwatcher-dashboard.png" alt="Dashboard Market Watcher" class="rounded-xl shadow-md max-w-xs" />
    </div>
  </div>
</section>

<!-- CTA Section -->
<section class="container mx-auto px-4 py-12 text-center">
  <div class="bg-primary/10 rounded-xl p-8 md:p-12 max-w-2xl mx-auto">
    <h2 class="text-2xl font-bold mb-4 text-primary">Essayez Market Watcher gratuitement</h2>
    <p class="mb-6">Lancez votre veille en moins de 5 minutes et découvrez toutes les possibilités de la plateforme. Aucun engagement, aucune carte bancaire demandée !</p>
    <a href="/account" class="btn btn-primary btn-lg px-8 py-3">Créer mon compte</a>
  </div>
</section>

<!-- FAQ Section -->
<section class="container mx-auto px-4 py-12">
  <h2 class="text-2xl font-bold text-center mb-8">Foire aux questions</h2>
  <div class="max-w-2xl mx-auto space-y-8">
    <div>
      <h3 class="font-bold mb-2">Est-ce que Market Watcher fonctionne avec tous les marketplaces ?</h3>
      <p>Oui, nous couvrons Amazon, eBay, Leboncoin, Rakuten, Back Market, et bien d’autres. Demandez-nous l’ajout d’une nouvelle plateforme si besoin.</p>
    </div>
    <div>
      <h3 class="font-bold mb-2">Combien coûte la solution ?</h3>
      <p>Vous pouvez consulter nos tarifs sur la page dédiée. Un essai gratuit est proposé à l’inscription.</p>
    </div>
    <div>
      <h3 class="font-bold mb-2">Comment les alertes sont-elles envoyées ?</h3>
      <p>Par e-mail, dans votre dashboard, et bientôt via Slack et SMS selon votre préférence !</p>
    </div>
  </div>
</section>

<!-- Footer -->
<footer class="footer md:footer-horizontal p-10 gap-x-48 lg:gap-x-64 xl:gap-x-96 place-content-center text-base border-t max-w-[1000px] mx-auto">
  <nav>
    <span class="footer-title opacity-80">Explorer</span>
    <a class="link link-hover mb-1" href="/">Accueil</a>
    <a class="link link-hover my-1" href="/pricing">Tarifs</a>
    <a class="link link-hover my-1" href="/blog">Blog</a>
    <a class="link link-hover my-1" href="/contact_us">Contact</a>
  </nav>
  <aside>
    <span class="footer-title opacity-80">Market Watcher</span>
    <div class="max-w-[260px]">
      <div class="font-bold text-2xl mb-1">Protégez votre marque, boostez vos ventes</div>
      <div class="font-medium mb-3">La solution de référence pour le suivi, la détection et la performance de vos produits sur tous les canaux de vente.</div>
    </div>
  </aside>
</footer>
