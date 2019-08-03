# Polska paczka językowa dla [Flarum](https://flarum.org/)

Paczka zawiera tłumaczenia dla Flarum (kompatybilne z wersją `0.1.0-beta.8.1` lub nowszą) oraz wybranych wtyczek.

<!-- TODO REMOVE -->
- [BestAnswer by Wiwatsrt ](https://github.com/wiwatsrt/flarum-ext-best-answer)
- [Upload by Flagrow](https://github.com/flagrow/upload)
- [Polls by ReFlar](https://github.com/ReFlar/polls)
- [Split by Flagrow ](https://github.com/flagrow/split)
- [Linguist by Flagrow](https://flagrow.io/extensions/flagrow/linguist)
- [Discussion Views by MichaelBelgium](https://github.com/MichaelBelgium/flarum-discussion-views)


## Instalacja

Rozszerzenie instalujemy za pomocą [Composera](https://getcomposer.org/):

```console
composer require rob006/flarum-lang-polish
```

## Aktualizacja

Aktualizacje instalujemy za pomocą [Composera](https://getcomposer.org/):

```console
composer update rob006/flarum-lang-polish
```

## Migracja z `bepro/lang-polish`

Jeśli masz już zainstalowane rozszerzenie [`bepro/lang-polish`](https://github.com/bepropl/lang-polish) musisz:

1. W panelu admina wyłączyć rozszerzenie `bepro/lang-polish`.

2. Odinstalować rozszerzenie za pomocą Composera:

   ```console
   composer remove bepro/lang-polish
   ```
   
3. Zainstalować nowe rozszerzenie za pomocą Composera:

   ```console
   composer require rob006/flarum-lang-polish
   ```

4. Włączyć nowe rozszerzenie w panelu admina.


## Status tłumaczeń głównego silnika Flarum

| Component | Status |
| --- | --- |
| [Core](https://github.com/flarum/core) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/core/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/core/) |
| Validation | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/validation/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/validation/) |


## Status tłumaczeń dla oficjalnych rozszerzeń

<!-- flarum-extensions-list-start -->

| Extension | Status |
| --- | --- |
| [Akismet](https://github.com/flarum/akismet) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-akismet/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-akismet/pl/) |
| [Approval](https://github.com/flarum/approval) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-approval/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-approval/pl/) |
| [Emoji](https://github.com/flarum/emoji) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-emoji/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-emoji/pl/) |
| [Facebook Login](https://github.com/flarum/auth-facebook) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-auth-facebook/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-auth-facebook/pl/) |
| [Flags](https://github.com/flarum/flags) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-flags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-flags/pl/) |
| [GitHub Login](https://github.com/flarum/auth-github) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-auth-github/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-auth-github/pl/) |
| [Likes](https://github.com/flarum/likes) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-likes/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-likes/pl/) |
| [Lock](https://github.com/flarum/lock) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-lock/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-lock/pl/) |
| [Markdown](https://github.com/flarum/markdown) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-markdown/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-markdown/pl/) |
| [Mentions](https://github.com/flarum/mentions) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-mentions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-mentions/pl/) |
| [Pusher](https://github.com/flarum/pusher) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-pusher/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-pusher/pl/) |
| [Statistics](https://github.com/flarum/statistics) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-statistics/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-statistics/pl/) |
| [Sticky](https://github.com/flarum/sticky) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-sticky/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-sticky/pl/) |
| [Subscriptions](https://github.com/flarum/subscriptions) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-subscriptions/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-subscriptions/pl/) |
| [Suspend](https://github.com/flarum/suspend) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-suspend/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-suspend/pl/) |
| [Tags](https://github.com/flarum/tags) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-tags/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-tags/pl/) |
| [Twitter Login](https://github.com/flarum/auth-twitter) | [![Translation status](https://weblate.rob006.net/widgets/flarum/pl/flarum-auth-twitter/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/flarum-auth-twitter/pl/) |

<!-- flarum-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń od Friend of Flarum

<!-- fof-extensions-list-start -->

| Extension | Status |
| --- | --- |
| [FoF Pages](https://github.com/FriendsOfFlarum/pages) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-pages/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-pages/pl/) |
| [FoF Polls](https://github.com/FriendsOfFlarum/polls) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-pools/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-pools/pl/) |
| [FoF Split](https://github.com/FriendsOfFlarum/split) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-split/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-split/pl/) |
| [FoF User Directory](https://github.com/FriendsOfFlarum/user-directory) | [![Translation status](https://weblate.rob006.net/widgets/friends-of-flarum/pl/fof-user-directory/svg-badge.svg)](https://weblate.rob006.net/projects/friends-of-flarum/fof-user-directory/pl/) |

<!-- fof-extensions-list-stop -->


## Status tłumaczeń dla rozszerzeń społeczności

<!-- various-extensions-list-start -->

| Extension | Status |
| --- | --- |
| [Bazaar by Extiverse](https://github.com/extiverse/bazaar) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/extiverse-bazaar/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/extiverse-bazaar/pl/) |
| [Best Answer by Wiwatsrt](https://github.com/wiwatsrt/flarum-ext-best-answer) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/wiwatsrt-best-answer/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/wiwatsrt-best-answer/pl/) |
| [Canonical Url by Migratetoflarum](https://github.com/migratetoflarum/canonical) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/migratetoflarum-canonical/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/migratetoflarum-canonical/pl/) |
| [Discussion views by Michaelbelgium](https://github.com/MichaelBelgium/flarum-discussion-views) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/michaelbelgium-discussion-views/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/michaelbelgium-discussion-views/pl/) |
| [Flagrow Linguist by Flagrow](https://github.com/FriendsOfFlarum/linguist) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/flagrow-linguist/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/flagrow-linguist/pl/) |
| [Upload by Flagrow](https://github.com/FriendsOfFlarum/upload) | [![Translation status](https://weblate.rob006.net/widgets/flarum-extensions/pl/flagrow-upload/svg-badge.svg)](https://weblate.rob006.net/projects/flarum-extensions/flagrow-upload/pl/) |

<!-- various-extensions-list-stop -->


## Credits

Paczka bazuje na [rozszerzeniu stworzonym przez bepropl](https://github.com/bepropl/lang-polish) - to on jest autorem 
większości tłumaczeń.

Tłumaczenie dla `moment.js` pochodzi bezpośrednio ze [źródła](https://github.com/moment/moment/blob/2.24.0/locale/pl.js).
