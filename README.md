# Astro Starter Kit: Minimal

```sh
npm create astro@latest -- --template minimal
```

[ViewTransitions](https://docs.astro.build/en/guides/view-transitions/)
```ts
// viewTransitions is a component that allows you to transition between pages
  <ViewTransitions />
// transition:name={`${name}-image`} is a transition that allows you to transition between images
transition:name={`${name}-image`}
```

[new view transition](https://astro.build/blog/future-of-astro-zero-js-view-transitions/?tw)

[Pagination](https://docs.astro.build/en/guides/pagination/)

cosas q me llamaron la atencion:

```ts
// regresa a la pagina anterior
<button onclick="history.back()" class="text-blue-500">Regresar</button>

// causa parpadeo
#btn-favorite {
  @apply hover:animate-pulse;
}
```




````bash
https://www.creative-tim.com/twcomponents/component/simple-navbar-3
https://www.astroicon.dev/getting-started/
