# PHP 8.6 pour php-wasm 3.1.65 (build apprendre.forelse.fr)

Binaires PHP 8.6.0 compilés avec les scripts de WordPress Playground au tag `v3.1.65`, plus les
correctifs de `source/`, en attendant les paquets officiels `@php-wasm/*-8-6`.

`node-8-6/` et `web-8-6/` remplacent les dossiers `asyncify/` et `jspi/` de `@php-wasm/node-8-5@3.1.65`
et `@php-wasm/web-8-5@3.1.65` : les chargeurs gardent le nom `php_8_5.js` pour que ces paquets les
importent sans modification. Extensions compilées en 8.6 : intl (Node et web). Xdebug, Redis et Memcached
ne sont pas inclus.

La contribution en amont est sur la branche `php-8-6-support`.
