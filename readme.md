



<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <meta name="defaultLanguage" content="en">
    <meta name="availableLanguages" content="en, es, fr, ja, pt_BR, uk, el, de, zh_Hans, zh_Hant, ru, he, eo">


    <title>vagrantgen · PyPI</title>
    <meta name="description" content="Vagrantfile generator">

    <link rel="stylesheet" href="/static/css/warehouse-ltr.99b3104d.css">
    <link rel="stylesheet" href="/static/css/fontawesome.b50b476c.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Source+Sans+3:400,400italic,600,600italic,700,700italic%7CSource+Code+Pro:500">
    <noscript>
      <link rel="stylesheet" href="/static/css/noscript.0673c9ea.css">
    </noscript>


    <link rel="icon" href="/static/images/favicon.35549fe8.ico" type="image/x-icon">

    <link rel="alternate" type="application/rss+xml" title="RSS: 40 latest updates" href="/rss/updates.xml">
    <link rel="alternate" type="application/rss+xml" title="RSS: 40 newest packages" href="/rss/packages.xml">
<link rel="alternate" type="application/rss+xml" title="RSS: latest releases for vagrantgen" href="/rss/project/vagrantgen/releases.xml">    <link rel="canonical" href="https://pypi.org/project/vagrantgen/">

    <meta property="og:url" content="https://pypi.org/project/vagrantgen/">
    <meta property="og:site_name" content="PyPI">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://pypi.org/static/images/twitter.abaf4b19.webp">
    <meta property="og:title" content="vagrantgen">
    <meta property="og:description" content="Vagrantfile generator">

    <link rel="search" type="application/opensearchdescription+xml" title="PyPI" href="/opensearch.xml">

    <script async
data-ga-id="UA-55961911-1"
data-ga4-id="G-RW7D75DF8V"
            src="/static/js/warehouse.dd4295c4.js">
    </script>
<script>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']]
  },
};
</script>
<script async
  src="https://cdn.jsdelivr.net/npm/mathjax@3.2.2/es5/tex-svg.js"
  integrity="sha256-1CldwzdEg2k1wTmf7s5RWVd7NMXI/7nxxjJM2C4DqII="
  crossorigin="anonymous"
></script>
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-55961911-1"></script>
<script async src="https://www.googletagmanager.com/gtag/js?id=G-RW7D75DF8V"></script>
<script defer src="https://www.fastly-insights.com/insights.js?k=6a52360a-f306-421e-8ed5-7417d0d4a4e9&dnt=true"></script>
    <script async
        src="https://media.ethicalads.io/media/client/v1.4.0/ethicalads.min.js"
        integrity="sha256-U3hKDidudIaxBDEzwGJApJgPEf2mWk6cfMWghrAa6i0= sha384-UcmsCqcNRSLW/dV3Lo1oCi2/VaurXbib6p4HyUEOeIa/4OpsrnucrugAefzVZJfI sha512-q4t1L4xEjGV2R4hzqCa41P8jrgFUS8xTb8rdNv4FGvw7FpydVj/kkxBJHOiaoxHa8olCcx1Slk9K+3sNbsM4ug=="
        crossorigin="anonymous"
    ></script>

  </head>

  <body data-controller="viewport-toggle">

    <!-- Accessibility: this link should always be the first piece of content inside the body-->
    <a href="#content" class="skip-to-content">Skip to main content</a>

    <button type="button" class="button button--primary button--switch-to-mobile hidden" data-viewport-toggle-target="switchToMobile" data-action="viewport-toggle#switchToMobile">
Switch to mobile version    </button>

    <div id="sticky-notifications" class="stick-to-top js-stick-to-top">
      <!-- Add browser warning. Will show for ie9 and below -->
      <!--[if IE]>
      <div class="notification-bar notification-bar--warning" role="status">
        <span class="notification-bar__icon">
          <i class="fa fa-exclamation-triangle" aria-hidden="true"></i>
          <span class="sr-only">Warning</span>
        </span>
        <span class="notification-bar__message">You are using an unsupported browser, upgrade to a newer version.</span>
      </div>
      <![endif]-->
      <noscript>
      <div class="notification-bar notification-bar--warning" role="status">
        <span class="notification-bar__icon">
          <i class="fa fa-exclamation-triangle" aria-hidden="true"></i>
          <span class="sr-only">Warning</span>
        </span>
        <span class="notification-bar__message">Some features may not work without JavaScript. Please try enabling it if you encounter problems.</span>
      </div>
      </noscript>

<div data-html-include="/_includes/notification-banners/"></div>    </div>

<div data-html-include="/_includes/flash-messages/"></div>

<div data-html-include="/_includes/session-notifications/"></div>
    <header class="site-header ">
      <div class="site-container">
        <div class="split-layout">
          <div class="split-layout">
            <div>
              <a class="site-header__logo" href="/">
                <img alt="PyPI" src="/static/images/logo-small.2a411bc6.svg">
              </a>
            </div>

            <form class="search-form search-form--primary" action="/search/" role="search">
              <label for="search" class="sr-only">Search PyPI</label>
              <input id="search" class="search-form__search" type="text" name="q" placeholder="Search projects" value="" autocomplete="off" autocapitalize="off" spellcheck="false" data-controller="search-focus" data-action="keydown@window->search-focus#focusSearchField" data-search-focus-target="searchField">
              <button type="submit" class="search-form__button">
                <i class="fa fa-search" aria-hidden="true"></i>
                <span class="sr-only">Search</span>
              </button>
            </form>
          </div>

