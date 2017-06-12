A clean Bootstrap theme that implements animation using ScrollReveal. Part of a series of projects that teaches me how to create websites with a clean UI/UX layout.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">



  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-3b630179b3ba661bed136319970519c14eae34456b7cf575d1126c208cd61d0e.css" integrity="sha256-O2MBebO6ZhvtE2MZlwUZwU6uNEVrfPV10RJsIIzWHQ4=" media="all" rel="stylesheet" />
  <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-adef29b21c28620124e601ee69f4b175d336f5fba00d9b75685d91beb2c6373d.css" integrity="sha256-re8pshwoYgEk5gHuafSxddM29fugDZt1aF2RvrLGNz0=" media="all" rel="stylesheet" />





  <meta name="viewport" content="width=device-width">

  <title>scrollreveal/README.md at master · jlmakes/scrollreveal</title>
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">


    <meta content="https://avatars3.githubusercontent.com/u/2044842?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="jlmakes/scrollreveal" property="og:title" /><meta content="https://github.com/jlmakes/scrollreveal" property="og:url" /><meta content="scrollreveal - Easy scroll animations for web and mobile browsers." property="og:description" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6MTY3MDI2MTg5OmNiNzEyMWRhOGI1OTMyY2ZmMTM1OTkwYTJjMzZkODdlYjhlNjg4NmEzYzYwMjAxZGQzMWI3Njk1MDMyMGZlZGY=--cb7ca74fafa6d0b93b7e88a540572a366aacca8d">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="CA46:6F02:39266B3:578F687:593DF56B" data-pjax-transient>


  <meta name="selected-link" value="repo_source" data-pjax-transient>

  <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="https://collector.githubapp.com/github-external/browser_event" name="octolytics-event-url" /><meta content="CA46:6F02:39266B3:578F687:593DF56B" name="octolytics-dimension-request_id" /><meta content="iad" name="octolytics-dimension-region_edge" /><meta content="iad" name="octolytics-dimension-region_render" /><meta content="22944663" name="octolytics-actor-id" /><meta content="luisdiaza" name="octolytics-actor-login" /><meta content="a0a0d7107fc469145ed722a8f6ad0cc2eae02fd621642b189cc110254618f381" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />




  <meta class="js-ga-set" name="dimension1" content="Logged In">




      <meta name="hostname" content="github.com">
  <meta name="user-login" content="luisdiaza">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="OTA0ZDg3YjlmNzVlY2ZjMGI0ZGEyZDk3NTZjZGQyMjJkNWFjNTFhNmVmOTdjZjczN2RlNmZlMjg3MjkxNjczNnx7InJlbW90ZV9hZGRyZXNzIjoiNzAuMjEuMTg3LjE5NSIsInJlcXVlc3RfaWQiOiJDQTQ2OjZGMDI6MzkyNjZCMzo1NzhGNjg3OjU5M0RGNTZCIiwidGltZXN0YW1wIjoxNDk3MjMyNzUyLCJob3N0IjoiZ2l0aHViLmNvbSJ9">


  <meta name="html-safe-nonce" content="5dfdc0fbc59eddd4d60703b711160c7db2c2d642">

  <meta http-equiv="x-pjax-version" content="379b97800ad43e21019100841c41525b">



  <meta name="description" content="scrollreveal - Easy scroll animations for web and mobile browsers.">
  <meta name="go-import" content="github.com/jlmakes/scrollreveal git https://github.com/jlmakes/scrollreveal.git">

  <meta content="2044842" name="octolytics-dimension-user_id" /><meta content="jlmakes" name="octolytics-dimension-user_login" /><meta content="15975439" name="octolytics-dimension-repository_id" /><meta content="jlmakes/scrollreveal" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="15975439" name="octolytics-dimension-repository_network_root_id" /><meta content="jlmakes/scrollreveal" name="octolytics-dimension-repository_network_root_nwo" /><meta content="false" name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" />
  <link href="https://github.com/jlmakes/scrollreveal/commits/master.atom" rel="alternate" title="Recent Commits to scrollreveal:master" type="application/atom+xml">


    <link rel="canonical" href="https://github.com/jlmakes/scrollreveal/blob/master/README.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-support" content="true">

  </head>

  <body class="logged-in env-production emoji-size-boost page-blob">




  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="bg-black text-white p-3 show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>








<div class="header" role="banner">
  <div class="container clearfix">
    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="32" version="1.1" viewBox="0 0 16 16" width="32"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jlmakes/scrollreveal/search" class="js-site-search-form" data-scoped-search-url="/jlmakes/scrollreveal/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
        <a href="/jlmakes/scrollreveal/blob/master/README.md" class="header-search-scope no-underline">This repository</a>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>


      <ul class="header-nav float-left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" aria-label="Pull requests you created" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" aria-label="Issues you created" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
            <li class="header-nav-item">
              <a href="/marketplace" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-selected-links=" /marketplace">
                Marketplace
</a>            </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>


<ul class="header-nav user-nav float-right" id="user-links">
  <li class="header-nav-item">


  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus float-left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"/></svg>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">

<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="jlmakes/scrollreveal">This repository</span>
  </div>
    <a class="dropdown-item" href="/jlmakes/scrollreveal/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/luisdiaza"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@luisdiaza" class="avatar" src="https://avatars0.githubusercontent.com/u/22944663?v=3&amp;s=40" height="20" width="20">
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">luisdiaza</strong>
        </div>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/luisdiaza" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/luisdiaza?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a>

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Jtf9A1Io0LmnCP8JbQSsmx79Bb0TOvEHR0jb2rBVB/6DuVMGLle/XMYU6RigKPLjkFjhJKB+TFofU4mmtlYLyQ==" /></div>
          <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/logout" class="sr-only right-0" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="sWIlnoLvDbGfkgZ3D+8ZuD4p8/AHgMt1hFTi3Q038RsUDIub/pBiVP6OEGbCw0fAsIwXabTEdijcT7ChCzT9LA==" /></div>
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
        Sign out
      </button>
