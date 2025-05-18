<script lang="ts">
  import { getContext } from "svelte"
  import type { Writable } from "svelte/store"

  let adminSection: Writable<string> = getContext("adminSection")
  adminSection.set("home")
</script>

<svelte:head>
  <title>Aparie: Home</title>
</svelte:head>

<h1 class="text-2xl font-bold mb-1">Welcome to Aparie!</h1>
<h2 class=" mb-1">Manage your decks</h2>

<!--<div class="my-6">-->
<!--  <h1 class="text-xl font-bold mb-1">Users</h1>-->
<!--  <div class="stats shadow-sm stats-vertical sm:stats-horizontal sm:w-[420px]">-->
<!--    <div class="stat place-items-center">-->
<!--      <div class="stat-title">Downloads</div>-->
<!--      <div class="stat-value">31K</div>-->
<!--      <div class="stat-desc">↗︎ 546 (2%)</div>-->
<!--    </div>-->

<!--    <div class="stat place-items-center">-->
<!--      <div class="stat-title">Users</div>-->
<!--      <div class="stat-value text-secondary">4,200</div>-->
<!--      <div class="stat-desc">↗︎ 40 (2%)</div>-->
<!--    </div>-->
<!--  </div>-->
<!--</div>-->
<!-- Place images in public/images folder -->
<div class="deck-card">
  <h3>French</h3>
  <img src="/images/heart-icon.svg" alt="Favorite" class="favorite-icon" />
  <p>Oui oui oui!</p>
  <div class="actions">
    <button class="practice-btn">
      <img src="/images/book-icon.svg" alt="Practice" />
      Practice
    </button>
    <button class="test-btn">
      <img src="/images/play-icon.svg" alt="Test" />
      Test
    </button>
    <div class="action-icons">
      <img src="/images/share-icon.svg" alt="Share" />
      <img src="/images/trash-icon.svg" alt="Delete" />
    </div>
  </div>
</div>

<!--<div class="my-6">-->
<!--  <h1 class="text-xl font-bold mb-1">Accounts</h1>-->
<!--  <div class="stats shadow-sm stats-vertical sm:stats-horizontal sm:w-[420px]">-->
<!--    <div class="stat place-items-center">-->
<!--      <div class="stat-title">New Registers</div>-->
<!--      <div class="stat-value">1,200</div>-->
<!--      <div class="stat-desc">↘︎ 90 (14%)</div>-->
<!--    </div>-->

<!--    <div class="stat place-items-center">-->
<!--      <div class="stat-title">Churned Accounts</div>-->
<!--      <div class="stat-value">42</div>-->
<!--      <div class="stat-desc">↘︎ 6 (12%)</div>-->
<!--    </div>-->
<!--  </div>-->
<!--</div>-->
<!--<div class="my-6">-->
<!--  <h1 class="text-xl font-bold mb-1">Revenue</h1>-->
<!--  <div class="stats shadow-sm stats-vertical sm:stats-horizontal sm:w-[420px]">-->
<!--    <div class="stat place-items-center">-->
<!--      <div class="stat-title text-success">Revenue</div>-->
<!--      <div class="stat-value text-success">$4200</div>-->
<!--      <div class="stat-desc">↗︎ $180 (4%)</div>-->
<!--    </div>-->

<!--    <div class="stat place-items-center">-->
<!--      <div class="stat-title">New Subscribers</div>-->
<!--      <div class="stat-value">16</div>-->
<!--      <div class="stat-desc">↘︎ 1 (%7)</div>-->
<!--    </div>-->
<!--  </div>-->
<!--</div>-->

<!--<div class="alert alert-error max-w-lg mt-2">-->
<!--  <svg-->
<!--    xmlns="http://www.w3.org/2000/svg"-->
<!--    class="stroke-current shrink-0 h-6 w-6"-->
<!--    fill="none"-->
<!--    viewBox="0 0 24 24"-->
<!--    ><path-->
<!--      stroke-linecap="round"-->
<!--      stroke-linejoin="round"-->
<!--      stroke-width="2"-->
<!--      d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z"-->
<!--    /></svg-->
<!--  >-->
<!--  <div>-->
<!--    <div class="font-bold">Demo Content</div>-->
<!--    <div class="my-2">-->
<!--      This page is just a placeholder. Replace this page with your app's content-->
<!--      and functionality.-->
<!--    </div>-->
<!--    <div class="my-2">-->
<!--      The <a href="/account/billing" class="link">billing</a> and-->
<!--      <a href="/account/settings" class="link">settings</a> pages are functional-->
<!--      demos.-->
<!--    </div>-->
<!--  </div>-->
<!--</div>-->