<div data-html-include="/_includes/current-user-indicator/">            <div id="user-indicator" class="horizontal-menu horizontal-menu--light horizontal-menu--tall">
  <nav class="horizontal-menu horizontal-menu--light horizontal-menu--tall hide-on-tablet" aria-label="Main navigation">
    <ul>
      <li class="horizontal-menu__item"><a href="/help/" class="horizontal-menu__link">Help</a></li>
      <li class="horizontal-menu__item"><a href="/sponsors/" class="horizontal-menu__link">Sponsors</a></li>
      <li class="horizontal-menu__item"><a href="/account/login/" class="horizontal-menu__link">Log in</a></li>
      <li class="horizontal-menu__item"><a href="/account/register/" class="horizontal-menu__link">Register</a></li>
    </ul>
  </nav>
  <nav class="dropdown dropdown--on-menu hidden show-on-tablet" aria-label="Main navigation">
    <button type="button" class="horizontal-menu__link dropdown__trigger" aria-haspopup="true" aria-expanded="false" aria-label="View menu">
Menu      <span class="dropdown__trigger-caret">
        <i class="fa fa-caret-down" aria-hidden="true"></i>
      </span>
    </button>
    <ul class="dropdown__content" aria-hidden="true" aria-label="Main menu">
      <li><a class="dropdown__link" href="/help/">Help</a></li>
      <li><a class="dropdown__link" href="/sponsors/">Sponsors</a></li>
      <li><a class="dropdown__link" href="/account/login/">Log in</a></li>
      <li><a class="dropdown__link" href="/account/register/">Register</a></li>
    </ul>
  </nav>
</div>
</div>        </div>
      </div>
    </header>

    <div class="mobile-search">
      <form class="search-form search-form--fullwidth" action="/search/" role="search">
        <label for="mobile-search" class="sr-only">Search PyPI</label>
        <input id="mobile-search" class="search-form__search" type="text" name="q" placeholder="Search projects" value="" autocomplete="off" autocapitalize="off" spellcheck="false">
        
        <button type="submit" class="search-form__button">
          <i class="fa fa-search" aria-hidden="true"></i>
          <span class="sr-only">Search</span>
        </button>
      </form>
    </div>

    <main id="content">
<div class="hidden"
  data-controller="github-repo-stats"
  data-github-repo-stats-github-repo-info-outlet=".github-repo-info"
  data-github-repo-stats-url-value="https://api.github.com/repos/aramcap/vagrantgen"
  data-github-repo-stats-issue-url-value="https://api.github.com/search/issues?q=repo:aramcap/vagrantgen+type:issue+state:open&amp;per_page=1">
</div>

<div class="banner">
  <div class="package-header">
    <div class="package-header__left">
      <h1 class="package-header__name">
        vagrantgen 0.5
      </h1>

      <div data-controller="clipboard">
        <p class="package-header__pip-instructions">
          <span id="pip-command" data-clipboard-target="source">pip install vagrantgen</span>
          <button type="button" class="copy-tooltip copy-tooltip-s" data-action="clipboard#copy" data-clipboard-target="tooltip" data-clipboard-tooltip-value="Copy to clipboard">
            <i class="fa fa-copy" aria-hidden="true"></i>
            <span class="sr-only">Copy PIP instructions</span>
          </button>
        </p>
      </div>
    </div>

    <div class="package-header__right">
      <a class="status-badge status-badge--good" href="/project/vagrantgen/">
        <span>Latest version</span>
      </a>
      <p class="package-header__date">
Released: <time datetime="2022-07-13T13:39:10+0000" data-controller="localized-time" data-localized-time-relative="true" data-localized-time-show-time="false">
  Jul 13, 2022
</time>      </p>
    </div>
  </div>
</div>

<div class="horizontal-section horizontal-section--grey horizontal-section--thin">
  <div class="site-container">
<div data-html-include="/_includes/administer-project-include/vagrantgen"></div>    <div class="split-layout split-layout--middle package-description">
      <p class="package-description__summary">Vagrantfile generator</p>
<div data-html-include="/_includes/edit-project-button/vagrantgen"></div>    </div>
  </div>
</div>

<div data-controller="project-tabs">
  <div class="tabs-container">
    <div class="vertical-tabs">
      <div class="vertical-tabs__tabs">
        <div class="sidebar-section">
          <h3 class="sidebar-section__title">Navigation</h3>
          <nav aria-label="Navigation for vagrantgen">
            <ul class="vertical-tabs__list" role="tablist">
              <li role="tab">
                <a id="description-tab" href="#description" data-project-tabs-target="tab" data-action="project-tabs#onTabClick" class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--is-active" aria-selected="true" aria-label="Project description. Focus will be moved to the description.">
                  <i class="fa fa-align-left" aria-hidden="true"></i>
Project description                </a>
              </li>
              <li role="tab">
                <a id="history-tab" href="#history" data-project-tabs-target="tab" data-action="project-tabs#onTabClick" class="vertical-tabs__tab vertical-tabs__tab--with-icon" aria-label="Release history. Focus will be moved to the history panel.">
                  <i class="fa fa-history" aria-hidden="true"></i>
Release history                </a>
              </li>
              <li role="tab">
                <a id="files-tab" href="#files" data-project-tabs-target="tab" data-action="project-tabs#onTabClick" class="vertical-tabs__tab vertical-tabs__tab--with-icon" aria-label="Download files. Focus will be moved to the project files.">
                  <i class="fa fa-download" aria-hidden="true"></i>
Download files                </a>
              </li>
            </ul>
          </nav>
        </div>
<div class="sidebar-section">
  <h3 class="sidebar-section__title">Project links</h3>
  <ul class="vertical-tabs__list">
    <li>
      <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed" href="https://github.com/aramcap/vagrantgen" rel="nofollow">
        