</form>  </div>
</div>




  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>






    <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
      <div class="container repohead-details-container">

        <ul class="pagehead-actions">
  <li>
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="XU4TmQ45CMnylB5oZNqyq/43zZNyEvmFLMZBEnEdAyGzukDy/SvZ4LFMRpaYvrCM7gTPvdlYpdqOTecdJp7pNQ==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="15975439" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/jlmakes/scrollreveal/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
                <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                Watch
            </span>
          </a>
            <a class="social-count js-social-count"
              href="/jlmakes/scrollreveal/watchers"
              aria-label="372 users are watching this repository">
              372
            </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                        Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                        Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container on">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jlmakes/scrollreveal/unstar" class="starred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="s6AI9eUWpTAOBc7rm1ZcxfOGzqMpd9FqIR68iNK9Fvs/oAYspVGavbGH6X3nTbuIPf13cKfnHRw9cfGCM/+Shg==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar jlmakes/scrollreveal"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/jlmakes/scrollreveal/stargazers"
           aria-label="12479 users starred this repository">
          12,479
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jlmakes/scrollreveal/star" class="unstarred" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="DOw1NDBVzJMDBsoNlIEYWMm7Hyl+GC12fjdqGa3kJrXauOkU1CjlFDqOMtkv8gbB9V2qltrENr0Qq4cHN2mysQ==" /></div>
      <button
        type="submit"
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star jlmakes/scrollreveal"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/jlmakes/scrollreveal/stargazers"
           aria-label="12479 users starred this repository">
          12,479
        </a>
</form>  </div>

  </li>

  <li>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jlmakes/scrollreveal/fork" class="btn-with-count" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="YeGy1yvzS7S9lk7z3WbRNOjp6TrfGPiyiFNnxLo1qvkg79B+qyo0QPQLmNt7fvuq+n4VKBHHXcKK3I5vrN7Yfw==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of jlmakes/scrollreveal to your account"
                aria-label="Fork your own copy of jlmakes/scrollreveal to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
              Fork
            </button>
</form>
    <a href="/jlmakes/scrollreveal/network" class="social-count"
       aria-label="1581 users forked this repository">
      1,581
    </a>
  </li>
</ul>

        <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a href="/jlmakes" class="url fn" rel="author">jlmakes</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/jlmakes/scrollreveal" data-pjax="#js-repo-pjax-container">scrollreveal</a></strong>

</h1>

      </div>
      <div class="container">

<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/jlmakes/scrollreveal" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /jlmakes/scrollreveal" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/jlmakes/scrollreveal/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /jlmakes/scrollreveal/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">13</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/jlmakes/scrollreveal/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /jlmakes/scrollreveal/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">1</span>
      <meta itemprop="position" content="3">
</a>  </span>


    <a href="/jlmakes/scrollreveal/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /jlmakes/scrollreveal/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>

    <div class="reponav-dropdown js-menu-container">
      <button type="button" class="btn-link reponav-item reponav-dropdown js-menu-target " data-no-toggle aria-expanded="false" aria-haspopup="true">
        Insights
        <svg aria-hidden="true" class="octicon octicon-triangle-down v-align-middle text-gray" height="11" version="1.1" viewBox="0 0 12 16" width="8"><path fill-rule="evenodd" d="M0 5l6 6 6-6z"/></svg>
      </button>
      <div class="dropdown-menu-content js-menu-content">
        <div class="dropdown-menu dropdown-menu-sw">
          <a class="dropdown-item" href="/jlmakes/scrollreveal/pulse" data-skip-pjax>
            <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"/></svg>
            Pulse
          </a>
          <a class="dropdown-item" href="/jlmakes/scrollreveal/graphs" data-skip-pjax>
            <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
            Graphs
          </a>
        </div>
      </div>
    </div>
</nav>

      </div>
    </div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">








  <a href="/jlmakes/scrollreveal/blob/37d9a31efe4213b2e52739d685fa1db7bb48d12c/README.md" class="d-none js-permalink-shortcut" data-hotkey="y">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:7d9152cb7aa4588e763003bddd0d2927 -->

  <div class="file-navigation js-zeroclipboard-container">

