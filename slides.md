---
theme: default
title: Compagnon Batisseur
---

<script>
(function () {
  try {
    const ls = window.localStorage;
    const k = '__test__';
    ls.setItem(k, '1'); ls.removeItem(k);
  } catch (e) {
    const mem = {};
    window.localStorage = {
      getItem: k => Object.prototype.hasOwnProperty.call(mem, k) ? mem[k] : null,
      setItem: (k, v) => { mem[k] = String(v); },
      removeItem: k => { delete mem[k]; },
      clear: () => { for (const k in mem) delete mem[k]; },
      key: i => Object.keys(mem)[i] ?? null,
      get length() { return Object.keys(mem).length; }
    };
  }
})();
</script>


# Compagnon Batisseur

Ceci est un test de visibilité ✅

---

## Plan

- Intro
- Objectifs
- Déroulé