<i class="fas fa-home" aria-hidden="true"></i>Homepage
      </a>
    </li>
  </ul>
</div>

<div class="sidebar-section">
  <h3 class="sidebar-section__title">Statistics</h3>
  <div class="hidden github-repo-info" data-controller="github-repo-info">
GitHub statistics:    <ul class="vertical-tabs__list">
      <li>
        <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed"
           data-github-repo-info-target="stargazersUrl" rel="noopener">
          <i class="fa fa-star" aria-hidden="true"></i>
          <strong>Stars:</strong>
          <span data-github-repo-info-target="stargazersCount"></span>
        </a>
      </li>
      <li>
        <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed"
           data-github-repo-info-target="forksUrl" rel="noopener">
          <i class="fa fa-code-branch" aria-hidden="true"></i>
          <strong>Forks:</strong>
          <span data-github-repo-info-target="forksCount"></span>
        </a>
      </li>
      <li>
        <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed"
           data-github-repo-info-target="openIssuesUrl" rel="noopener">
          <i class="fa fa-exclamation-circle" aria-hidden="true"></i>
          <strong>Open issues:</strong>
          <span data-github-repo-info-target="openIssuesCount"></span>
        </a>
      </li>
      <li>
        <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed"
           data-github-repo-info-target="openPRsUrl" rel="noopener">
          <i class="fa fa-code-pull-request" aria-hidden="true"></i>
          <strong>Open PRs:</strong>
          <span data-github-repo-info-target="openPRsCount"></span>
        </a>
      </li>
    </ul>
  </div>
  <p>
View statistics for this project via <a href="https://libraries.io/pypi/vagrantgen" title="External link" target="_blank" rel="noopener">Libraries.io</a>, or by using <a href="https://packaging.python.org/guides/analyzing-pypi-package-downloads/" target="_blank" rel="noopener">our public dataset on Google BigQuery</a>  </p>
</div>

<div class="sidebar-section">
  <h3 class="sidebar-section__title">Meta</h3>
  <p><strong>License:</strong> LICENSE</p>
    <p><strong>Author:</strong> Adrian Ramos</p>
</div>

<div class="sidebar-section">
    <h3 class="sidebar-section__title">Maintainers</h3>
      <span class="sidebar-section__maintainer">
        <a href="/user/aramcap/" aria-label="aramcap">
          <span class="sidebar-section__user-gravatar">
            <img src="https://pypi-camo.freetls.fastly.net/e0c8b18e01b0efbd86b3fdfe20c7012e31d92b95/68747470733a2f2f7365637572652e67726176617461722e636f6d2f6176617461722f65313439353630663837386134343236313266356361613261333830316434313f73697a653d3530" height="50" width="50" alt="Avatar for aramcap from gravatar.com" title="Avatar for aramcap from gravatar.com">
          </span>
          <span class="sidebar-section__user-gravatar-text">
            aramcap
          </span>
        </a>
      </span>
</div>

<div class="sidebar-section">
  <h3 class="sidebar-section__title">Classifiers</h3>
  <ul class="sidebar-section__classifiers">
    <li>
      <strong>Development Status</strong>
      <ul>
        <li>
          <a href="/search/?c=Development+Status+%3A%3A+4+-+Beta">
            4 - Beta
          </a>
        </li>
      </ul>
    </li>
    <li>
      <strong>Environment</strong>
      <ul>
        <li>
          <a href="/search/?c=Environment+%3A%3A+Console">
            Console
          </a>
        </li>
      </ul>
    </li>
    <li>
      <strong>Programming Language</strong>
      <ul>
        <li>
          <a href="/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3">
            Python :: 3
          </a>
        </li>
      </ul>
    </li>
  </ul>
</div>
<div class="sidebar-section" data-ea-publisher="psf" data-ea-type="psf" data-ea-keywords="pypi-sidebar"></div>

      </div>
      <div class="vertical-tabs__panel">
        <!-- mobile menu -->
        <nav aria-label="Navigation for vagrantgen">
          <ul class="vertical-tabs__list" role="tablist">
            <li role="tab">
              <a id="mobile-description-tab" href="#description" data-project-tabs-target="mobileTab" data-action="project-tabs#onTabClick" class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--mobile vertical-tabs__tab--no-top-border vertical-tabs__tab--is-active" aria-selected="true" aria-label="Project description. Focus will be moved to the description.">
                <i class="fa fa-align-left" aria-hidden="true"></i>
Project description              </a>
            </li>
            <li role="tab">
              <a id="mobile-data-tab" href="#data" data-project-tabs-target="mobileTab" data-action="project-tabs#onTabClick" class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--mobile" aria-label="Project details. Focus will be moved to the project details.">
                <i class="fa fa-info-circle" aria-hidden="true"></i>
Project details              </a>
            </li>
            <li role="tab">
              <a id="mobile-history-tab" href="#history" data-project-tabs-target="mobileTab" data-action="project-tabs#onTabClick" class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--mobile" aria-label="Release history. Focus will be moved to the history panel.">
              <i class="fa fa-history" aria-hidden="true"></i>
Release history            </a>
            </li>
            <li role="tab">
              <a id="mobile-files-tab" href="#files" data-project-tabs-target="mobileTab" data-action="project-tabs#onTabClick" class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--mobile" aria-label="Download files. Focus will be moved to the project files.">
                <i class="fa fa-download" aria-hidden="true"></i>
Download files              </a>
            </li>
          </ul>
        </nav>

        <div id="description" data-project-tabs-target="content" class="vertical-tabs__content" role="tabpanel" aria-labelledby="description-tab mobile-description-tab" tabindex="-1">
          <h2 class="page-title">Project description</h2>
          <div class="project-description">
            <h1>Vagrantgen</h1>