<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"

    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/jlmakes/scrollreveal/blob/development/README.md"
               data-name="development"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                development
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/jlmakes/scrollreveal/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v4.0.0-beta.8/README.md"
              data-name="v4.0.0-beta.8"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.8">
                v4.0.0-beta.8
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v4.0.0-beta.7/README.md"
              data-name="v4.0.0-beta.7"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.7">
                v4.0.0-beta.7
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v4.0.0-beta.6/README.md"
              data-name="v4.0.0-beta.6"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.6">
                v4.0.0-beta.6
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v4.0.0-beta.5/README.md"
              data-name="v4.0.0-beta.5"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.5">
                v4.0.0-beta.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v4.0.0-beta.4/README.md"
              data-name="v4.0.0-beta.4"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.4">
                v4.0.0-beta.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v4.0.0-beta.3/README.md"
              data-name="v4.0.0-beta.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.3">
                v4.0.0-beta.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v4.0.0-beta.2/README.md"
              data-name="v4.0.0-beta.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.2">
                v4.0.0-beta.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v4.0.0-beta.1/README.md"
              data-name="v4.0.0-beta.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.1">
                v4.0.0-beta.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v4.0.0-beta.0/README.md"
              data-name="v4.0.0-beta.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v4.0.0-beta.0">
                v4.0.0-beta.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.3.5/README.md"
              data-name="v3.3.5"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.5">
                v3.3.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.3.4/README.md"
              data-name="v3.3.4"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.4">
                v3.3.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.3.3/README.md"
              data-name="v3.3.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.3">
                v3.3.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.3.2/README.md"
              data-name="v3.3.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.2">
                v3.3.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.3.1/README.md"
              data-name="v3.3.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.1">
                v3.3.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.3.0/README.md"
              data-name="v3.3.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.3.0">
                v3.3.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.2.0/README.md"
              data-name="v3.2.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.2.0">
                v3.2.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.1.5/README.md"
              data-name="v3.1.5"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.1.5">
                v3.1.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.1.4/README.md"
              data-name="v3.1.4"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.1.4">
                v3.1.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.1.3/README.md"
              data-name="v3.1.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.1.3">
                v3.1.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.1.2/README.md"
              data-name="v3.1.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.1.2">
                v3.1.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.1.1/README.md"
              data-name="v3.1.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.1.1">
                v3.1.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.1.0/README.md"
              data-name="v3.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.1.0">
                v3.1.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.9/README.md"
              data-name="v3.0.9"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.9">
                v3.0.9
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.8/README.md"
              data-name="v3.0.8"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.8">
                v3.0.8
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.7/README.md"
              data-name="v3.0.7"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.7">
                v3.0.7
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.6/README.md"
              data-name="v3.0.6"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.6">
                v3.0.6
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.5/README.md"
              data-name="v3.0.5"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.5">
                v3.0.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.4/README.md"
              data-name="v3.0.4"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.4">
                v3.0.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.3/README.md"
              data-name="v3.0.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.3">
                v3.0.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.2/README.md"
              data-name="v3.0.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.2">
                v3.0.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.1/README.md"
              data-name="v3.0.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.1">
                v3.0.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v3.0.0/README.md"
              data-name="v3.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v3.0.0">
                v3.0.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.3.2/README.md"
              data-name="v2.3.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.3.2">
                v2.3.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.3.1/README.md"
              data-name="v2.3.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.3.1">
                v2.3.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.3.0/README.md"
              data-name="v2.3.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.3.0">
                v2.3.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.2.0/README.md"
              data-name="v2.2.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.2.0">
                v2.2.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.1.0/README.md"
              data-name="v2.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.1.0">
                v2.1.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.0.5/README.md"
              data-name="v2.0.5"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.5">
                v2.0.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.0.4/README.md"
              data-name="v2.0.4"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.4">
                v2.0.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.0.3/README.md"
              data-name="v2.0.3"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.3">
                v2.0.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.0.2/README.md"
              data-name="v2.0.2"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.2">
                v2.0.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.0.1/README.md"
              data-name="v2.0.1"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.1">
                v2.0.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/jlmakes/scrollreveal/tree/v2.0.0/README.md"
              data-name="v2.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target" title="v2.0.0">
                v2.0.0
              </span>
            </a>
        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/jlmakes/scrollreveal/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm BtnGroup-item tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
    </div>
    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/jlmakes/scrollreveal"><span>scrollreveal</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
    </div>
  </div>



  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/jlmakes/scrollreveal/commit/37d9a31efe4213b2e52739d685fa1db7bb48d12c" data-pjax>
          37d9a31
        </a>
        <relative-time datetime="2017-04-05T14:08:06Z">Apr 5, 2017</relative-time>
      </span>
      <div>
        <img alt="@jlmakes" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/2044842?v=3&amp;s=40" width="20" />
        <a href="/jlmakes" class="user-mention" rel="author">jlmakes</a>
          <a href="/jlmakes/scrollreveal/commit/37d9a31efe4213b2e52739d685fa1db7bb48d12c" class="message" data-pjax="true" title="ScrollReveal v3.3.5">ScrollReveal v3.3.5</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>1</strong>
         contributor
      </button>

    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@jlmakes" height="24" src="https://avatars2.githubusercontent.com/u/2044842?v=3&amp;s=48" width="24" />
            <a href="/jlmakes">jlmakes</a>
          </li>
      </ul>
    </div>
  </div>

  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a href="/jlmakes/scrollreveal/raw/master/README.md" class="btn btn-sm BtnGroup-item" id="raw-url">Raw</a>
        <a href="/jlmakes/scrollreveal/blame/master/README.md" class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b">Blame</a>
      <a href="/jlmakes/scrollreveal/commits/master/README.md" class="btn btn-sm BtnGroup-item" rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="https://desktop.github.com"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:mac">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
        </a>

        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jlmakes/scrollreveal/edit/master/README.md" class="inline-form js-update-url-with-hash" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Aq6K+moNmsHtDs5EHD+6GJivQStxqIYT0PWKESXZb9fS2tX7q/jnIAPkE9VtvmnKygOYRFCRjCdsOQ3VTSEf2A==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Edit the file in your fork of this project" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
          </button>
</form>        <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="/jlmakes/scrollreveal/delete/master/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Yl02o2RNGbMqdjbqOxY6VHymJpoqPTp2QpxcW+MyGko0LyAcH1Q7YIxzXtkqiHAwvwekBh7v+32UAGB77F4O+Q==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Delete the file in your fork of this project" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
</form>  </div>

  <div class="file-info">
      414 lines (300 sloc)
      <span class="file-info-divider"></span>
    12.1 KB
  </div>
</div>


  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><p><a href="https://scrollrevealjs.org"><img src="https://camo.githubusercontent.com/bcba2683fa4ffc9961ff5e350c14a8d433f2df8a/68747470733a2f2f7363726f6c6c72657665616c6a732e6f72672f6173736574732f7363726f6c6c72657665616c2d7265706f2d6865616465722e706e67" alt="ScrollReveal — Easy scroll animations for web and mobile browsers." data-canonical-src="https://scrollrevealjs.org/assets/scrollreveal-repo-header.png" style="max-width:100%;"></a></p>
