## Índice

- [Índice](#índice)


## Tags & Techs
* [![Contributors][contributors-shield]][contributors-url]

[contributors-shield]: https://img.shields.io/github/contributors/AlbertLnz/dice-API.svg?style=for-the-badge
[contributors-url]: https://github.com/AlbertLnz/dice-API/graphs/contributors

* [![Forks][forks-shield]][forks-url]

[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members

* [![Stargazers][stars-shield]][stars-url]

[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers

* [![Issues][issues-shield]][issues-url]

[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues

* [![MIT License][license-shield]][license-url]

[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt

* [![LinkedIn][linkedin-shield]][linkedin-url]

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew

* [![Next][Next.js]][Next-url]

[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/

* [![React][React.js]][React-url]

[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/

* [![Vue][Vue.js]][Vue-url]

[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/

* [![Angular][Angular.io]][Angular-url]

[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/

* [![Svelte][Svelte.dev]][Svelte-url]

[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/

* [![Laravel][Laravel.com]][Laravel-url]

[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com

* [![Bootstrap][Bootstrap.com]][Bootstrap-url]

[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com

* [![JQuery][JQuery.com]][JQuery-url]

[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 


### Tables
|     | Command          | Action                                        |
| :-- | :--------------- | :-------------------------------------------- |
| ⚙️  | `dev` or `start` | Starts local dev server at `localhost:3000`.  |
| ⚙️  | `build`          | Build your production site to `./dist/`.      |
| ⚙️  | `preview`        | Preview your build locally, before deploying. |


### 🤝 Contributing
<a href="https://github.com/midudev/esland-web/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=midudev/esland-web" />
</a>


## Math expression
$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$


## Syntaxis
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## Syntaxis Oculta
<details>
<summary>Recursive quicksort implemented in Raku.</summary>

```raku
multi quicksort([]) { () }
multi quicksort([$pivot, *@rest]) {
    my $before := @rest.grep(* before $pivot);
    my $after  := @rest.grep(* !before $pivot);
    flat quicksort($before), $pivot, quicksort($after)
}
```
</details>

## Horizontal Lines (3 ways)
---
***
___

## Basics
**This is bold text** <br>
_This text is italicized_ <br>
~~This was mistaken text~~ <br>
**This text is _extremely_ important** <br>
***All this text is important*** <br>
This is a <sub>subscript</sub> text <br>
This is a <sup>superscript</sup> text <br>
<kbd>cmd + shift + p</kbd>
<kbd> <br> cmd + shift + p <br> </kbd>
<kbd>[Link with blue](https://google.es)</kbd>
[<kbd>Link without blue</kbd>](https://google.es)

> Text that is a quote
```
php artisan serve
```
The background color is `#ffffff`

This site was built using [GitHub Pages](https://pages.github.com/)


## Lists 1
- George Washington
* John Adams
+ Thomas Jefferson

## Lists 2
1. James Madison
1. James Monroe
1. John Quincy Adams

## Lists 3
1. First list item
   - First nested list item
     - Second nested list item

## Task Lists
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] \(Optional) Open a followup issue

## Notas de pie
Here is a simple footnote[^1].
A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

## Mensaje oculto en el Readme
<!-- This content will not appear in the rendered Markdown -->

## Details code (md)

````md
<details>
<summary>title of the content (*not* support **markdown** syntax ~~hmm~~)</summary>

content body (support **markdown** syntax ~~hmm~~)

</details>
````

## Details code 2 (md)
````md
```
{
  support: "codeblock to"
}
````

## Details code 3 (md + json)
````md
```json
{
  support: "codeblock to"
}
````

## Info icon
ℹ️

## Volver a un link personalizado
**[⬆ Volver a índice](#índice)**


## Box 0
<table><tr><td>The quick brown fox jumps over the lazy dog.</td></tr></table>

## Box 1
| :exclamation:  You have to read about this   |
|----------------------------------------------|

## Box 2
| :warning: WARNING           |
|:----------------------------|
| Another way to warn you     |

## Box 3
| :memo:        | This is something that is good to note       |
|---------------|:---------------------------------------------|

## Box 4

> Buenas <br>
> Use `git status` to list all new or modified files that haven't yet been committed.

> Buenas <br>
>> Use `git status` to list all new or modified files that haven't yet been committed.

> [!WARNING]
> Alerta Warning

> [!NOTE]
> Alerta Note

> [!TIP]
> Alerta Tip

> [!IMPORTANT]
> Alerta Warning

> [!CAUTION]
> Alerta Caution