<p>Vagrantgen is a simply CLI to generate Vagrantfiles from a standard YAML.</p>
<p>This is a YAML example:</p>
<pre lang=yml>- projectname: cluster1
  provider: virtualbox
  vms:
  - name: vm01
    box: rockylinux/8
    mem: 1024
    cpu: 2
</pre>
<p>And this the Vagrantfile generated:</p>
<pre lang=rb><span class=no>Vagrant</span><span class=o>.</span><span class=n>configure</span><span class=p>(</span><span class=s2>"2"</span><span class=p>)</span><span class=w> </span><span class=k>do</span><span class=w> </span><span class=o>|</span><span class=n>config</span><span class=o>|</span>
<span class=w>    </span><span class=n>config</span><span class=o>.</span><span class=n>vm</span><span class=o>.</span><span class=n>synced_folder</span><span class=w> </span><span class=s2>"."</span><span class=p>,</span><span class=w> </span><span class=s2>"/vagrant"</span><span class=p>,</span><span class=w> </span><span class=ss>disabled</span><span class=p>:</span><span class=w> </span><span class=kp>true</span>

<span class=w>    </span><span class=n>config</span><span class=o>.</span><span class=n>vm</span><span class=o>.</span><span class=n>define</span><span class=w> </span><span class=s2>"cluster1vm01"</span><span class=w> </span><span class=k>do</span><span class=w> </span><span class=o>|</span><span class=n>node</span><span class=o>|</span>
<span class=w>        </span><span class=n>node</span><span class=o>.</span><span class=n>vm</span><span class=o>.</span><span class=n>hostname</span><span class=w> </span><span class=o>=</span><span class=w> </span><span class=s2>"cluster1vm01"</span>
<span class=w>        </span><span class=n>node</span><span class=o>.</span><span class=n>vm</span><span class=o>.</span><span class=n>box</span><span class=w> </span><span class=o>=</span><span class=w> </span><span class=s2>"rockylinux/8"</span>
<span class=w>        </span><span class=n>node</span><span class=o>.</span><span class=n>vm</span><span class=o>.</span><span class=n>provider</span><span class=w> </span><span class=s2>"virtualbox"</span><span class=w> </span><span class=k>do</span><span class=w> </span><span class=o>|</span><span class=n>provider</span><span class=o>|</span>
<span class=w>            </span><span class=n>provider</span><span class=o>.</span><span class=n>memory</span><span class=w> </span><span class=o>=</span><span class=w> </span><span class=s2>"1024"</span>
<span class=w>            </span><span class=n>provider</span><span class=o>.</span><span class=n>cpus</span><span class=w> </span><span class=o>=</span><span class=w> </span><span class=s2>"2"</span>
<span class=w>        </span><span class=k>end</span>
<span class=w>    </span><span class=k>end</span>
<span class=k>end</span>
</pre>
<h2>How use the CLI</h2>
<p>If you run <code>vagrantgen -h</code>, then you find the help menu:</p>
<pre lang=sh>$<span class=w> </span>vagrantgen<span class=w> </span>-h

usage:<span class=w> </span>vagrantgen<span class=w> </span><span class=o>[</span>-h<span class=o>]</span><span class=w> </span><span class=o>{</span>template,vf,ai<span class=o>}</span><span class=w> </span>...

Vagrantfile<span class=w> </span>Generator<span class=w> </span>-<span class=w> </span>github.com/aramcap/vagrantgen

positional<span class=w> </span>arguments:
<span class=w>  </span><span class=o>{</span>template,vf,ai<span class=o>}</span><span class=w>  </span>Subcommands
<span class=w>    </span>template<span class=w>        </span>Generate<span class=w> </span>template
<span class=w>    </span>vf<span class=w>              </span>Generate<span class=w> </span>Vagrantfile
<span class=w>    </span>ai<span class=w>              </span>Generate<span class=w> </span>ansible-inventory<span class=w> </span>file<span class=w> </span>from<span class=w> </span><span class=s2>"vagrant ssh-config"</span><span class=w> </span><span class=nb>command</span>

optional<span class=w> </span>arguments:
<span class=w>  </span>-h,<span class=w> </span>--help<span class=w>        </span>show<span class=w> </span>this<span class=w> </span><span class=nb>help</span><span class=w> </span>message<span class=w> </span>and<span class=w> </span><span class=nb>exit</span>
</pre>
<p>Any menu has <code>--help</code> command available.</p>
<ul>
<li><code>vagrantgen template</code>: Generates a template to facilitate the use.</li>
<li><code>vagrantgen vf</code>: Generates a Vagrantfile from a template file.
<ul>
<li>With argument <code>-i</code> you can specify a filename (by default <em>vagrant-template.yaml</em>).</li>
<li>With argument <code>-o</code> the output is in stdout.</li>
<li>With argument <code>-f</code> the output file is overwriten if exists.</li>
</ul>
</li>
<li><code>vagrantgen ai</code>: Generates a Ansible inventory file from <code>vagrant ssh-config</code> command.
<ul>
<li>With argument <code>-o</code> the output is in stdout.</li>
<li>With argument <code>-f</code> the output file is overwriten if exists.</li>
</ul>
</li>
</ul>
<h2>Another examples</h2>
<pre lang=yml>- projectname: cluster1
  provider: libvirt # libvirt or virtualbox or docker
  vms:
  - name: vm01
    box: rockylinux/8
    mem: 1024
    cpu: 2
    disks:
    - name: disk1.qcow2
      size: 10G
    net:
    - network: private_network
      ip: 192.168.122.100
    provision:
    - provisioner: ansible
      payload: "playbook.yml"