<p><a href="https://scrollrevealjs.org"><img src="https://camo.githubusercontent.com/2541acda98c5f3555cfc765e24f3845cb714a77e/68747470733a2f2f7363726f6c6c72657665616c6a732e6f72672f6173736574732f7363726f6c6c72657665616c2d64656d6f2e706e67" alt="ScrollReveal Demo" data-canonical-src="https://scrollrevealjs.org/assets/scrollreveal-demo.png" style="max-width:100%;"></a></p>
<hr>
<p><a href="https://github.com/jlmakes/scrollreveal.js/blob/master/LICENSE.md"><img src="https://camo.githubusercontent.com/0d26b531e3752dd7fd705963ff7f16bb16a76267/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d3132383363332e737667" alt="License" data-canonical-src="https://img.shields.io/badge/license-MIT-1283c3.svg" style="max-width:100%;"></a>
<a href="https://npmjs.org/package/scrollreveal"><img src="https://camo.githubusercontent.com/a9af335e0af95dd4bf41e19296bbfc92359cefd9/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f7363726f6c6c72657665616c2e7376673f7374796c653d666c6174" alt="NPM version" data-canonical-src="https://img.shields.io/npm/v/scrollreveal.svg?style=flat" style="max-width:100%;"></a>
<a href="https://npmjs.org/package/scrollreveal"><img src="https://camo.githubusercontent.com/b8b5bc73f707792ef03cec562c41284a88f959c0/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f646d2f7363726f6c6c72657665616c2e7376673f7374796c653d666c6174" alt="NPM downloads" data-canonical-src="https://img.shields.io/npm/dm/scrollreveal.svg?style=flat" style="max-width:100%;"></a></p>
<ul>
<li>3.3KB minified and Gzipped</li>
<li>No dependencies</li>
<li>From the <a href="https://camo.githubusercontent.com/3fb3047c452fd259059a0f7fc1921e8fe82e1bbd/687474703a2f2f692e696d6775722e636f6d2f6f584a6d64747a2e676966" target="_blank"><img src="https://camo.githubusercontent.com/3fb3047c452fd259059a0f7fc1921e8fe82e1bbd/687474703a2f2f692e696d6775722e636f6d2f6f584a6d64747a2e676966" alt="heart" data-canonical-src="http://i.imgur.com/oXJmdtz.gif" style="max-width:100%;"></a> of <a href="https://twitter.com/jlmakes">@jlmakes</a></li>
</ul>
<hr>
<h2><a id="user-content-1-getting-started" class="anchor" href="#1-getting-started" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1. Getting Started</h2>
<h4><a id="user-content-11-installation" class="anchor" href="#11-installation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.1. Installation</h4>
<p>The simplest method is to copy paste this snippet just before your closing <code>&lt;/body&gt;</code> tag.</p>
<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>https://unpkg.com/scrollreveal/dist/scrollreveal.min.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;</pre></div>
<p>But you can also:</p>
<ul>
<li><a href="https://github.com/jlmakes/scrollreveal.js/archive/master.zip">Download ZIP</a></li>
<li><code>npm install scrollreveal</code></li>
<li><code>bower install scrollreveal</code></li>
</ul>
<h4><a id="user-content-12-the-basics" class="anchor" href="#12-the-basics" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>1.2. The Basics</h4>
<p>The <code>reveal()</code> method is the primary API, and makes it easy to create and manage various types of animations.</p>
<div class="highlight highlight-text-html-basic"><pre><span class="pl-c"><span class="pl-c">&lt;!--</span> HTML <span class="pl-c">--&gt;</span></span>
&lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
&lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>bar<span class="pl-pds">"</span></span>&gt; Bar &lt;/<span class="pl-ent">div</span>&gt;</pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> JavaScript</span>
<span class="pl-c1">window</span>.<span class="pl-smi">sr</span> <span class="pl-k">=</span> <span class="pl-en">ScrollReveal</span>();
<span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.foo<span class="pl-pds">'</span></span>);
<span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.bar<span class="pl-pds">'</span></span>);</pre></div>
<h2><a id="user-content-2-configuration" class="anchor" href="#2-configuration" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2. Configuration</h2>
<p>Passing a configuration object to <code>ScrollReveal()</code> changes the defaults for all reveals, and passing <code>reveal()</code> a configuration object customizes that reveal set further.</p>
<h4><a id="user-content-21-practical-example" class="anchor" href="#21-practical-example" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.1. Practical Example</h4>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> Changing the defaults</span>
<span class="pl-c1">window</span>.<span class="pl-smi">sr</span> <span class="pl-k">=</span> <span class="pl-en">ScrollReveal</span>({ reset<span class="pl-k">:</span> <span class="pl-c1">true</span> });

<span class="pl-c"><span class="pl-c">//</span> Customizing a reveal set</span>
<span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.foo<span class="pl-pds">'</span></span>, { duration<span class="pl-k">:</span> <span class="pl-c1">200</span> });</pre></div>
<h4><a id="user-content-22-the-starting-defaults" class="anchor" href="#22-the-starting-defaults" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>2.2. The Starting Defaults</h4>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> 'bottom', 'left', 'top', 'right'</span>
origin<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>bottom<span class="pl-pds">'</span></span>,

<span class="pl-c"><span class="pl-c">//</span> Can be any valid CSS distance, e.g. '5rem', '10%', '20vw', etc.</span>
distance<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>20px<span class="pl-pds">'</span></span>,

<span class="pl-c"><span class="pl-c">//</span> Time in milliseconds.</span>
duration<span class="pl-k">:</span> <span class="pl-c1">500</span>,
delay<span class="pl-k">:</span> <span class="pl-c1">0</span>,

<span class="pl-c"><span class="pl-c">//</span> Starting angles in degrees, will transition from these values to 0 in all axes.</span>
rotate<span class="pl-k">:</span> { x<span class="pl-k">:</span> <span class="pl-c1">0</span>, y<span class="pl-k">:</span> <span class="pl-c1">0</span>, z<span class="pl-k">:</span> <span class="pl-c1">0</span> },

<span class="pl-c"><span class="pl-c">//</span> Starting opacity value, before transitioning to the computed opacity.</span>
opacity<span class="pl-k">:</span> <span class="pl-c1">0</span>,

<span class="pl-c"><span class="pl-c">//</span> Starting scale value, will transition from this value to 1</span>
scale<span class="pl-k">:</span> <span class="pl-c1">0.9</span>,

<span class="pl-c"><span class="pl-c">//</span> Accepts any valid CSS easing, e.g. 'ease', 'ease-in-out', 'linear', etc.</span>
easing<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>cubic-bezier(0.6, 0.2, 0.1, 1)<span class="pl-pds">'</span></span>,

<span class="pl-c"><span class="pl-c">//</span> `&lt;html&gt;` is the default reveal container. You can pass either:</span>
<span class="pl-c"><span class="pl-c">//</span> DOM Node, e.g. document.querySelector('.fooContainer')</span>
<span class="pl-c"><span class="pl-c">//</span> Selector, e.g. '.fooContainer'</span>
container<span class="pl-k">:</span> <span class="pl-c1">window</span>.<span class="pl-smi">document</span>.<span class="pl-c1">documentElement</span>,

<span class="pl-c"><span class="pl-c">//</span> true/false to control reveal animations on mobile.</span>
mobile<span class="pl-k">:</span> <span class="pl-c1">true</span>,

<span class="pl-c"><span class="pl-c">//</span> true:  reveals occur every time elements become visible</span>
<span class="pl-c"><span class="pl-c">//</span> false: reveals occur once as elements become visible</span>
reset<span class="pl-k">:</span> <span class="pl-c1">false</span>,

<span class="pl-c"><span class="pl-c">//</span> 'always' — delay for all reveal animations</span>
<span class="pl-c"><span class="pl-c">//</span> 'once'   — delay only the first time reveals occur</span>
<span class="pl-c"><span class="pl-c">//</span> 'onload' - delay only for animations triggered by first load</span>
useDelay<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>always<span class="pl-pds">'</span></span>,

<span class="pl-c"><span class="pl-c">//</span> Change when an element is considered in the viewport. The default value</span>
<span class="pl-c"><span class="pl-c">//</span> of 0.20 means 20% of an element must be visible for its reveal to occur.</span>
viewFactor<span class="pl-k">:</span> <span class="pl-c1">0.2</span>,

