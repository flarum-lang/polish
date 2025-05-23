# Polska paczka językowa dla [Flarum](https://flarum.org/)

[![Latest Stable Version](https://img.shields.io/packagist/v/flarum-lang/polish?color=success&label=stable)](https://packagist.org/packages/flarum-lang/polish) 
[![Latest Unstable Version](https://img.shields.io/badge/unstable-v1.x--dev-fe7d37)](https://packagist.org/packages/flarum-lang/polish) 
[![License](https://img.shields.io/packagist/l/flarum-lang/polish)](https://packagist.org/packages/flarum-lang/polish) 
[![Total Downloads](https://img.shields.io/packagist/dt/flarum-lang/polish)](https://packagist.org/packages/flarum-lang/polish/stats) 
[![Monthly Downloads](https://img.shields.io/packagist/dm/flarum-lang/polish)](https://packagist.org/packages/flarum-lang/polish/stats) 

Paczka zawiera tłumaczenia dla Flarum (kompatybilne z wersją `1.3.0` lub nowszą) oraz niemal wszystkich popularnych rozszerzeń. Pełna lista obsługiwanych rozszerzeń dostępna jest poniżej.


## Instalacja

Rozszerzenie instalujemy za pomocą [Composera](https://getcomposer.org/):

```console
composer require flarum-lang/polish
```

Po czym w panelu admina włączamy rozszerzenie.


## Aktualizacja

Aktualizacje instalujemy za pomocą [Composera](https://getcomposer.org/):

```console
composer update flarum-lang/polish
```

Lub aby wymusić najnowszą wersję (zalecane przy aktualizacji do nowej wersji Flarum — sprawdź wcześniej [changelog](https://github.com/flarum-lang/polish/blob/master/CHANGELOG.md), czy żadne z wykorzystywanych przez Ciebie rozszerzeń nie utraciło wsparcia):

```console
composer require flarum-lang/polish
```

Jeśli lubisz życie na krawędzi, możesz korzystać z wersji niestabilnej (może zawierać niezweryfikowane frazy zaproponowane przez społeczność):

```console
composer require "flarum-lang/polish:1.x-dev"
```

Po aktualizacji czyścimy cache:

```console
php flarum cache:clear
```

## Migracja z `rob006/flarum-lang-polish`

Przy wydaniu wersji `1.0.0` paczka zmieniła nazwę z `rob006/flarum-lang-polish` na `flarum-lang/polish`. Jeśli korzystałeś wcześniej z `rob006/flarum-lang-polish`, musisz odinstalować starą paczkę i zainstalować nową:

```console
composer remove rob006/flarum-lang-polish
composer require flarum-lang/polish
```

Po czym w panelu admina włączamy nowe rozszerzenie.


## Znalazłem błąd / Brakuje rozszerzenia X

Uwagi oraz błędy można zgłaszać na [GitHubie](https://github.com/flarum-lang/polish/issues) lub na [forum](https://discuss.flarum.org/d/18134-polish-language-pack). Propozycje tłumaczeń można zgłaszać bezpośrednio korzystając z [Weblate](https://weblate.rob006.net/) (wystarczy kliknąć status tłumaczenia na liście poniżej lub na [tej stronie](https://rob006-software.github.io/flarum-translations/status/pl.html), aby przejść do tłumaczenia danego rozszerzenia/komponentu).

> [Tłumaczenia można dostosowywać też na poziomie konkretnej instalacji forum](https://rob006.net/blog/jak-nadpisac-lub-dodac-brakujace-tlumaczenia-dla-flarum/). Stworzenie paczki językowej, która będzie odpowiadała każdemu, jest praktycznie niemożliwe. Zmiany specyficzne dla konkretnego forum lepiej ustawiać lokalnie — nie każda fraza jest na tyle uniwersalna, aby mogła znaleźć się w ogólnej paczce językowej.


## Status tłumaczeń głównego silnika Flarum

| Component | Status |
| --- | --- |
| [Core](https://github.com/flarum/flarum-core) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/core/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/core/pl/) |
| Validation | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/validation/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/validation/pl/) |


## Status tłumaczeń dla oficjalnych rozszerzeń

<!-- flarum-extensions-list-start -->

| Rozszerzenie | Status |
| --- | --- |
| [`flarum/akismet`](https://github.com/flarum/akismet) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-akismet/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-akismet/pl/) |
| [`flarum/approval`](https://github.com/flarum/approval) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-approval/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-approval/pl/) |
| [`flarum/bbcode`](https://github.com/flarum/bbcode) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-bbcode/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-bbcode/pl/) |
| [`flarum/emoji`](https://github.com/flarum/emoji) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-emoji/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-emoji/pl/) |
| [`flarum/flags`](https://github.com/flarum/flags) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-flags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-flags/pl/) |
| [`flarum/gdpr`](https://github.com/flarum/gdpr) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-gdpr/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-gdpr/pl/) |
| [`flarum/likes`](https://github.com/flarum/likes) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-likes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-likes/pl/) |
| [`flarum/lock`](https://github.com/flarum/lock) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-lock/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-lock/pl/) |
| [`flarum/markdown`](https://github.com/flarum/markdown) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-markdown/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-markdown/pl/) |
| [`flarum/mentions`](https://github.com/flarum/mentions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-mentions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-mentions/pl/) |
| [`flarum/nicknames`](https://github.com/flarum/nicknames) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-nicknames/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-nicknames/pl/) |
| [`flarum/pusher`](https://github.com/flarum/pusher) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-pusher/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-pusher/pl/) |
| [`flarum/statistics`](https://github.com/flarum/statistics) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-statistics/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-statistics/pl/) |
| [`flarum/sticky`](https://github.com/flarum/sticky) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-sticky/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-sticky/pl/) |
| [`flarum/subscriptions`](https://github.com/flarum/subscriptions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-subscriptions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-subscriptions/pl/) |
| [`flarum/suspend`](https://github.com/flarum/suspend) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-suspend/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-suspend/pl/) |
| [`flarum/tags`](https://github.com/flarum/tags) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/flarum-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-tags/pl/) |

<!-- flarum-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń od Friends of Flarum

<!-- fof-extensions-list-start -->

| Rozszerzenie | Status |
| --- | --- |
| [`fof/amazon-affiliation`](https://github.com/FriendsOfFlarum/amazon-affiliation) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-amazon-affiliation/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-amazon-affiliation/pl/) |
| [`fof/analytics`](https://github.com/FriendsOfFlarum/analytics) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-analytics/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-analytics/pl/) |
| [`fof/anti-spam`](https://github.com/FriendsOfFlarum/anti-spam) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-anti-spam/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-anti-spam/pl/) |
| [`fof/ban-ips`](https://github.com/FriendsOfFlarum/ban-ips) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-ban-ips/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-ban-ips/pl/) |
| [`fof/best-answer`](https://github.com/FriendsOfFlarum/best-answer) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-best-answer/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-best-answer/pl/) |
| [`fof/byobu`](https://github.com/FriendsOfFlarum/byobu) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-byobu/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-byobu/pl/) |
| [`fof/cookie-consent`](https://github.com/FriendsOfFlarum/cookie-consent) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-cookie-consent/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-cookie-consent/pl/) |
| [`fof/custom-footer`](https://github.com/FriendsOfFlarum/custom-footer) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-custom-footer/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-custom-footer/pl/) |
| [`fof/default-group`](https://github.com/FriendsOfFlarum/default-group) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-default-group/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-default-group/pl/) |
| [`fof/default-user-preferences`](https://github.com/FriendsOfFlarum/default-user-preferences) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-default-user-preferences/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-default-user-preferences/pl/) |
| [`fof/discussion-language`](https://github.com/FriendsOfFlarum/discussion-language) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-discussion-language/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-discussion-language/pl/) |
| [`fof/discussion-thumbnail`](https://github.com/FriendsOfFlarum/discussion-thumbnail) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-discussion-thumbnail/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-discussion-thumbnail/pl/) |
| [`fof/discussion-views`](https://github.com/FriendsOfFlarum/discussion-views) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-discussion-views/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-discussion-views/pl/) |
| [`fof/disposable-emails`](https://github.com/FriendsOfFlarum/disposable-emails) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-disposable-emails/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-disposable-emails/pl/) |
| [`fof/doorman`](https://github.com/FriendsOfFlarum/doorman) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-doorman/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-doorman/pl/) |
| [`fof/drafts`](https://github.com/FriendsOfFlarum/drafts) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-drafts/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-drafts/pl/) |
| [`fof/filter`](https://github.com/FriendsOfFlarum/filter) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-filter/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-filter/pl/) |
| [`fof/follow-tags`](https://github.com/FriendsOfFlarum/follow-tags) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-follow-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-follow-tags/pl/) |
| [`fof/formatting`](https://github.com/FriendsOfFlarum/formatting) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-formatting/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-formatting/pl/) |
| [`fof/forum-statistics-widget`](https://github.com/FriendsOfFlarum/forum-statistics-widget) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-forum-statistics-widget/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-forum-statistics-widget/pl/) |
| [`fof/frontpage`](https://github.com/FriendsOfFlarum/frontpage) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-frontpage/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-frontpage/pl/) |
| [`fof/gamification`](https://github.com/FriendsOfFlarum/gamification) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-gamification/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-gamification/pl/) |
| [`fof/geoip`](https://github.com/FriendsOfFlarum/geoip) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-geoip/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-geoip/pl/) |
| [`fof/github-sponsors`](https://github.com/FriendsOfFlarum/github-sponsors) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-github-sponsors/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-github-sponsors/pl/) |
| [`fof/html-errors`](https://github.com/FriendsOfFlarum/html-errors) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-html-errors/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-html-errors/pl/) |
| [`fof/ignore-users`](https://github.com/FriendsOfFlarum/ignore-users) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-ignore-users/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-ignore-users/pl/) |
| [`fof/impersonate`](https://github.com/FriendsOfFlarum/impersonate) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-impersonate/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-impersonate/pl/) |
| [`fof/linguist`](https://github.com/FriendsOfFlarum/linguist) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-linguist/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-linguist/pl/) |
| [`fof/links`](https://github.com/FriendsOfFlarum/links) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-links/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-links/pl/) |
| [`fof/mason`](https://github.com/FriendsOfFlarum/mason) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-mason/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-mason/pl/) |
| [`fof/masquerade`](https://github.com/FriendsOfFlarum/masquerade) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-masquerade/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-masquerade/pl/) |
| [`fof/merge-discussions`](https://github.com/FriendsOfFlarum/merge-discussions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-merge-discussions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-merge-discussions/pl/) |
| [`fof/moderator-notes`](https://github.com/FriendsOfFlarum/moderator-notes) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-moderator-notes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-moderator-notes/pl/) |
| [`fof/nightmode`](https://github.com/FriendsOfFlarum/nightmode) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-nightmode/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-nightmode/pl/) |
| [`fof/oauth`](https://github.com/FriendsOfFlarum/oauth) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-oauth/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-oauth/pl/) |
| [`fof/open-collective`](https://github.com/FriendsOfFlarum/open-collective) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-open-collective/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-open-collective/pl/) |
| [`fof/pages`](https://github.com/FriendsOfFlarum/pages) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-pages/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-pages/pl/) |
| [`fof/passport`](https://github.com/FriendsOfFlarum/passport) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-passport/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-passport/pl/) |
| [`fof/polls`](https://github.com/FriendsOfFlarum/polls) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-polls/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-polls/pl/) |
| [`fof/pretty-mail`](https://github.com/FriendsOfFlarum/pretty-mail) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-pretty-mail/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-pretty-mail/pl/) |
| [`fof/prevent-necrobumping`](https://github.com/FriendsOfFlarum/prevent-necrobumping) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-prevent-necrobumping/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-prevent-necrobumping/pl/) |
| [`fof/pwned-passwords`](https://github.com/FriendsOfFlarum/pwned-passwords) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-pwned-passwords/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-pwned-passwords/pl/) |
| [`fof/reactions`](https://github.com/FriendsOfFlarum/reactions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-reactions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-reactions/pl/) |
| [`fof/recaptcha`](https://github.com/FriendsOfFlarum/recaptcha) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-recaptcha/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-recaptcha/pl/) |
| [`fof/secure-https`](https://github.com/FriendsOfFlarum/secure-https) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-secure-https/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-secure-https/pl/) |
| [`fof/sentry`](https://github.com/FriendsOfFlarum/sentry) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-sentry/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-sentry/pl/) |
| [`fof/share-social`](https://github.com/FriendsOfFlarum/share-social) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-share-social/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-share-social/pl/) |
| [`fof/sitemap`](https://github.com/FriendsOfFlarum/sitemap) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-sitemap/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-sitemap/pl/) |
| [`fof/socialprofile`](https://github.com/FriendsOfFlarum/socialprofile) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-socialprofile/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-socialprofile/pl/) |
| [`fof/split`](https://github.com/FriendsOfFlarum/split) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-split/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-split/pl/) |
| [`fof/subscribed`](https://github.com/FriendsOfFlarum/subscribed) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-subscribed/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-subscribed/pl/) |
| [`fof/synopsis`](https://github.com/FriendsOfFlarum/synopsis) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-synopsis/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-synopsis/pl/) |
| [`fof/terms`](https://github.com/FriendsOfFlarum/terms) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-terms/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-terms/pl/) |
| [`fof/upload`](https://github.com/FriendsOfFlarum/upload) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-upload/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-upload/pl/) |
| [`fof/user-bio`](https://github.com/FriendsOfFlarum/user-bio) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-user-bio/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-user-bio/pl/) |
| [`fof/user-directory`](https://github.com/FriendsOfFlarum/user-directory) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-user-directory/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-user-directory/pl/) |
| [`fof/username-request`](https://github.com/FriendsOfFlarum/username-request) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-username-request/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-username-request/pl/) |
| [`fof/webhooks`](https://github.com/FriendsOfFlarum/webhooks) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/fof-webhooks/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/fof-webhooks/pl/) |

<!-- fof-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń społeczności

<!-- various-extensions-list-start -->

| Rozszerzenie | Status |
| --- | --- |
| [`acpl/flarum-lscache`](https://github.com/android-com-pl/flarum-lscache) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/acpl-lscache/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/acpl-lscache/pl/) |
| [`acpl/mobile-tab`](https://github.com/android-com-pl/mobile-tab) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/acpl-mobile-tab/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/acpl-mobile-tab/pl/) |
| [`acpl/my-tags`](https://github.com/android-com-pl/my-tags) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/acpl-my-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/acpl-my-tags/pl/) |
| [`afrux/asirem`](https://github.com/afrux/asirem) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/afrux-asirem/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/afrux-asirem/pl/) |
| [`afrux/forum-stats-widget`](https://github.com/afrux/forum-stats-widget) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/afrux-forum-stats-widget/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/afrux-forum-stats-widget/pl/) |
| [`afrux/forum-widgets-core`](https://github.com/afrux/forum-widgets-core) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/afrux-forum-widgets-core/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/afrux-forum-widgets-core/pl/) |
| [`afrux/news-widget`](https://github.com/afrux/news-widget) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/afrux-news-widget/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/afrux-news-widget/pl/) |
| [`afrux/online-users-widget`](https://github.com/afrux/online-users-widget) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/afrux-online-users-widget/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/afrux-online-users-widget/pl/) |
| [`afrux/top-posters-widget`](https://github.com/afrux/top-posters-widget) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/afrux-top-posters-widget/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/afrux-top-posters-widget/pl/) |
| [`akr/chevereto`](https://github.com/AKR-Developers/flarum-chevereto) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/akr-chevereto/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/akr-chevereto/pl/) |
| [`antoinefr/flarum-ext-money`](https://github.com/AntoineFr/flarum-ext-money) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/antoinefr-money/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/antoinefr-money/pl/) |
| [`antoinefr/flarum-ext-online`](https://github.com/AntoineFr/flarum-ext-online) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/antoinefr-online/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/antoinefr-online/pl/) |
| [`askvortsov/flarum-auto-moderator`](https://github.com/askvortsov1/flarum-automod) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-auto-moderator/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-auto-moderator/pl/) |
| [`askvortsov/flarum-categories`](https://github.com/askvortsov1/flarum-categories) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-categories/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-categories/pl/) |
| [`askvortsov/flarum-checklist`](https://github.com/askvortsov1/flarum-checklist) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-checklist/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-checklist/pl/) |
| [`askvortsov/flarum-discussion-templates`](https://github.com/askvortsov1/flarum-discussion-templates) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-discussion-templates/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-discussion-templates/pl/) |
| [`askvortsov/flarum-help-tags`](https://github.com/askvortsov1/flarum-help-tags) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-help-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-help-tags/pl/) |
| [`askvortsov/flarum-markdown-tables`](https://github.com/askvortsov1/flarum-markdown-tables) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-markdown-tables/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-markdown-tables/pl/) |
| [`askvortsov/flarum-moderator-warnings`](https://github.com/askvortsov1/flarum-moderator-warnings) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-moderator-warnings/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-moderator-warnings/pl/) |
| [`askvortsov/flarum-pwa`](https://github.com/askvortsov1/flarum-pwa) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-pwa/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-pwa/pl/) |
| [`askvortsov/flarum-rich-text`](https://github.com/askvortsov1/flarum-rich-text) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-rich-text/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-rich-text/pl/) |
| [`askvortsov/flarum-saml`](https://github.com/askvortsov1/flarum-saml) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/askvortsov-saml/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/askvortsov-saml/pl/) |
| [`blazite/flarum-turnstile`](https://github.com/blazite/flarum-ext-turnstile) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/blazite-turnstile/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/blazite-turnstile/pl/) |
| [`blomstra/mark-unread`](https://github.com/blomstra/flarum-ext-mark-unread) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/blomstra-mark-unread/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/blomstra-mark-unread/pl/) |
| [`blomstra/user-filter`](https://github.com/blomstra/flarum-ext-user-filter) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/blomstra-user-filter/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/blomstra-user-filter/pl/) |
| [`blomstra/usercard-stats`](https://github.com/blomstra/flarum-ext-usercard-stats) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/blomstra-usercard-stats/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/blomstra-usercard-stats/pl/) |
| [`cadiducho/bbcode`](https://github.com/EdorasMinecraft/BBcode) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/cadiducho-bbcode/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/cadiducho-bbcode/pl/) |
| [`clarkwinkelmann/catch-the-fish`](https://github.com/clarkwinkelmann/catch-the-fish) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-catch-the-fish/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-catch-the-fish/pl/) |
| [`clarkwinkelmann/flarum-ext-author-change`](https://github.com/clarkwinkelmann/flarum-ext-author-change) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-author-change/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-author-change/pl/) |
| [`clarkwinkelmann/flarum-ext-carving-contest`](https://github.com/clarkwinkelmann/flarum-ext-carving-contest) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-carving-contest/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-carving-contest/pl/) |
| [`clarkwinkelmann/flarum-ext-colorful-borders`](https://github.com/clarkwinkelmann/flarum-ext-colorful-borders) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-colorful-borders/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-colorful-borders/pl/) |
| [`clarkwinkelmann/flarum-ext-create-user-modal`](https://github.com/clarkwinkelmann/flarum-ext-create-user-modal) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-create-user-modal/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-create-user-modal/pl/) |
| [`clarkwinkelmann/flarum-ext-discussion-bookmarks`](https://github.com/clarkwinkelmann/flarum-ext-discussion-bookmarks) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-discussion-bookmarks/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-discussion-bookmarks/pl/) |
| [`clarkwinkelmann/flarum-ext-email-as-display-name`](https://github.com/clarkwinkelmann/flarum-ext-email-as-display-name) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-email-as-display-name/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-email-as-display-name/pl/) |
| [`clarkwinkelmann/flarum-ext-emojionearea`](https://github.com/clarkwinkelmann/flarum-ext-emojionearea) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-emojionearea/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-emojionearea/pl/) |
| [`clarkwinkelmann/flarum-ext-first-post-approval`](https://github.com/clarkwinkelmann/flarum-ext-first-post-approval) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-first-post-approval/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-first-post-approval/pl/) |
| [`clarkwinkelmann/flarum-ext-follow-tags-prompt`](https://github.com/clarkwinkelmann/flarum-ext-follow-tags-prompt) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-follow-tags-prompt/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-follow-tags-prompt/pl/) |
| [`clarkwinkelmann/flarum-ext-ipsum-autocomplete`](https://github.com/clarkwinkelmann/flarum-ext-ipsum-autocomplete) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-ipsum-autocomplete/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-ipsum-autocomplete/pl/) |
| [`clarkwinkelmann/flarum-ext-likes-received`](https://github.com/clarkwinkelmann/flarum-ext-likes-received) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-likes-received/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-likes-received/pl/) |
| [`clarkwinkelmann/flarum-ext-mailing`](https://github.com/clarkwinkelmann/flarum-ext-mailing) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-mailing/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-mailing/pl/) |
| [`clarkwinkelmann/flarum-ext-passwordless`](https://github.com/clarkwinkelmann/flarum-ext-passwordless) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-passwordless/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-passwordless/pl/) |
| [`clarkwinkelmann/flarum-ext-popular-discussion-badge`](https://github.com/clarkwinkelmann/flarum-ext-popular-discussion-badge) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-popular-discussion-badge/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-popular-discussion-badge/pl/) |
| [`clarkwinkelmann/flarum-ext-post-bookmarks`](https://github.com/clarkwinkelmann/flarum-ext-post-bookmarks) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-post-bookmarks/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-post-bookmarks/pl/) |
| [`clarkwinkelmann/flarum-ext-post-permissions`](https://github.com/clarkwinkelmann/flarum-ext-post-permissions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-post-permissions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-post-permissions/pl/) |
| [`clarkwinkelmann/flarum-ext-scratchpad`](https://github.com/clarkwinkelmann/flarum-ext-scratchpad) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-scratchpad/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-scratchpad/pl/) |
| [`clarkwinkelmann/flarum-ext-see-past-first-post`](https://github.com/clarkwinkelmann/flarum-ext-see-past-first-post) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-see-past-first-post/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-see-past-first-post/pl/) |
| [`clarkwinkelmann/flarum-ext-shadow-ban`](https://github.com/clarkwinkelmann/flarum-ext-shadow-ban) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-shadow-ban/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-shadow-ban/pl/) |
| [`clarkwinkelmann/flarum-ext-status`](https://github.com/clarkwinkelmann/flarum-ext-status) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-status/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-status/pl/) |
| [`clarkwinkelmann/flarum-ext-who-read`](https://github.com/clarkwinkelmann/flarum-ext-who-read) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/clarkwinkelmann-who-read/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/clarkwinkelmann-who-read/pl/) |
| [`club-1/flarum-ext-cross-references`](https://github.com/club-1/flarum-ext-cross-references) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/club-1-cross-references/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/club-1-cross-references/pl/) |
| [`datlechin/flarum-bbcode-hide-content`](https://github.com/datlechin/flarum-bbcode-hide-content) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datlechin-bbcode-hide-content/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-bbcode-hide-content/pl/) |
| [`datlechin/flarum-birthdays`](https://github.com/datlechin/flarum-birthdays) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datlechin-birthdays/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-birthdays/pl/) |
| [`datlechin/flarum-birthdays-widget`](https://github.com/datlechin/flarum-birthdays-widget) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datlechin-birthdays-widget/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-birthdays-widget/pl/) |
| [`datlechin/flarum-copy-links`](https://github.com/datlechin/flarum-copy-links) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datlechin-copy-links/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-copy-links/pl/) |
| [`datlechin/flarum-discussion-overview`](https://github.com/datlechin/flarum-discussion-overview) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datlechin-discussion-overview/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-discussion-overview/pl/) |
| [`datlechin/flarum-keyboard-shortcuts`](https://github.com/datlechin/flarum-keyboard-shortcuts) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datlechin-keyboard-shortcuts/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-keyboard-shortcuts/pl/) |
| [`datlechin/flarum-more-discussions`](https://github.com/datlechin/flarum-more-discussions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datlechin-more-discussions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-more-discussions/pl/) |
| [`datlechin/flarum-signup-button`](https://github.com/datlechin/flarum-signup-button) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datlechin-signup-button/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datlechin-signup-button/pl/) |
| [`dem13n/topic-starter-label`](https://github.com/Dem13n/topic-starter-label) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/dem13n-topic-starter-label/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/dem13n-topic-starter-label/pl/) |
| [`glowingblue/password-strength`](https://github.com/glowingblue/flarum-ext-password-strength) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/glowingblue-password-strength/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/glowingblue-password-strength/pl/) |
| [`gtdxyz/flarum-ext-badges`](https://github.com/daocatt/flarum-ext-badges) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/gtdxyz-badges/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/gtdxyz-badges/pl/) |
| [`ianm/follow-users`](https://github.com/imorland/follow-users) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/ianm-follow-users/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/ianm-follow-users/pl/) |
| [`ianm/html-head`](https://github.com/imorland/html-head) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/ianm-html-head/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/ianm-html-head/pl/) |
| [`ianm/level-ranks`](https://github.com/imorland/level-ranks) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/ianm-level-ranks/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/ianm-level-ranks/pl/) |
| [`ianm/syndication`](https://github.com/imorland/syndication) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/ianm-syndication/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/ianm-syndication/pl/) |
| [`ianm/twofactor`](https://github.com/imorland/flarum-ext-twofactor) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/ianm-twofactor/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/ianm-twofactor/pl/) |
| [`jslirola/flarum-ext-login2seeplus`](https://github.com/jslirola/flarum-ext-login2seeplus) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/jslirola-login2seeplus/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/jslirola-login2seeplus/pl/) |
| [`justoverclock/flarum-ext-hashtag`](https://github.com/justoverclockl/flarum-ext-hashtag) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/justoverclock-hashtag/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-hashtag/pl/) |
| [`justoverclock/flarum-ext-keywords`](https://github.com/justoverclockl/flarum-ext-keywords) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/justoverclock-keywords/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-keywords/pl/) |
| [`justoverclock/flarum-ext-welcomebox`](https://github.com/justoverclockl/flarum-ext-welcomebox) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/justoverclock-welcomebox/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-welcomebox/pl/) |
| [`justoverclock/hot-discussions`](https://github.com/justoverclockl/hot-discussions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/justoverclock-hot-discussions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-hot-discussions/pl/) |
| [`justoverclock/hot-discussions-cards`](https://github.com/justoverclockl/hot-discussions-cards) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/justoverclock-hot-discussions-cards/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-hot-discussions-cards/pl/) |
| [`justoverclock/user-statistics`](https://github.com/justoverclockl/user-statistics) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/justoverclock-user-statistics/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/justoverclock-user-statistics/pl/) |
| [`katosdev/signature`](https://github.com/katosdev/signature) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/katosdev-signature/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/katosdev-signature/pl/) |
| [`kyrne/whisper`](https://github.com/KyrneDev/whisper) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/kyrne-whisper/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/kyrne-whisper/pl/) |
| [`littlecxm/flarum-reply-to-see`](https://github.com/littlecxm/flarum-reply-to-see) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/littlecxm-reply-to-see/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/littlecxm-reply-to-see/pl/) |
| [`maicol07/flarum-ext-sso`](https://github.com/maicol07/flarum-ext-sso) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/maicol07-sso/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/maicol07-sso/pl/) |
| [`malago/flarum-achievements`](https://github.com/malago86/flarum-achievements) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/malago-achievements/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/malago-achievements/pl/) |
| [`malago/flarum-ads`](https://github.com/malago86/flarum-ads) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/malago-ads/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/malago-ads/pl/) |
| [`matteocontrini/flarum-imgur-upload`](https://github.com/matteocontrini/flarum-imgur-upload) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/matteocontrini-imgur-upload/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/matteocontrini-imgur-upload/pl/) |
| [`michaelbelgium/flarum-discussion-views`](https://github.com/MichaelBelgium/flarum-discussion-views) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/michaelbelgium-discussion-views/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/michaelbelgium-discussion-views/pl/) |
| [`michaelbelgium/flarum-profile-views`](https://github.com/MichaelBelgium/flarum-profile-views) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/michaelbelgium-profile-views/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/michaelbelgium-profile-views/pl/) |
| [`michaelbelgium/mybb-to-flarum`](https://github.com/MichaelBelgium/mybb_to_flarum) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/michaelbelgium-mybb-to-flarum/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/michaelbelgium-mybb-to-flarum/pl/) |
| [`migratetoflarum/canonical`](https://github.com/migratetoflarum/canonical) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/migratetoflarum-canonical/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/migratetoflarum-canonical/pl/) |
| [`migratetoflarum/fake-data`](https://github.com/migratetoflarum/fake-data) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/migratetoflarum-fake-data/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/migratetoflarum-fake-data/pl/) |
| [`nearata/flarum-ext-cakeday`](https://github.com/Nearata/flarum-ext-cakeday) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/nearata-cakeday/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-cakeday/pl/) |
| [`nearata/flarum-ext-copy-code-to-clipboard`](https://github.com/Nearata/flarum-ext-copy-code-to-clipboard) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/nearata-copy-code-to-clipboard/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-copy-code-to-clipboard/pl/) |
| [`nearata/flarum-ext-tags-color-generator`](https://github.com/Nearata/flarum-ext-tags-color-generator) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/nearata-tags-color-generator/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-tags-color-generator/pl/) |
| [`nearata/flarum-ext-twofactor`](https://github.com/Nearata/flarum-ext-twofactor) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/nearata-twofactor/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nearata-twofactor/pl/) |
| [`nomiscz/flarum-ext-auth-steam`](https://github.com/NomisCZ/flarum-ext-auth-steam) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/nomiscz-auth-steam/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nomiscz-auth-steam/pl/) |
| [`nomiscz/flarum-ext-auth-wechat`](https://github.com/NomisCZ/flarum-ext-auth-wechat) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/nomiscz-auth-wechat/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nomiscz-auth-wechat/pl/) |
| [`nosun/reply-to-see`](https://github.com/nosun/flarum-ext-reply2see) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/nosun-reply-to-see/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/nosun-reply-to-see/pl/) |
| [`sycho/flarum-move-posts`](https://github.com/SychO9/flarum-move-posts) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/sycho-move-posts/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/sycho-move-posts/pl/) |
| [`sycho/flarum-profile-cover`](https://github.com/SychO9/flarum-profile-cover) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/sycho-profile-cover/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/sycho-profile-cover/pl/) |
| [`the-turk/flarum-diff`](https://github.com/the-turk/flarum-diff) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/the-turk-diff/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/the-turk-diff/pl/) |
| [`the-turk/flarum-mathren`](https://github.com/the-turk/flarum-mathren) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/the-turk-mathren/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/the-turk-mathren/pl/) |
| [`the-turk/flarum-nodp`](https://github.com/the-turk/flarum-nodp) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/the-turk-nodp/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/the-turk-nodp/pl/) |
| [`the-turk/flarum-quiet-edits`](https://github.com/the-turk/flarum-quiet-edits) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/the-turk-quiet-edits/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/the-turk-quiet-edits/pl/) |
| [`therealsujitk/flarum-ext-gifs`](https://github.com/therealsujitk/flarum-ext-gifs) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/therealsujitk-gifs/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/therealsujitk-gifs/pl/) |
| [`tituspijean/flarum-ext-auth-ldap`](https://github.com/tituspijean/flarum-ext-auth-ldap) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/tituspijean-auth-ldap/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/tituspijean-auth-ldap/pl/) |
| [`tpokorra/flarum-ext-post-notification`](https://github.com/tpokorra/flarum-ext-post-notification) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/tpokorra-post-notification/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/tpokorra-post-notification/pl/) |
| [`v17development/flarum-blog`](https://github.com/v17development/flarum-blog) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/v17development-blog/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/v17development-blog/pl/) |
| [`v17development/flarum-seo`](https://github.com/v17development/flarum-seo) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/v17development-seo/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/v17development-seo/pl/) |
| [`v17development/flarum-user-badges`](https://github.com/v17development/flarum-user-badges) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/v17development-user-badges/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/v17development-user-badges/pl/) |
| [`xelson/flarum-ext-chat`](https://github.com/Xelson/flarum-ext-chat) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/xelson-chat/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/xelson-chat/pl/) |

<!-- various-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń premium

<!-- premium-extensions-list-start -->

| Rozszerzenie | Status |
| --- | --- |
| [`blomstra/realtime`](https://flarum.org/extension/blomstra/realtime) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/blomstra-realtime/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/blomstra-realtime/pl/) |
| [`datitisev/flarum-backup`](https://flarum.org/extension/datitisev/flarum-backup) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datitisev-backup/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datitisev-backup/pl/) |
| [`datitisev/flarum-maintenance`](https://flarum.org/extension/datitisev/flarum-maintenance) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/datitisev-maintenance/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/datitisev-maintenance/pl/) |
| [`v17development/flarum-support`](https://flarum.org/extension/v17development/flarum-support) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum/pl/v17development-support/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/v17development-support/pl/) |

<!-- premium-extensions-list-stop -->


## Credits

Paczka bazuje na [rozszerzeniu stworzonym przez bepropl](https://github.com/bepropl/lang-polish). Tworzona z udziałem społeczności jako część [Kolektywu tłumaczeń Flarum](https://github.com/rob006-software/flarum-translations).

Tłumaczenie dla Day.js pochodzi bezpośrednio ze [źródła](https://github.com/iamkun/dayjs/blob/v1.10.4/src/locale/pl.js).

Tłumaczenie dla `validation.yml` bazuje na [paczce językowej dla Laravela](https://github.com/Laravel-Lang/lang/blob/8.1.3/src/pl/validation.php).