</pre>
<pre lang=yml>- projectname: cluster1
  provider: docker # libvirt or virtualbox or docker
  vms:
  - name: vm01
    box: centos-ssh
</pre>
<p>Docker provider not support net tag (ports is optional tag):</p>
<pre lang=yml>- projectname: cluster1
  provider: docker # libvirt or virtualbox or docker
  vms:
  - name: vm01
    box: centos-ssh
    ports:
      - "10023:23"
</pre>
<p>Example with provision (optional tag):</p>
<pre lang=yml>- projectname: cluster1
  provider: docker # libvirt or virtualbox or docker
  vms:
  - name: vm01
    box: centos-ssh
    provision:
    - provisioner: shell-inline # shell-inline, shell-external, ansible
      payload: "echo Hello &gt; /home/vagrant/hello; chown vagrant:vagrant /home/vagrant/hello"
</pre>
<pre lang=yml>- projectname: cluster1
  provider: docker # libvirt or virtualbox or docker
  vms:
  - name: vm01
    box: centos-ssh
    provision:
    - provisioner: ansible # shell-inline, shell-external, ansible
      payload: "playbook.yml"
</pre>
<p>Libvirt or Virtualbox providers not support ports tag:</p>
<pre lang=yml>- projectname: cluster1
  provider: virtualbox # libvirt or virtualbox or docker
  vms:
  - name: vm01
    box: centos/7
    mem: 1024
    cpu: 2
</pre>
<p>Example with network (optional tag):</p>
<pre lang=yml>- projectname: cluster1
  provider: virtualbox # libvirt or virtualbox or docker
  vms:
  - name: vm01
    box: centos/7
    mem: 1024
    cpu: 2
    disks:
    - name: disk1.vdi
      size: 20 # GBs
    net:
    - network: private_network
      ip: 192.168.122.100
    - network: public_network
      dev: br01
    - network: forwarded_port
      guest: 80
      host: 8080
      host_ip: 127.0.0.1
</pre>
<h2>Colaborate</h2>
<p>If do you want to colaborate, you can make a pull-request on <a href="https://github.com/aramcap/vagrantgen" rel=nofollow>https://github.com/aramcap/vagrantgen</a>.</p>
<h2>License</h2>
<p>GNU AFFERO GENERAL PUBLIC LICENSE version 3</p>

          </div>
        </div>

        <div id="data" data-project-tabs-target="content" class="vertical-tabs__content" role="tabpanel" aria-labelledby="mobile-data-tab" tabindex="-1">
          <h2 class="page-title">Project details</h2>
<div class="sidebar-section">
  <h3 class="sidebar-section__title">Project links</h3>
  <ul class="vertical-tabs__list">
    <li>
      <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed" href="https://github.com/aramcap/vagrantgen" rel="nofollow">
        

<i class="fas fa-home" aria-hidden="true"></i>Homepage
      </a>
    </li>
  </ul>
</div>

<div class="sidebar-section">
  <h3 class="sidebar-section__title">Statistics</h3>
  <div class="hidden github-repo-info" data-controller="github-repo-info">
GitHub statistics:    <ul class="vertical-tabs__list">
      <li>
        <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed"
           data-github-repo-info-target="stargazersUrl" rel="noopener">
          <i class="fa fa-star" aria-hidden="true"></i>
          <strong>Stars:</strong>
          <span data-github-repo-info-target="stargazersCount"></span>
        </a>
      </li>
      <li>
        <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed"
           data-github-repo-info-target="forksUrl" rel="noopener">
          <i class="fa fa-code-branch" aria-hidden="true"></i>
          <strong>Forks:</strong>
          <span data-github-repo-info-target="forksCount"></span>
        </a>
      </li>
      <li>
        <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed"
           data-github-repo-info-target="openIssuesUrl" rel="noopener">
          <i class="fa fa-exclamation-circle" aria-hidden="true"></i>
          <strong>Open issues:</strong>
          <span data-github-repo-info-target="openIssuesCount"></span>
        </a>
      </li>
      <li>
        <a class="vertical-tabs__tab vertical-tabs__tab--with-icon vertical-tabs__tab--condensed"
           data-github-repo-info-target="openPRsUrl" rel="noopener">
          <i class="fa fa-code-pull-request" aria-hidden="true"></i>
          <strong>Open PRs:</strong>
          <span data-github-repo-info-target="openPRsCount"></span>
        </a>
      </li>
    </ul>
  </div>
  <p>
View statistics for this project via <a href="https://libraries.io/pypi/vagrantgen" title="External link" target="_blank" rel="noopener">Libraries.io</a>, or by using <a href="https://packaging.python.org/guides/analyzing-pypi-package-downloads/" target="_blank" rel="noopener">our public dataset on Google BigQuery</a>  </p>
</div>

<div class="sidebar-section">
  <h3 class="sidebar-section__title">Meta</h3>
  <p><strong>License:</strong> LICENSE</p>
    <p><strong>Author:</strong> Adrian Ramos</p>
</div>

<div class="sidebar-section">
    <h3 class="sidebar-section__title">Maintainers</h3>
      <span class="sidebar-section__maintainer">
        <a href="/user/aramcap/" aria-label="aramcap">
          <span class="sidebar-section__user-gravatar">
            <img src="https://pypi-camo.freetls.fastly.net/e0c8b18e01b0efbd86b3fdfe20c7012e31d92b95/68747470733a2f2f7365637572652e67726176617461722e636f6d2f6176617461722f65313439353630663837386134343236313266356361613261333830316434313f73697a653d3530" height="50" width="50" alt="Avatar for aramcap from gravatar.com" title="Avatar for aramcap from gravatar.com">
          </span>
          <span class="sidebar-section__user-gravatar-text">
            aramcap
          </span>
        </a>
      </span>
