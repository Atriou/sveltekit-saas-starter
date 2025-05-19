<script lang="ts">
  import { WebsiteName } from "./../../config"
  import "../../app.css"

  interface Props {
    children?: import("svelte").Snippet
  }

  let { children }: Props = $props()
</script>

<div class="navbar bg-base-100 container mx-auto">
  <div class="flex-1">
    <a class="btn btn-ghost normal-case text-xl" href="/">{WebsiteName}</a>
  </div>
  <div class="flex-none">
    <ul class="menu menu-horizontal px-1 hidden sm:flex font-bold text-lg">
      <li class="md:mx-4">
        <a
          href="https://github.com/Atriou/sveltekit-saas-starter"
          class="border border-primary">★ Nous soutenir sur Github</a>
      </li>
      <li class="md:mx-2"><a href="/blog">Blog</a></li>
      <li class="md:mx-2"><a href="/pricing">Tarifs</a></li>
      <li class="md:mx-2"><a href="/account">Compte</a></li>
      <li class="md:mx-0">
        <a href="/search" aria-label="Recherche">
          <svg fill="#000000" class="w-6 h-6" viewBox="0 0 20 20">
            <path d="M17.545 15.467l-3.779-3.779a6.15 6.15 0 0 0 .898-3.21c0-3.417-2.961-6.377-6.378-6.377A6.185 6.185 0 0 0 2.1 8.287c0 3.416 2.961 6.377 6.377 6.377a6.15 6.15 0 0 0 3.115-.844l3.799 3.801a.953.953 0 0 0 1.346 0l.943-.943c.371-.371.236-.84-.135-1.211zM4.004 8.287a4.282 4.282 0 0 1 4.282-4.283c2.366 0 4.474 2.107 4.474 4.474a4.284 4.284 0 0 1-4.283 4.283c-2.366-.001-4.473-2.109-4.473-4.474z" fill="currentColor"/>
          </svg>
        </a>
      </li>
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
        <li><a href="/account">Compte</a></li>
        <li><a href="/search">Recherche</a></li>
        <li>
          <a href="https://github.com/Atriou/sveltekit-saas-starter" class="border border-primary">★ Github</a>
        </li>
      </ul>
    </div>
  </div>
</div>

<div class="container mx-auto px-4 py-16 text-center">
  <h1 class="text-4xl font-bold mb-6">Le SaaS de tracking ultime pour vos produits sur les marketplaces</h1>
  <p class="mb-8 text-lg">
    Surveillez, analysez et maîtrisez la revente de vos produits sur Amazon, eBay et toutes les marketplaces.<br>
    Détectez instantanément les revendeurs, suivez l’évolution de vos listings et protégez votre business !
  </p>
  <a href="/account" class="btn btn-primary btn-lg px-8 mt-4 shadow-lg">Essayer gratuitement</a>
  <div class="flex flex-wrap justify-center mt-10 gap-8">
    <div class="card w-80 bg-base-100 shadow-md">
      <div class="card-body">
        <h2 class="card-title">🛒 Multi-Marketplaces</h2>
        <p>Suivi automatique sur Amazon, eBay, Leboncoin, Rakuten et bien plus.</p>
      </div>
    </div>
    <div class="card w-80 bg-base-100 shadow-md">
      <div class="card-body">
        <h2 class="card-title">⚡ Alertes instantanées</h2>
        <p>Soyez notifié dès qu’un nouveau revendeur apparaît ou qu’une offre change.</p>
      </div>
    </div>
    <div class="card w-80 bg-base-100 shadow-md">
      <div class="card-body">
        <h2 class="card-title">📊 Dashboard en temps réel</h2>
        <p>Visualisez toutes les données clés : prix, stock, historique, concurrents…</p>
      </div>
    </div>
  </div>
</div>

<div class="grow"></div>
<div>
  <div class="border-t max-w-[1000px] mx-auto"></div>
  <footer class="footer md:footer-horizontal p-10 gap-x-48 lg:gap-x-64 xl:gap-x-96 place-content-center text-base">
    <nav>
      <span class="footer-title opacity-80">Explorer</span>
      <a class="link link-hover mb-1" href="/">Accueil</a>
      <a class="link link-hover my-1" href="/pricing">Tarifs</a>
      <a class="link link-hover my-1" href="/blog">Blog</a>
      <a class="link link-hover my-1" href="/contact_us">Contact</a>
      <a class="link link-hover my-1" href="https://github.com/Atriou/sveltekit-saas-starter">Github</a>
    </nav>
    <aside>
      <span class="footer-title opacity-80">Pourquoi notre SaaS ?</span>
      <div class="max-w-[260px]">
        <div class="font-bold text-2xl mb-1">Protégez votre marque, boostez vos ventes</div>
        <div class="font-medium mb-3">La solution de référence pour le suivi, la détection et la performance de vos produits sur tous les canaux de vente.</div>
      </div>
    </aside>
  </footer>
</div>