<span class="pl-c"><span class="pl-c">//</span> Pixel values that alter the container boundaries.</span>
<span class="pl-c"><span class="pl-c">//</span> e.g. Set `{ top: 48 }`, if you have a 48px tall fixed toolbar.</span>
<span class="pl-c"><span class="pl-c">//</span> --</span>
<span class="pl-c"><span class="pl-c">//</span> Visual Aid: https://scrollrevealjs.org/assets/viewoffset.png</span>
viewOffset<span class="pl-k">:</span> { top<span class="pl-k">:</span> <span class="pl-c1">0</span>, right<span class="pl-k">:</span> <span class="pl-c1">0</span>, bottom<span class="pl-k">:</span> <span class="pl-c1">0</span>, left<span class="pl-k">:</span> <span class="pl-c1">0</span> },

<span class="pl-c"><span class="pl-c">//</span> Callbacks that fire for each triggered element reveal, and reset.</span>
<span class="pl-en">beforeReveal</span><span class="pl-k">:</span> <span class="pl-k">function</span> (<span class="pl-smi">domEl</span>) {},
<span class="pl-en">beforeReset</span><span class="pl-k">:</span> <span class="pl-k">function</span> (<span class="pl-smi">domEl</span>) {},

<span class="pl-c"><span class="pl-c">//</span> Callbacks that fire for each completed element reveal, and reset.</span>
<span class="pl-en">afterReveal</span><span class="pl-k">:</span> <span class="pl-k">function</span> (<span class="pl-smi">domEl</span>) {},
<span class="pl-en">afterReset</span><span class="pl-k">:</span> <span class="pl-k">function</span> (<span class="pl-smi">domEl</span>) {}</pre></div>
<h2><a id="user-content-3-advanced" class="anchor" href="#3-advanced" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3. Advanced</h2>
<h4><a id="user-content-31-sequenced-animations" class="anchor" href="#31-sequenced-animations" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.1. Sequenced Animations</h4>
<p>You can pass a sequence interval (in milliseconds) to the <code>reveal()</code> method, making sequenced animations a breeze.</p>
<blockquote>
<p><strong>Note:</strong> The interval is the time until the next element in the sequence begins its reveal, which is separate from the time until the element’s animation completes. In this example, the animation duration is 2 seconds, but the sequence interval is 50 milliseconds.</p>
</blockquote>
<div class="highlight highlight-source-js"><pre><span class="pl-c"><span class="pl-c">//</span> interval passed to reveal</span>
<span class="pl-c1">window</span>.<span class="pl-smi">sr</span> <span class="pl-k">=</span> <span class="pl-en">ScrollReveal</span>({ duration<span class="pl-k">:</span> <span class="pl-c1">2000</span> });
<span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.box<span class="pl-pds">'</span></span>, <span class="pl-c1">50</span>);

<span class="pl-c"><span class="pl-c">//</span> or...</span>

<span class="pl-c"><span class="pl-c">//</span> interval and custom config passed to reveal</span>
<span class="pl-c1">window</span>.<span class="pl-smi">sr</span> <span class="pl-k">=</span> <span class="pl-en">ScrollReveal</span>();
<span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.box<span class="pl-pds">'</span></span>, { duration<span class="pl-k">:</span> <span class="pl-c1">2000</span> }, <span class="pl-c1">50</span>);</pre></div>
<p><a href="https://cloud.githubusercontent.com/assets/2044842/13556788/a7dda6c6-e3e2-11e5-93fa-d6a227cbb5dc.gif" target="_blank"><img src="https://cloud.githubusercontent.com/assets/2044842/13556788/a7dda6c6-e3e2-11e5-93fa-d6a227cbb5dc.gif" alt="sequencer" style="max-width:100%;"></a></p>
<h4><a id="user-content-32-working-with-dom-nodes" class="anchor" href="#32-working-with-dom-nodes" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.2. Working With DOM Nodes</h4>
<p>You are not just limited to using selectors with <code>reveal()</code>, it also accepts a Node or Node List as the first argument.</p>
<div class="highlight highlight-source-js"><pre><span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-c1">document</span>.<span class="pl-c1">getElementById</span>(<span class="pl-s"><span class="pl-pds">'</span>foo<span class="pl-pds">'</span></span>));
<span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-c1">document</span>.<span class="pl-c1">querySelectorAll</span>(<span class="pl-s"><span class="pl-pds">'</span>.bar<span class="pl-pds">'</span></span>));</pre></div>
<h4><a id="user-content-33-custommultiple-containers" class="anchor" href="#33-custommultiple-containers" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.3. Custom/Multiple Containers</h4>
<p>The default container is the viewport, but you can assign any container to any reveal set.</p>
<blockquote>
<p><strong>Tip:</strong> ScrollReveal works just as well with horizontally scrolling containers too!</p>
</blockquote>
<div class="highlight highlight-text-html-basic"><pre>&lt;<span class="pl-ent">div</span> <span class="pl-e">id</span>=<span class="pl-s"><span class="pl-pds">"</span>fooContainer<span class="pl-pds">"</span></span>&gt;
  &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt; Foo 1 &lt;/<span class="pl-ent">div</span>&gt;
  &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt; Foo 2 &lt;/<span class="pl-ent">div</span>&gt;
  &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt; Foo 3 &lt;/<span class="pl-ent">div</span>&gt;
&lt;/<span class="pl-ent">div</span>&gt;

&lt;<span class="pl-ent">div</span> <span class="pl-e">id</span>=<span class="pl-s"><span class="pl-pds">"</span>barContainer<span class="pl-pds">"</span></span>&gt;
  &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>bar<span class="pl-pds">"</span></span>&gt; Bar 1 &lt;/<span class="pl-ent">div</span>&gt;
  &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>bar<span class="pl-pds">"</span></span>&gt; Bar 2 &lt;/<span class="pl-ent">div</span>&gt;
  &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>bar<span class="pl-pds">"</span></span>&gt; Bar 3 &lt;/<span class="pl-ent">div</span>&gt;
&lt;/<span class="pl-ent">div</span>&gt;</pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-c1">window</span>.<span class="pl-smi">sr</span> <span class="pl-k">=</span> <span class="pl-en">ScrollReveal</span>();

