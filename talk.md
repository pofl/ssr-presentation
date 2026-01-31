# SSR talk

* As a backend engineer only writing json APIs I had to relearn what classical web development is
  * Colleague: this feature is just a form. Me:??
* History recap
  * HTML / Web 1.0
    * knows only POST and GET
    * All logic on the server
    * Browser is just a client
    * PHP is perfect fit here
  * Ajax / jQuery era: Javascript führt requests aus. XML + JSON skyrocket
  * SPA era: Angular + React
    * Coincided with rise of Apple + Android
    * server serves JSON-data-API
    * Mobile clients and Web client in parallel
  * Next.js era: SPA hangover: websites are MBs of download. React alone doesn't cut it. You need react-router, react-query, react-forms. You need tooling for styles, usually Tailwind. Waterfalls are slow.
* GET & DELETE requests will include values via query parameters, other request types will submit them as a form encoded body.
* React SPAs were the default for a long time but recently I felt a new wave of SSR momentum
* SSR
  * Post redirect get
* SPA + JSON API
  * CDN
  * API für
* REST + HATEOAS
* Htmx
  * Why should only `<a>` & `<form>` be able to make HTTP requests?
  * Why should only click & submit events trigger them?
  * Why should only GET & POST methods be available?
  * Why should you only be able to replace the entire screen?
