<p align="center">
  <a href="https://getbootstrap.com/">
    <img src="https://getbootstrap.com/docs/5.2/assets/brand/bootstrap-logo-shadow.png" alt="Bootstrap logo" width="200" height="165">
  </a>
</p>

<h3 align="center">Bootstrap</h3>

<p align="center">
  Sleek, intuitive, and powerful front-end framework for faster and easier web development.
  <br>
  <a href="https://getbootstrap.com/docs/5.2/"><strong>Explore Bootstrap docs »</strong></a>
  <br>
  <br>
  <a href="https://github.com/twbs/bootstrap/issues/new?assignees=-&labels=bug&template=bug_report.yml">Report bug</a>
  ·
  <a href="https://github.com/twbs/bootstrap/issues/new?assignees=&labels=feature&template=feature_request.yml">Request feature</a>
  ·
  <a href="https://themes.getbootstrap.com/">Themes</a>
  ·
  <a href="https://blog.getbootstrap.com/">Blog</a>
</p>


## Bootstrap 5

Our default branch is for development of our Bootstrap 5 release. Head to the [`v4-dev` branch](https://github.com/twbs/bootstrap/tree/v4-dev) to view the readme, documentation, and source code for Bootstrap 4.


## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Community](#community)
- [Versioning](#versioning)
- [Creators](#creators)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)


## Quick start

Several quick start options are available:

- [Download the latest release](https://github.com/twbs/bootstrap/archive/v5.2.1.zip)
- Clone the repo: `git clone https://github.com/twbs/bootstrap.git`
- Install with [npm](https://www.npmjs.com/): `npm install bootstrap@v5.2.1`
- Install with [yarn](https://yarnpkg.com/): `yarn add bootstrap@v5.2.1`
- Install with [Composer](https://getcomposer.org/): `composer require twbs/bootstrap:5.2.1`
- Install with [NuGet](https://www.nuget.org/): CSS: `Install-Package bootstrap` Sass: `Install-Package bootstrap.sass`

Read the [Getting started page](https://getbootstrap.com/docs/5.2/getting-started/introduction/) for information on the framework contents, templates, examples, and more.


## Status

[![Build Status](https://img.shields.io/github/workflow/status/twbs/bootstrap/JS%20Tests/main?label=JS%20Tests&logo=github)](https://github.com/twbs/bootstrap/actions?query=workflow%3AJS+Tests+branch%3Amain)
[![npm version](https://img.shields.io/npm/v/bootstrap)](https://www.npmjs.com/package/bootstrap)
[![Gem version](https://img.shields.io/gem/v/bootstrap)](https://rubygems.org/gems/bootstrap)
[![Meteor Atmosphere](https://img.shields.io/badge/meteor-twbs%3Abootstrap-blue)](https://atmospherejs.com/twbs/bootstrap)
[![Packagist Prerelease](https://img.shields.io/packagist/vpre/twbs/bootstrap)](https://packagist.org/packages/twbs/bootstrap)
[![NuGet](https://img.shields.io/nuget/vpre/bootstrap)](https://www.nuget.org/packages/bootstrap/absoluteLatest)
[![Coverage Status](https://img.shields.io/coveralls/github/twbs/bootstrap/main)](https://coveralls.io/github/twbs/bootstrap?branch=main)
[![CSS gzip size](https://img.badgesize.io/twbs/bootstrap/main/dist/css/bootstrap.min.css?compression=gzip&label=CSS%20gzip%20size)](https://github.com/twbs/bootstrap/blob/main/dist/css/bootstrap.min.css)
[![CSS Brotli size](https://img.badgesize.io/twbs/bootstrap/main/dist/css/bootstrap.min.css?compression=brotli&label=CSS%20Brotli%20size)](https://github.com/twbs/bootstrap/blob/main/dist/css/bootstrap.min.css)
[![JS gzip size](https://img.badgesize.io/twbs/bootstrap/main/dist/js/bootstrap.min.js?compression=gzip&label=JS%20gzip%20size)](https://github.com/twbs/bootstrap/blob/main/dist/js/bootstrap.min.js)
[![JS Brotli size](https://img.badgesize.io/twbs/bootstrap/main/dist/js/bootstrap.min.js?compression=brotli&label=JS%20Brotli%20size)](https://github.com/twbs/bootstrap/blob/main/dist/js/bootstrap.min.js)
[![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)](https://www.browserstack.com/automate/public-build/SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)
[![Backers on Open Collective](https://img.shields.io/opencollective/backers/bootstrap)](#backers)
[![Sponsors on Open Collective](https://img.shields.io/opencollective/sponsors/bootstrap)](#sponsors)


## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations.

<details>
  <summary>Download contents</summary>

  ```text
  bootstrap/
  ├── css/
  │   ├── bootstrap-grid.css
  │   ├── bootstrap-grid.css.map
  │   ├── bootstrap-grid.min.css
  │   ├── bootstrap-grid.min.css.map
  │   ├── bootstrap-grid.rtl.css
  │   ├── bootstrap-grid.rtl.css.map
  │   ├── bootstrap-grid.rtl.min.css
  │   ├── bootstrap-grid.rtl.min.css.map
  │   ├── bootstrap-reboot.css
  │   ├── bootstrap-reboot.css.map
  │   ├── bootstrap-reboot.min.css
  │   ├── bootstrap-reboot.min.css.map
  │   ├── bootstrap-reboot.rtl.css
  │   ├── bootstrap-reboot.rtl.css.map
  │   ├── bootstrap-reboot.rtl.min.css
  │   ├── bootstrap-reboot.rtl.min.css.map
  │   ├── bootstrap-utilities.css
  │   ├── bootstrap-utilities.css.map
  │   ├── bootstrap-utilities.min.css
  │   ├── bootstrap-utilities.min.css.map
  │   ├── bootstrap-utilities.rtl.css
  │   ├── bootstrap-utilities.rtl.css.map
  │   ├── bootstrap-utilities.rtl.min.css
  │   ├── bootstrap-utilities.rtl.min.css.map
  │   ├── bootstrap.css
  │   ├── bootstrap.css.map
  │   ├── bootstrap.min.css
  │   ├── bootstrap.min.css.map
  │   ├── bootstrap.rtl.css
  │   ├── bootstrap.rtl.css.map
  │   ├── bootstrap.rtl.min.css
  │   └── bootstrap.rtl.min.css.map
  └── js/
      ├── bootstrap.bundle.js
      ├── bootstrap.bundle.js.map
      ├── bootstrap.bundle.min.js
      ├── bootstrap.bundle.min.js.map
      ├── bootstrap.esm.js
      ├── bootstrap.esm.js.map
      ├── bootstrap.esm.min.js
      ├── bootstrap.esm.min.js.map
      ├── bootstrap.js
      ├── bootstrap.js.map
      ├── bootstrap.min.js
      └── bootstrap.min.js.map
  ```
</details>

We provide compiled CSS and JS (`bootstrap.*`), as well as compiled and minified CSS and JS (`bootstrap.min.*`). [Source maps](https://developers.google.com/web/tools/chrome-devtools/javascript/source-maps) (`bootstrap.*.map`) are available for use with certain browsers' developer tools. Bundled JS files (`bootstrap.bundle.js` and minified `bootstrap.bundle.min.js`) include [Popper](https://popper.js.org/).


## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/twbs/bootstrap/blob/main/.github/CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/twbs/bootstrap/issues/new/choose).


## Documentation

Bootstrap's documentation, included in this repo in the root directory, is built with [Hugo](https://gohugo.io/) and publicly hosted on GitHub Pages at <https://getbootstrap.com/>. The docs may also be run locally.

Documentation search is powered by [Algolia's DocSearch](https://docsearch.algolia.com/). Working on our search? Be sure to set `debug: true` in `site/assets/js/search.js`.

### Running documentation locally

1. Run `npm install` to install the Node.js dependencies, including Hugo (the site builder).
2. Run `npm run test` (or a specific npm script) to rebuild distributed CSS and JavaScript files, as well as our docs assets.
3. From the root `/bootstrap` directory, run `npm run docs-serve` in the command line.
4. Open `http://localhost:9001/` in your browser, and voilà.

Learn more about using Hugo by reading its [documentation](https://gohugo.io/documentation/).

### Documentation for previous releases

You can find all our previous releases docs on <https://getbootstrap.com/docs/versions/>.

[Previous releases](https://github.com/twbs/bootstrap/releases) and their documentation are also available for download.


## Contributing

Please read through our [contributing guidelines](https://github.com/twbs/bootstrap/blob/main/.github/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, if your pull request contains JavaScript patches or features, you must include [relevant unit tests](https://github.com/twbs/bootstrap/tree/main/js/tests). All HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Mark Otto](https://github.com/mdo).

Editor preferences are available in the [editor config](https://github.com/twbs/bootstrap/blob/main/.editorconfig) for easy use in common text editors. Read more and download plugins at <https://editorconfig.org/>.


## Community

Get updates on Bootstrap's development and chat with the project maintainers and community members.

- Follow [@getbootstrap on Twitter](https://twitter.com/getbootstrap).
- Read and subscribe to [The Official Bootstrap Blog](https://blog.getbootstrap.com/).
- Ask and explore [our GitHub Discussions](https://github.com/twbs/bootstrap/discussions).
- Chat with fellow Bootstrappers in IRC. On the `irc.libera.chat` server, in the `#bootstrap` channel.
- Implementation help may be found at Stack Overflow (tagged [`bootstrap-5`](https://stackoverflow.com/questions/tagged/bootstrap-5)).
- Developers should use the keyword `bootstrap` on packages which modify or add to the functionality of Bootstrap when distributing through [npm](https://www.npmjs.com/browse/keyword/bootstrap) or similar delivery mechanisms for maximum discoverability.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under [the Semantic Versioning guidelines](https://semver.org/). Sometimes we screw up, but we adhere to those rules whenever possible.

See [the Releases section of our GitHub project](https://github.com/twbs/bootstrap/releases) for changelogs for each release version of Bootstrap. Release announcement posts on [the official Bootstrap blog](https://blog.getbootstrap.com/) contain summaries of the most noteworthy changes made in each release.


## Creators

**Mark Otto**

- <https://twitter.com/mdo>
- <https://github.com/mdo>

**Jacob Thornton**

- <https://twitter.com/fat>
- <https://github.com/fat>


## Thanks

<a href="https://www.browserstack.com/">
  <img src="https://live.browserstack.com/images/opensource/browserstack-logo.svg" alt="BrowserStack" width="192" height="42">
</a>

Thanks to [BrowserStack](https://www.browserstack.com/) for providing the infrastructure that allows us to test in real browsers!

<a href="https://www.netlify.com/">
  <img src="https://www.netlify.com/v3/img/components/full-logo-light.svg" alt="Netlify" width="147" height="40">
</a>

Thanks to [Netlify](https://www.netlify.com/) for providing us with Deploy Previews!


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/bootstrap#sponsor)]

[![OC sponsor 0](https://opencollective.com/bootstrap/sponsor/0/avatar.svg)](https://opencollective.com/bootstrap/sponsor/0/website)
[![OC sponsor 1](https://opencollective.com/bootstrap/sponsor/1/avatar.svg)](https://opencollective.com/bootstrap/sponsor/1/website)
[![OC sponsor 2](https://opencollective.com/bootstrap/sponsor/2/avatar.svg)](https://opencollective.com/bootstrap/sponsor/2/website)
[![OC sponsor 3](https://opencollective.com/bootstrap/sponsor/3/avatar.svg)](https://opencollective.com/bootstrap/sponsor/3/website)
[![OC sponsor 4](https://opencollective.com/bootstrap/sponsor/4/avatar.svg)](https://opencollective.com/bootstrap/sponsor/4/website)
[![OC sponsor 5](https://opencollective.com/bootstrap/sponsor/5/avatar.svg)](https://opencollective.com/bootstrap/sponsor/5/website)
[![OC sponsor 6](https://opencollective.com/bootstrap/sponsor/6/avatar.svg)](https://opencollective.com/bootstrap/sponsor/6/website)
[![OC sponsor 7](https://opencollective.com/bootstrap/sponsor/7/avatar.svg)](https://opencollective.com/bootstrap/sponsor/7/website)
[![OC sponsor 8](https://opencollective.com/bootstrap/sponsor/8/avatar.svg)](https://opencollective.com/bootstrap/sponsor/8/website)
[![OC sponsor 9](https://opencollective.com/bootstrap/sponsor/9/avatar.svg)](https://opencollective.com/bootstrap/sponsor/9/website)


## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/bootstrap#backer)]

[![Backers](https://opencollective.com/bootstrap/backers.svg?width=890)](https://opencollective.com/bootstrap#backers)


## Copyright and license

Code and documentation copyright 2011–2022 the [Bootstrap Authors](https://github.com/twbs/bootstrap/graphs/contributors) and [Twitter, Inc.](https://twitter.com) Code released under the [MIT License](https://github.com/twbs/bootstrap/blob/main/LICENSE). Docs released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/).

## Persian Version نسخه فارسی

<p align="center">
  <a href="https://getbootstrap.com/">
    <img src="https://getbootstrap.com/docs/5.2/assets/brand/bootstrap-logo-shadow.png" alt="آرم بوت استرپ" width="200" height="165">
  </a>
</p>

<h3 align="center">بوت استرپ</h3>

<p align="center">
چارچوب جلویی براق ، بصری و قدرتمند برای توسعه وب سریعتر و آسان تر.
  <br>
  <a href="https://getbootstrap.com/docs/5.2/"><strong>اسناد بوت استرپ را کاوش کنید »</strong></a>
  <br>
  <br>
  <a href="https://github.com/twbs/bootstrap/issues/new?assignees=-&labels=bug&template=bug_report.yml">گزارش اشکال</a>
  ·
  <a href="https://github.com/twbs/bootstrap/issues/new?assignees=&labels=feature&template=feature_request.yml">ویژگی درخواست</a>
  ·
  <a href="https://themes.getbootstrap.com/">مضامین</a>
  ·
  <a href="https://blog.getbootstrap.com/">وبلاگ</a>
</p>


## بوت استرپ 5

شاخه پیش فرض ما برای توسعه نسخه Bootstrap 5 ما است.سر به [`v4-dev` branch](https://github.com/twbs/bootstrap/tree/v4-dev) برای مشاهده README ، مستندات و کد منبع برای Bootstrap 4.


## فهرست مطالب

- [شروع سریع](#quick-start)
- [وضعیت](#status)
- [آنچه شامل می شود](#whats-included)
- [اشکالات و درخواست های ویژگی](#bugs-and-feature-requests)
- [مستندات](#documentation)
- [مشارکت کننده](#contributing)
- [انجمن](#community)
- [نسخه سازی](#versioning)
- [سازندگان](#creators)
- [با تشکر](#thanks)
- [حق چاپ و مجوز](#copyright-and-license)


## شروع سریع

چندین گزینه شروع سریع در دسترس است:

- [آخرین نسخه را بارگیری کنید](https://github.com/twbs/bootstrap/archive/v5.2.1.zip)
- کلون مخزن: `git clone https://github.com/twbs/bootstrap.git`
- نصب کردن [npm](https://www.npmjs.com/): `npm install bootstrap@v5.2.1`
- نصب کردن [yarn](https://yarnpkg.com/): `yarn add bootstrap@v5.2.1`
- نصب کردن [Composer](https://getcomposer.org/): `composer require twbs/bootstrap:5.2.1`
- نصب کردن [NuGet](https://www.nuget.org/): CSS: `Install-Package bootstrap` Sass: `Install-Package bootstrap.sass`

خواندن [شروع صفحه](https://getbootstrap.com/docs/5.2/getting-started/introduction/) برای اطلاعات در مورد مطالب چارچوب ، الگوها ، نمونه ها و موارد دیگر.


## وضعیت

[![ایجاد وضعیت](https://img.shields.io/github/workflow/status/twbs/bootstrap/JS%20Tests/main?label=JS%20Tests&logo=github)](https://github.com/twbs/bootstrap/actions?query=workflow%3AJS+Tests+branch%3Amain)
[![نسخه NPM](https://img.shields.io/npm/v/bootstrap)](https://www.npmjs.com/package/bootstrap)
[![نسخه گوهر](https://img.shields.io/gem/v/bootstrap)](https://rubygems.org/gems/bootstrap)
[![جو](https://img.shields.io/badge/meteor-twbs%3Abootstrap-blue)](https://atmospherejs.com/twbs/bootstrap)
[![پیش نمایش](https://img.shields.io/packagist/vpre/twbs/bootstrap)](https://packagist.org/packages/twbs/bootstrap)
[![نای](https://img.shields.io/nuget/vpre/bootstrap)](https://www.nuget.org/packages/bootstrap/absoluteLatest)
[![وضعیت پوشش](https://img.shields.io/coveralls/github/twbs/bootstrap/main)](https://coveralls.io/github/twbs/bootstrap?branch=main)
[![اندازه CSS GZIP](https://img.badgesize.io/twbs/bootstrap/main/dist/css/bootstrap.min.css?compression=gzip&label=CSS%20gzip%20size)](https://github.com/twbs/bootstrap/blob/main/dist/css/bootstrap.min.css)
[![اندازه CSS Brotli](https://img.badgesize.io/twbs/bootstrap/main/dist/css/bootstrap.min.css?compression=brotli&label=CSS%20Brotli%20size)](https://github.com/twbs/bootstrap/blob/main/dist/css/bootstrap.min.css)
[![اندازه JS GZIP](https://img.badgesize.io/twbs/bootstrap/main/dist/js/bootstrap.min.js?compression=gzip&label=JS%20gzip%20size)](https://github.com/twbs/bootstrap/blob/main/dist/js/bootstrap.min.js)
[![اندازه JS Brotli](https://img.badgesize.io/twbs/bootstrap/main/dist/js/bootstrap.min.js?compression=brotli&label=JS%20Brotli%20size)](https://github.com/twbs/bootstrap/blob/main/dist/js/bootstrap.min.js)
[![وضعیت مرورگر](https://www.browserstack.com/automate/badge.svg?badge_key=SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)](https://www.browserstack.com/automate/public-build/SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)
[![پشتیبانان در مجموعه باز](https://img.shields.io/opencollective/backers/bootstrap)](#backers)
[![حامیان مالی در مجموعه باز](https://img.shields.io/opencollective/sponsors/bootstrap)](#sponsors)


## آنچه شامل می شود

در این بارگیری ، دایرکتوری ها و پرونده های زیر را پیدا خواهید کرد ، که از نظر منطقی گروه بندی دارایی های مشترک را انجام می دهید و هر دو تغییرات کامپایل شده و کوچک را ارائه می دهید.
<details>
  <summary>محتویات را بارگیری کنید</summary>

  ```text
  bootstrap/
  ├── css/
  │   ├── bootstrap-grid.css
  │   ├── bootstrap-grid.css.map
  │   ├── bootstrap-grid.min.css
  │   ├── bootstrap-grid.min.css.map
  │   ├── bootstrap-grid.rtl.css
  │   ├── bootstrap-grid.rtl.css.map
  │   ├── bootstrap-grid.rtl.min.css
  │   ├── bootstrap-grid.rtl.min.css.map
  │   ├── bootstrap-reboot.css
  │   ├── bootstrap-reboot.css.map
  │   ├── bootstrap-reboot.min.css
  │   ├── bootstrap-reboot.min.css.map
  │   ├── bootstrap-reboot.rtl.css
  │   ├── bootstrap-reboot.rtl.css.map
  │   ├── bootstrap-reboot.rtl.min.css
  │   ├── bootstrap-reboot.rtl.min.css.map
  │   ├── bootstrap-utilities.css
  │   ├── bootstrap-utilities.css.map
  │   ├── bootstrap-utilities.min.css
  │   ├── bootstrap-utilities.min.css.map
  │   ├── bootstrap-utilities.rtl.css
  │   ├── bootstrap-utilities.rtl.css.map
  │   ├── bootstrap-utilities.rtl.min.css
  │   ├── bootstrap-utilities.rtl.min.css.map
  │   ├── bootstrap.css
  │   ├── bootstrap.css.map
  │   ├── bootstrap.min.css
  │   ├── bootstrap.min.css.map
  │   ├── bootstrap.rtl.css
  │   ├── bootstrap.rtl.css.map
  │   ├── bootstrap.rtl.min.css
  │   └── bootstrap.rtl.min.css.map
  └── js/
      ├── bootstrap.bundle.js
      ├── bootstrap.bundle.js.map
      ├── bootstrap.bundle.min.js
      ├── bootstrap.bundle.min.js.map
      ├── bootstrap.esm.js
      ├── bootstrap.esm.js.map
      ├── bootstrap.esm.min.js
      ├── bootstrap.esm.min.js.map
      ├── bootstrap.js
      ├── bootstrap.js.map
      ├── bootstrap.min.js
      └── bootstrap.min.js.map
  ```
</details>

ما CSS و JS کامپایل شده را ارائه می دهیم (`bootstrap.*`), و همچنین CSS و JS کامپایل و کوچک شده (`bootstrap.min.*`). [نقشه منبع](https://developers.google.com/web/tools/chrome-devtools/javascript/source-maps) (`bootstrap.*.map`) برای استفاده با ابزارهای توسعه دهنده مرورگرهای خاص در دسترس هستند.پرونده های JS (`bootstrap.bundle.js` و کوچک شده `bootstrap.bundle.min.js`) عبارتند از [Popper](https://popper.js.org/).


## اشکالات ودرخواست های ویژگی

یک اشکال یا درخواست ویژگی دارید؟لطفا ابتدا بخوانید [دستورالعمل های صدور](https://github.com/twbs/bootstrap/blob/main/.github/CONTRIBUTING.md#using-the-issue-tracker) و موارد موجود و بسته را جستجو کنید.اگر هنوز مشکل یا ایده شما مورد توجه قرار نگرفته است, [لطفا یک شماره جدید را باز کنید](https://github.com/twbs/bootstrap/issues/new/choose).


## مستندات

مستندات Bootstrap ، که در این repo در فهرست root گنجانده شده است ، با ساخته شده است [Hugo](https://gohugo.io/) و به طور عمومی در صفحات GitHub در<https://getbootstrap.com/>. اسناد همچنین ممکن است به صورت محلی اجرا شوند.جستجوی مستندات توسط [Algolia's DocSearch](https://docsearch.algolia.com/). روی جستجوی ما کار می کنید؟حتماً تنظیم کنید `debug: true` که در `site/assets/js/search.js`.

### در حال اجرا اسناد به صورت محلی

1. اجرا کن `npm install` برای نصب وابستگی های Node.js ، از جمله هوگو (سازنده سایت).
2. اجرا کن `npm run test` (یا یک اسکریپت NPM خاص) برای بازسازی پرونده های توزیع شده CSS و JavaScript و همچنین دارایی های Docs ما.
3. از ریشه `/bootstrap` directory, run `npm run docs-serve` در خط فرمان
4. باز کن `http://localhost:9001/` در مرورگر و voilà.

در مورد استفاده از هوگو با خواندن آن بیشتر بدانید [مستندات](https://gohugo.io/documentation/).

### مستندات برای نسخه های قبلی

شما می توانید تمام نسخه های قبلی ما را پیدا کنید <https://getbootstrap.com/docs/versions/>.

[نسخه های قبلی](https://github.com/twbs/bootstrap/releases) و مستندات آنها نیز برای بارگیری در دسترس است.


## مشارکت کننده

لطفا از طریق ما بخوانید [دستورالعمل های کمک کننده](https://github.com/twbs/bootstrap/blob/main/.github/CONTRIBUTING.md). شامل دستورالعمل هایی برای افتتاح مسائل ، استانداردهای برنامه نویسی و یادداشت های مربوط به توسعه است.

علاوه بر این ، اگر درخواست کشش شما حاوی تکه ها یا ویژگی های JavaScript است ، باید شامل شوید [تست های واحد مربوطه](https://github.com/twbs/bootstrap/tree/main/js/tests). همه HTML و CSS باید مطابق با [Code Guide](https://github.com/mdo/code-guide), حفظ شده توسط [Mark Otto](https://github.com/mdo).

تنظیمات ویرایشگر در موجود است [editor config](https://github.com/twbs/bootstrap/blob/main/.editorconfig) برای استفاده آسان در ویرایشگرهای متن مشترک.بیشتر بخوانید و افزونه ها را بارگیری کنید <https://editorconfig.org/>.


## انجمن

به روزرسانی در مورد توسعه Bootstrap و گپ زدن با نگهدارنده پروژه و اعضای جامعه دریافت کنید.

- دنبال کردن [@getbootstrap on Twitter](https://twitter.com/getbootstrap).
- بخوانید و مشترک شوید [وبلاگ رسمی بوت استرپ](https://blog.getbootstrap.com/).
-بپرسید و کاوش کنید [بحث های GitHub ما](https://github.com/twbs/bootstrap/discussions).
- با بوت استراپندگان دیگر در IRC گپ بزنید.در `irc.libera.chat` سرور ، در `#bootstrap` کانال.
- کمک پیاده سازی ممکن است در Overflow Stack پیدا شود (با برچسب [`bootstrap-5`](https://stackoverflow.com/questions/tagged/bootstrap-5)).
- Developers should use the keyword `bootstrap` در بسته هایی که هنگام توزیع از طریق عملکرد Bootstrap را تغییر داده یا اضافه می کنند [npm](https://www.npmjs.com/browse/keyword/bootstrap) یا مکانیسم های تحویل مشابه برای حداکثر کشف.


## نسخه سازی

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under [دستورالعمل های نسخه معنایی](https://semver.org/). بعضی اوقات ما پیچ می خوریم ، اما هر زمان ممکن به آن قوانین پیروی می کنیم.

دیدن [بخش انتشار پروژه GitHub ما](https://github.com/twbs/bootstrap/releases) برای ChangeLogs برای هر نسخه نسخه Bootstrap.انتشار پست های اعلامیه در [وبلاگ رسمی بوت استرپ](https://blog.getbootstrap.com/) حاوی خلاصه ای از قابل توجه ترین تغییرات در هر نسخه است.


## سازندگان

**مارک اتو**

- <https://twitter.com/mdo>
- <https://github.com/mdo>

**یعقوب تورنتون**

- <https://twitter.com/fat>
- <https://github.com/fat>


## با تشکر

<a href="https://www.browserstack.com/">
  <img src="https://live.browserstack.com/images/opensource/browserstack-logo.svg" alt="BrowserStack" width="192" height="42">
</a>

با تشکر از [BrowserStack](https://www.browserstack.com/) برای ارائه زیرساخت هایی که به ما امکان می دهد در مرورگرهای واقعی آزمایش کنیم!

<a href="https://www.netlify.com/">
  <img src="https://www.netlify.com/v3/img/components/full-logo-light.svg" alt="Netlify" width="147" height="40">
</a>

با تشکر از [Netlify](https://www.netlify.com/) برای ارائه پیش نمایش های مستقر به ما!


## حامی

با تبدیل شدن به یک اسپانسر از این پروژه پشتیبانی کنید.آرم شما با پیوندی به وب سایت شما در اینجا نمایش داده می شود. [[Become a sponsor](https://opencollective.com/bootstrap#sponsor)]

[![OC sponsor 0](https://opencollective.com/bootstrap/sponsor/0/avatar.svg)](https://opencollective.com/bootstrap/sponsor/0/website)
[![OC sponsor 1](https://opencollective.com/bootstrap/sponsor/1/avatar.svg)](https://opencollective.com/bootstrap/sponsor/1/website)
[![OC sponsor 2](https://opencollective.com/bootstrap/sponsor/2/avatar.svg)](https://opencollective.com/bootstrap/sponsor/2/website)
[![OC sponsor 3](https://opencollective.com/bootstrap/sponsor/3/avatar.svg)](https://opencollective.com/bootstrap/sponsor/3/website)
[![OC sponsor 4](https://opencollective.com/bootstrap/sponsor/4/avatar.svg)](https://opencollective.com/bootstrap/sponsor/4/website)
[![OC sponsor 5](https://opencollective.com/bootstrap/sponsor/5/avatar.svg)](https://opencollective.com/bootstrap/sponsor/5/website)
[![OC sponsor 6](https://opencollective.com/bootstrap/sponsor/6/avatar.svg)](https://opencollective.com/bootstrap/sponsor/6/website)
[![OC sponsor 7](https://opencollective.com/bootstrap/sponsor/7/avatar.svg)](https://opencollective.com/bootstrap/sponsor/7/website)
[![OC sponsor 8](https://opencollective.com/bootstrap/sponsor/8/avatar.svg)](https://opencollective.com/bootstrap/sponsor/8/website)
[![OC sponsor 9](https://opencollective.com/bootstrap/sponsor/9/avatar.svg)](https://opencollective.com/bootstrap/sponsor/9/website)


## پشتیبانان

با تشکر از همه پشتیبانان ما! 🙏 [[Become a backer](https://opencollective.com/bootstrap#backer)]

[![Backers](https://opencollective.com/bootstrap/backers.svg?width=890)](https://opencollective.com/bootstrap#backers)


## حق چاپ و مجوز

کد و مستندات کپی رایت 2011–2022 [نویسندگان بوت استرپ](https://github.com/twbs/bootstrap/graphs/contributors) وت [Twitter, Inc.](https://twitter.com) کد منتشر شده در زیر [MIT License](https://github.com/twbs/bootstrap/blob/main/LICENSE). اسناد منتشر شده در زیر [عوام خلاق](https://creativecommons.org/licenses/by/3.0/).