<span class="pl-c"><span class="pl-c">//</span> as a DOM node...</span>
<span class="pl-k">var</span> fooContainer <span class="pl-k">=</span> <span class="pl-c1">document</span>.<span class="pl-c1">getElementById</span>(<span class="pl-s"><span class="pl-pds">'</span>fooContainer<span class="pl-pds">'</span></span>);
<span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.foo<span class="pl-pds">'</span></span>, { container<span class="pl-k">:</span> fooContainer });

<span class="pl-c"><span class="pl-c">//</span> as a selector...</span>
<span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.bar<span class="pl-pds">'</span></span>, { container<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>#barContainer<span class="pl-pds">'</span></span> });</pre></div>
<h4><a id="user-content-34-asynchronous-content" class="anchor" href="#34-asynchronous-content" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>3.4. Asynchronous Content</h4>
<p>The <code>sync()</code> method updates asynchronously loaded content with any existing reveal sets.</p>
<p><em>Example:</em></p>
<div class="highlight highlight-text-html-basic"><pre><span class="pl-c"><span class="pl-c">&lt;!--</span> index.html <span class="pl-c">--&gt;</span></span>
&lt;<span class="pl-ent">div</span> <span class="pl-e">id</span>=<span class="pl-s"><span class="pl-pds">"</span>fooContainer<span class="pl-pds">"</span></span>&gt;
  &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt;foo&lt;/<span class="pl-ent">div</span>&gt;
  &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt;foo&lt;/<span class="pl-ent">div</span>&gt;
  &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt;foo&lt;/<span class="pl-ent">div</span>&gt;
&lt;/<span class="pl-ent">div</span>&gt;

<span class="pl-c"><span class="pl-c">&lt;!--</span> ajax.html <span class="pl-c">--&gt;</span></span>
&lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt;foo async&lt;/<span class="pl-ent">div</span>&gt;
&lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt;foo async&lt;/<span class="pl-ent">div</span>&gt;
&lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>foo<span class="pl-pds">"</span></span>&gt;foo async&lt;/<span class="pl-ent">div</span>&gt;</pre></div>
<div class="highlight highlight-source-js"><pre><span class="pl-k">var</span> fooContainer, content, sr, xmlhttp;

fooContainer <span class="pl-k">=</span> <span class="pl-c1">document</span>.<span class="pl-c1">getElementById</span>(<span class="pl-s"><span class="pl-pds">'</span>fooContainer<span class="pl-pds">'</span></span>);

sr <span class="pl-k">=</span> <span class="pl-en">ScrollReveal</span>();
<span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.foo<span class="pl-pds">'</span></span>, { container<span class="pl-k">:</span> fooContainer });

<span class="pl-c"><span class="pl-c">//</span> Setup a new asynchronous request...</span>
xmlhttp <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">XMLHttpRequest</span>();
<span class="pl-smi">xmlhttp</span>.<span class="pl-en">onreadystatechange</span> <span class="pl-k">=</span> <span class="pl-k">function</span>() {
  <span class="pl-k">if</span> (<span class="pl-smi">xmlhttp</span>.<span class="pl-c1">readyState</span> <span class="pl-k">==</span> <span class="pl-c1">XMLHttpRequest</span>.<span class="pl-c1">DONE</span>) {
    <span class="pl-k">if</span> (<span class="pl-smi">xmlhttp</span>.<span class="pl-c1">status</span> <span class="pl-k">==</span> <span class="pl-c1">200</span>) {

      <span class="pl-c"><span class="pl-c">//</span> Turn our response into HTML...</span>
      <span class="pl-k">var</span> content <span class="pl-k">=</span> <span class="pl-c1">document</span>.<span class="pl-c1">createElement</span>(<span class="pl-s"><span class="pl-pds">'</span>div<span class="pl-pds">'</span></span>);
      <span class="pl-smi">content</span>.<span class="pl-smi">innerHTML</span> <span class="pl-k">=</span> <span class="pl-smi">xmlhttp</span>.<span class="pl-c1">responseText</span>;
      content <span class="pl-k">=</span> <span class="pl-smi">content</span>.<span class="pl-c1">childNodes</span>;

      <span class="pl-c"><span class="pl-c">//</span> Add each element to the DOM...</span>
      <span class="pl-k">for</span> (<span class="pl-k">var</span> i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> <span class="pl-smi">content</span>.<span class="pl-c1">length</span>; i<span class="pl-k">++</span>) {
        <span class="pl-smi">fooContainer</span>.<span class="pl-c1">appendChild</span>(content[ i ]);
      };

      <span class="pl-c"><span class="pl-c">//</span> Finally!</span>
      <span class="pl-smi">sr</span>.<span class="pl-en">sync</span>();
    }
  }
}

<span class="pl-smi">xmlhttp</span>.<span class="pl-c1">open</span>(<span class="pl-s"><span class="pl-pds">'</span>GET<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>ajax.html<span class="pl-pds">'</span></span>, <span class="pl-c1">true</span>);
<span class="pl-smi">xmlhttp</span>.<span class="pl-c1">send</span>();</pre></div>
<h2><a id="user-content-4-tips" class="anchor" href="#4-tips" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4. Tips</h2>
<h4><a id="user-content-41-order-matters" class="anchor" href="#41-order-matters" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.1. Order Matters</h4>
<p>It’s important that <code>reveal()</code> calls be made as close to last in your page as possible, so that:</p>
<ul>
<li>Elements on the page have loaded</li>
<li>Any other 3rd party libraries have had a chance to run</li>
<li>Any other styles added to your elements wont be overwritten</li>
</ul>
<p><em>Example:</em></p>
<div class="highlight highlight-text-html-basic"><pre>&lt;!DOCTYPE html&gt;
&lt;<span class="pl-ent">html</span>&gt;
  &lt;<span class="pl-ent">head</span>&gt;
    <span class="pl-c"><span class="pl-c">&lt;!--</span> load and instantiate ScrollReveal first <span class="pl-c">--&gt;</span></span>
    &lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>js/scrollreveal.min.js<span class="pl-pds">"</span></span>&gt;<span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;
    &lt;<span class="pl-ent">script</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-c1">window</span>.<span class="pl-smi">sr</span> <span class="pl-k">=</span> <span class="pl-en">ScrollReveal</span>();</span>
