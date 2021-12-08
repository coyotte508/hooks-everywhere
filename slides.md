---
theme: seriph
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
title: Des hooks, toujours des hooks...
---

# Des hooks, toujours des hooks...

De React à Svelte, en passant par Vue.

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
preload: false
---

# Chapitre 1 - React

Il était une fois...
<br>
<br>
<br>

<img src="data:image/png;base64,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" class="ml-auto mr-auto" />

<v-click>
<div class="relative">
<div class="h-10 w-10 rounded-full bg-sky-800 text-2xl text-center font-mono flex flex-col justify-around text-cyan-200 absolute top-30 left-0 right-0 bottom-0" v-motion :initial="{x: 0, rotate: 0}" :enter="{x: 800, rotate: 720, transition: {duration: 1000, repeat: Infinity, repeatType: 'mirror', repeatDelay: 1000}}">
  T
</div>
</div>
</v-click>

<!--
Il était une fois un petit Eliott qui arrivait à Zenika.

On lui a proposé une mission super:

- En interne
- Avec du React, du Node, du Typescript
- De la blockchain

Mais on ne l'a pas prévénu qu'il y aurait des hooks!
-->

---

# Introduction aux 🪝

Quelques hooks parmi les plus utilisés

<v-click>
  
### Quelque hooks de base

</v-click>

<v-after>

|               |                                   |
| ------------- | --------------------------------- |
| `useState`    | Stocker une valeur                |
| `useContext`  | Récupérer une valeur d'un ancêtre |
| `useEffect`   | Réagir à des changements          |
| `useMemo`     | Garder une valeur en cache        |
| `useCallback` | Le pire hook                      |

</v-after>

---

# Exemple de 🪝

Du code!

<v-click>
```ts {all|2|3|all|3}
function Counter() {
  const [counter, setCounter] = useState(0);
  const increment = useCallback(() => setCounter(counter + 1));
  
  return <button onClick={increment}>{counter}</button>
}
```
</v-click>

<v-click at=4>

  <br>

Un exemple plus simple...

  <br>
  
```ts
function Counter() {
  const [counter, setCounter] = useState(0);
  
  return <button onClick={() => setCounter(counter+1)}>{counter}</button>
}
```
</v-click>

<!--
Une mauvaise influence
-->

---

# Des erreurs de 🪝

Qui peut trouver l'erreur?

```ts {all|4|all}
function RealStuff() {
  const [counter, setCounter] = useState(0);

  if (counter < 1000) {
    useEffect(() => {
      if (counter > 1000) {
        alert("Vous avez dépassé la limite!");
      }
    }, [counter]);
  }

  return <button click={() => setCounter(counter + Math.random() * 100)}>{counter}</button>;
}
```

<v-click at="3">

Un simple `if` met React en PLS

</v-click>

<!--
Et puis c'est pas tout: ne parlons même pas d'`await`
-->

---

# Définition d'un 🪝

C'est pas un peu trop tard...?

<br><br><br>

<v-clicks>
  
- La fonction s'appelle `useXxxx`
- Appelée dans le contexte immédiat du composant (pas de `await`...)
- Pas dans un `if` (seulement en React)
  
</v-clicks>

<!--
Qui peut deviner le troisième point? Il n'y en a pas...
-->

---
preload: false
---

# Chapitre 2 - Vue 3
Donner des formations ça sert à quelque chose?!

<img src="https://v3.vuejs.org/logo.png" class="ml-auto mr-auto w-50 mt-25"/>


---

# Un tableau de 🪝
Ne nous attardons pas..



|               |                                   |
| ------------- | --------------------------------- |
| `useState`    | `ref`                |
| `useContext`  | `inject` |
| `useEffect`   | `watch`          |
| `useMemo`     | `computed`        |
| `useCallback` | Disparu! 🎉🎉                      |


---

# Du code de 🪝 en Vue
Voilà un exemple de code Vue 3 pour les curieux

```ts {all|11|all}
import { useInterval, useTimeAgo } from "@vueuse/core";

const christmas = new Date("2021-12-25");
const toChristmas = useTimeAgo(christmas);

const {counter, pause} = useInterval(400, {controls: true});

watch(counter, () => {
  if (Date.now() > christmas.getTime()) {
    pause();
    alert("C'est Noël! 🎅");
  }
});

<template>
  Chistmas is {{toChristmas}} {{".".repeat(counter % 4)}}
</template>
```

<br>

<Time />

<!--
Voilà un exemple Vue pour les curieux
-->

---

# Chapitre 3 - Svelte
La libération

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Svelte_Logo.svg/langfr-220px-Svelte_Logo.svg.png" class="ml-auto mr-auto mt-10">

<v-click>
  <div class="flex flex-row items-center justify-between -mt-30">
    <img src="https://kit.svelte.dev/_app/assets/svelte-kit-machine-f2b9147a.avif" class="w-80 h-80 -ml-15">
    
<img src="/trollface.webp" class="w-40 h-30 mr-5">
  </div>
</v-click>

<!--
J'ai converti un projet entier en Svelte avec 0 hooks!
-->

---

# La malédiction des 🪝
Des espoirs brisés

<br>


```ts
// Stores globaux
export const refreshToken = writable<Token | null>(null);
export const user = writable<User | null>(null);

user.subscribe($user => {
  if (!$user) {
    refreshToken.set(null);
  }
});
```

<br>
<br>
<br>

- Côté navigateur: 👌
- Côté SSR: 😵

---

# Comment faire des stores globaux avec SvelteKit ?
Avec des 🪝

<br>
<br>
<br>

<v-clicks>

- Comment récupérer l'utilisateur actuel ?

Avec une session 

- Comment récupérer la session ?

Avec `getStores()`

- Quand peut-on appeler `getStores()`?

Dans le contexte immédiat du composant 😭
  
</v-clicks>

---

# La solution
A base de 🪝


```ts {all|1|2|2-3|5-11|13|all}
export const useUser = defineStore(() => {
  const refreshToken = useRefreshToken();
  const user = writable<IUser | null>(null);
  
  if (browser) { // Attention aux fuites de mémoire!
    user.subscribe($user => {
      if (!$user) {
         refreshToken.set(null);
      }
    });
  }

  return user;
});
```

<br/>
<br/>

<v-click at="7">

  Inspiré par [Pinia](https://github.com/posva/pinia) 🍍
  
</v-click>


---

# Sous le capot



```ts
import { getStores } from "$app/stores";
import { get as $ } from "svelte/store";

export function defineStore<T>(fn: () => T): () => T {
  return () => {
    const session = $(getStores().session);

    if (!session.stores.has(fn)) {
      session.stores.set(fn, fn());
    }

    return session.stores.get(fn);
  }
}
```

<div class="text-10xl mt-2 text-center">
  🪝
</div>