</div>

<div class="sidebar-section">
  <h3 class="sidebar-section__title">Classifiers</h3>
  <ul class="sidebar-section__classifiers">
    <li>
      <strong>Development Status</strong>
      <ul>
        <li>
          <a href="/search/?c=Development+Status+%3A%3A+4+-+Beta">
            4 - Beta
          </a>
        </li>
      </ul>
    </li>
    <li>
      <strong>Environment</strong>
      <ul>
        <li>
          <a href="/search/?c=Environment+%3A%3A+Console">
            Console
          </a>
        </li>
      </ul>
    </li>
    <li>
      <strong>Programming Language</strong>
      <ul>
        <li>
          <a href="/search/?c=Programming+Language+%3A%3A+Python+%3A%3A+3">
            Python :: 3
          </a>
        </li>
      </ul>
    </li>
  </ul>
</div>
          <br>
        </div>

        <div id="history" data-project-tabs-target="content" class="vertical-tabs__content" role="tabpanel" aria-labelledby="history-tab mobile-history-tab" tabindex="-1">
          <h2 class="page-title split-layout">
            <span>Release history</span>
            <span class="reset-text margin-top">
              <a href="/help/#project-release-notifications">Release notifications</a> |
              <a href="/rss/project/vagrantgen/releases.xml">RSS feed <i class="fa fa-rss" aria-hidden="true"></i></a>
            </span>
          </h2>

          <div class="release-timeline">
            <div class="release release--latest release--current">
              <div class="release__meta">
                <span class="badge">This version</span>
              </div>

              <div class="release__graphic">
                <div class="release__line"></div>
                <img class="release__node" alt="" src="https://pypi.org/static/images/blue-cube.572a5bfb.svg">
              </div>

              <a class="card release__card" href="/project/vagrantgen/0.5/">
                <p class="release__version">
                  0.5
                </p>
                <p class="release__version-date">
                  <time datetime="2022-07-13T13:39:10+0000" data-controller="localized-time" data-localized-time-relative="true" data-localized-time-show-time="false">
  Jul 13, 2022
</time>
                </p>
              </a>
            </div>
            <div class="release release--oldest">
              <div class="release__meta">
              </div>

              <div class="release__graphic">
                <div class="release__line"></div>
                <img class="release__node" alt="" src="https://pypi.org/static/images/white-cube.2351a86c.svg">
              </div>

              <a class="card release__card" href="/project/vagrantgen/0.4/">
                <p class="release__version">
                  0.4
                </p>
                <p class="release__version-date">
                  <time datetime="2022-04-28T10:47:36+0000" data-controller="localized-time" data-localized-time-relative="true" data-localized-time-show-time="false">
  Apr 28, 2022
</time>
                </p>
              </a>
            </div>
          </div>
        </div>

          <div id="files" data-project-tabs-target="content" class="vertical-tabs__content" role="tabpanel" aria-labelledby="files-tab mobile-files-tab" tabindex="-1">
            <h2 class="page-title">Download files</h2>
            <p>Download the file for your platform. If you're not sure which to choose, learn more about <a href="https://packaging.python.org/tutorials/installing-packages/" title="External link" target="_blank" rel="noopener">installing packages</a>.</p>
            <h3>
Source Distributions            </h3>

              <div class="file">
                <div class="file__graphic">
                  <i class="fas fa-exclamation-circle" aria-hidden="true"></i>
                </div>

                <div class="card">
No source distribution files available for this release.See tutorial on <a href="https://packaging.python.org/tutorials/packaging-projects/#generating-distribution-archives" title="External link" target="_blank" rel="noopener">generating distribution archives</a>.                </div>
              </div>

            <h3>
Built Distribution            </h3>

                <div class="file">
      <div class="file__graphic">
        <i class="far fa-file" aria-hidden="true"></i>
      </div>

      <div class="card file__card">
        <a href="https://files.pythonhosted.org/packages/de/80/e9644434008f63f4911d76e0d9251594b2e200e407cd0f0d0c9c5c6f8b90/vagrantgen-0.5-py3-none-any.whl">
          vagrantgen-0.5-py3-none-any.whl
        </a>
        (18.5 kB
        <a href="#copy-hash-modal-1ce4ce2f-b630-46dc-81e0-3e1e1f1e6377">view hashes</a>)
        <p class="file__meta">
          Uploaded <time datetime="2022-07-13T13:39:10+0000" data-controller="localized-time" data-localized-time-relative="true" data-localized-time-show-time="false">
  Jul 13, 2022
</time>
          <code>py3</code>
        </p>
      </div>
    </div>

          </div>

<div id="copy-hash-modal-1ce4ce2f-b630-46dc-81e0-3e1e1f1e6377" class="modal modal--wide">
  <div class="modal__content" role="dialog">
    <a href="#modal-close" title="Close" class="modal__close">
      <i class="fa fa-times" aria-hidden="true"></i>
      <span class="sr-only">Close</span>
    </a>
    <div class="modal__body">
      <h3 class="modal__title">