<span class="pl-s1">    </span><span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;
  &lt;/<span class="pl-ent">head</span>&gt;
  &lt;<span class="pl-ent">body</span>&gt;

    &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooContainer<span class="pl-pds">"</span></span>&gt;
      &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooReveal<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
      &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooReveal<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
      &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooReveal<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
    &lt;/<span class="pl-ent">div</span>&gt;

    <span class="pl-c"><span class="pl-c">&lt;!--</span> make reveal calls last <span class="pl-c">--&gt;</span></span>
    &lt;<span class="pl-ent">script</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.fooReveal<span class="pl-pds">'</span></span>, { container<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>.fooContainer<span class="pl-pds">'</span></span> });</span>
<span class="pl-s1">    </span><span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;

  &lt;/<span class="pl-ent">body</span>&gt;
&lt;/<span class="pl-ent">html</span>&gt;</pre></div>
<h4><a id="user-content-42-improve-user-experience" class="anchor" href="#42-improve-user-experience" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.2. Improve User Experience</h4>
<p>In most cases, your elements will start at <code>opacity: 0</code> so they can fade in. However, since JavaScript loads after the page begins rendering, you might see your elements flickering as they begin rendering before being hidden by ScrollReveal's JavaScript.</p>
<p>The ideal solution is to <strong>set your reveal elements visibility to hidden</strong> in the <code>&lt;head&gt;</code> of your page, to ensure they render hidden while your JavaScript loads:</p>
<p><em>Continuing our example from 4.1.</em></p>
<div class="highlight highlight-text-html-basic"><pre>&lt;!DOCTYPE html&gt;
&lt;<span class="pl-ent">html</span>&gt;
  &lt;<span class="pl-ent">head</span>&gt;
    <span class="pl-c"><span class="pl-c">&lt;!--</span> load and instantiate ScrollReveal first <span class="pl-c">--&gt;</span></span>
    &lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>js/scrollreveal.min.js<span class="pl-pds">"</span></span>&gt;<span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;
    &lt;<span class="pl-ent">script</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-c1">window</span>.<span class="pl-smi">sr</span> <span class="pl-k">=</span> <span class="pl-en">ScrollReveal</span>();</span>
<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-c"><span class="pl-c">//</span> Add class to &lt;html&gt; if ScrollReveal is supported</span></span>
<span class="pl-s1">      <span class="pl-c"><span class="pl-c">//</span> Note: this method is deprecated, and only works in version 3</span></span>
<span class="pl-s1">      <span class="pl-k">if</span> (<span class="pl-smi">sr</span>.<span class="pl-en">isSupported</span>()) {</span>
<span class="pl-s1">        <span class="pl-c1">document</span>.<span class="pl-c1">documentElement</span>.<span class="pl-smi">classList</span>.<span class="pl-c1">add</span>(<span class="pl-s"><span class="pl-pds">'</span>sr<span class="pl-pds">'</span></span>);</span>
<span class="pl-s1">      }</span>
<span class="pl-s1"></span>
<span class="pl-s1">    </span><span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;

    &lt;<span class="pl-ent">style</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-c"><span class="pl-c">/*</span> Ensure elements load hidden before ScrollReveal runs <span class="pl-c">*/</span></span></span>
<span class="pl-s1">      <span class="pl-e">.sr</span> <span class="pl-e">.fooReveal</span> { <span class="pl-c1"><span class="pl-c1">visibility</span></span>: <span class="pl-c1">hidden</span>; }</span>
<span class="pl-s1"></span>
<span class="pl-s1">    </span><span class="pl-s1">&lt;</span>/<span class="pl-ent">style</span>&gt;

  &lt;/<span class="pl-ent">head</span>&gt;
  &lt;<span class="pl-ent">body</span>&gt;

    &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooContainer<span class="pl-pds">"</span></span>&gt;
      &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooReveal<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
      &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooReveal<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
      &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooReveal<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
    &lt;/<span class="pl-ent">div</span>&gt;

    <span class="pl-c"><span class="pl-c">&lt;!--</span> make reveal calls last <span class="pl-c">--&gt;</span></span>
    &lt;<span class="pl-ent">script</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.fooReveal<span class="pl-pds">'</span></span>, { container<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>.fooContainer<span class="pl-pds">'</span></span> });</span>
<span class="pl-s1">    </span><span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;

  &lt;/<span class="pl-ent">body</span>&gt;
&lt;/<span class="pl-ent">html</span>&gt;</pre></div>
<blockquote>
<p><strong>Note:</strong> If you prefer not to put styles in the <code>&lt;head&gt;</code> of your page, including this style in your primary stylesheet will still help with element flickering since your CSS will likely load before your JavaScript.</p>
</blockquote>
<h4><a id="user-content-43-add-perspective-to-3d-rotation" class="anchor" href="#43-add-perspective-to-3d-rotation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>4.3. Add Perspective to 3D Rotation</h4>
<p>ScrollReveal supports 3d rotation out of the box, but you may want to emphasize the effect by specifying a perspective property on your container.</p>
<p><em>Continuing our example from 4.2.</em></p>
<div class="highlight highlight-text-html-basic"><pre>&lt;!DOCTYPE html&gt;
&lt;<span class="pl-ent">html</span>&gt;
  &lt;<span class="pl-ent">head</span>&gt;
    <span class="pl-c"><span class="pl-c">&lt;!--</span> load and instantiate ScrollReveal first <span class="pl-c">--&gt;</span></span>
    &lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>js/scrollreveal.min.js<span class="pl-pds">"</span></span>&gt;<span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;
    &lt;<span class="pl-ent">script</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-c1">window</span>.<span class="pl-smi">sr</span> <span class="pl-k">=</span> <span class="pl-en">ScrollReveal</span>();</span>
<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-c"><span class="pl-c">//</span> Add class to &lt;html&gt; if ScrollReveal is supported</span></span>
<span class="pl-s1">      <span class="pl-c"><span class="pl-c">//</span> Note: this method is deprecated, and only works in version 3</span></span>
<span class="pl-s1">      <span class="pl-k">if</span> (<span class="pl-smi">sr</span>.<span class="pl-en">isSupported</span>()) {</span>
<span class="pl-s1">        <span class="pl-c1">document</span>.<span class="pl-c1">documentElement</span>.<span class="pl-smi">classList</span>.<span class="pl-c1">add</span>(<span class="pl-s"><span class="pl-pds">'</span>sr<span class="pl-pds">'</span></span>);</span>
<span class="pl-s1">      }</span>
<span class="pl-s1"></span>
<span class="pl-s1">    </span><span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;

    &lt;<span class="pl-ent">style</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-c"><span class="pl-c">/*</span> Ensure elements load hidden before ScrollReveal runs <span class="pl-c">*/</span></span></span>
