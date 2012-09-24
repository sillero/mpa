# Announcing the First Beta Release of Persona
# Anunciando o Primeiro Lançamento Beta de Persona

For the past year Mozilla has been working on an experimental login system that completely eliminates passwords on websites while being safe, secure, and easy to use. Today we're casting off the "experimental" label and announcing the first "beta" release of Persona.

Pelo último ano, a Mozilla esteve trabalhando em um sistema de login experimental que completamente elimina senhas em websites e ao mesmo tempo permanece protegido, seguro e fácil de usar. Hoje estamos removendo a etiqueta de "experimental" e anunciando o primeiro lançamento "beta" do Persona

[PLACEHOLDER FOR SCREENCAST VIDEO]

Persona is ready to use for authentication: [it works in all major smartphone, tablet, and desktop browsers][1], the user experience has been thoroughly reviewed and polished, [we're committed to the core APIs][2], and its infrastructure is highly available and stable.

O Persona está pronto para ser usado para autenticação: [funciona em todos os principais navegadores de smartphones, tablets e desktops][1], a experiência do usuário foi cuidadosamente revisada e polida, [estamos comprometidos com as APIs centrais][2], e sua infraestrutura é altamente disponível e estável.

What's it like to integrate Persona? Check out this video from The Times Crossword:

Como é integrar o Persona? Veja este vídeo de The Times Crossword:

[PLACEHOLDER FOR TIMES CROSSWORD VIDEO]
<center><em>"[Persona] was definitely easier than OpenID or OAuth because it can almost all be done on the client side in JavaScript".</em></center>

<center><em>"[Persona] foi definitavamente mais fácil que OpenID ou OAuth porque quase tudo pode ser feito do lado do cliente em Javascript".</em></center>

We haven't just refined Persona, we've also significantly improved it since we first [introduced it][3]. Over the past few months we:

Nós não apenas refinaos o Persona, como também o melhoramos consideravelmente desde a primeira vez que [o introduzimos][3]. Durante os últimos meses nós:

* [Completely refreshed our brand][4], changing from the "BrowserID" codename to "Persona."
* Developed an [entirely new (and better) API][5].
* Streamlined the [first-time user experience][6].
* Added support for [showing your site's name and logo][7] in the login dialog.
* Enhanced the login dialog to optionally [include links to your site's terms of service and privacy policy][8].

These changes have been well received and we're [seeing Persona gain traction][9] outside of Mozilla. If you are a developer, now is the time to try Persona out. Persona is an [open source project][10] and we gladly welcome input and collaboration from the broader community via our [mailing list][11] or our [IRC channel][12] (#identity on irc.mozilla.org).

This is the first of many beta releases, and we have some fantastic things planned for the future.

So, what are you waiting for? Persona coexists well with existing login systems and only takes a single afternoon to integrate. What's more, because Persona logins are based on email addresses, sites still maintain a direct relationship with their users. Check out [the documentation][13] and add Persona to your site today!

[1]: https://developer.mozilla.org/en-US/docs/persona/Browser_compatibility
[2]: http://identity.mozilla.com/post/31739234834/committing-to-a-stable-api-for-persona
[3]: http://identity.mozilla.com/post/7616727542/introducing-browserid-a-better-way-to-sign-in
[4]: http://identity.mozilla.com/post/18038609895/introducing-mozilla-persona
[5]: http://identity.mozilla.com/post/28513408358/a-new-api-for-persona
[6]: http://identity.mozilla.com/post/27914354400/improvements-to-the-first-time-sign-up-flow
[7]: http://identity.mozilla.com/post/27122712140/new-feature-adding-your-websites-name-and-logo-to-the
[8]: http://identity.mozilla.com/post/23038368841/streamlining-login-with-privacy-policy-and-terms-of
[9]: http://identity.mozilla.com/post/31008721633/application-and-platform-integration-of-persona
[10]: https://github.com/mozilla/browserid
[11]: https://lists.mozilla.org/listinfo/dev-identity
[12]: https://wiki.mozilla.org/IRC
[13]: https://developer.mozilla.org/Persona
