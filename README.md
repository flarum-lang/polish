# Polska paczka językowa dla [Flarum](https://flarum.org/)

[![Latest Stable Version](https://img.shields.io/packagist/v/flarum-lang/polish?color=success&label=stable)](https://packagist.org/packages/flarum-lang/polish) 
[![Latest Unstable Version](https://img.shields.io/badge/unstable-v2.x--dev-fe7d37)](https://packagist.org/packages/flarum-lang/polish) 
[![License](https://img.shields.io/packagist/l/flarum-lang/polish)](https://packagist.org/packages/flarum-lang/polish) 
[![Total Downloads](https://img.shields.io/packagist/dt/flarum-lang/polish)](https://packagist.org/packages/flarum-lang/polish/stats) 
[![Monthly Downloads](https://img.shields.io/packagist/dm/flarum-lang/polish)](https://packagist.org/packages/flarum-lang/polish/stats) 

Paczka zawiera tłumaczenia dla Flarum (kompatybilne z wersją `2.0.0` lub nowszą) oraz niemal wszystkich popularnych rozszerzeń. Pełna lista obsługiwanych rozszerzeń dostępna jest poniżej.


## Instalacja

Rozszerzenie instalujemy za pomocą [Composera](https://getcomposer.org/):

```console
composer require "flarum-lang/polish:*"
```

Po czym w panelu admina włączamy rozszerzenie.


## Aktualizacja

Aktualizacje instalujemy za pomocą [Composera](https://getcomposer.org/):

```console
composer update flarum-lang/polish
```

Jeśli lubisz życie na krawędzi, możesz korzystać z wersji niestabilnej (może zawierać niezweryfikowane frazy zaproponowane przez społeczność):

```console
composer require "flarum-lang/polish:@dev"
```

Po aktualizacji czyścimy cache:

```console
php flarum cache:clear
```

## Migracja z `rob006/flarum-lang-polish`

Przy wydaniu wersji `1.0.0` paczka zmieniła nazwę z `rob006/flarum-lang-polish` na `flarum-lang/polish`. Jeśli korzystałeś wcześniej z `rob006/flarum-lang-polish`, musisz odinstalować starą paczkę i zainstalować nową:

```console
composer remove rob006/flarum-lang-polish
composer require "flarum-lang/polish:*"
```

Po czym w panelu admina włączamy nowe rozszerzenie.


## Znalazłem błąd / Brakuje rozszerzenia X

Uwagi oraz błędy można zgłaszać na [GitHubie](https://github.com/flarum-lang/polish/issues) lub na [forum](https://discuss.flarum.org/d/18134-polish-language-pack). Propozycje tłumaczeń można zgłaszać bezpośrednio korzystając z [Weblate](https://weblate.rob006.net/) (wystarczy kliknąć status tłumaczenia na liście poniżej lub na [tej stronie](https://rob006-software.github.io/flarum-translations/status/pl.html), aby przejść do tłumaczenia danego rozszerzenia/komponentu).

> [Tłumaczenia można dostosowywać też na poziomie konkretnej instalacji forum](https://rob006.net/blog/jak-nadpisac-lub-dodac-brakujace-tlumaczenia-dla-flarum/). Stworzenie paczki językowej, która będzie odpowiadała każdemu, jest praktycznie niemożliwe. Zmiany specyficzne dla konkretnego forum lepiej ustawiać lokalnie — nie każda fraza jest na tyle uniwersalna, aby mogła znaleźć się w ogólnej paczce językowej.


## Status tłumaczeń głównego silnika Flarum

| Component | Status |
| --- | --- |
| [Core](https://github.com/flarum/flarum-core) | [![Translation status](https://weblate.rob006.net/widgets/flarum2/pl/core/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/core/pl/) |
| Validation | [![Translation status](https://weblate.rob006.net/widgets/flarum2/pl/validation/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/validation/pl/) |


## Status tłumaczeń dla oficjalnych rozszerzeń

<!-- flarum-extensions-list-start -->

| Rozszerzenie | Status |
| --- | --- |
| [`flarum/akismet`](https://github.com/flarum/akismet) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-akismet/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-akismet/pl/) |
| [`flarum/approval`](https://github.com/flarum/approval) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-approval/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-approval/pl/) |
| [`flarum/bbcode`](https://github.com/flarum/bbcode) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-bbcode/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-bbcode/pl/) |
| [`flarum/emoji`](https://github.com/flarum/emoji) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-emoji/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-emoji/pl/) |
| [`flarum/flags`](https://github.com/flarum/flags) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-flags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-flags/pl/) |
| [`flarum/gdpr`](https://github.com/flarum/gdpr) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-gdpr/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-gdpr/pl/) |
| [`flarum/likes`](https://github.com/flarum/likes) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-likes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-likes/pl/) |
| [`flarum/lock`](https://github.com/flarum/lock) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-lock/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-lock/pl/) |
| [`flarum/markdown`](https://github.com/flarum/markdown) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-markdown/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-markdown/pl/) |
| [`flarum/mentions`](https://github.com/flarum/mentions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-mentions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-mentions/pl/) |
| [`flarum/nicknames`](https://github.com/flarum/nicknames) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-nicknames/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-nicknames/pl/) |
| [`flarum/pusher`](https://github.com/flarum/pusher) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-pusher/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-pusher/pl/) |
| [`flarum/statistics`](https://github.com/flarum/statistics) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-statistics/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-statistics/pl/) |
| [`flarum/sticky`](https://github.com/flarum/sticky) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-sticky/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-sticky/pl/) |
| [`flarum/subscriptions`](https://github.com/flarum/subscriptions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-subscriptions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-subscriptions/pl/) |
| [`flarum/suspend`](https://github.com/flarum/suspend) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-suspend/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-suspend/pl/) |
| [`flarum/tags`](https://github.com/flarum/tags) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flarum-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flarum-tags/pl/) |

<!-- flarum-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń od Friends of Flarum

<!-- fof-extensions-list-start -->

| Rozszerzenie | Status |
| --- | --- |
| [`fof/analytics`](https://github.com/FriendsOfFlarum/analytics) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-analytics/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-analytics/pl/) |
| [`fof/anti-spam`](https://github.com/FriendsOfFlarum/anti-spam) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-anti-spam/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-anti-spam/pl/) |
| [`fof/best-answer`](https://github.com/FriendsOfFlarum/best-answer) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-best-answer/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-best-answer/pl/) |
| [`fof/byobu`](https://github.com/FriendsOfFlarum/byobu) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-byobu/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-byobu/pl/) |
| [`fof/default-group`](https://github.com/FriendsOfFlarum/default-group) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-default-group/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-default-group/pl/) |
| [`fof/default-user-preferences`](https://github.com/FriendsOfFlarum/default-user-preferences) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-default-user-preferences/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-default-user-preferences/pl/) |
| [`fof/discussion-templates`](https://github.com/FriendsOfFlarum/discussion-templates) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-discussion-templates/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-discussion-templates/pl/) |
| [`fof/discussion-thumbnail`](https://github.com/FriendsOfFlarum/discussion-thumbnail) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-discussion-thumbnail/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-discussion-thumbnail/pl/) |
| [`fof/discussion-views`](https://github.com/FriendsOfFlarum/discussion-views) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-discussion-views/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-discussion-views/pl/) |
| [`fof/disposable-emails`](https://github.com/FriendsOfFlarum/disposable-emails) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-disposable-emails/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-disposable-emails/pl/) |
| [`fof/drafts`](https://github.com/FriendsOfFlarum/drafts) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-drafts/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-drafts/pl/) |
| [`fof/follow-tags`](https://github.com/FriendsOfFlarum/follow-tags) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-follow-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-follow-tags/pl/) |
| [`fof/formatting`](https://github.com/FriendsOfFlarum/formatting) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-formatting/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-formatting/pl/) |
| [`fof/frontpage`](https://github.com/FriendsOfFlarum/frontpage) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-frontpage/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-frontpage/pl/) |
| [`fof/gamification`](https://github.com/FriendsOfFlarum/gamification) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-gamification/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-gamification/pl/) |
| [`fof/geoip`](https://github.com/FriendsOfFlarum/geoip) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-geoip/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-geoip/pl/) |
| [`fof/github-sponsors`](https://github.com/FriendsOfFlarum/github-sponsors) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-github-sponsors/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-github-sponsors/pl/) |
| [`fof/ignore-users`](https://github.com/FriendsOfFlarum/ignore-users) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-ignore-users/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-ignore-users/pl/) |
| [`fof/impersonate`](https://github.com/FriendsOfFlarum/impersonate) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-impersonate/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-impersonate/pl/) |
| [`fof/linguist`](https://github.com/FriendsOfFlarum/linguist) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-linguist/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-linguist/pl/) |
| [`fof/links`](https://github.com/FriendsOfFlarum/links) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-links/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-links/pl/) |
| [`fof/merge-discussions`](https://github.com/FriendsOfFlarum/merge-discussions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-merge-discussions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-merge-discussions/pl/) |
| [`fof/moderator-notes`](https://github.com/FriendsOfFlarum/moderator-notes) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-moderator-notes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-moderator-notes/pl/) |
| [`fof/moderator-warnings`](https://github.com/FriendsOfFlarum/moderator-warnings) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-moderator-warnings/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-moderator-warnings/pl/) |
| [`fof/oauth`](https://github.com/FriendsOfFlarum/oauth) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-oauth/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-oauth/pl/) |
| [`fof/open-collective`](https://github.com/FriendsOfFlarum/open-collective) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-open-collective/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-open-collective/pl/) |
| [`fof/pages`](https://github.com/FriendsOfFlarum/pages) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-pages/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-pages/pl/) |
| [`fof/reactions`](https://github.com/FriendsOfFlarum/reactions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-reactions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-reactions/pl/) |
| [`fof/rich-text`](https://github.com/FriendsOfFlarum/rich-text) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-rich-text/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-rich-text/pl/) |
| [`fof/sentry`](https://github.com/FriendsOfFlarum/sentry) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-sentry/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-sentry/pl/) |
| [`fof/share-social`](https://github.com/FriendsOfFlarum/share-social) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-share-social/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-share-social/pl/) |
| [`fof/sitemap`](https://github.com/FriendsOfFlarum/sitemap) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-sitemap/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-sitemap/pl/) |
| [`fof/socialprofile`](https://github.com/FriendsOfFlarum/socialprofile) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-socialprofile/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-socialprofile/pl/) |
| [`fof/split`](https://github.com/FriendsOfFlarum/split) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-split/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-split/pl/) |
| [`fof/synopsis`](https://github.com/FriendsOfFlarum/synopsis) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-synopsis/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-synopsis/pl/) |
| [`fof/terms`](https://github.com/FriendsOfFlarum/terms) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-terms/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-terms/pl/) |
| [`fof/upload`](https://github.com/FriendsOfFlarum/upload) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-upload/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-upload/pl/) |
| [`fof/user-bio`](https://github.com/FriendsOfFlarum/user-bio) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-user-bio/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-user-bio/pl/) |
| [`fof/user-directory`](https://github.com/FriendsOfFlarum/user-directory) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-user-directory/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-user-directory/pl/) |
| [`fof/username-request`](https://github.com/FriendsOfFlarum/username-request) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-username-request/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-username-request/pl/) |
| [`fof/webhooks`](https://github.com/FriendsOfFlarum/webhooks) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/fof-webhooks/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/fof-webhooks/pl/) |

<!-- fof-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń społeczności

<!-- various-extensions-list-start -->

| Rozszerzenie | Status |
| --- | --- |
| [`acpl/flarum-lscache`](https://github.com/android-com-pl/flarum-lscache) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/acpl-lscache/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/acpl-lscache/pl/) |
| [`acpl/my-tags`](https://github.com/android-com-pl/my-tags) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/acpl-my-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/acpl-my-tags/pl/) |
| [`datlechin/flarum-bbcode-hide-content`](https://github.com/datlechin/flarum-bbcode-hide-content) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/datlechin-bbcode-hide-content/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/datlechin-bbcode-hide-content/pl/) |
| [`datlechin/flarum-birthdays`](https://github.com/datlechin/flarum-birthdays) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/datlechin-birthdays/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/datlechin-birthdays/pl/) |
| [`datlechin/flarum-copy-links`](https://github.com/datlechin/flarum-copy-links) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/datlechin-copy-links/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/datlechin-copy-links/pl/) |
| [`datlechin/flarum-discussion-overview`](https://github.com/datlechin/flarum-discussion-overview) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/datlechin-discussion-overview/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/datlechin-discussion-overview/pl/) |
| [`datlechin/flarum-more-discussions`](https://github.com/datlechin/flarum-more-discussions) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/datlechin-more-discussions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/datlechin-more-discussions/pl/) |
| [`datlechin/flarum-signup-button`](https://github.com/datlechin/flarum-signup-button) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/datlechin-signup-button/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/datlechin-signup-button/pl/) |
| [`flectar/flarum-turnstile`](https://github.com/flectar/flarum-ext-turnstile) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/flectar-turnstile/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/flectar-turnstile/pl/) |
| [`huseyinfiliz/flarum-diff`](https://github.com/huseyinfiliz/flarum-diff) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/huseyinfiliz-diff/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/huseyinfiliz-diff/pl/) |
| [`ianm/follow-users`](https://github.com/imorland/follow-users) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/ianm-follow-users/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/ianm-follow-users/pl/) |
| [`ianm/html-head`](https://github.com/imorland/html-head) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/ianm-html-head/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/ianm-html-head/pl/) |
| [`ianm/twofactor`](https://github.com/imorland/flarum-ext-twofactor) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/ianm-twofactor/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/ianm-twofactor/pl/) |
| [`justoverclock/flarum-ext-welcomebox`](https://github.com/justoverclockl/flarum-ext-welcomebox) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/justoverclock-welcomebox/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/justoverclock-welcomebox/pl/) |
| [`migratetoflarum/fake-data`](https://github.com/migratetoflarum/fake-data) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/migratetoflarum-fake-data/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/migratetoflarum-fake-data/pl/) |
| [`sycho/flarum-move-posts`](https://github.com/SychO9/flarum-move-posts) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/sycho-move-posts/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/sycho-move-posts/pl/) |
| [`sycho/flarum-profile-cover`](https://github.com/SychO9/flarum-profile-cover) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/sycho-profile-cover/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/sycho-profile-cover/pl/) |

<!-- various-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń premium

<!-- premium-extensions-list-start -->

| Rozszerzenie | Status |
| --- | --- |
| [`datitisev/flarum-backup`](https://flarum.org/extension/datitisev/flarum-backup) | [![Status tłumaczeń](https://weblate.rob006.net/widgets/flarum2/pl/datitisev-backup/svg-badge.svg)](https://weblate.rob006.net/projects/flarum2/datitisev-backup/pl/) |

<!-- premium-extensions-list-stop -->


## Credits

Paczka bazuje na [rozszerzeniu stworzonym przez bepropl](https://github.com/bepropl/lang-polish). Tworzona z udziałem społeczności jako część [Kolektywu tłumaczeń Flarum](https://github.com/rob006-software/flarum-translations).

Tłumaczenie dla Day.js pochodzi bezpośrednio ze [źródła](https://github.com/iamkun/dayjs/blob/v1.10.4/src/locale/pl.js).

Tłumaczenie dla `validation.yml` bazuje na [paczce językowej dla Laravela](https://github.com/Laravel-Lang/lang/blob/8.1.3/src/pl/validation.php).
