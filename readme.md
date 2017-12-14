<!--lint disable no-html-->

# ![Backend - Course 2017-2018][banner]

## Table of Contents

*   [Synopsis](#synopsis)
*   [Description](#description)
*   [Communication](#communication)
*   [Goals](#goals)
*   [Grade](#grade)
*   [Calendar](#calendar)
*   [Effort](#effort)
*   [Materials](#materials)
*   [Bugs](#bugs)
*   [Programme](#programme)
*   [Conduct](#conduct)
*   [License](#license)

## Synopsis

The course **Backend** is given at [**@CMDA**][cmda] in 2018 between
5 February and 12 April.

*   **Course**: Backend
*   **Coordinator**: [Titus Wormer][wooorm-mail]
*   **Lecturers**:
    [Albert de Klein][lbrt-mail] ([**@lbrt**][lbrt-gh]) (BT 1),
    [Laurens Aarnoudse][razpudding-mail] ([**@razpudding**][razpudding-gh])
    (BT 2), and [Titus Wormer][wooorm-mail] ([**@wooorm**][wooorm-gh]) (BT 3)
*   **SIS**: Backend Development
*   **Credit**: 3 ECTS
*   **Academic year**: 2017-2018
*   **Period**: Quarter 3 (spring)
*   **Programme**: Communication and Multimedia Design (full time bachelor)
*   **Language**: Dutch instructions and English resources
*   **Entry requirements**: N/A

## Description

In **Backend** we peek behind the curtains and inspect what’s behind the web.
You build web apps with [Node.js][node], communicate with [HTTP][], and store
data in a database with [SQL][] and [NoSQL][].
Additionally, you’ll navigate the [command line][command-line], version control
with [Git][], and deploy your app.
In this course you’ll advance your web dev skills.
You’ll learn to use computers to actually make what you design work: people can
actually fill in forms, like things, and upload files.

**Backend** is an elective course given in Quarter 3 (spring) after the core
curriculum of our programme, building further on knowledge acquired in
**Internetstandaarden**, **Inleiding Programmeren**, and **Frontend 1**.
This course is chosen alongside **Frontend 2** and **Project Tech**, together
making up **Block Tech**.
In **Project Tech** you’ll apply your newfound backend skills.

If you’d like to continue with web development after this course, make sure to
pick a tech internship for Q4, choose [**Frontend 3**][fe3] in Q1 of next year
and check out [Minor Web Development][minor].

## Communication

<!-- TODO: Add link to home (gh org), when published. -->

*   [GitHub][gh-be] — Main source of information, assignments, important dates,
    and more
*   [Slack][slack] — General chatter and Q&A
*   [Moodle][moodle-be] — Schedulers

## Goals

#### Main goals

The 2 main goals in this course are that you’re able to:

*   Build web apps with node
*   Store data in a database

#### Subgoals

In practice you’ll learn to:

1.  <a name="subgoal-1"></a> Navigate the command line
2.  <a name="subgoal-2"></a> Version control with git
3.  <a name="subgoal-3"></a> Use packages from npm
4.  <a name="subgoal-4"></a> Use web frameworks like express
5.  <a name="subgoal-5"></a> Communicate over HTTP
6.  <a name="subgoal-6"></a> Use SQL and NoSQL databases like MySQL and MongoDB
7.  <a name="subgoal-7"></a> Render data server-side
8.  <a name="subgoal-8"></a> Request data from clients
9.  <a name="subgoal-9"></a> Respond with data from a server
10. <a name="subgoal-10"></a> Deploy web apps

## Grade

| Task                               | Weight |
| ---------------------------------- | -----: |
| [Participation][]                  |    10% |
| [Assessment 1※][a1] (written test) |    40% |
| [Assessment 2※][a2] (oral test)    |    50% |
| **Total**                          |   100% |

> ※ passing both tests (min 5.5) is required

```js
if (!participation || !a1 || !a2) {
  grade = 'GR'
} else if (a1 < 5.5 || a2 < 5.5) {
  grade = 1
} else {
  grade = (participation * 0.1) + (a1 * 0.4) + (a2 * 0.5)
}
```

## Calendar

Dates are indicative.  Check [`rooster.hva.nl`][rooster] for info on actual
date, time, and place.

| Class                        | Date BT 1 |    Date BT 2   |    Date BT 3   |
| ---------------------------- | :-------: | :------------: | :------------: |
| [Lecture 1][w1lec]           |   05-02   |      05-02     |      05-02     |
| [Lab 1][w1lab]               |   08-02   |      06-02     |      ??-??     |
| [Lecture 2][w2lec]           |   12-02   |      12-02     |      12-02     |
| [Lab 2][w2lab]               |   15-02   |      13-02     |      13-02     |
| [Lecture 3][w3lec]           |   19-02   |      19-02     |      19-02     |
| [Lab 3][w3lab]               |   22-02   |      20-02     |      20-02     |
| [Lecture 4][w4lec]           |   05-03   |      05-03     |      05-03     |
| [Lab 4][w4lab]               |   08-03   |      06-03     |      06-03     |
| [Lecture 5][w5lec]           |   12-03   |      12-03     |      12-03     |
| [Lab 5][w5lab]               |   15-03   |      13-03     |      13-03     |
| [Lecture 6][w6lec]           |   19-03   |      19-03     |      19-03     |
| [Lab 6][w6lab]               |   22-03   |      20-03     |      20-03     |
| [**Assessment 1**][a1]       |   26-03   |      26-03     |      26-03     |
| [Lab 7][w7lab]               |   29-03   |      27-03     |      27-03     |
| [Lab 8][w8lab]               |   05-04   |      03-04     |      03-04     |
| [**Assessment 2**][a2]       |   12-04   | 09-04 or 12-04 | 09-04 or 12-04 |
| [**Assessment 1**][a1] resit |   29-07   |      29-07     |      29-07     |
| [**Assessment 2**][a1] resit |   28-07   |      28-07     |      25-07     |

## Effort

The table below breaks down the general time needed to complete activities.

| Activity               | Effort (hrs) |
| ---------------------- | -----------: |
| Lecture (6 × 1⅔hrs)    |           10 |
| Lab (8 × 1⅔hrs)        |          13⅓ |
| Assignments (5 × 6hrs) |           30 |
| Assessment 1           |           10 |
| Assessment 2           |          20⅔ |
| **Total**              |       **84** |

## Materials

#### Resources used in this course

*   🆓 GitHub account (**required**)
    — [Sign Up](https://help.github.com/articles/signing-up-for-a-new-github-account/)
*   🆓 Text Editor (**required**)
    — [Atom](https://atom.io) or [Sublime](https://www.sublimetext.com)
*   🆓 Installation of [Python](https://www.python.org) or
    [Ruby](https://www.ruby-lang.org/en/) (**required**)
*   🆓 Young, Alex, and Mike Cantelon.
    _Node.js in Action_.
    Manning, 2017.
    (**optional**)
*   🆓 [Chacon, Scott, and Ben Straub.
    _Pro Git_.
    Apress, 2014](https://git-scm.com/book/en/v2).
    (**optional**)
*   🆓 Demaree, David.
    _Git for Humans_.
    A Book Apart, 2016.
    (**optional**)

> 💁 The optional books are either linked to or free for AUAS students through
> [Safari Books][safari].

#### Resources to refresh your memory

*   🆓 [Codecademy](https://www.codecademy.com/learn/introduction-to-javascript)
    (**course**) — Intro to JavaScript: Learn to code interactively
*   🆓 [Re-introduction to JavaScript](https://developer.mozilla.org/Web/JavaScript/A_re-introduction_to_JavaScript)
    (**article**) — Short re-introduction to JavaScript
*   🆓 [JavaScript Essentials](https://www.lynda.com/JavaScript-tutorials/JavaScript-Essential-Training/574716-2.html)
    (**course**) — Learn JavaScript on Lynda
    (free for AUAS students through our [portal][lynda-portal])
*   🆓 [JavaScript For Cats](http://jsforcats.com)
    (**book**) — Intro to JavaScript for new programmers
*   🆓 [JavaScript 30](https://javascript30.com)
    (**course**) — 30 day vanilla JavaScript coding challenge
*   🆓 [Eloquent JavaScript](https://eloquentjavascript.net)
    (**book**) — Modern intro to programming
*   🆓 [Basics of HTML & CSS](http://webdive.ktam.org/web/basics)
    (**tutorial**) — Learn how to use HTML & CSS
*   💸 [Tutoring](http://piratepad.net/HeB4FUsI0t)
    — Match up with another CMD student

#### Resources used in previous courses

*   Duckett, Jon.
    _HTML & CSS_.
    John Wiley & Sons, 2015
    (**internetstandaarden**)
*   [Howe, Shay.
    _Learn to Code HTML & CSS_.
    New Riders, 2014][html-css]
    (**internetstandaarden**)
*   Duckett, Jon.
    _JavaScript & jQuery_.
    John Wiley & Sons, 2015
    (**inleiding programmeren**)

#### Resources used in Frontend 2

*   [Simpson, Kyle.
    _YDKJS: Up & Going_.
    O’Reilly Media, 2015][ydkjs-1]
*   [Simpson, Kyle.
    _YDKJS: Scope & Closures_.
    O’Reilly Media, 2015][ydkjs-2]
*   [Simpson, Kyle.
    _YDKJS: this & Object Prototypes_.
    O’Reilly Media, 2015][ydkjs-3]
*   [Simpson, Kyle.
    _YDKJS: Types & Grammar_.
    O’Reilly Media, 2015][ydkjs-4]
*   [Simpson, Kyle.
    _YDKJS: Async & Performance_.
    O’Reilly Media, 2015][ydkjs-5]
*   [Simpson, Kyle.
    _YDKJS: ES6 & Beyond_.
    O’Reilly Media, 2016][ydkjs-6]

## Bugs

If you have questions:

<!--
  TODO: [Browse examples][examples] (before search)
-->

*   Read the manual for the technology in question
    ([git](https://git-scm.com/docs),
    [github](https://guides.github.com),
    [node](https://nodejs.org/api/),
    [npm](https://docs.npmjs.com),
    [express](http://expressjs.com/en/4x/api.html),
    [mysql](https://dev.mysql.com/doc/refman/5.7/en/),
    [mongodb](https://docs.mongodb.com))
*   [Search StackOverflow][stackoverflow]
*   Use a search engine (like [DuckDuckGo][])
*   [Ask questions on Slack][slack]
*   [Contact a lecturer][synopsis]

## Programme

**Backend** is given at [Communication and Multimedia Design][bachelor], a
design bachelor focused on interactive digital products and services.  CMD is
part of the [Faculty of Digital Media and Creative Industries][faculty] at the
[Amsterdam University of Applied Sciences][university].

[![][cmd-logo]][bachelor]

## Conduct

This course has a [Code of Conduct][coc].  Anyone interacting with this
repository, organisation, or community is bound by it.

Staff and students of the Amsterdam University of Applied Sciences (Hogeschool
van Amsterdam) are additionally bound by the [Regulation Undesirable
Conduct][ruc] ([Regeling Ongewenst Gedrag][rog]).

## License

Unless stated otherwise, code is [MIT][] © [Titus Wormer][author],
docs and images are [CC-BY-4.0][].

[banner]: https://cdn.rawgit.com/cmda-be/logo/93c03f4/banner.svg

[mit]: license.md#code

[cc-by-4.0]: license.md#documentation-and-images

[author]: http://wooorm.com

[wooorm-gh]: https://github.com/wooorm

[lbrt-gh]: https://github.com/lbrt

[razpudding-gh]: https://github.com/Razpudding

[wooorm-mail]: mailto:t.e.wormer@hva.nl?subject=backend:%20

[lbrt-mail]: mailto:a.s.de.klein@hva.nl?subject=backend:%20

[razpudding-mail]: mailto:l.n.aarnoudse@hva.nl?subject=backend:%20

[cmda]: https://github.com/cmda

[fe3]: https://github.com/cmda-fe3/course-17-18

[gh-be]: https://github.com/cmda-be/course-17-18

[slack]: https://cmda-tech.slack.com

[moodle-be]: https://moodle.cmd.hva.nl/course/view.php?id=431

[rooster]: https://rooster.hva.nl

[node]: https://nodejs.org

[http]: https://tools.ietf.org/html/rfc2068

[sql]: https://en.wikipedia.org/wiki/SQL

[nosql]: https://en.wikipedia.org/wiki/NoSQL

[command-line]: https://en.wikipedia.org/wiki/Command-line_interface

[git]: https://git-scm.com

[stackoverflow]: https://stackoverflow.com/questions/tagged/d3.js

[duckduckgo]: https://duckduckgo.com

[synopsis]: #synopsis

[minor]: https://cmda.github.io/minor-everything-web/

[html-css]: https://learn.shayhowe.com/html-css/

[safari]: http://rps.hva.nl:2048/login?url=http://proquest.safaribooksonline.com/?uicode=hva

[lynda-portal]: https://lyndaportal.ict.hva.nl

[ydkjs-1]: https://github.com/getify/You-Dont-Know-JS/blob/master/up%20&%20going/README.md#you-dont-know-js-up--going

[ydkjs-2]: https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20&%20closures/README.md#you-dont-know-js-scope--closures

[ydkjs-3]: https://github.com/getify/You-Dont-Know-JS/blob/master/this%20&%20object%20prototypes/README.md#you-dont-know-js-this--object-prototypes

[ydkjs-4]: https://github.com/getify/You-Dont-Know-JS/blob/master/types%20&%20grammar/README.md#you-dont-know-js-types--grammar

[ydkjs-5]: https://github.com/getify/You-Dont-Know-JS/blob/master/async%20&%20performance/README.md#you-dont-know-js-async--performance

[ydkjs-6]: https://github.com/getify/You-Dont-Know-JS/blob/master/es6%20&%20beyond/README.md#you-dont-know-js-es6--beyond

[a1]: assessment-1.md

[a2]: assessment-2.md

[participation]: participation.md

[bachelor]: https://www.cmd-amsterdam.nl/english/

[faculty]: https://www.amsterdamuas.com/faculty/fdmci/faculty-of-digital-media-and-creative-industries.html

[university]: https://www.amsterdamuas.com

[cmd-logo]: images/cmd.jpg

[coc]: code-of-conduct.md

[ruc]: https://www.amsterdamuas.com/practical-matters/algemeen/hva-breed/juridische-zaken/legal-affairs/regulation-undesirable-conduct/regulation-undesirable-conduct.html#anker-3-complaints-authority

[rog]: https://www.hva.nl/praktisch/algemeen/hva-breed/juridische-zaken/loket-beroep-bezwaar-en-klacht/regeling-ongewenst-gedrag/regeling-ongewenst-gedrag.html?origin=gbS4rg%2FDTZuxQ6lGVF%2BN1A

[w1lec]: week-1.md#lecture

[w2lec]: week-2.md#lecture

[w3lec]: week-3.md#lecture

[w4lec]: week-4.md#lecture

[w5lec]: week-5.md#lecture

[w6lec]: week-6.md#lecture

[w1lab]: week-1.md#lab

[w2lab]: week-2.md#lab

[w3lab]: week-3.md#lab

[w4lab]: week-4.md#lab

[w5lab]: week-5.md#lab

[w6lab]: week-6.md#lab

[w7lab]: week-7.md#lab

[w8lab]: week-8.md#lab