<span class="pl-s1">      <span class="pl-e">.sr</span> <span class="pl-e">.fooReveal</span> { <span class="pl-c1"><span class="pl-c1">visibility</span></span>: <span class="pl-c1">hidden</span>; }</span>
<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-c"><span class="pl-c">/*</span> add perspective to your container <span class="pl-c">*/</span></span></span>
<span class="pl-s1">      <span class="pl-e">.fooContainer</span> { <span class="pl-c1"><span class="pl-c1">perspective</span></span>: <span class="pl-c1">800<span class="pl-k">px</span></span>; }</span>
<span class="pl-s1"></span>
<span class="pl-s1">    </span><span class="pl-s1">&lt;</span>/<span class="pl-ent">style</span>&gt;

  &lt;/<span class="pl-ent">head</span>&gt;
  &lt;<span class="pl-ent">body</span>&gt;

    &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooContainer<span class="pl-pds">"</span></span>&gt;
      &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooReveal<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
      &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooReveal<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
      &lt;<span class="pl-ent">div</span> <span class="pl-e">class</span>=<span class="pl-s"><span class="pl-pds">"</span>fooReveal<span class="pl-pds">"</span></span>&gt; Foo &lt;/<span class="pl-ent">div</span>&gt;
    &lt;/<span class="pl-ent">div</span>&gt;

  <span class="pl-c"><span class="pl-c">&lt;!--</span> make reveal calls last <span class="pl-c">--&gt;</span></span>
    &lt;<span class="pl-ent">script</span>&gt;<span class="pl-s1"></span>
<span class="pl-s1">      <span class="pl-c"><span class="pl-c">//</span> use rotation in reveal configuration</span></span>
<span class="pl-s1">      <span class="pl-smi">sr</span>.<span class="pl-en">reveal</span>(<span class="pl-s"><span class="pl-pds">'</span>.fooReveal<span class="pl-pds">'</span></span>, { container<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>.fooContainer<span class="pl-pds">'</span></span>, rotate<span class="pl-k">:</span> {x<span class="pl-k">:</span> <span class="pl-c1">65</span>} });</span>
<span class="pl-s1">    </span><span class="pl-s1">&lt;</span>/<span class="pl-ent">script</span>&gt;

  &lt;/<span class="pl-ent">body</span>&gt;
&lt;/<span class="pl-ent">html</span>&gt;</pre></div>
<h2><a id="user-content-5-appendix" class="anchor" href="#5-appendix" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5. Appendix</h2>
<p>Open source under the <a href="https://github.com/jlmakes/scrollreveal.js/blob/master/LICENSE.md">MIT License</a>. ©2014–2016 Julian Lloyd.</p>
<h4><a id="user-content-51-browser-compatibility" class="anchor" href="#51-browser-compatibility" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5.1. Browser Compatibility</h4>
<p>ScrollReveal works on any JavaScript enabled browser that supports both <a href="http://caniuse.com/#search=transform">CSS Transform</a> and <a href="http://caniuse.com/#search=transitions">CSS Transition</a>. This includes Internet Explorer 10+, and most modern desktop and mobile browsers.</p>
<h4><a id="user-content-52-issues-and-reporting-bugs" class="anchor" href="#52-issues-and-reporting-bugs" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5.2. Issues and Reporting Bugs</h4>
<p><strong>Please search existing issues, before creating a new one;</strong> every issue is labeled and attended carefully. If you open a duplicate issue, it will be closed immediately.</p>
<p>If you cannot find your issue/bug in a previous ticket, please include details such as your browser, any other 3rd party JavaScript libraries you are using, and ideally a code sample demonstrating the problem. (Try <a href="http://jsbin.com/nuqapopefo/1/edit?html,output">JSBin</a>)</p>
<h4><a id="user-content-53-pull-requests" class="anchor" href="#53-pull-requests" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5.3. Pull Requests</h4>
<p>Feeling inspired? Please contribute! Optimizations, compatibility and bug fixes are greatly preferred over new features, but don’t be shy. One thing sorely missing from ScrollReveal right now is a test suite.</p>
<h4><a id="user-content-54-showcase" class="anchor" href="#54-showcase" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5.4. Showcase</h4>
<p>Here are some cool sites using ScrollReveal:</p>
<ul>
<li><a href="https://www.sequoiacap.com">Sequoia Capital</a></li>
<li><a href="http://petravic.us/">Andrius Petravic</a></li>
<li><a href="http://www.ispg.co/">ISPG Co.</a></li>
<li><a href="https://www.whiterabbitexpress.com/">White Rabit Express</a></li>
</ul>
<p>Want to see your page here? Please send me your work (or of others) using ScrollReveal on Twitter (<a href="https://twitter.com/jlmakes">@jlmakes</a>)</p>
<h4><a id="user-content-55-special-thanks" class="anchor" href="#55-special-thanks" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>5.5. Special Thanks</h4>
<p>ScrollReveal was inspired by the talented <a href="https://twitter.com/crnacura">Manoela Ilic</a> and her <a href="http://tympanus.net/codrops/2013/07/18/on-scroll-effect-layout/">cbpScroller.js</a>.</p>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>






  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>



    </div>
  </div>

  </div>


<div class="container site-footer-container">
  <div class="site-footer " role="contentinfo">
    <ul class="site-footer-links float-right">
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage" class="site-footer-mark" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2017 <span title="0.15182s from github-fe-134ed95.cp1-iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>



    <script crossorigin="anonymous" integrity="sha256-c3IPAnuzF/zrEYwlknXaS+Xvo0TCRqEjQaaMMWjO6qc=" src="https://assets-cdn.github.com/assets/frameworks-73720f027bb317fceb118c259275da4be5efa344c246a12341a68c3168ceeaa7.js"></script>
    <script async="async" crossorigin="anonymous" integrity="sha256-GN/IkMekqEwUJ/XFXLI40SgKITaRc3nE7ro5WulQaG8=" src="https://assets-cdn.github.com/assets/github-18dfc890c7a4a84c1427f5c55cb238d1280a2136917379c4eeba395ae950686f.js"></script>




  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>


  </body>
</html>