<a href="https://pip.pypa.io/en/stable/topics/secure-installs/#hash-checking-mode" title="External link" target="_blank" rel="noopener">Hashes</a> for vagrantgen-0.5-py3-none-any.whl      </h3>
      <table class="table table--hashes">
        <caption class="sr-only">Hashes for vagrantgen-0.5-py3-none-any.whl</caption>
        <thead>
          <tr>
            <th scope="col">Algorithm</th>
            <th scope="col">Hash digest</th>
            <th></th>
          </tr>
        </thead>
        <tbody>
          <tr data-controller="clipboard">
            <th scope="row">SHA256</th>
            <td><code data-clipboard-target="source">e8100882c82c58d101aef429b2a016d0350c48bde47f614503a60bc740e61559</code></td>
            <td class="table__align-right">
              <button type="button" class="button button--small copy-tooltip copy-tooltip-w" data-action="clipboard#copy" data-clipboard-target="tooltip" data-clipboard-tooltip-value="Copy to clipboard">
Copy              </button>
            </td>
          </tr>
          <tr data-controller="clipboard">
            <th scope="row">MD5</th>
            <td><code data-clipboard-target="source">082c6f52ddeac52646d2cff894f14c9c</code></td>
            <td class="table__align-right">
              <button type="button" class="button button--small copy-tooltip copy-tooltip-w" data-action="clipboard#copy" data-clipboard-target="tooltip" data-clipboard-tooltip-value="Copy to clipboard">
Copy              </button>
            </td>
          </tr>
          <tr data-controller="clipboard">
            <th scope="row">BLAKE2b-256</th>
            <td><code data-clipboard-target="source">de80e9644434008f63f4911d76e0d9251594b2e200e407cd0f0d0c9c5c6f8b90</code></td>
            <td class="table__align-right">
              <button type="button" class="button button--small copy-tooltip copy-tooltip-w" data-action="clipboard#copy" data-clipboard-target="tooltip" data-clipboard-tooltip-value="Copy to clipboard">
Copy              </button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="modal__footer">
      <a href="#modal-close" class="button button--primary modal__action">Close</a>
    </div>
  </div>
</div>
      </div>
    </div>
  </div>
</div>
    </main>

    <footer class="footer">
      <div class="footer__logo">
        <img src="/static/images/white-cube.2351a86c.svg" alt="" class="-js-white-cube">
      </div>

      <div class="footer__menus">
        <div class="footer__menu">
          <h2>Help</h2>
          <nav aria-label="Help navigation">
            <ul>
              <li><a href="https://packaging.python.org/tutorials/installing-packages/" title="External link" target="_blank" rel="noopener">Installing packages</a></li>
              <li><a href="https://packaging.python.org/tutorials/packaging-projects/" title="External link" target="_blank" rel="noopener">Uploading packages</a></li>
              <li><a href="https://packaging.python.org/" title="External link" target="_blank" rel="noopener">User guide</a></li>
              <li><a href="https://www.python.org/dev/peps/pep-0541/" title="External link" target="_blank" rel="noopener">Project name retention</a></li>
              <li><a href="/help/">FAQs</a></li>
            </ul>
          </nav>
        </div>

        <div class="footer__menu">
          <h2>About PyPI</h2>
          <nav aria-label="About PyPI navigation">
            <ul>
              <li><a href="https://twitter.com/PyPI" title="External link" target="_blank" rel="noopener">PyPI on Twitter</a></li>
              <li><a href="https://dtdg.co/pypi" title="External link" target="_blank" rel="noopener">Infrastructure dashboard</a></li>
              <li><a href="/stats/">Statistics</a></li>
              <li><a href="/trademarks/">Logos & trademarks</a></li>
              <li><a href="/sponsors/">Our sponsors</a></li>
            </ul>
          </nav>
        </div>

        <div class="footer__menu">
          <h2>Contributing to PyPI</h2>
          <nav aria-label="How to contribute navigation">
            <ul>
              <li><a href="/help/#feedback">Bugs and feedback</a></li>
              <li><a href="https://github.com/pypi/warehouse" title="External link" target="_blank" rel="noopener">Contribute on GitHub</a></li>
              <li><a href="https://hosted.weblate.org/projects/pypa/warehouse/" title="External link" target="_blank" rel="noopener">Translate PyPI</a></li>
              <li><a href="/sponsors/">Sponsor PyPI</a></li>
              <li><a href="https://github.com/pypi/warehouse/graphs/contributors" title="External link" target="_blank" rel="noopener">Development credits</a></li>
            </ul>
          </nav>
        </div>

        <div class="footer__menu">
          <h2>Using PyPI</h2>
          <nav aria-label="Using PyPI navigation">
            <ul>
              <li><a href="https://github.com/pypa/.github/blob/main/CODE_OF_CONDUCT.md" title="External link" target="_blank" rel="noopener">Code of conduct</a></li>
              <li><a href="/security/">Report security issue</a></li>
              <li><a href="https://www.python.org/privacy/" title="External link" target="_blank" rel="noopener">Privacy policy</a></li>
              <li><a href="/policy/terms-of-use/">Terms of use</a></li>
              <li><a href="/policy/acceptable-use-policy/">Acceptable Use Policy</a></li>
            </ul>
          </nav>
        </div>
      </div>

      <hr class="footer__divider">

      <div class="footer__text">
        <p>Status:<a href="https://status.python.org/" title="External link" target="_blank" rel="noopener">
          <span data-statuspage-domain="https://2p66nmmycsj3.statuspage.io">all systems operational</span></a>
        </p>
        <p>
Developed and maintained by the Python community, for the Python community.          <br>
          <a href="https://donate.pypi.org">Donate today!</a>
        </p>
        <p>
          "PyPI", "Python Package Index", and the blocks logos are registered <a href="/trademarks/">trademarks</a> of the <a href="https://python.org/psf-landing" target="_blank" rel="noopener">Python Software Foundation</a>.<br>
        </p>
        <p>
          © 2024 <a href="https://www.python.org/psf-landing/" title="External link" target="_blank" rel="noopener">Python Software Foundation</a><br>
          <a href="/sitemap/">Site map</a>
        </p>
      </div>

      <div class="centered hide-on-desktop">
        <button type="button" class="button button--switch-to-desktop hidden" data-viewport-toggle-target="switchToDesktop" data-action="viewport-toggle#switchToDesktop">
