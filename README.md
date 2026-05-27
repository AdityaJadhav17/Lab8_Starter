# Lab 8 - Fetch API & ServiceWorkers

**Name:** Aditya

**Lab Partner(s):** N/A

**Deployed GitHub Pages URL:**  https://adityajadhav17.github.io/Lab8_Starter/

## PWA Screenshot

![PWA install screenshot](pwa.png)

## Graceful Degradation & Service Workers

Graceful degradation is the principle that a web app should continue to provide a usable experience even when some capabilities are unavailable, for example, when the user is offline, on a slow connection, or when an external API is down. Service workers are one of the main tools that make this possible. By sitting between the page and the network, a service worker can intercept requests and serve cached responses when the network fails, so the core content (HTML, CSS, JS, and recipe data) still loads. In this lab, the service worker precaches the recipe JSON on install and uses a cache-first strategy for all subsequent fetches, which means the app degrades gracefully into a fully functional offline experience instead of breaking when the network is gone.