Switch to desktop version        </button>
      </div>
    </footer>


    <div class="language-switcher">
      <form action="/locale/">
        <ul>
          <li>
            <button
              class="language-switcher__selected"
              name="locale_id" value="en" type="submit"
            >
              English
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="es" type="submit"
            >
              español
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="fr" type="submit"
            >
              français
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="ja" type="submit"
            >
              日本語
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="pt_BR" type="submit"
            >
              português (Brasil)
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="uk" type="submit"
            >
              українська
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="el" type="submit"
            >
              Ελληνικά
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="de" type="submit"
            >
              Deutsch
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="zh_Hans" type="submit"
            >
              中文 (简体)
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="zh_Hant" type="submit"
            >
              中文 (繁體)
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="ru" type="submit"
            >
              русский
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="he" type="submit"
            >
              עברית
            </button>
          </li>
          <li>
            <button
              name="locale_id" value="eo" type="submit"
            >
              esperanto
            </button>
          </li>
        </ul>
      </form>
    </div>


<div class="sponsors">
  <p class="sponsors__title">Supported by</p>
  <div class="sponsors__divider"></div>
        <a class="sponsors__sponsor" target="_blank" rel="noopener" href="https://aws.amazon.com/">
          <img class=sponsors__image src="https://pypi-camo.freetls.fastly.net/ed7074cadad1a06f56bc520ad9bd3e00d0704c5b/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f6177732d77686974652d6c6f676f2d7443615473387a432e706e67" alt=AWS loading=lazy>
          <span class="sponsors__name">AWS</span>
          <span class="sponsors__service">
            Cloud computing and Security Sponsor
          </span>
        </a>
        <a class="sponsors__sponsor" target="_blank" rel="noopener" href="https://www.datadoghq.com/">
          <img class=sponsors__image src="https://pypi-camo.freetls.fastly.net/8855f7c063a3bdb5b0ce8d91bfc50cf851cc5c51/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f64617461646f672d77686974652d6c6f676f2d6668644c4e666c6f2e706e67" alt=Datadog loading=lazy>
          <span class="sponsors__name">Datadog</span>
          <span class="sponsors__service">
            Monitoring
          </span>
        </a>
        <a class="sponsors__sponsor" target="_blank" rel="noopener" href="https://www.fastly.com/">
          <img class=sponsors__image src="https://pypi-camo.freetls.fastly.net/df6fe8829cbff2d7f668d98571df1fd011f36192/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f666173746c792d77686974652d6c6f676f2d65684d3077735f6f2e706e67" alt=Fastly loading=lazy>
          <span class="sponsors__name">Fastly</span>
          <span class="sponsors__service">
            CDN
          </span>
        </a>
        <a class="sponsors__sponsor" target="_blank" rel="noopener" href="https://careers.google.com/">
          <img class=sponsors__image src="https://pypi-camo.freetls.fastly.net/420cc8cf360bac879e24c923b2f50ba7d1314fb0/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f676f6f676c652d77686974652d6c6f676f2d616734424e3774332e706e67" alt=Google loading=lazy>
          <span class="sponsors__name">Google</span>
          <span class="sponsors__service">
            Download Analytics
          </span>
        </a>
        <a class="sponsors__sponsor" target="_blank" rel="noopener" href="https://www.python.org/psf/sponsors/#microsoft">
          <img class=sponsors__image src="https://pypi-camo.freetls.fastly.net/524d1ce72f7772294ca4c1fe05d21dec8fa3f8ea/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f6d6963726f736f66742d77686974652d6c6f676f2d5a443172685444462e706e67" alt=Microsoft loading=lazy>
          <span class="sponsors__name">Microsoft</span>
          <span class="sponsors__service">
            PSF Sponsor
          </span>
        </a>
        <a class="sponsors__sponsor" target="_blank" rel="noopener" href="https://www.pingdom.com/">
          <img class=sponsors__image src="https://pypi-camo.freetls.fastly.net/d01053c02f3a626b73ffcb06b96367fdbbf9e230/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f70696e67646f6d2d77686974652d6c6f676f2d67355831547546362e706e67" alt=Pingdom loading=lazy>
          <span class="sponsors__name">Pingdom</span>
          <span class="sponsors__service">
            Monitoring
          </span>
        </a>
        <a class="sponsors__sponsor" target="_blank" rel="noopener" href="https://getsentry.com/for/python">
          <img class=sponsors__image src="https://pypi-camo.freetls.fastly.net/67af7117035e2345bacb5a82e9aa8b5b3e70701d/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f73656e7472792d77686974652d6c6f676f2d4a2d6b64742d706e2e706e67" alt=Sentry loading=lazy>
          <span class="sponsors__name">Sentry</span>
          <span class="sponsors__service">
            Error logging
          </span>
        </a>
        <a class="sponsors__sponsor" target="_blank" rel="noopener" href="https://statuspage.io">
          <img class=sponsors__image src="https://pypi-camo.freetls.fastly.net/b611884ff90435a0575dbab7d9b0d3e60f136466/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f707970692d6173736574732f73706f6e736f726c6f676f732f737461747573706167652d77686974652d6c6f676f2d5467476c6a4a2d502e706e67" alt=StatusPage loading=lazy>
          <span class="sponsors__name">StatusPage</span>
          <span class="sponsors__service">
            Status page
          </span>
        </a>
</div>
  </body>

</html>