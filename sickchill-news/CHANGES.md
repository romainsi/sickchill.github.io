### v2020.09.14-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.14-1...v2020.09.14-2)

* Locale for imdbpy is broken
* Fix bundled libs, Remove imdbpie re-add imdbpy ([#6740](https://github.com/SickChill/SickChill/issues/6740))

### v2020.09.14-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.13-2...v2020.09.14-1)

* Disable re-register of legendas and fix indentation error in addic7ed

### v2020.09.13-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.13-1...v2020.09.13-2)

* Fixes [SickChill/SickChill#6732](https://github.com/SickChill/SickChill/issues/6732) ([#6736](https://github.com/SickChill/SickChill/issues/6736))
* Release 2020.9.13.post1

### v2020.09.13-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.12-3...v2020.09.13-1)

* Use certifi for cert verification Replaces [#6737](https://github.com/SickChill/SickChill/issues/6737)
* Update bundled libs in lib3

### v2020.09.12-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.12-2...v2020.09.12-3)

* Episode thumbs only have one option. Fixes multiple error Fixes [#6735](https://github.com/SickChill/SickChill/issues/6735)
* Update init.freebsd
* Release 2020.9.12.post2

### v2020.09.12-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.12-1...v2020.09.12-2)

* Do not log an error if a show has no network on thetvdb
* Release 2020.9.12.post1

### v2020.09.12-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.11-3...v2020.09.12-1)

* Fix extra blank line
* Fix encoding error in sb.searchtvdb webapi, by not casting =P Fixes [#6733](https://github.com/SickChill/SickChill/issues/6733)
* Release 2020.9.11.post3

### v2020.09.11-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.11-2...v2020.09.11-3)

* Fix labelling when snatching manual (provide the show in the result) Fixes [#6693](https://github.com/SickChill/SickChill/issues/6693)#issuecomment-691201067
* Release 2020.9.11.post2

### v2020.09.11-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.11-1...v2020.09.11-2)

* Fix getting show from scene exception Thanks Nyaran

### v2020.09.11-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.10-3...v2020.09.11-1)

* Fix image selector for shows Fixes [#6721](https://github.com/SickChill/SickChill/issues/6721)
* isort
* Release 2020.9.10.post3

### v2020.09.10-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.10-2...v2020.09.10-3)

* Fix error on add from imdb popular and make the code use imdbpie (for now) Fixes [#6719](https://github.com/SickChill/SickChill/issues/6719)
* Release 2020.9.10.post2

### v2020.09.10-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.10-1...v2020.09.10-2)

* Fix error on testRename Fixes [#6711](https://github.com/SickChill/SickChill/issues/6711)

### v2020.09.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.09-2...v2020.09.10-1)

* Use the date string as q when doing nzb tvdbid search for shows that are air by date, and leave season and ep out Fixes [#6718](https://github.com/SickChill/SickChill/issues/6718)
* Fix error in rarbg Fixes [#6715](https://github.com/SickChill/SickChill/issues/6715)
* isort
* Release 2020.9.9.post2

### v2020.09.09-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.09-1...v2020.09.09-2)

* Fix emby notifications Fixes [#6701](https://github.com/SickChill/SickChill/issues/6701)
* Relase 2020.9.9.post1

### v2020.09.09-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.08-1...v2020.09.09-1)

* Fix sending with qbittorrent Fix error with manual snatching on qbit (all will use regualr sickchill label on manual snatch for now) Fixes [#6706](https://github.com/SickChill/SickChill/issues/6706)
* Release 2020.9.8.post1

### v2020.09.08-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.07-5...v2020.09.08-1)

* Fix adding labels in deluged Fixes [#6693](https://github.com/SickChill/SickChill/issues/6693)

### v2020.09.07-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.07-4...v2020.09.07-5)

* Fix toggling log level (debug on/off) which was stopping all logging (It was set to critical level) Fixes [#6691](https://github.com/SickChill/SickChill/issues/6691)
* Release pypi 2020.9.7.post4

### v2020.09.07-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.07-3...v2020.09.07-4)

* Fix sending torrent-file results to transmission, deluge, and deluged Fixes [#6690](https://github.com/SickChill/SickChill/issues/6690)
* Make sure tvdb image url does not have _cache in it
* Fix url for update comparison
* Merge branch 'develop'
* Revert "Pypi release 2020.9.7.post3"
* Pypi release 2020.9.7.post3

### v2020.09.07-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.07-2...v2020.09.07-3)

* Fix failure to start due to translations by byassing if it fails (hacky) Try to fix an empty environment variable for language Fixes [#6702](https://github.com/SickChill/SickChill/issues/6702)

### v2020.09.07-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.07-1...v2020.09.07-2)

* PyPi release 2020.9.7.post1

### v2020.09.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.06-7...v2020.09.07-1)

* Fix rtorrent (bug in new-rtorrent-python) Add debug around rtorrent error and update lib3
* Release 2020.9.6.post7

### v2020.09.06-7

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.06-6...v2020.09.06-7)

* Use pills for episode statuses in displayShow Clean up updater code a bit, set url for pip updater to take the user to pypi Do not show branch warning on pip installs Better classes for true/false on status page
* PiPy 2020.9.6.post6

### v2020.09.06-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.06-5...v2020.09.06-6)

* Fix updater checking if installed via pip

### v2020.09.06-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.06-4...v2020.09.06-5)

* Fix build
* Isort

### v2020.09.06-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.06-3...v2020.09.06-4)

* Fix error when creating hash for torrent files (bencode error) Fixes [#6686](https://github.com/SickChill/SickChill/issues/6686)

### v2020.09.06-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.06-2...v2020.09.06-3)

* Disable urllib3 warnings so that log is not spammed when settings.SSL_VERIFY is False. Fixes [#6687](https://github.com/SickChill/SickChill/issues/6687)

### v2020.09.06-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.06-1...v2020.09.06-2)

* Set external loggers back to critical level. Stops logging of missing static files Fixes [#6683](https://github.com/SickChill/SickChill/issues/6683)

### v2020.09.06-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.05-5...v2020.09.06-1)

* Fix error on displayshow if you have a download url set in settings. Fixes [#6688](https://github.com/SickChill/SickChill/issues/6688)
* Resize ctv drama
* Added CTV Drama icon

### v2020.09.05-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.05-4...v2020.09.05-5)

* Fix missed string decode on massEDit Fixes [#6545](https://github.com/SickChill/SickChill/issues/6545)#issuecomment-687687584

### v2020.09.05-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.05-3...v2020.09.05-4)

* Fix error on status page when show queue has items. Fixes [#6682](https://github.com/SickChill/SickChill/issues/6682)

### v2020.09.05-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.05-2...v2020.09.05-3)

* Ignore sickbeard.db

### v2020.09.05-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.09.05-1...v2020.09.05-2)

* Yarn upgrade
* Release 0.0.56 to PyPi

### v2020.09.05-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.08.07-1...v2020.09.05-1)

* Yarn upgrade
* Add cookie auth to speedcd (cookies required due to cloudflare), fix search and page parsing. Fixes [#6562](https://github.com/SickChill/SickChill/issues/6562)
* Add s to update message when number of commits is not 1
* Bump pypy version to 0.0.55
* Fix loggers displaying access messages after enabling/disabling debug and show imdb images for movies index and details
* Fix error when uid/gid is passed to docker and the user does not exist in the container. Try to fix logging levels for tornado.access
* gitignore movies.db
* Instantiate movie list for tests, fix build
* Make rss work better for movies with rarbg
* Make rss work for movies with rarbg
* More
* Add movie backlog queue item
* RARBG provider supports movies
* Work on methods to search for movies
* Cleaner merged imdb/tmdb data on adding movies
* Add adult option checkbox for movies, and get both imdb and tmdb data regardless of which was used to add the movie
* Clean up movie-search page, imdb/tmdb popular movies
* Fix xo errors
* Add genres, fix title on movie-details
* Grunt
* Make adding movies work, add some info to movie-details
* Isort
* More fleshing out of movies GUI
* More work on getting movies added to the DB
* Bump pypi to 0.0.54
* Make some more concise error/debug logging in name parser tests and disable testing anime_bare without specifying anime. anime_bare is only when adding existing shows or the folder name has the group/release name.
* Clear name parser cache between tests
* Run anime tests...
* Add some tests
* Fix string.format to fstrings, some cleanup, and undo the filtering for series_name
* Apply fixes and suggestions by @miigotu
* Extra checks
* Improve anime series detection [SickChill/SickChill#6646](https://github.com/SickChill/SickChill/issues/6646)
* Bump pypi to 0.0.53
* Fix SORT_ARTICLE
* Remove hardcoded ref in checkout for deploy runner
* Fix core.js import when DEVELOPER mode is enabled
* Remove hardcoded ref in checkout for test runner
* Bump pypi to 0.0.52
* Enum34 should not be installed in lib3
* Bump pypi to 0.0.51
* Update bundled libs
* Some more
* More work on views, hidden unless developer=True
* Add some skeleton-views and methods for movies
=P
* Fixing xo alerts
* Fix scrollable content on ui-dialog (file dialog and image selector dialog)
* Shh, anyone wanna help?
* Bump pypi to 0.0.50
* Fix thread statuses when --daemon is set, fork before starting threads =P, Fixes [#6545](https://github.com/SickChill/SickChill/issues/6545)#issuecomment-678732143 Fixes [#6637](https://github.com/SickChill/SickChill/issues/6637)
* Make update method call the correct updater
* isort
* Bump pypi to 0.0.49
* Fixes [#6545](https://github.com/SickChill/SickChill/issues/6545)#issuecomment-678068706
* Bump pypi to 0.0.48
* Fix update url
* Bump pypi version to 0.0.47
* Bring back support for python 3.6
* Bump pypi to 0.0.46
* Fix rtorrent connection
* Bump pypi to 0.0.45
* Fixes [#6545](https://github.com/SickChill/SickChill/issues/6545)#issuecomment-677995622
* Fix clearing warnings button
* Clean up unused imports
* Bump pypi to 0.0.44
* Some cleanup of unused variables
* Fix error parsing rss cache items (horriblsubs) [#6545](https://github.com/SickChill/SickChill/issues/6545)#issuecomment-675506303
* Fix error in proper finder [#6545](https://github.com/SickChill/SickChill/issues/6545)#issuecomment-675506303
* Bump pypi to 0.0.43
* Try to fix delete rar contents (Almost never need to save those) Drop support for python 3.6 due to text parameter of subprocess.Popen
* Fix build
* Merge pull request [#6663](https://github.com/SickChill/SickChill/issues/6663) from RB14060/RB14060-bet+
* Remove old db upgrades. We will only support db 44+ now. Improves speedup and code.
* Some fstrings and translatable strings
* fix() Duplicated line
* feat() ui-dialog: Pin browser input & imageSelector drowdown to top
* Fix xo error
* fix() Hotfix to remove "Close" text on dialogs
* isort
* Make show image selector work with adblockers by self-proxying
* Bump pypy to 0.0.42
* Merge pull request [#6655](https://github.com/SickChill/SickChill/issues/6655) from SickChill/custom_show
* feat() Add network logo for Audience, La Uno (TVE1), Jiangsu TV, YTV (JP)
* Bump pypi to 0.0.41
* Make status prettier with timeago
* Make status page prettier with more thread status colors. Try to fix is_alive error.
* Clean up api builder and use main navbar, and add a link to it in the config menu
* Fix season/episode selection on apiBuilder
* Fix some deprecated and incompatible tags in html/mako
* Add itv encore network image
* Add font-awesome into bower instead of included in source manually. Add fork-awesome css map
* Add slack and telegram links to help&info and menu
* Add discord invite link and add fork-awesome fonts/css.
* Bump pypi to 0.0.40
* Remove random_user_agent altogether (slows startup and triggers CF). Re-enable yggtorrent and torrentz
* yarn upgrade
* Bump pypi to 0.0.39
* Fix error with tornado returning bytes for requests arguments causing nzbToMedia to fail. Fixes [#1765](https://github.com/clinton-hall/nzbToMedia/issues/1765)#issuecomment-673974074
* Use real user agent for xem and non-providers, spoof only on a case-by-case basis if necessary
* Refactor tv from oldbeard to sickchill
* Fix startup on python3.8 when libs arent install in the environment. Rename deprecated mathods
* Python3 - Fix issue with new tv dirty setter not always being marked dirty ([#6636](https://github.com/SickChill/SickChill/issues/6636))
* Python3 ([#6635](https://github.com/SickChill/SickChill/issues/6635))
* Python3 - Fix magentDL ([#6634](https://github.com/SickChill/SickChill/issues/6634))
* Add method mass_upsert, and use it for cache entries. Add test making sure it works. ([#6633](https://github.com/SickChill/SickChill/issues/6633))
* Cleanup a bit and make tests work through setuptools ([#6631](https://github.com/SickChill/SickChill/issues/6631))
* Fix url for main db version check ([#6630](https://github.com/SickChill/SickChill/issues/6630))
* Fix error on traktTrending: [#6545](https://github.com/SickChill/SickChill/issues/6545)#issuecomment-672630826 ([#6629](https://github.com/SickChill/SickChill/issues/6629))
* Python3 fixes ([#6628](https://github.com/SickChill/SickChill/issues/6628))
* isort
* Bump version for pypi
* Fix editShow
* Fix telegram and some other type mismatches
* Isort
* Bump pypi version to 0.0.28
* First preview of manual snatch. There will probably be a few hiccups but it seems to work
* Minor cleaning
* Bump pypi version 0.0.27
* Fix restore of sickbeard.db to sickchill.db
* Fix mako error on login page
* Remove unused imports, bump versionb
* Fix error in web api
* Bump version
* Fix missed comma
* Fix undefined on errorlogs page
* Fix quirk with urllib3 proxies not working without a default scheme set. Fixes [#6621](https://github.com/SickChill/SickChill/issues/6621)
* Fix dynamic import for clients, Fixes [#6622](https://github.com/SickChill/SickChill/issues/6622)
* Add view and template for manual snatch selection. Unfinished Fix cache duping, add indexes and use SQLITE CONFLICT syntax
* Bump version
* Add seeders, leechers, size, added to provider cache and keep results
* Bump pypi to 0.0.22
* Eliminate tox.ini
* bump pypi version to 0.0.21
* Fix mistake in backup resotre Fixes [#6619](https://github.com/SickChill/SickChill/issues/6619)
* Bump pypi to 0.0.20
* Rename sickchill.sickbeard to sickchill.oldbeard and clean up some md
* Move logger from sickchill.sickbeard to sickchill
* Refactor updater, rename and move it, add preliminary pip updater/notifier
* Bump pypi version
* Fix backlog overview error. Fixes [#6618](https://github.com/SickChill/SickChill/issues/6618)
* Update version for pypi
* Rename sickbeard.db to sickchill.db Fix some errors with PROG_DIR and DATA_DIR Fix problem with the git updater Check if installed by pip, use /home/dusted/sickchill for DATA if so and disable updater for now. Use /home/dusted/sickchill for default DATA_DIR if old location does not have existing db/ini
* Add setuptools-scm
* Try to get codecov working again
* Cleanup ical/googlecal events and image
* Merge pull request [#6572](https://github.com/SickChill/SickChill/issues/6572) from SickChill/py3-again

### v2020.08.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.07.18-1...v2020.08.07-1)

* Merge branch 'develop'

### v2020.07.18-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.07.09-1...v2020.07.18-1)

* Merge branch 'develop'
* Bump lodash from 4.17.15 to 4.17.19 ([#6577](https://github.com/SickChill/SickChill/issues/6577))
* Update pythonpackage.yml ([#6569](https://github.com/SickChill/SickChill/issues/6569))

### v2020.07.09-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.07.08-1...v2020.07.09-1)

* Update pythonpackage.yml ([#6566](https://github.com/SickChill/SickChill/issues/6566))

### v2020.07.08-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.07.06-1...v2020.07.08-1)

* testRename
* Update libs

### v2020.07.06-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.20-2...v2020.07.06-1)

* push default arch only to github packages only if master
* push default arch only to github packages
* Undo changes to deploy
* Bump tmdbsimple from 2.2.25 to 2.4.0 ([#6561](https://github.com/SickChill/SickChill/issues/6561))
* switch from unrar-free to unrar ([#6555](https://github.com/SickChill/SickChill/issues/6555))
* useful discord notifications ([#6558](https://github.com/SickChill/SickChill/issues/6558))
* Update libs
* Bump tmdbsimple from 2.2.23 to 2.2.25 ([#6550](https://github.com/SickChill/SickChill/issues/6550))
* Bump html5lib from 1.0.1 to 1.1 ([#6551](https://github.com/SickChill/SickChill/issues/6551))
* Test deploy to pkg.github
* Cache docker layers for the whole branch rather than just a commit
* lowercase docker image name

### v2020.06.20-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.20-1...v2020.06.20-2)

* Use local build caching for docker buildx and also push to github packages

### v2020.06.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.17-1...v2020.06.20-1)

* Fix is-alive callback for restarting SC. Fixes [#6543](https://github.com/SickChill/SickChill/issues/6543)
* Merge pull request [#6546](https://github.com/SickChill/SickChill/issues/6546) from SickChill/dependabot/pip/develop/tmdbsimple-2.2.23

### v2020.06.17-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.15-4...v2020.06.17-1)

* Some gui updates, use https for github/thetvdb/sickchill.github.io
* Merge pull request [#6542](https://github.com/SickChill/SickChill/issues/6542) from SickChill/dependabot/pip/develop/tmdbsimple-2.2.22
* Merge pull request [#6540](https://github.com/SickChill/SickChill/issues/6540) from SickChill/dependabot/pip/develop/tmdbsimple-2.2.21

### v2020.06.15-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.15-3...v2020.06.15-4)

* Use full size images for thumbs since tvdb would rather waste bandwidth than allow us to use the cached thumbnails. Fixes [#6537](https://github.com/SickChill/SickChill/issues/6537)
* New Crowdin updates ([#6538](https://github.com/SickChill/SickChill/issues/6538))
* Fix issues with updating inside linuxserver.io docker container, by checking out master instead of the tag. You will need to update with watchtowerrr or another method once to get this fix once the container is built, or run: docker exec -it sickchill /bin/bash -c 'cd /app/sickchill && git checkout master' && docker restart sickchill
* Rename inc_home_showList.mako -> inc_home_show_list.mako
* Bump tmdbsimple from 2.2.17 to 2.2.20 ([#6535](https://github.com/SickChill/SickChill/issues/6535))

### v2020.06.15-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.15-2...v2020.06.15-3)

* Add post processor queue tasks to the status page. Refactor and clean up html/mako for status page
* Allow forcing an auto post process on the manage searches page. Add post processor task scheduler to status page Sort schedulers on status page Refactor Auto post processor Clean up log lines for clarity in code for post processor

### v2020.06.15-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.15-1...v2020.06.15-2)

* Show release_name in logging when post processing a specific release. Fixes [#6509](https://github.com/SickChill/SickChill/issues/6509)

### v2020.06.15-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.14-4...v2020.06.15-1)

* Show release_name in response to webapi post process call if it was provided, otherwise show the path. Fixes [#6509](https://github.com/SickChill/SickChill/issues/6509)

### v2020.06.14-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.14-3...v2020.06.14-4)

* Fix docker deploy

### v2020.06.14-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.14-2...v2020.06.14-3)

* Add specific keys to edit in config.ini when the forced credentials message appears.

### v2020.06.14-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.14-1...v2020.06.14-2)

* Allow all private IP ranges without a password, in addition to  local IPs, until we can parse ip routes for docker and other container installs. Fixes [#6531](https://github.com/SickChill/SickChill/issues/6531)

### v2020.06.14-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.12-3...v2020.06.14-1)

* Update requirements.txt
* Fix code errors, optimize method, and replace is_ip_private with is_ip_local
* Don't require passwords local networks

### v2020.06.12-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.12-2...v2020.06.12-3)

* grunt
* Make an attempt to fix dbCompare when it errors, by trying https instead of http, and just checking master. Fixes [#6510](https://github.com/SickChill/SickChill/issues/6510)

### v2020.06.12-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.12-1...v2020.06.12-2)

* Prevent sbfdate and sbfdatetime from causing an error. Fixes [#6155](https://github.com/SickChill/SickChill/issues/6155)

### v2020.06.12-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.07-6...v2020.06.12-1)

* Update the docker-compose with suggested gui/cache and timezone mounts Set the source to 777 so git updater works with docker (makes the image larger) and provide a docker run example in the Dockerfile Add more logging for [#6522](https://github.com/SickChill/SickChill/issues/6522)
* Bump tmdbsimple from 2.2.15 to 2.2.17 ([#6527](https://github.com/SickChill/SickChill/issues/6527))
* Bump tmdbsimple from 2.2.11 to 2.2.15 ([#6515](https://github.com/SickChill/SickChill/issues/6515))
* New Crowdin translations ([#6516](https://github.com/SickChill/SickChill/issues/6516))
* Add missing Discovery Canada logo ([#6524](https://github.com/SickChill/SickChill/issues/6524))
* Adding Rocket.Chat Notifications ([#6526](https://github.com/SickChill/SickChill/issues/6526))

### v2020.06.07-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.07-5...v2020.06.07-6)

* Prevent tvshow-trailer.mp4 from being mistaken as a media file Fixes [#6513](https://github.com/SickChill/SickChill/issues/6513)

### v2020.06.07-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.07-4...v2020.06.07-5)

* Try to get all data removed from all places of the db when removing a show. Fixes [#6511](https://github.com/SickChill/SickChill/issues/6511) Hopefully

### v2020.06.07-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.07-3...v2020.06.07-4)

* Fix issue with setting correct port. Fixes [#6512](https://github.com/SickChill/SickChill/issues/6512)

### v2020.06.07-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.07-2...v2020.06.07-3)

* Better logging when nfo file has bunk info

### v2020.06.07-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.07-1...v2020.06.07-2)

* Add ability to pass release_name (nzbName/TorrentName) when calling post process from the api Fixes [#6509](https://github.com/SickChill/SickChill/issues/6509)

### v2020.06.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.03-4...v2020.06.07-1)

* Allow certs external to SC to be set without having to link or copy them to the SC source root Add logging around creating ssl certs (There is an x509 error currently when creating certs)
* Bump websocket-extensions from 0.1.3 to 0.1.4 ([#6508](https://github.com/SickChill/SickChill/issues/6508))
* Update tmdbsimple
* Bump tmdbsimple from 2.2.10 to 2.2.11 ([#6505](https://github.com/SickChill/SickChill/issues/6505))

### v2020.06.03-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.03-3...v2020.06.03-4)

* Adjust deluge clients to not set paths when they arent set in SC, so that defaults work in deluge.

### v2020.06.03-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.03-2...v2020.06.03-3)

* Use new github action for buildx

### v2020.06.03-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.06.03-1...v2020.06.03-2)

* Allow cross origin for api if the correct api key is given. Fixes [#6475](https://github.com/SickChill/SickChill/issues/6475)

### v2020.06.03-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.30-1...v2020.06.03-1)

* Update libs
* Adding missing network logos ([#6490](https://github.com/SickChill/SickChill/issues/6490))
* Merge pull request [#6493](https://github.com/SickChill/SickChill/issues/6493) from SickChill/dependabot/pip/develop/mako-1.1.3
* Merge pull request [#6494](https://github.com/SickChill/SickChill/issues/6494) from SickChill/dependabot/pip/develop/tmdbsimple-2.2.10

### v2020.05.30-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.28-1...v2020.05.30-1)

* Add ParseError exception catching for update_episode_metadata - Best I can do for now (needs refactored) Fixes [#6484](https://github.com/SickChill/SickChill/issues/6484)

### v2020.05.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.26-2...v2020.05.28-1)

* Deluge: Also set completed path and move_completed paramter to override client defaults. Fixes [#6474](https://github.com/SickChill/SickChill/issues/6474)
* Update included tmdbsimple
* Bump tmdbsimple from 2.2.5 to 2.2.6 ([#6473](https://github.com/SickChill/SickChill/issues/6473))
* Catch error preventing show from loading from the database if imdb cannot be reached. Fixes [#6481](https://github.com/SickChill/SickChill/issues/6481)

### v2020.05.26-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.26-1...v2020.05.26-2)

* Fix build

### v2020.05.26-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.25-1...v2020.05.26-1)

* Fixes iptorrents, and automagically parse the login form from the login page. Fixes [#6472](https://github.com/SickChill/SickChill/issues/6472)
* Merge pull request [#6471](https://github.com/SickChill/SickChill/issues/6471) from SickChill/dependabot/pip/develop/tmdbsimple-2.2.5

### v2020.05.25-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.23-5...v2020.05.25-1)

* Fix library update on emby Fixes [#6469](https://github.com/SickChill/SickChill/issues/6469)

### v2020.05.23-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.23-4...v2020.05.23-5)

* Fix show refresh after a show update happens. It was being blocked because the update was still being performed Fixes [#6417](https://github.com/SickChill/SickChill/issues/6417)

### v2020.05.23-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.23-3...v2020.05.23-4)

* Fix build

### v2020.05.23-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.23-2...v2020.05.23-3)

* Update episode nfo's when update, force refresh, post process, etc. Fixes [#6468](https://github.com/SickChill/SickChill/issues/6468)

### v2020.05.23-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.23-1...v2020.05.23-2)

* Put a try block around set attributes in refine_video, so we can see what fails. Fixes [#6465](https://github.com/SickChill/SickChill/issues/6465)

### v2020.05.23-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.19-1...v2020.05.23-1)

* Merge branch 'master' into develop
* Not sure why this is indented in pypi but not github, mistake somewhere in the release maybe. Fixes [#6467](https://github.com/SickChill/SickChill/issues/6467)
* Update libs
* Py35 fixes
* Merge pull request [#6462](https://github.com/SickChill/SickChill/issues/6462) from SickChill/dependabot/pip/develop/httplib2-0.18.1
* Merge pull request [#6460](https://github.com/SickChill/SickChill/issues/6460) from SickChill/dependabot/pip/develop/httplib2-0.18.0
* Merge pull request [#6456](https://github.com/SickChill/SickChill/issues/6456) from SickChill/dependabot/pip/develop/tmdbsimple-2.2.2
* Merge pull request [#6455](https://github.com/SickChill/SickChill/issues/6455) from SickChill/dependabot/pip/develop/httplib2-0.17.4
* Merge pull request [#6452](https://github.com/SickChill/SickChill/issues/6452) from SickChill/dependabot/pip/develop/tmdbsimple-2.2.1

### v2020.05.19-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.17-1...v2020.05.19-1)

* Merge branch 'develop'

### v2020.05.17-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.16-4...v2020.05.17-1)

* Merge branch 'develop'

### v2020.05.16-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.16-3...v2020.05.16-4)

* Merge branch 'develop'

### v2020.05.16-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.16-2...v2020.05.16-3)

* Merge branch 'develop'

### v2020.05.16-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.16-1...v2020.05.16-2)

* Merge branch 'develop'

### v2020.05.16-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.15-6...v2020.05.16-1)

* Merge branch 'develop'

### v2020.05.15-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.15-5...v2020.05.15-6)

* Merge branch 'develop'

### v2020.05.15-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.15-4...v2020.05.15-5)

* Merge branch 'develop'

### v2020.05.15-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.15-3...v2020.05.15-4)

* Merge branch 'develop'

### v2020.05.15-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.15-2...v2020.05.15-3)

* Merge branch 'develop'

### v2020.05.15-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.15-1...v2020.05.15-2)

* Merge branch 'develop'

### v2020.05.15-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.14-1...v2020.05.15-1)

* Merge branch 'develop'

### v2020.05.14-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.13-2...v2020.05.14-1)

* Merge branch 'develop'

### v2020.05.13-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.13-1...v2020.05.13-2)

* Merge branch 'develop'

### v2020.05.13-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.12-3...v2020.05.13-1)

* Merge branch 'develop'
* fix: requirements.txt to reduce vulnerabilities ([#6424](https://github.com/SickChill/SickChill/issues/6424))

### v2020.05.12-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.12-2...v2020.05.12-3)

* See if this helps cfshit

### v2020.05.12-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.12-1...v2020.05.12-2)

* Allow shows to be refreshed en-mass from mass update even if they are paused. Fixes [#6419](https://github.com/SickChill/SickChill/issues/6419)

### v2020.05.12-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.08-4...v2020.05.12-1)

* Fix mistake in emby code. Fixes [#6418](https://github.com/SickChill/SickChill/issues/6418)
* Fix exception when downloading subtitles Fixes [#6421](https://github.com/SickChill/SickChill/issues/6421) Fix error when removing shows and show dir does not exist
* Merge pull request [#6410](https://github.com/SickChill/SickChill/issues/6410) from SickChill/dependabot/pip/develop/validators-0.15.0

### v2020.05.08-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.08-3...v2020.05.08-4)

* Dont skip refresh on ended shows Fixes [#6355](https://github.com/SickChill/SickChill/issues/6355)

### v2020.05.08-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.08-2...v2020.05.08-3)

* Add back missing send2trash library Fixes [#6356](https://github.com/SickChill/SickChill/issues/6356)

### v2020.05.08-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.08-1...v2020.05.08-2)

* Add some network images Fixes [#6346](https://github.com/SickChill/SickChill/issues/6346)

### v2020.05.08-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.07-3...v2020.05.08-1)

* Fix build
* Remove accidentally added shared objects from libs
* Use the SC Cache dir for imdbpie, hopefully fixing the issue of adding shows for some people. Fail gracefully if we cannot get IMDB info Fixes [#6350](https://github.com/SickChill/SickChill/issues/6350) Fixes [#6370](https://github.com/SickChill/SickChill/issues/6370)
* Remove hachoir completely, use imagesize_py to guess image aspect ratio, use rtorrent9.lib.torrentparser.NewTorrentParser to verify torrent file downloads
* Update libs per new requirements.txt and fix imports for new subliminal

### v2020.05.07-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.07-2...v2020.05.07-3)

* Allow specifying http/https in the empy host, while maintaining previous functionality. Also, In the future a special host with path can be specified with a starting !, such as !https://localhost:5555/path/to/api Fixes [#6351](https://github.com/SickChill/SickChill/issues/6351)
* Fix error testing kodi notifications when specifying port. Fixes [#6358](https://github.com/SickChill/SickChill/issues/6358)
* Fixes [#6375](https://github.com/SickChill/SickChill/issues/6375) - Update filelist provider url

### v2020.05.07-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.07-1...v2020.05.07-2)

* Revert "Update Dockerfile"

### v2020.05.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.05.03-1...v2020.05.07-1)

* New Crowdin translations ([#6365](https://github.com/SickChill/SickChill/issues/6365))
* Bump subliminal from 2.0.5 to 2.1.0 ([#6373](https://github.com/SickChill/SickChill/issues/6373))
* Bump cloudscraper from 1.2.34 to 1.2.36 ([#6374](https://github.com/SickChill/SickChill/issues/6374))
* Revert "Docker permissions ([#6081](https://github.com/SickChill/SickChill/issues/6081))" ([#6406](https://github.com/SickChill/SickChill/issues/6406))
* Merge pull request [#6378](https://github.com/SickChill/SickChill/issues/6378) from nopoz/deluge

### v2020.05.03-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.28-3...v2020.05.03-1)

* Fix bug when TVDB returns 0 or -1 for airdate -.- Disable log line that people confuse for an error.
* New translations messages.pot (French) ([#6349](https://github.com/SickChill/SickChill/issues/6349))

### v2020.04.28-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.28-2...v2020.04.28-3)

* isort to fix build

### v2020.04.28-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.28-1...v2020.04.28-2)

* Fix some issues with getting tvdb favorites

### v2020.04.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.27-2...v2020.04.28-1)

* Basic feature implementation to add shows from tvdb favorites list. Adds with default set show options User key is on https://thetvdb.com/dashboard/account/editinfo Fixes [#6334](https://github.com/SickChill/SickChill/issues/6334)

### v2020.04.27-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.27-1...v2020.04.27-2)

* Add BBC iPlayer network image Fixes [#6337](https://github.com/SickChill/SickChill/issues/6337)

### v2020.04.27-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.25-9...v2020.04.27-1)

* Undo default hidden seasons for now. Fixes [#6333](https://github.com/SickChill/SickChill/issues/6333)

### v2020.04.25-9

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.25-8...v2020.04.25-9)

* Improve sorting by completeion percentage. Fixes [#6330](https://github.com/SickChill/SickChill/issues/6330)

### v2020.04.25-8

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.25-7...v2020.04.25-8)

* Fix error getting imdb info  when a show has a "World Wide" title Fixes [#6329](https://github.com/SickChill/SickChill/issues/6329) Fixes [#6327](https://github.com/SickChill/SickChill/issues/6327)

### v2020.04.25-7

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.25-6...v2020.04.25-7)

* Missed record

### v2020.04.25-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.25-5...v2020.04.25-6)

* Fix error getting imdb info that was causing problems adding some shows Fixes [#6329](https://github.com/SickChill/SickChill/issues/6329) Fixes [#6327](https://github.com/SickChill/SickChill/issues/6327)

### v2020.04.25-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.25-4...v2020.04.25-5)

* Fix error when show airdate is missing entirely Fixes [#6304](https://github.com/SickChill/SickChill/issues/6304)

### v2020.04.25-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.25-3...v2020.04.25-4)

* Fix build by sorting imports

### v2020.04.25-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.25-2...v2020.04.25-3)

* Fix exception in tpb tracker if a user has a broken js2py

### v2020.04.25-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.25-1...v2020.04.25-2)

* Fix KeyError: region in imdb code

### v2020.04.25-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.24-3...v2020.04.25-1)

* Missed reference to imdbpy exceptions
* Fix missed import removal
* Use imdbpie instead of imdbpy, because it does not rely on c-extensions/lxml/sqlalchemy Fixes [#6264](https://github.com/SickChill/SickChill/issues/6264) [#6254](https://github.com/SickChill/SickChill/issues/6254) [#6239](https://github.com/SickChill/SickChill/issues/6239) [#6322](https://github.com/SickChill/SickChill/issues/6322)

### v2020.04.24-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.24-2...v2020.04.24-3)

* Fix build

### v2020.04.24-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.24-1...v2020.04.24-2)

* Fix error when a show is not completely populated in the database, causing a rendering error Fixes [#6304](https://github.com/SickChill/SickChill/issues/6304)

### v2020.04.24-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.23-8...v2020.04.24-1)

* Fix fake useragent pool creation when a user starts SC before network is up. Fixes [#6314](https://github.com/SickChill/SickChill/issues/6314)
* New Crowdin translations ([#6311](https://github.com/SickChill/SickChill/issues/6311))

### v2020.04.23-8

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.23-7...v2020.04.23-8)

* Fix issue with kodi notifier always doing full library update when show name has a space in it, and not honoring settings Fixes [#6306](https://github.com/SickChill/SickChill/issues/6306)

### v2020.04.23-7

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.23-6...v2020.04.23-7)

* Fix displaying more than one entry for related episodes on Preview Rename Fixes [#6307](https://github.com/SickChill/SickChill/issues/6307)

### v2020.04.23-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.23-5...v2020.04.23-6)

* Fix another one of the errors in imdbpy

### v2020.04.23-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.23-4...v2020.04.23-5)

* Fix one of the errors in imdbpy

### v2020.04.23-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.23-3...v2020.04.23-4)

* Update cloudscraper and httplib2
* Bump cloudscraper from 1.2.33 to 1.2.34 ([#6303](https://github.com/SickChill/SickChill/issues/6303))
* Bump httplib2 from 0.17.2 to 0.17.3 ([#6302](https://github.com/SickChill/SickChill/issues/6302))

### v2020.04.23-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.23-2...v2020.04.23-3)

* Fix hiding season headers when filtering episodes on the show page. Fixes [#6259](https://github.com/SickChill/SickChill/issues/6259)
* New translations messages.pot (French) ([#6292](https://github.com/SickChill/SickChill/issues/6292))

### v2020.04.23-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.23-1...v2020.04.23-2)

* Fix error with js updating text on adding existing shows. Fixes [#6265](https://github.com/SickChill/SickChill/issues/6265)

### v2020.04.23-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.22-4...v2020.04.23-1)

* Fix error getting episode. Fixes [#6297](https://github.com/SickChill/SickChill/issues/6297)

### v2020.04.22-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.22-3...v2020.04.22-4)

* Fix mistake

### v2020.04.22-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.22-2...v2020.04.22-3)

* New Crowdin translations ([#6263](https://github.com/SickChill/SickChill/issues/6263))
* Revert to using name parser over guessit for the release groups Fixes [#6268](https://github.com/SickChill/SickChill/issues/6268)
* Fix growl.py for GNTP 1.0.3 update ([#6267](https://github.com/SickChill/SickChill/issues/6267))

### v2020.04.22-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.22-1...v2020.04.22-2)

* Merge branch 'develop'
* Update Crowdin configuration file

### v2020.04.22-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.21-4...v2020.04.22-1)

* Avoid error when apibay is failing to return results. Fixes [#2614](https://github.com/SickChill/SickChill/issues/2614) Fixes [#6256](https://github.com/SickChill/SickChill/issues/6256)

### v2020.04.21-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.21-3...v2020.04.21-4)

* Try to improve Preview Rename speed and memory usage. Might not help much Fixes [#5984](https://github.com/SickChill/SickChill/issues/5984)

### v2020.04.21-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.21-2...v2020.04.21-3)

* Fix Greetings
* Fix build

### v2020.04.21-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.21-1...v2020.04.21-2)

* Try a new slick way to change root dirs when a user moves their library from  windows to linux or vice versa and does a massEdit to change the root. Fixes [#6249](https://github.com/SickChill/SickChill/issues/6249) (I hope)

### v2020.04.21-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.20-8...v2020.04.21-1)

* Make rescan on show page into a force refresh, so people can refresh ended/paused shows manually.

### v2020.04.20-8

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.20-7...v2020.04.20-8)

* Fix adba for anidb errors. Fixes [#6244](https://github.com/SickChill/SickChill/issues/6244)

### v2020.04.20-7

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.20-6...v2020.04.20-7)

* Set airdates to Never for wanted/unaired/unknown episodes that no longer have an airdate on TVDB, without deleting them Minor datetime cleanup

### v2020.04.20-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.20-5...v2020.04.20-6)

* Update/remove broken links and images from the readme

### v2020.04.20-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.20-4...v2020.04.20-5)

* Always collapse if  show has more than one season, show at most the most recent 3 seasons expanded by default Fixes slow load for large shows Fixes [#6179](https://github.com/SickChill/SickChill/issues/6179)

### v2020.04.20-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.20-3...v2020.04.20-4)

* Prevent show episodes from being deleted when tvdb does not answer Fixes [#6176](https://github.com/SickChill/SickChill/issues/6176) Fixes [#6091](https://github.com/SickChill/SickChill/issues/6091)

### v2020.04.20-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.20-2...v2020.04.20-3)

* Fix mistake in lib cleaner code.

### v2020.04.20-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.20-1...v2020.04.20-2)

* Fix sorting by number of downloads on home page Fixes [#4978](https://github.com/SickChill/SickChill/issues/4978)

### v2020.04.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-9...v2020.04.20-1)

* Fix issue re-testing email notifications after save and page reload due to passwords being masked in the loaded page. Fixes [#4943](https://github.com/SickChill/SickChill/issues/4943)
* Fix build
* Seems to fix issues with post processor sometimes not processing files. Unknown why yet. Fixes [#6215](https://github.com/SickChill/SickChill/issues/6215)

### v2020.04.19-9

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-8...v2020.04.19-9)

* Fixes renamer not moving associated files when MOVE_ASSOCIATED_FILES is disabled in the post processor settings. Fixes [#6191](https://github.com/SickChill/SickChill/issues/6191)

### v2020.04.19-8

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-7...v2020.04.19-8)

* Js2Py does not work on Python less than 2.7.9 - Disable grabbing tpb provided trackers and only use custom_trackers if this is the case This will disable the provider if you do not have python 2.7.9 OR set custom trackers in config/search on the torrent tab. Fixes [#6236](https://github.com/SickChill/SickChill/issues/6236)
* Remove pyc and empty folders from libs when SC updates. Hopefully this prevents [#6230](https://github.com/SickChill/SickChill/issues/6230) in the future
* Fix missed coding change in tvdb handler Fixes [#6190](https://github.com/SickChill/SickChill/issues/6190)

### v2020.04.19-7

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-6...v2020.04.19-7)

* Fix KeyError with imdb_info on show page Fixes [#6227](https://github.com/SickChill/SickChill/issues/6227)

### v2020.04.19-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-5...v2020.04.19-6)

* Fix imports for rtorrent

### v2020.04.19-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-4...v2020.04.19-5)

* Remove extensions
* Add more libs back

### v2020.04.19-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-3...v2020.04.19-4)

* Add synchronousdeluge dirty

### v2020.04.19-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-2...v2020.04.19-3)

* Add more libs back

### v2020.04.19-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-10...v2020.04.19-2)

* Do not download propers for paused shows. Fixes [#6210](https://github.com/SickChill/SickChill/issues/6210)

### v2020.04.19-10

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.19-1...v2020.04.19-10)

* Fix build
* Seems to fix issues with post processor sometimes not processing files. Unknown why yet. Fixes [#6215](https://github.com/SickChill/SickChill/issues/6215)

### v2020.04.19-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.18-3...v2020.04.19-1)

* Update imdbpy to IMDbPY-6.9.dev20200419 (fixes etree issue, hopefully), Add certgen from pyopenssl example to create certs
* Rework libs and enable fanart.tv for images Updates python-fanart Fixes lib dir to be 100% vanilla, moved adba and trakt to root for now Replaced growl lib with gntp Replaced python-fanart with python3-fanart
* Fix adding from imdbpopular
* Update translations (build 11159) [skip ci]

### v2020.04.18-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.18-2...v2020.04.18-3)

* Remove lxml - pip install lxml manually if you have issues related to elementree/etree/lxml
* Update thepiratebay to use API. Fixes [#6195](https://github.com/SickChill/SickChill/issues/6195)
* Update translations (build 11156) [skip ci]

### v2020.04.18-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.18-1...v2020.04.18-2)

* Update libs, need to figure out issue with binaries
* Update translations (build 11152) [skip ci]

### v2020.04.18-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.01-2...v2020.04.18-1)

* Bump httplib2 from 0.17.1 to 0.17.2 ([#6197](https://github.com/SickChill/SickChill/issues/6197))
* Bump twilio from 6.38.0 to 6.38.1 ([#6202](https://github.com/SickChill/SickChill/issues/6202))
* Workaround for SickChill[#6199](https://github.com/SickChill/SickChill/issues/6199) to support RFC 4007 IPv6 Scoped Literal Addresses in remote_ip ([#6201](https://github.com/SickChill/SickChill/issues/6201))
* Update yarn packages, add missed requirements commit
* Update subliminal, sqlalchemy, dogpile.cache
* Tornado to 4.5.3 (5.0 breaks SC for unknown reason)
* Update libs based on requirements. Pin Tornado to 4.5
* Bump putio-py from 8.6.0 to 8.6.2 ([#6173](https://github.com/SickChill/SickChill/issues/6173))
* Bump beautifulsoup4 from 4.8.2 to 4.9.0 ([#6174](https://github.com/SickChill/SickChill/issues/6174))
* Bump certifi from 2019.11.28 to 2020.4.5.1 ([#6175](https://github.com/SickChill/SickChill/issues/6175))
* Add BSPlayer subtitle provider ([#6177](https://github.com/SickChill/SickChill/issues/6177))
* Bump httplib2 from 0.17.0 to 0.17.1 ([#6170](https://github.com/SickChill/SickChill/issues/6170))
* Bump tus-py from 1.2.0 to 1.3.4 ([#6165](https://github.com/SickChill/SickChill/issues/6165))
* Update Dockerfile
* Bump twilio from 6.37.0 to 6.38.0 ([#6166](https://github.com/SickChill/SickChill/issues/6166))
* Docker permissions ([#6081](https://github.com/SickChill/SickChill/issues/6081))
* Update translations (build 11109) [skip ci]

### v2020.04.01-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.04.01-1...v2020.04.01-2)

* Fixes [#6138](https://github.com/SickChill/SickChill/issues/6138) - API::sb.searchtvdb error
* Update translations (build 11107) [skip ci]

### v2020.04.01-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.15-1...v2020.04.01-1)

* Fix issue where user cannot add a scene exception for the latest season of a show. Fix issue of Season torrents that are tried to be splitted when snatched through torznab
* Bump beautifulsoup4 from 4.5.3 to 4.8.2 ([#6145](https://github.com/SickChill/SickChill/issues/6145))
* Bump httplib2 from 0.9.2 to 0.17.0 ([#6146](https://github.com/SickChill/SickChill/issues/6146))
* Bump pytz from 2019.1 to 2019.3 ([#6147](https://github.com/SickChill/SickChill/issues/6147))
* Bump pymediainfo from 2.0 to 4.1 ([#6148](https://github.com/SickChill/SickChill/issues/6148))
* Bump tzlocal from 1.4 to 2.0.0 ([#6149](https://github.com/SickChill/SickChill/issues/6149))
* Bump ndg-httpsclient from 0.3.3 to 0.5.1 ([#6150](https://github.com/SickChill/SickChill/issues/6150))
* Bump xmltodict from 0.11.0 to 0.12.0 ([#6151](https://github.com/SickChill/SickChill/issues/6151))
* Bump pysrt from 1.1.1 to 1.1.2 ([#6152](https://github.com/SickChill/SickChill/issues/6152))
* Bump fake-useragent from 0.1.2 to 0.1.11 ([#6153](https://github.com/SickChill/SickChill/issues/6153))
* Bump mako from 1.0.12 to 1.1.2 ([#6154](https://github.com/SickChill/SickChill/issues/6154))
* Bump profilehooks from 1.5 to 1.11.2 ([#6139](https://github.com/SickChill/SickChill/issues/6139))
* Bump validators from 0.10 to 0.14.2 ([#6140](https://github.com/SickChill/SickChill/issues/6140))
* Bump idna from 2.5 to 2.9 ([#6141](https://github.com/SickChill/SickChill/issues/6141))
* Bump futures from 3.1.1 to 3.3.0 ([#6142](https://github.com/SickChill/SickChill/issues/6142))
* Bump markdown2 from 2.3.6 to 2.3.8 ([#6143](https://github.com/SickChill/SickChill/issues/6143))
* Bump pyjwt from 1.5.0 to 1.7.1 ([#6127](https://github.com/SickChill/SickChill/issues/6127))
* Bump unidecode from 0.04.21 to 1.1.1 ([#6128](https://github.com/SickChill/SickChill/issues/6128))
* Bump twilio from 6.36.0 to 6.37.0 ([#6129](https://github.com/SickChill/SickChill/issues/6129))
* Bump enum34 from 1.0.4 to 1.1.10 ([#6131](https://github.com/SickChill/SickChill/issues/6131))
* Bump backports-ssl-match-hostname from 3.5.0.1 to 3.7.0.1 ([#6130](https://github.com/SickChill/SickChill/issues/6130))
* Bump certifi from 2017.4.17 to 2019.11.28 ([#6116](https://github.com/SickChill/SickChill/issues/6116))
* Bump decorator from 4.0.10 to 4.4.2 ([#6117](https://github.com/SickChill/SickChill/issues/6117))
* Bump pygithub from 1.34 to 1.45 ([#6118](https://github.com/SickChill/SickChill/issues/6118))
* Bump putio-py from 6.1.0 to 8.6.0 ([#6119](https://github.com/SickChill/SickChill/issues/6119))
* Bump python-dateutil from 2.8.0 to 2.8.1 ([#6120](https://github.com/SickChill/SickChill/issues/6120))
* Bump six from 1.12.0 to 1.14.0 ([#6122](https://github.com/SickChill/SickChill/issues/6122))
* Bump pysocks from 1.6.7 to 1.7.1 ([#6123](https://github.com/SickChill/SickChill/issues/6123))
* Bump oauthlib from 2.0.2 to 3.1.0 ([#6124](https://github.com/SickChill/SickChill/issues/6124))
* Bump guessit from 3.0.4 to 3.1.0 ([#6125](https://github.com/SickChill/SickChill/issues/6125))
* Bump configobj from 4.6.0 to 5.0.6 ([#6126](https://github.com/SickChill/SickChill/issues/6126))
[Security] Bump markdown2 from 2.3.4 to 2.3.6 ([#6110](https://github.com/SickChill/SickChill/issues/6110))
* Bump html5lib from 1.0b10 to 1.0.1 ([#6111](https://github.com/SickChill/SickChill/issues/6111))
* Bump stevedore from 1.10.0 to 1.32.0 ([#6112](https://github.com/SickChill/SickChill/issues/6112))
* Bump tmdbsimple from 0.3.0 to 2.2.0 ([#6113](https://github.com/SickChill/SickChill/issues/6113))
* Bump requests-oauthlib from 0.8.0 to 1.3.0 ([#6114](https://github.com/SickChill/SickChill/issues/6114))
* Update translations (build 10991) [skip ci]

### v2020.03.15-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.13-6...v2020.03.15-1)

* Sleep 3 seconds in between requests to xthor (2 + 1 for good measure) Fixes [#6107](https://github.com/SickChill/SickChill/issues/6107)
* Update some libs and update the docker packaging script ([#6106](https://github.com/SickChill/SickChill/issues/6106))
* Bump tornado from 4.5.1 to 5.1.1 ([#6102](https://github.com/SickChill/SickChill/issues/6102))
* Bump cachecontrol from 0.11.5 to 0.12.6 ([#6101](https://github.com/SickChill/SickChill/issues/6101))
* Bump rebulk from 1.0.0 to 2.0.0 ([#6103](https://github.com/SickChill/SickChill/issues/6103))
* Bump twilio from 5.7.0 to 6.36.0 ([#6104](https://github.com/SickChill/SickChill/issues/6104))
* Bump python-twitter from 3.3 to 3.5 ([#6105](https://github.com/SickChill/SickChill/issues/6105))
* Update translations (build 10956) [skip ci]

### v2020.03.13-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.13-5...v2020.03.13-6)

* Merge branch 'develop'
* Update translations (build 10948) [skip ci]

### v2020.03.13-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.13-4...v2020.03.13-5)

* Update build
* Update translations (build 10946) [skip ci]

### v2020.03.13-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.13-3...v2020.03.13-4)

* Update build
* Update translations (build 10943) [skip ci]

### v2020.03.13-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.13-2...v2020.03.13-3)

* Typo space

### v2020.03.13-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.13-1...v2020.03.13-2)

* Update greetings so it doesnt build unless an issue or pr was opened
* Update translations (build 10936) [skip ci]

### v2020.03.13-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.12-1...v2020.03.13-1)

* Test SC and build multiarch (linux/amd64,linux/arm/v6,linux/arm/v7,linux/arm64,linux/386,linux/ppc64le,linux/s390x) docker images with buildx through github workflow
* Update translations (build 10933) [skip ci]

### v2020.03.12-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.10-2...v2020.03.12-1)

* Change API key for TVDB. https://thetvdb.com
* Update translations (build 10881) [skip ci]

### v2020.03.10-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.10-1...v2020.03.10-2)

* Add amazon (japan) logo Fixes [#6035](https://github.com/SickChill/SickChill/issues/6035)
* Update translations (build 10879) [skip ci]

### v2020.03.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.08-4...v2020.03.10-1)

* Add '-xpost' to removeWords Fixes [#6079](https://github.com/SickChill/SickChill/issues/6079)
* Update translations (build 10863) [skip ci]

### v2020.03.08-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.08-3...v2020.03.08-4)

* Typo

### v2020.03.08-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.08-2...v2020.03.08-3)

* Create pythonpackage.yml ([#6077](https://github.com/SickChill/SickChill/issues/6077))
* Update translations (build 10853) [skip ci]

### v2020.03.08-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.08-1...v2020.03.08-2)

* Temporary solution for bower warning. TODO: Get rid of bower entirely.
* Update translations (build 10850) [skip ci]

### v2020.03.08-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.07-4...v2020.03.08-1)

* Add yaml for issue bot
* Update translations (build 10847) [skip ci]

### v2020.03.07-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.07-3...v2020.03.07-4)

* Fixes [#6069](https://github.com/SickChill/SickChill/issues/6069)
* Update translations (build 10844) [skip ci]

### v2020.03.07-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.07-2...v2020.03.07-3)

* Lets see if TVDB fixed their updates api. Starts at today and gets the last 7 days first rather than last update time in case limits are hit, and always updates the last 7 days.
* Update translations (build 10841) [skip ci]

### v2020.03.07-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.07-1...v2020.03.07-2)

* Fix branch list in config
* Update translations (build 10839) [skip ci]

### v2020.03.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.03.02-1...v2020.03.07-1)

* fix login when rev proxy has auth basic ([#6070](https://github.com/SickChill/SickChill/issues/6070))
* Update translations (build 10834) [skip ci]

### v2020.03.02-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.27-2...v2020.03.02-1)

* Check if queueing is enabled in qbittorrent before trying to set priority. Fixes [#5980](https://github.com/SickChill/SickChill/issues/5980)
* Update translations (build 10832) [skip ci]

### v2020.02.27-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.27-1...v2020.02.27-2)

* Add ipaddress package Fixes [#6032](https://github.com/SickChill/SickChill/issues/6032)

### v2020.02.27-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.26-3...v2020.02.27-1)

* is_ip_private() should handle IPv6 addresses ([#6030](https://github.com/SickChill/SickChill/issues/6030))
* Update translations (build 10824) [skip ci]

### v2020.02.26-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.26-2...v2020.02.26-3)

* Make sure a failing kodi connection doesnt prevent a user from accessing displayShow
* Update translations (build 10822) [skip ci]

### v2020.02.26-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.26-1...v2020.02.26-2)

* Make sure SC still starts if user does not have cryptography, which is needed for the jwt auth.

### v2020.02.26-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.25-8...v2020.02.26-1)

* Implement SC login FROM Cloudflare Access using jwt token auth ([#6021](https://github.com/SickChill/SickChill/issues/6021))
* Add IPv6 loopback support to is_ip_private() ([#6024](https://github.com/SickChill/SickChill/issues/6024))
* Update translations (build 10803) [skip ci]

### v2020.02.25-8

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.25-7...v2020.02.25-8)

* Update cloudscraper and cfscrape. Good Luck
* Update translations (build 10801) [skip ci]

### v2020.02.25-7

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.25-6...v2020.02.25-7)

* Fix problem when using black hole and a bittorrent cache site must be used (Hundreds of No schema supplied. Perhaps you meant lines in the logs)
* Update translations (build 10798) [skip ci]

### v2020.02.25-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.25-5...v2020.02.25-6)

* Do not refresh shows on startup Update all shows every night until TVDB fixes their updates api
* Update translations (build 10794) [skip ci]

### v2020.02.25-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.25-4...v2020.02.25-5)

* Oops, this allowed Bearer : as authorization if the user had no user/pass set. Also return false if incorrect header is present.
* Update translations (build 10791) [skip ci]

### v2020.02.25-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.25-3...v2020.02.25-4)

* Change value of port to an int when port is passed in KODI_HOST.
* Update translations (build 10788) [skip ci]

### v2020.02.25-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.25-2...v2020.02.25-3)

* Allow basic auth to bypass login (for reverse proxies, unsecure if used outside of a local network!) Fixes [#6018](https://github.com/SickChill/SickChill/issues/6018)
* Update translations (build 10784) [skip ci]

### v2020.02.25-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.25-1...v2020.02.25-2)

* Link cache data ([#6014](https://github.com/SickChill/SickChill/issues/6014))

### v2020.02.25-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.24-3...v2020.02.25-1)

* Improve login code from remote, log the access attempt if the error page was shown.
* Update translations (build 10774) [skip ci]

### v2020.02.24-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.24-2...v2020.02.24-3)

* Adjust code for login page
* Update translations (build 10769) [skip ci]

### v2020.02.24-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.24-1...v2020.02.24-2)

* Force users to set a username and password if accessible from the internet, or block the con
* Update translations (build 10765) [skip ci]

### v2020.02.24-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.23-2...v2020.02.24-1)

* Try to fix itorrents error with skytorrents and limetorrents Fixes [#6012](https://github.com/SickChill/SickChill/issues/6012) Fixes [#5942](https://github.com/SickChill/SickChill/issues/5942)
* Fixes [#5108](https://github.com/SickChill/SickChill/issues/5108)
* Update translations (build 10749) [skip ci]

### v2020.02.23-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.23-1...v2020.02.23-2)

* New limetorrents url
* Update translations (build 10745) [skip ci]

### v2020.02.23-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.22-1...v2020.02.23-1)

* Upgrade requests, idna
* Update tvdb series/poster/banner/fanart/season images ordering to get the most popular images when adding
* Update translations (build 10743) [skip ci]

### v2020.02.22-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.15-3...v2020.02.22-1)

* Hide kodi play button when kodi is not enabled and prevent the modal from causing an exception Fixes [#5990](https://github.com/SickChill/SickChill/issues/5990)
* Network Logos - Duplicate Chiba TV for "CTC (JA)" network ([#6001](https://github.com/SickChill/SickChill/issues/6001))
* Network logo - Add CraveTV ([#5997](https://github.com/SickChill/SickChill/issues/5997))
* Update translations (build 10736) [skip ci]

### v2020.02.15-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.15-2...v2020.02.15-3)

* Fall back to english for series images if the show has a non-english language and the language-specific image is not found. Fixes [#5979](https://github.com/SickChill/SickChill/issues/5979)
* Option to restrict backlog searches to 'missing' episodes only ([#5977](https://github.com/SickChill/SickChill/issues/5977))
* Update translations (build 10730) [skip ci]

### v2020.02.15-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.15-1...v2020.02.15-2)

* Fix [#5981](https://github.com/SickChill/SickChill/issues/5981) - Kodi notifications if you put the port on the settings line. via kyuuk (thanks) [untested]
* Update translations (build 10726) [skip ci]

### v2020.02.15-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.11-3...v2020.02.15-1)

* iSort and fix build. Disable demonoid rss search until I can finish it.
* Force cache dir to be in gui/slick/cache and remove setting. Force Log dir to be in data_dir/Logs and remove setting Add demonoid and kat providers
* Update translations (build 10721) [skip ci]

### v2020.02.11-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.11-2...v2020.02.11-3)

* Only run rarbg test manually

### v2020.02.11-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.11-1...v2020.02.11-2)

* Use rarbg for search test, as it is one of our most reliable providers
* Fixes [#5972](https://github.com/SickChill/SickChill/issues/5972) - mede8er xml not being created Fixes [#5962](https://github.com/SickChill/SickChill/issues/5962) - Rating tag set to mpp rating rather than site rating
* Update translations (build 10715) [skip ci]

### v2020.02.11-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.09-3...v2020.02.11-1)

* Hide debug logging about items/images not found on tvdb
* Update translations (build 10711) [skip ci]

### v2020.02.09-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.09-2...v2020.02.09-3)

* Fixes [#5964](https://github.com/SickChill/SickChill/issues/5964) - Mistake
* Fixes [#5964](https://github.com/SickChill/SickChill/issues/5964)
* Update translations (build 10707) [skip ci]

### v2020.02.09-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.09-1...v2020.02.09-2)

* Temp fix for image_url so it doesnt error everyone
* Update translations (build 10705) [skip ci]

### v2020.02.09-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.05-2...v2020.02.09-1)

* Fixes [#5963](https://github.com/SickChill/SickChill/issues/5963)
* Fix reverse parsing scene names, and possibly match scene releases better as well as when re-adding already-renamed show folders.
* Add ability to play file on kodi over api in the notifier, remove old kodi notifier code ([#5938](https://github.com/SickChill/SickChill/issues/5938))
* Fix image cache, only works if cache dir is inside gui dir ([#5961](https://github.com/SickChill/SickChill/issues/5961))
* Update translations (build 10687) [skip ci]

### v2020.02.05-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.05-1...v2020.02.05-2)

* Fix build

### v2020.02.05-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.02-2...v2020.02.05-1)

* Force show updater to run on startup. Fix error where last_update was always set so older shows never updated. Get all show updates if not updated before rather than just 6 months in the past (older shows) Fix episodeguide in kodi nfo's and a logging bug
* Update translations (build 10681) [skip ci]

### v2020.02.02-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.02.02-1...v2020.02.02-2)

* Fix build

### v2020.02.02-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.29-4...v2020.02.02-1)

* Let's catch tvdbapi exceptions better
* Update translations (build 10675) [skip ci]

### v2020.01.29-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.29-3...v2020.01.29-4)

* Update cloudscraper and urllib3
* Update translations (build 10672) [skip ci]

### v2020.01.29-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.29-2...v2020.01.29-3)

* Fix error when adding show by tvdbid
* Update translations (build 10669) [skip ci]

### v2020.01.29-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.29-1...v2020.01.29-2)

* Add status as a sorting option on poster view. Sort better when loading page on poster view for next episode
* Do not cache posters, thumbs, banners, network logos until cachebreaking can be worked in or cache and gui can be combined for staticfiles.
* Update translations (build 10666) [skip ci]

### v2020.01.29-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.25-1...v2020.01.29-1)

* Fix ebuild
* Fix error when a show is added by the trakt checker
* Fixes [#5944](https://github.com/SickChill/SickChill/issues/5944) - Sorting posters by next episode
* Fixes [#5944](https://github.com/SickChill/SickChill/issues/5944) - Sorting posters by next episode
* Update translations (build 10650) [skip ci]

### v2020.01.25-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.24-1...v2020.01.25-1)

* Fixes [#5923](https://github.com/SickChill/SickChill/issues/5923)
* Update translations (build 10647) [skip ci]

### v2020.01.24-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.23-2...v2020.01.24-1)

* Fix apibuilder syntax error Fixes [#5922](https://github.com/SickChill/SickChill/issues/5922)

### v2020.01.23-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.23-1...v2020.01.23-2)

* Fix build
* Ability to sort the search results when adding a show. Click the table headers Fixes [#5917](https://github.com/SickChill/SickChill/issues/5917)

### v2020.01.23-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.21-1...v2020.01.23-1)

* Allow searching with imdbid (tt6546758 or 6546758 will bring up schooled) Do not delete episode if tvdb fails. Keep the data we have. [#5915](https://github.com/SickChill/SickChill/issues/5915) [#5912](https://github.com/SickChill/SickChill/issues/5912)
* Ability to append year to end of show dirs when adding shows. ([#5912](https://github.com/SickChill/SickChill/issues/5912))

### v2020.01.21-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.20-5...v2020.01.21-1)

* Force add 5090 to default nzb provider categories when HEVC is enabled. Fix being able to edit builtin nzb providers settings (on the Configure Custom Newznab Providers page)
* Don't warn when filling cache with show images and the show dir doesnt exist
* Fix footer rowspan on schedule and add trakt link to schedule poster and list layouts
* Use personal access tokens only for submitting issues (new github policy) ([#5909](https://github.com/SickChill/SickChill/issues/5909))

### v2020.01.20-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.20-4...v2020.01.20-5)

* Always include the show's all-season scene exception in search string, even if it has a season specific scene exception Fixes [#4974](https://github.com/SickChill/SickChill/issues/4974)

### v2020.01.20-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.20-3...v2020.01.20-4)

* Fix not being able to add scene season exceptions for most recent season of a show Fixes [#5905](https://github.com/SickChill/SickChill/issues/5905)

### v2020.01.20-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.20-2...v2020.01.20-3)

* Disable vcr for skytorrents, cloudflare breaking tests
* Fix parsing skytorrents
* Update requirements.txt (this file is NOT USED) Fixes [#5316](https://github.com/SickChill/SickChill/issues/5316)

### v2020.01.20-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.20-1...v2020.01.20-2)

* Fix skytorrents Fixes [#5579](https://github.com/SickChill/SickChill/issues/5579)

### v2020.01.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.19-7...v2020.01.20-1)

* Clean up some logs with proper thread names and make all missing networks go to the same issue
* Update isotope and dependancies. Try to fix empty space problem. Fixes [#5724](https://github.com/SickChill/SickChill/issues/5724)

### v2020.01.19-7

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.19-6...v2020.01.19-7)

* Don't error if show doesn't have any episodes

### v2020.01.19-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.19-5...v2020.01.19-6)

* Allow adding shows from the future with no episodes yet Fixes [#5588](https://github.com/SickChill/SickChill/issues/5588)

### v2020.01.19-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.19-4...v2020.01.19-5)

* Fixes [#5899](https://github.com/SickChill/SickChill/issues/5899)

### v2020.01.19-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.19-3...v2020.01.19-4)

* Typo, [#5900](https://github.com/SickChill/SickChill/issues/5900)
* Add a trakt icon link to the show page ([#5896](https://github.com/SickChill/SickChill/issues/5896))

### v2020.01.19-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.19-2...v2020.01.19-3)

* Only use nfo/xml when adding existing shows. Adding using the dir name to automatically search providers is unreliable. Instead, when metadata is missing, prompt to search and select the show manually

### v2020.01.19-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.19-1...v2020.01.19-2)

* Only show info log while creating kodi meta files when cannot find a show on tvdb, usually when the api is failing. Fixes [#5898](https://github.com/SickChill/SickChill/issues/5898)

### v2020.01.19-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.17-1...v2020.01.19-1)

* Allow lesser versions of python 2.7 (uses cfscrape, probably fails on many sites) Fixes [#5894](https://github.com/SickChill/SickChill/issues/5894)

### v2020.01.17-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.16-2...v2020.01.17-1)

* Also catch TypeError in episode_image_url when episode is not found. Fixes [#5874](https://github.com/SickChill/SickChill/issues/5874)
* Better way to check that a torrent was added in the old qbittorent client. Fixes [#5881](https://github.com/SickChill/SickChill/issues/5881) Fixes [#5016](https://github.com/SickChill/SickChill/issues/5016) Fixes [#4385](https://github.com/SickChill/SickChill/issues/4385) Thanks sumarimike

### v2020.01.16-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.16-1...v2020.01.16-2)

* Remove unnecessary api call to tvdb

### v2020.01.16-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.14-2...v2020.01.16-1)

* Use the correct method when loading episodes from indexer, so error handling is used. Fixes [#5879](https://github.com/SickChill/SickChill/issues/5879)
* check parent dir names in addition to current ([#5864](https://github.com/SickChill/SickChill/issues/5864))

### v2020.01.14-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.14-1...v2020.01.14-2)

* Handle regex substitution error when item to search for contains a repeat repeat such as ++ or ** Fixes [#5869](https://github.com/SickChill/SickChill/issues/5869)

### v2020.01.14-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.13-3...v2020.01.14-1)

* Handle adding a show when tvdb does not have it's start date. Fixes [#5867](https://github.com/SickChill/SickChill/issues/5867)

### v2020.01.13-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.13-2...v2020.01.13-3)

* Apply user supplied fix for bjshare from [#5591](https://github.com/SickChill/SickChill/issues/5591)#issuecomment-537029104 Fixes [#5591](https://github.com/SickChill/SickChill/issues/5591)

### v2020.01.13-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.13-1...v2020.01.13-2)

* Fixes [#5766](https://github.com/SickChill/SickChill/issues/5766) - Might need improved. Hides usernames/passwords if it is a full word. Also, hide jackett_apikey from logs
* Fixes [#5749](https://github.com/SickChill/SickChill/issues/5749) feature to avoid updating shows with status Ended for a set amount of days. Defaults to 7 days, configurable on config->general->interface

### v2020.01.13-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.12-4...v2020.01.13-1)

* Fix [#5863](https://github.com/SickChill/SickChill/issues/5863)

### v2020.01.12-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.12-3...v2020.01.12-4)

* Try again to fix build.

### v2020.01.12-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.12-2...v2020.01.12-3)

* Fix build hopefully. py3 is urgent
* Update FUNDING.yml

### v2020.01.12-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.12-1...v2020.01.12-2)

* Jacket url is returning a magnet when expecting a torrent file. Why not eliminate that 302 redirect and just put the magnet in the xml response instead.... Fixes [#5600](https://github.com/SickChill/SickChill/issues/5600) Fixes [#5862](https://github.com/SickChill/SickChill/issues/5862)

### v2020.01.12-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.11-1...v2020.01.12-1)

* Fixes [#5858](https://github.com/SickChill/SickChill/issues/5858) Fixes [#5859](https://github.com/SickChill/SickChill/issues/5859) Change rarbg url to rarbg.to

### v2020.01.11-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2020.01.03-1...v2020.01.11-1)

* Update bower and eslint in yarn.lock and package.json
* Call _location instead of location for show where necessary Fix [#5836](https://github.com/SickChill/SickChill/issues/5836) when info in nfo has & included Go supersaiyan on finding correct show from nfo, indexer and id, or show name should be enough, it is working fairly well
* Create FUNDING.yml ([#5835](https://github.com/SickChill/SickChill/issues/5835))
* Fix a potentially undefined result variable
* Use cloudscraper when running 2.7.9, cfscrape when running 2.7-2.7.8
* cloudscraper requires Python 2.7.9+ but less than 3! [#5829](https://github.com/SickChill/SickChill/issues/5829)
* Use cloudscraper for now. cfscrape is borked ([#5828](https://github.com/SickChill/SickChill/issues/5828))
* Apply [Anorov/cloudflare-scrape#315](https://github.com/Anorov/cloudflare-scrape/issues/315) ([#5827](https://github.com/SickChill/SickChill/issues/5827))
* Fix error on kodi12+ metadata relating to imdb country codes. Improve search results when show is not found the first time Remove writers and directors from kodi12+ metadata (info is not on tvdb for shows, only episodes)
* Fix error  updating trakt watchlist
* Adding Parsing for WebUHD like ([#5824](https://github.com/SickChill/SickChill/issues/5824))
* Fix error on genre split in webapi Fixes [#5825](https://github.com/SickChill/SickChill/issues/5825)
* Fix error with coverage==5 breaking codecov. Fixes build
* Fix show forced update and refresh (all episodes having same or no data on displayshow)
* Fix airdates, fix mistake on mediabrowser metadata, fix the rest of metdata
* Fix failure on most metadata providers. FIXME: tvdbapi returning no airdate for some episodes, such as schooled
* Tvdb3 ([#5789](https://github.com/SickChill/SickChill/issues/5789))
* Update translations (build 10488) [skip ci]

### v2020.01.03-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.12.22-1...v2020.01.03-1)

* Fix error when sending a download to rtorrent9 that caused item to not be seen as snatched Fixes [#5802](https://github.com/SickChill/SickChill/issues/5802)
* Ygg have changed their URL to www2.yggtorrent.ws ([#5801](https://github.com/SickChill/SickChill/issues/5801))
* Rename Shudder icon to correct name. Fixes [#5790](https://github.com/SickChill/SickChill/issues/5790)
* Update translations (build 10420) [skip ci]

### v2019.12.22-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.12.20-1...v2019.12.22-1)

* Fix js for rtorrent9 client
* Add DC Universe and Shutter network icons from [#5777](https://github.com/SickChill/SickChill/issues/5777)
* Rtorrent9 - rTorrent 0.9.0 compatible torrent client, while keeping the older client intact. ([#5787](https://github.com/SickChill/SickChill/issues/5787))
* Qbittorrent apiv2 ([#5785](https://github.com/SickChill/SickChill/issues/5785))
* Update translations (build 10408) [skip ci]

### v2019.12.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.12.19-1...v2019.12.20-1)

* Create greetings.yml ([#5775](https://github.com/SickChill/SickChill/issues/5775))

### v2019.12.19-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.11.28-1...v2019.12.19-1)

* Fix: logging of sent matrix messages was not properly escaped causing the page to break ([#5645](https://github.com/SickChill/SickChill/issues/5645))
* Implementation suggestion for "Prefer words" ([#5629](https://github.com/SickChill/SickChill/issues/5629)) ([#5699](https://github.com/SickChill/SickChill/issues/5699))
* Fixing error when accessing html for torrent size ([#5770](https://github.com/SickChill/SickChill/issues/5770))
* Update tvdb api to v3  (credits to @BenjV) ([#5738](https://github.com/SickChill/SickChill/issues/5738))
* Fix for [#5436](https://github.com/SickChill/SickChill/issues/5436) ([#5762](https://github.com/SickChill/SickChill/issues/5762))
* Add network logo for Apple TV Plus ([#5750](https://github.com/SickChill/SickChill/issues/5750))
* Added Disney+ network icon [#5759](https://github.com/SickChill/SickChill/issues/5759) ([#5761](https://github.com/SickChill/SickChill/issues/5761))
* Update translations (build 10367) [skip ci]

### v2019.11.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.09.02-1...v2019.11.28-1)

* Update depends
* Update xthor.py ([#5723](https://github.com/SickChill/SickChill/issues/5723))
* Update tvdb_api.py ([#5731](https://github.com/SickChill/SickChill/issues/5731))
* Merge pull request [#5701](https://github.com/SickChill/SickChill/issues/5701) from kmartin36/kmartin36-patch-5686-2
* Merge pull request [#5687](https://github.com/SickChill/SickChill/issues/5687) from kmartin36/kmartin36-patch-5686
* Merge pull request [#5667](https://github.com/SickChill/SickChill/issues/5667) from VixsTy/fix/xthor-fqdn-change
* Schedule View - add banner to list ([#5653](https://github.com/SickChill/SickChill/issues/5653))
* Bump lodash.merge from 4.6.1 to 4.6.2 ([#5639](https://github.com/SickChill/SickChill/issues/5639))
* Bump mixin-deep from 1.3.1 to 1.3.2 ([#5640](https://github.com/SickChill/SickChill/issues/5640))
* Update index.py ([#5625](https://github.com/SickChill/SickChill/issues/5625))
* Merge pull request [#5618](https://github.com/SickChill/SickChill/issues/5618) from mvn23/patch-3
* Update translations (build 10323) [skip ci]

### v2019.09.02-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.06.28-1...v2019.09.02-1)

* Merge pull request [#5617](https://github.com/SickChill/SickChill/issues/5617) from SickChill/develop

* Release dev to master

### v2019.06.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.06.27-2...v2019.06.28-1)

* Update \_\_init\_\_.py ([#5556](https://github.com/SickChill/SickChill/issues/5556))

### v2019.06.27-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.06.27-1...v2019.06.27-2)

* Issue 5551 ([#5552](https://github.com/SickChill/SickChill/issues/5552))
* Update translations (build 10292) [skip ci]

### v2019.06.27-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.05.31-1...v2019.06.27-1)

* Merge branch 'develop'
* Update translations (build 10222) [skip ci]
* Remove ncu, fixes WS-2018-0076
* Update translations (build 10205) [skip ci]

### v2019.05.31-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.05.26-1...v2019.05.31-1)

* Patch urllib3 ciphers
* Fix typo
* change seeders and leechers label strings to reflect site changes

### v2019.05.26-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.05.24-1...v2019.05.26-1)

* Update translations (build 10187) [skip ci]
* deluged: make labels the same across all files
* Update translations (build 10183) [skip ci]

### v2019.05.24-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.05.20-1...v2019.05.24-1)

* Update config_search.mako
* merges divs into one, and labels renamed as requested
* Deluged: add download and completed dirs to config
* Update init.systemd
* Update translations (build 10170) [skip ci]

### v2019.05.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.05.15-3...v2019.05.20-1)

* Remove NZBS.org, fixes [#5490](https://github.com/SickChill/SickChill/issues/5490) ([#5492](https://github.com/SickChill/SickChill/issues/5492))
* Fix issue with session headers ([#5491](https://github.com/SickChill/SickChill/issues/5491))
* Branch matrix notifications ([#5377](https://github.com/SickChill/SickChill/issues/5377))

### v2019.05.15-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.05.15-2...v2019.05.15-3)

* Update stale.yml

### v2019.05.15-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.05.15-1...v2019.05.15-2)

* Update yarn packages

### v2019.05.15-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.04.07-1...v2019.05.15-1)

* Bump cfscrape version to 2.0.0 ([#5462](https://github.com/SickChill/SickChill/issues/5462))
* Update ygg URL due to TLD migration ([#5468](https://github.com/SickChill/SickChill/issues/5468))
* feat: Slack Icon options ([#5424](https://github.com/SickChill/SickChill/issues/5424))
* Update usenet-crawler URL  ([#5433](https://github.com/SickChill/SickChill/issues/5433))
* Add notification after postprocessin (SickChill[#4348](https://github.com/SickChill/SickChill/issues/4348)) ([#5444](https://github.com/SickChill/SickChill/issues/5444))
* new url ([#5445](https://github.com/SickChill/SickChill/issues/5445))
* Changed search order to 7 as 8 was the least seeders first. Probably browser and search order was unified at some point. ([#5434](https://github.com/SickChill/SickChill/issues/5434))
* Fix broken unrar validation. ([#5396](https://github.com/SickChill/SickChill/issues/5396))

### v2019.04.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2019.01.06-1...v2019.04.07-1)

* Upgrade cfscrape to version 1.9.7 ([#5405](https://github.com/SickChill/SickChill/issues/5405))
* Update \_\_init\_\_.py 1.9.6 ([#5374](https://github.com/SickChill/SickChill/issues/5374))
* corrected poster.png ([#5356](https://github.com/SickChill/SickChill/issues/5356))
* Update ygg search url ([#5349](https://github.com/SickChill/SickChill/issues/5349))
* Fix orig_root_dir comparison between str/unicode ([#5275](https://github.com/SickChill/SickChill/issues/5275))
* Adding support for SSL into Docker container ([#5315](https://github.com/SickChill/SickChill/issues/5315))
* Add Irib TV1 and Qatar TV networks icons ([#5319](https://github.com/SickChill/SickChill/issues/5319))
* Update library's after removing shows ([#5282](https://github.com/SickChill/SickChill/issues/5282))
* Add logo for Epix network ([#5272](https://github.com/SickChill/SickChill/issues/5272))
* Update translations (build 10034) [skip ci]

### v2019.01.06-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.12.24-1...v2019.01.06-1)

* Fixes Gimmepeers timeout issue and syntax ([#5263](https://github.com/SickChill/SickChill/issues/5263))
* Update translations (build 10027) [skip ci]

### v2018.12.24-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.12.19-1...v2018.12.24-1)

* Update stale.yml ([#5257](https://github.com/SickChill/SickChill/issues/5257))
* Grunt, Update translations (build 10022) [skip ci]

### v2018.12.19-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.11.30-1...v2018.12.19-1)

* Fix [#5244](https://github.com/SickChill/SickChill/issues/5244): add new Torrent9 indexer file prefix 'Torrent9.PH ---> ' ([#5249](https://github.com/SickChill/SickChill/issues/5249))
* Torrent9 custom url ([#5246](https://github.com/SickChill/SickChill/issues/5246))
* Updating cfscrape to 1.9.5 ([#5243](https://github.com/SickChill/SickChill/issues/5243))
* update youtube.png and added youtube red/premium ([#5240](https://github.com/SickChill/SickChill/issues/5240))
* Update SpeedCD HTML parser ([#5226](https://github.com/SickChill/SickChill/issues/5226))
* Remove NotifyMyAndroid, service stopped ([#5231](https://github.com/SickChill/SickChill/issues/5231))
* Update Usenet-Crawler URL to new API endpoint ([#5223](https://github.com/SickChill/SickChill/issues/5223))
* Grunt, Update translations (build 9985) [skip ci]

### v2018.11.30-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.11.22-1...v2018.11.30-1)

* Use all subcategory on YggTorrent, to catch anime and documentaries better ([#5210](https://github.com/SickChill/SickChill/issues/5210))
* Update translations (build 9972) [skip ci]

### v2018.11.22-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.11.07-1...v2018.11.22-1)

* Hoskar2ben patch 1 ([#5199](https://github.com/SickChill/SickChill/issues/5199))
* Prevent error when trying to copy and source file is already an existing hard link to the destination, or when doing reverse symlinks. Also allow copying file mode when this is true. ([#5173](https://github.com/SickChill/SickChill/issues/5173))
* Update translations (build 9945) [skip ci]

### v2018.11.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.31-1...v2018.11.07-1)

* install nodejs in Docker ([#5171](https://github.com/SickChill/SickChill/issues/5171))
* Force subliminal to save subtitle in UTF8 ([#3989](https://github.com/SickChill/SickChill/issues/3989))
* Add magnetdl.com provider. May need some adjustment ([#5165](https://github.com/SickChill/SickChill/issues/5165))
* Update yggtorrent.py ([#5150](https://github.com/SickChill/SickChill/issues/5150))
* Update ignorewords and requirewords to be fully case insensitive ([#5153](https://github.com/SickChill/SickChill/issues/5153))
* Update translations (build 9915) [skip ci]

### v2018.10.31-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.30-6...v2018.10.31-1)

* Add probot to automatically close stale issues Fixes [#5145](https://github.com/SickChill/SickChill/issues/5145)
* Update translations (build 9911) [skip ci]

### v2018.10.30-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.30-5...v2018.10.30-6)

* Change requests requirements to exclude vulnerability.
* Subs Notification for Slack ([#4150](https://github.com/SickChill/SickChill/issues/4150))
* Update translations (build 9904) [skip ci]

### v2018.10.30-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.30-4...v2018.10.30-5)

* Fix build
* Fix build

### v2018.10.30-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.30-3...v2018.10.30-4)

* Bad search/replace

### v2018.10.30-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.30-2...v2018.10.30-3)

* Do not quote_plus params/payload/post data in dicts. Fixes [#5110](https://github.com/SickChill/SickChill/issues/5110)
* Update translations (build 9893) [skip ci]

### v2018.10.30-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.30-1...v2018.10.30-2)

* isort, fix build

### v2018.10.30-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.29-2...v2018.10.30-1)

* Dont pass season/ep param when using torznab. (Torznab should ignore season/ep if they dont support tvdbid - either q OR tvdbid/season/ep should be used, it isnt a mix and match) ([#5138](https://github.com/SickChill/SickChill/issues/5138))
* Porzino develop ([#5134](https://github.com/SickChill/SickChill/issues/5134))
* Update translations (build 9869) [skip ci]

### v2018.10.29-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.29-1...v2018.10.29-2)

* Try and catch the node error generated by cfscrape "s,t,o,p,b,r,e,a,k,i,n,g" Use translations for log entries generated in helpers.
* add tzdata package  #issue 5130
* Update translations (build 9863) [skip ci]

### v2018.10.29-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.28-1...v2018.10.29-1)

* Fix [#5126](https://github.com/SickChill/SickChill/issues/5126) - Temporary versions for loading images when adding a new show. Simply the temporary logo text with an "ice" background
* Update translations (build 9854) [skip ci]

### v2018.10.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.27-2...v2018.10.28-1)

* Fix [#5127](https://github.com/SickChill/SickChill/issues/5127)
* add support for biglybt and vuze
* Update README w/ more links, clearer language ([#5078](https://github.com/SickChill/SickChill/issues/5078))
* Update translations (build 9844) [skip ci]

### v2018.10.27-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.27-1...v2018.10.27-2)

* sickchill length for js slice

### v2018.10.27-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.16-3...v2018.10.27-1)

* Update translations (build 9840) [skip ci]
* Have to redo this whole test once I think about it more.
* change_unrar_tool
* Fix icorsaronero more
* change_unrar_tool is difficult to test.
* isort
* Fix skytorrents, horriblesubs, ilcorsaronero, torrent9
* Set record mode to new_episodes
* Torrent9 changed domain
* Re-Vanilla rarfile and rewrite change_unrar_tool and the test. Update enzyme.
* Set default timezone for unknown network timezones to US/Eastern
* Catch ValueError to try and see the cfscrape error in the log rather than sending it to the issue tracker. Upgrade cfscrape depends (includes urllib3, requests, certifi, etc)
* Remove broken screenshot links pending valid ones
* Change the way we add labels (And now possible to use torrent path, but the UI does not support it yet) for qBittorrent. [#5095](https://github.com/SickChill/SickChill/issues/5095)
* Add gitter webhook to travis
* Update translations (build 9798) [skip ci]

### v2018.10.16-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.16-2...v2018.10.16-3)

* Fix rawgit issue
* Update translations (build 9793) [skip ci]

### v2018.10.16-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.16-1...v2018.10.16-2)

* Archetorrent error from [#4447](https://github.com/SickChill/SickChill/issues/4447) - Maybe there is a login issue?

### v2018.10.16-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.15-4...v2018.10.16-1)

* fix mask icon issue
* Update translations (build 9783) [skip ci]

### v2018.10.15-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.15-3...v2018.10.15-4)

* Fix detection of *rage* in git_remote_url on config.ini
* Refactor-rename sickrage_tests to sickchill_tests Remove street sharks mascot
* Icons
* Update translations (build 9773) [skip ci]

### v2018.10.15-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.15-2...v2018.10.15-3)

* Revert "Update imdbpy -Fixes star ratings on displayShow"
* Revert "Use main imdb url like imdbpy, instead of akas"
* Revert "Patch imdbpy for etree error. Please test"
* Patch imdbpy for etree error. Please test
* Revert "Remove lxml since imdbpy loads it without error handling."
* Remove lxml since imdbpy loads it without error handling.

### v2018.10.15-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.15-1...v2018.10.15-2)

* Add another empty string falback in processDir for xhtml_escape

### v2018.10.15-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.14-3...v2018.10.15-1)

* Fix 16,32 size icons
* Made some rudimentary images to use for icons/logos for now
* Use main imdb url like imdbpy, instead of akas
* Update translations (build 9758) [skip ci]

### v2018.10.14-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.14-2...v2018.10.14-3)

* Update imdbpy -Fixes star ratings on displayShow Fixes [#5061](https://github.com/SickChill/SickChill/issues/5061)
* Update translations (build 9756) [skip ci]

### v2018.10.14-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.14-1...v2018.10.14-2)

* Log actual data when torrent can't be bedecoded (Usually credentials or ratio issue)
* Update translations (build 9752) [skip ci]

### v2018.10.14-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.13-6...v2018.10.14-1)

* Update app id for rarbg
* Add Indonesian translation option
* Revert "Have to use sickrage as crowdin project identifier until crowdin staff respond. I renamed the project there but cannot rename the identifier."
* Have to use sickrage as crowdin project identifier until crowdin staff respond. I renamed the project there but cannot rename the identifier.

### v2018.10.13-6

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.13-5...v2018.10.13-6)

* Update translations (build 9747) [skip ci]

### v2018.10.13-5

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.13-4...v2018.10.13-5)

* Change to toplevel SickChill irc room
* Remove pullaprove
* Update translations (build 9743) [skip ci]

### v2018.10.13-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.13-3...v2018.10.13-4)

* Fix broken image links in readme
* Update pullaprove
* Update translations (build 9697) [skip ci]

### v2018.10.13-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.13-2...v2018.10.13-3)

* Update default usenet-crawler url Add pullaprove (may remove, not sure if we need this or if the built in one from github works better) Update docker-compose to use our official sickchill/sickchill from docker-hub registry

### v2018.10.13-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.13-1...v2018.10.13-2)

* Update dockerfile

### v2018.10.13-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.12-1...v2018.10.13-1)

* Compile translations
* Fix some more references to the wrong URLS.

### v2018.10.12-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.10-2...v2018.10.12-1)

* Fix travis push
* Error
* Grunt
* Mass renaming, THERE WILL BE A FEW ERRORS

### v2018.10.10-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.10-1...v2018.10.10-2)

* Update translations (build 9616) [skip ci]

### v2018.10.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.06-2...v2018.10.10-1)

* Typo (!s vs :s)
* Update db.py
* Update db.py
* Update translations (build 9612) [skip ci]

### v2018.10.06-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.10.06-1...v2018.10.06-2)

* Typo
* Update translations (build 9595) [skip ci]

### v2018.10.06-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.09.17-1...v2018.10.06-1)

* Print tag for debug
* Update translations (build 9593) [skip ci]
* Update translations
* Update most links in repo
* Update readme
* Update translations (build 9586) [skip ci]

### v2018.09.17-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.09.14-2...v2018.09.17-1)

* Fixes [#4959](https://github.com/SickChill/SickChill/issues/4959) - By avoiding phony imdbid and info, and also providing a usable dict to avoid keyerrors
* Update translations (build 9582) [skip ci]

### v2018.09.14-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.09.14-1...v2018.09.14-2)

* Fix [#4856](https://github.com/SickChill/SickChill/issues/4856) - Upsert could be called with empty values for imdb_info

### v2018.09.14-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.09.13-3...v2018.09.14-1)

* Add back columnSelector to Gruntfile, which is not included in jquery.tablesorter.combined.js
* Update translations (build 9575) [skip ci]

### v2018.09.13-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.09.13-2...v2018.09.13-3)

* Merge branch 'develop'
* Update translations (build 9562) [skip ci]

### v2018.09.13-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.09.13-1...v2018.09.13-2)

* Fix releae when commit messages have double quotes

### v2018.09.13-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.07.21-1...v2018.09.13-1)

* Detect yggtorrent url automatically, but only when it is enabled and used and a login is attempted Add custom url functionality to the provider Fixes [#4914](https://github.com/SickChill/SickChill/issues/4914) Fixes [#4931](https://github.com/SickChill/SickChill/issues/4931)
* Update requirements.txt to reflect protection against CVE-2017-7235
* Fixes [#3987](https://github.com/SickChill/SickChill/issues/3987)
* Remove domain auto detection
* Add anime subcategory for YGG
* Auto detect YGG domain name
* Move verbose regex above scene_date_format to fix [#4839](https://github.com/SickChill/SickChill/issues/4839)
* change yggtorrent url
* Changed "Download Finished" Notification String
* Fix issue [#4675](https://github.com/SickChill/SickChill/issues/4675) (Filelist provider not working)
* Provider changed the domain
* Update translations (build 9519) [skip ci]

### v2018.07.21-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.07.18-2...v2018.07.21-1)

* change yggtorrent url
* Update translations (build 9513) [skip ci]

### v2018.07.18-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.07.18-1...v2018.07.18-2)

* Fix red text warnings on provider settings
* Add helper functions to make sure enable_daily, enable_backlog, and search_fallback are integers Fixes [#4721](https://github.com/SickChill/SickChill/issues/4721) Closes [#4829](https://github.com/SickChill/SickChill/issues/4829)
* Add new provider: BJ-Share (Brazillian) ([#4727](https://github.com/SickChill/SickChill/issues/4727))
* Update translations (build 9506) [skip ci]

### v2018.07.18-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.06.15-1...v2018.07.18-1)

* run isort to fix import order
* fix import order
* fix order \_\_init\_\_.py
* add gimmepeers icon + \_\_init\_\_ + gimmepeers.py
* Move inside ss
* Fix [#4771](https://github.com/SickChill/SickChill/issues/4771)
* change yggtorrent url
* Fixed manual post processing not honouring settings when moving files
* Do not assume that torrenttable div will be present and well formed.
* Update translations (build 9487) [skip ci]

### v2018.06.15-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.06.10-1...v2018.06.15-1)

* Fix comments.
* Update cassette test to be consistant with the new requests.
* Iterate on each row of the table.
* FIX your changes
* Fix issue when trying to download torrent from torrent9 tracker.
* add missing '/' for for limetorrents rss search
* fix limetorrent search
* Fix danishbits daily search
* Update Scenetime provider after api change
* Add TV UHD category
* Update speedcd.py
* Update travis-ci python version
* Fix appveyor build
* Grunt, Update translations (build 9460) [skip ci]

### v2018.06.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.05.11-1...v2018.06.10-1)

* apostrophe fix
* more apostrophe fixes
* YggTorrent : Fix for session expiration (very short)
* Adding missing Dutch network names: BNN-VARA, KRO-NCRV and Videoland (NL)
* Apostrophe fixes
* Unescape HTML in paths in WebFileBrowser
* Update translations (build 9432) [skip ci]

### v2018.05.11-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.04.08-1...v2018.05.11-1)

* Fix bad YggTorrent credentials handling
* Update sublimina to latest develop, with added [Diaoul/Subliminal#836](https://github.com/Diaoul/Subliminal/issues/836) for a temporary fix to format.lower issue Fixes [#4546](https://github.com/SickChill/SickChill/issues/4546) Signed-off-by: miigotu <miigotu@gmail.com>
* Fix the number of columns error in tfoot of the compact view in history.mako
* Typo
* Rename check_db_version to get_db_version
* Clean up db.py and fix logging when database errors occur. Added extra information to help debug database issues.
* Remove invalid js file reference and make nzb splitter request failure only a warning
* Implement broken provider notifications and disable feedparser test until a replacement to binsearch is available or the test is reworked. unescape rss, client, and custom urls Fixes [#4624](https://github.com/SickChill/SickChill/issues/4624) Fixes [#4548](https://github.com/SickChill/SickChill/issues/4548) Signed-off-by: miigotu <miigotu@gmail.com>
* Try and fix appveyor
* Try and fix appveyor
* Updated .in TLDs to .lol in test definitions
* Skytorrents URL changed to proper ending
* Add Paramount Network logo
* Update translations (build 9390) [skip ci]

### v2018.04.08-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.04.02-1...v2018.04.08-1)

* Update the YggTorrent provider due to the new version of the website
* Update \_\_init\_\_.py
* Add todo
* Update provider to call the torrentleech v5 paths
* Update translations (build 9377) [skip ci]

### v2018.04.02-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.25-2...v2018.04.02-1)

* Resolved Jackett snatching malfunction
* Check for other shows using the same location before deleting a show, and if so remove individual files instead [#4441](https://github.com/SickChill/SickChill/issues/4441)
* Update translations (build 9368) [skip ci]

### v2018.03.25-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.25-1...v2018.03.25-2)

* Prevent deleting a folder if other shows use the folder as a root dir. Temporary workaround as this should use sql to check and also remove episodes by location. [#4441](https://github.com/SickChill/SickChill/issues/4441)
* Update translations (build 9360) [skip ci]

### v2018.03.25-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.23-1...v2018.03.25-1)

* Merge branch 'develop'
* Update translations (build 9345) [skip ci]

### v2018.03.23-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.22-1...v2018.03.23-1)

* Update Torrent9.py ([#4435](https://github.com/SickChill/SickChill/issues/4435))
* Cast to the correct types and objects for comparison to skip writing out a new tvshow.nfo Fixes [#4428](https://github.com/SickChill/SickChill/issues/4428) Closes [#4429](https://github.com/SickChill/SickChill/issues/4429)
* Don't recreate tvshow.nfo unnecessarily
* Update translations (build 9329) [skip ci]

### v2018.03.22-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.19-2...v2018.03.22-1)

* Add browser to list of requested information for bug reports
* Fixed [#4225](https://github.com/SickChill/SickChill/issues/4225) - Use indexOf instead of findIndex and set headers in webserverve.searchIndexersForShowName for cache and content type
* Update translations (build 9316) [skip ci]

### v2018.03.19-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.19-1...v2018.03.19-2)

* Update itasa for new subliminal
* Update subliminal Fixed [#4153](https://github.com/SickChill/SickChill/issues/4153) [#4400](https://github.com/SickChill/SickChill/issues/4400) - Update subliminal to [4ad5d31](https://github.com/SickChill/SickChill/commit/4ad5d31a6c52c7fa0061ad0da16254580d31dc2a)
* Update translations (build 9307) [skip ci]

### v2018.03.19-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.17-2...v2018.03.19-1)

* Fixed [#4304](https://github.com/SickChill/SickChill/issues/4304) by using a workaround for TD api failures
* Update pynma.py
* Update translations (build 9296) [skip ci]

### v2018.03.17-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.17-1...v2018.03.17-2)

* Add weak.pem (shouldnt be needed)
* Grunt, Update translations (build 9292) [skip ci]

### v2018.03.17-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.12-1...v2018.03.17-1)

* Merge branch 'develop'

### v2018.03.12-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.11-1...v2018.03.12-1)

* Merge branch 'develop'

### v2018.03.11-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.10-3...v2018.03.11-1)

* Merge branch 'develop'

### v2018.03.10-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.10-2...v2018.03.10-3)

* Merge branch 'develop'

### v2018.03.10-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.10-1...v2018.03.10-2)

* Merge branch 'develop'

### v2018.03.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.03.09-1...v2018.03.10-1)

* Merge branch 'develop'

### v2018.03.09-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.02.26-2...v2018.03.09-1)

* Merge branch 'develop'

### v2018.02.26-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.02.26-1...v2018.02.26-2)

* Merge branch 'develop'

### v2018.02.26-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.02.17-1...v2018.02.26-1)

* Merge branch 'develop'

### v2018.02.17-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.02.06-1...v2018.02.17-1)

* Merge branch 'develop'

### v2018.02.06-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2018.01.24-1...v2018.02.06-1)

* Merge branch 'develop'

### v2018.01.24-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.12.19-1...v2018.01.24-1)

* Merge branch 'develop'

### v2017.12.19-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.12.17-1...v2017.12.19-1)

* Merge branch 'develop'

### v2017.12.17-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.12.16-1...v2017.12.17-1)

* Fix [#4200](https://github.com/SickChill/SickChill/issues/4200)

### v2017.12.16-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.06.05-1...v2017.12.16-1)

* Revert "remove parens from commit messages for publish"
* remove parens from commit messages for publish
* Miigotu patch 1 ([#4198](https://github.com/SickChill/SickChill/issues/4198))
* Fix Jackett ([#4197](https://github.com/SickChill/SickChill/issues/4197))
* Remove self.include_host to fix reverse proxying. Fixes [#3959](https://github.com/SickChill/SickChill/issues/3959) ([#4194](https://github.com/SickChill/SickChill/issues/4194))
* API Subtitle, Proper, and Daily Search ([#4193](https://github.com/SickChill/SickChill/issues/4193))
* Update thepiratebay.py ([#4192](https://github.com/SickChill/SickChill/issues/4192))
* hot fix for ygg ([#4170](https://github.com/SickChill/SickChill/issues/4170))
* Update xthor.py ([#4161](https://github.com/SickChill/SickChill/issues/4161))
* Quick fix due to the change of the site yggtorrent ([#4154](https://github.com/SickChill/SickChill/issues/4154))
* Fix issue with jackett hopefully (untested) ([#4152](https://github.com/SickChill/SickChill/issues/4152))
* Add Yggtorrent, remove T411, fix Cpasbien ([#4118](https://github.com/SickChill/SickChill/issues/4118))
* Elitetorrent provider - New web address ([#4122](https://github.com/SickChill/SickChill/issues/4122))
* Add sane name preset ([#4112](https://github.com/SickChill/SickChill/issues/4112))
* Add provider YggTorrent ([#3963](https://github.com/SickChill/SickChill/issues/3963))
* Responsive add show page ([#3580](https://github.com/SickChill/SickChill/issues/3580))
* Merge pull request [#4017](https://github.com/SickChill/SickChill/issues/4017) from Goeny/patch-2
* Python libraries - trivial updates ([#3993](https://github.com/SickChill/SickChill/issues/3993))
* Scene exceptions ui ([#4000](https://github.com/SickChill/SickChill/issues/4000))
* Fix tooltips and manual search ([#3994](https://github.com/SickChill/SickChill/issues/3994))
* Create Safari pinned tab icon. ([#3996](https://github.com/SickChill/SickChill/issues/3996))
* Fix ItaSa login ([#3991](https://github.com/SickChill/SickChill/issues/3991))
* Season_folders was inverted ([#3979](https://github.com/SickChill/SickChill/issues/3979))
* Fix Safari JS errors ([#3966](https://github.com/SickChill/SickChill/issues/3966))
* Fix IndexError in error submitter ([#3957](https://github.com/SickChill/SickChill/issues/3957))
* Delete provider T411 ([#3954](https://github.com/SickChill/SickChill/issues/3954))
* Update tox `py27-flake8` test-env ([#3947](https://github.com/SickChill/SickChill/issues/3947))
* Fix UI bugs ([#3944](https://github.com/SickChill/SickChill/issues/3944))
* Refactor fetching remote branches (/config/general/) ([#3945](https://github.com/SickChill/SickChill/issues/3945))
* Fix SkyTorrents ([#3946](https://github.com/SickChill/SickChill/issues/3946))
* Fix calendar link and CalendarHandler route (allow trailing slash) ([#3943](https://github.com/SickChill/SickChill/issues/3943))
* Update Torrent9 URL and fix tests ([#3942](https://github.com/SickChill/SickChill/issues/3942))
* Add a Grunt exec:test task that runs the 'test' script ([#3939](https://github.com/SickChill/SickChill/issues/3939))
* add ava testing ([#3930](https://github.com/SickChill/SickChill/issues/3930))
* Filter commits in grunt/exec/git_list_changes task ([#3937](https://github.com/SickChill/SickChill/issues/3937))
* Fix issue with variable in static_url call, add more static calls ([#3921](https://github.com/SickChill/SickChill/issues/3921))
* Add midgetspy back to copywrite, because echelon sent a DMCA. ([#3938](https://github.com/SickChill/SickChill/issues/3938))
* Merge pull request [#3923](https://github.com/SickChill/SickChill/issues/3923) from SickRage/lint-js_libs
* core.js: Switch .checked on jQuery elements to .is('checked') ([#3926](https://github.com/SickChill/SickChill/issues/3926))
* Merge pull request [#3922](https://github.com/SickChill/SickChill/issues/3922) from SickRage/lint_js-click-to-on
* Merge pull request [#3919](https://github.com/SickChill/SickChill/issues/3919) from SickRage/lint_corejs
* Docker support ([#3901](https://github.com/SickChill/SickChill/issues/3901))
* Switched to use sickbeard's TMDB API key. ([#3920](https://github.com/SickChill/SickChill/issues/3920))
* Swap jshint with xo (+2 more small fixes) ([#3916](https://github.com/SickChill/SickChill/issues/3916))
* Re-apply isort ([#3908](https://github.com/SickChill/SickChill/issues/3908))
* Test Skytorrents ([#3911](https://github.com/SickChill/SickChill/issues/3911))
* Update requirements list ([#3912](https://github.com/SickChill/SickChill/issues/3912))
* Fixed TMDB API key. ([#3909](https://github.com/SickChill/SickChill/issues/3909))
* Switched from thewiz to the new version - wizdom. ([#3900](https://github.com/SickChill/SickChill/issues/3900))
* Update ilcorsaronero (+isort config) ([#3906](https://github.com/SickChill/SickChill/issues/3906))
* Enable and use `static_url` function in all templates ([#3873](https://github.com/SickChill/SickChill/issues/3873))
* Update .codecov.yml ([#3876](https://github.com/SickChill/SickChill/issues/3876))
* Additional IndexError handling ([#3890](https://github.com/SickChill/SickChill/issues/3890))
* Updates to SkyTorrents and Nyaa ([#3889](https://github.com/SickChill/SickChill/issues/3889))
* Requirements list ([#3888](https://github.com/SickChill/SickChill/issues/3888))
* Update Python dependencies - 2nd batch ([#3877](https://github.com/SickChill/SickChill/issues/3877))
* Fix [#3631](https://github.com/SickChill/SickChill/issues/3631) (includes a minor API change) ([#3882](https://github.com/SickChill/SickChill/issues/3882))
* Use `fa-fw` for fixed-width icons in navbar (looks better) ([#3883](https://github.com/SickChill/SickChill/issues/3883))
* Git auto-update - always prune remotes when fetching ([#3885](https://github.com/SickChill/SickChill/issues/3885))
* Update .gitattributes ([#3886](https://github.com/SickChill/SickChill/issues/3886))
* Set a fixed width to the Network column in the Mass Update table ([#3887](https://github.com/SickChill/SickChill/issues/3887))
* Update Python dependencies (requests, python-twitter) ([#3870](https://github.com/SickChill/SickChill/issues/3870))
* Fix bdecode regression ([#3871](https://github.com/SickChill/SickChill/issues/3871))
* Show floating notification badge in small views ([#3872](https://github.com/SickChill/SickChill/issues/3872))
* BTN: append quality on release name if not present ([#3874](https://github.com/SickChill/SickChill/issues/3874))
* Fix notifications overwriting each-other because of duplicate ids ([#3868](https://github.com/SickChill/SickChill/issues/3868))
* Update MoreThanTV Provider - Allow for proper season searches ([#3854](https://github.com/SickChill/SickChill/issues/3854))
* Restore `bencode` library to vanilla state ([#3858](https://github.com/SickChill/SickChill/issues/3858))
* fix missing network discovery channel (uk) ([#3862](https://github.com/SickChill/SickChill/issues/3862))
* Fix BTN Anime search ([#3851](https://github.com/SickChill/SickChill/issues/3851))
* Added support for TheWiz Hebrew subtitles website. ([#3650](https://github.com/SickChill/SickChill/issues/3650))
* ajaxNotifications.js: Replace base64 image with actual image ([#3859](https://github.com/SickChill/SickChill/issues/3859))
* Update subscenter domain to .info ([#3861](https://github.com/SickChill/SickChill/issues/3861))
* Try and fix multiple desktop notifications ([#3837](https://github.com/SickChill/SickChill/issues/3837))
* Fix qBittorrent ([#3836](https://github.com/SickChill/SickChill/issues/3836))

### v2017.06.05-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.05.23-1...v2017.06.05-1)

* Sorry about that.. Fixed breaking change. ([#3825](https://github.com/SickChill/SickChill/issues/3825))
* updating torrentday provider to use the new api ([#3830](https://github.com/SickChill/SickChill/issues/3830))
* lossless compression of images saved 2.1MB ([#3827](https://github.com/SickChill/SickChill/issues/3827))
* Fix providers, fix tests, fix build... ([#3826](https://github.com/SickChill/SickChill/issues/3826))
* Disable new SubsCenter provider from [#3820](https://github.com/SickChill/SickChill/issues/3820) - The unregister/register causes SR to not start for me
* Fix issue submitter regex and auto log submission ([#3822](https://github.com/SickChill/SickChill/issues/3822))
* Hotfix/subscenter fix ([#3820](https://github.com/SickChill/SickChill/issues/3820))
* Update config_notifications.mako ([#3803](https://github.com/SickChill/SickChill/issues/3803))
* Add username & pass to subscenter ([#3813](https://github.com/SickChill/SickChill/issues/3813))
* Fixes [#2809](https://github.com/SickChill/SickChill/issues/2809) ([#3812](https://github.com/SickChill/SickChill/issues/3812))
* Danishbits provider now abides by their new rules, using couchpotato.php as systems are not allowed to search torrents.php. ([#3811](https://github.com/SickChill/SickChill/issues/3811))
* Nyaa RSS update ([#3793](https://github.com/SickChill/SickChill/issues/3793))
* Fix [#3795](https://github.com/SickChill/SickChill/issues/3795) + added test for cert generation ([#3796](https://github.com/SickChill/SickChill/issues/3796))

### v2017.05.23-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.05.21-1...v2017.05.23-1)

* Re-add language names ([#3790](https://github.com/SickChill/SickChill/issues/3790))
* Fix source update notification ([#3784](https://github.com/SickChill/SickChill/issues/3784))
* Remove Freshon.tv provider ([#3789](https://github.com/SickChill/SickChill/issues/3789))

### v2017.05.21-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.05.10-1...v2017.05.21-1)

* Remove ExtraTorrent ([#3765](https://github.com/SickChill/SickChill/issues/3765))
* Add Nyaa.si provider ([#3754](https://github.com/SickChill/SickChill/issues/3754))
* Fixed sorting error where double/triple headers with the same air date & time show in random order. ([#3776](https://github.com/SickChill/SickChill/issues/3776))
* Generate self-signed certificates using 'sha256' digest ([#3777](https://github.com/SickChill/SickChill/issues/3777))
* Update requests to 2.14.2 (was 2.13.0) ([#3762](https://github.com/SickChill/SickChill/issues/3762))
* Attempt to fix [#3656](https://github.com/SickChill/SickChill/issues/3656) ([#3748](https://github.com/SickChill/SickChill/issues/3748))
* Changed Transmithe.net to Nebulance.io ([#3747](https://github.com/SickChill/SickChill/issues/3747))

### v2017.05.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.05.07-1...v2017.05.10-1)

* Fix name parser for regex which thinks there are more than 4 episodes ([#3742](https://github.com/SickChill/SickChill/issues/3742))
* Added Season Search mode in torrent9.py ([#3732](https://github.com/SickChill/SickChill/issues/3732))

### v2017.05.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.05.04-1...v2017.05.07-1)

* Site messages 'tag', enhancements for translations ([#3718](https://github.com/SickChill/SickChill/issues/3718))
* Fix git error logging ([#3724](https://github.com/SickChill/SickChill/issues/3724))
* Fix HorribleSubs search with group constraint ([#3719](https://github.com/SickChill/SickChill/issues/3719))
* prevent obvious bad date from changing statuses ([#3723](https://github.com/SickChill/SickChill/issues/3723))
* Update Python dependencies ([#3716](https://github.com/SickChill/SickChill/issues/3716))
* Remove NyaaTorrents ([#3717](https://github.com/SickChill/SickChill/issues/3717))
* Add option to show/hide snatched episodes in Schedule ([#3720](https://github.com/SickChill/SickChill/issues/3720))

### v2017.05.04-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.05.02-1...v2017.05.04-1)

* Support adding LabelPlus labels to Deluge client torrents. ([#3713](https://github.com/SickChill/SickChill/issues/3713))
* Standardize GIT errors ([#3710](https://github.com/SickChill/SickChill/issues/3710))
* Fallback to magnet links for HorribleSubsProvider ([#3712](https://github.com/SickChill/SickChill/issues/3712))
* qBittorrent: Verify torrent was added ([#3706](https://github.com/SickChill/SickChill/issues/3706))

### v2017.05.02-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.04.26-1...v2017.05.02-1)

* FSF address fixed ([#3697](https://github.com/SickChill/SickChill/issues/3697))
* New T411 domain ([#3700](https://github.com/SickChill/SickChill/issues/3700)) ([#3701](https://github.com/SickChill/SickChill/issues/3701))
* Snatched episodes in Schedule view ([#3616](https://github.com/SickChill/SickChill/issues/3616))
* Fix the webcal protocol when running behind a reverse proxy ([#3679](https://github.com/SickChill/SickChill/issues/3679))
* Changes in error logging ([#3685](https://github.com/SickChill/SickChill/issues/3685))
* Conditionally skip BinSearch provider test ([#3690](https://github.com/SickChill/SickChill/issues/3690))
* Ignore broken symlink ([#3687](https://github.com/SickChill/SickChill/issues/3687))
* Consolidate location to postprocessor methods to keep api in sync ([#3681](https://github.com/SickChill/SickChill/issues/3681))

### v2017.04.26-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.04.14-1...v2017.04.26-1)

* Fallback for anime search on absolute numbering ([#3657](https://github.com/SickChill/SickChill/issues/3657))
* Fix travis:update task ([#3630](https://github.com/SickChill/SickChill/issues/3630))
* ncore - Add new search terms ([#3643](https://github.com/SickChill/SickChill/issues/3643))

### v2017.04.14-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.04.03-1...v2017.04.14-1)

* Update node packages and grunt....please grunt all js changes in each PR
* Bugfixes for ilCorsaroNero provider ([#3620](https://github.com/SickChill/SickChill/issues/3620))
* Update login.mako ([#3621](https://github.com/SickChill/SickChill/issues/3621))
* Auto grunt and update translations ([#3557](https://github.com/SickChill/SickChill/issues/3557))
* Fix error when adding show with invalid TVDB ID ([#3598](https://github.com/SickChill/SickChill/issues/3598))
* Fix schedule table layout ([#3604](https://github.com/SickChill/SickChill/issues/3604))
* finnish tv network logos ([#3612](https://github.com/SickChill/SickChill/issues/3612))
* Add --force-update argument ([#3591](https://github.com/SickChill/SickChill/issues/3591))
* Faster helpers.py file functions ([#3597](https://github.com/SickChill/SickChill/issues/3597))
* Get Trakt trending show images from TVDB ([#3368](https://github.com/SickChill/SickChill/issues/3368))
* Bump requests ([#3596](https://github.com/SickChill/SickChill/issues/3596))
* No need to import all of github module in logger - [#3587](https://github.com/SickChill/SickChill/issues/3587)
* Fixes [#3585](https://github.com/SickChill/SickChill/issues/3585)

### v2017.04.03-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.31-2...v2017.04.03-1)

* Log the exception when starting the web server fails ([#3587](https://github.com/SickChill/SickChill/issues/3587))
* Grunt Improvements ([#3562](https://github.com/SickChill/SickChill/issues/3562))
* Don't delete .stfolder ([#3569](https://github.com/SickChill/SickChill/issues/3569))
* XThor: Fix KeyError(u'torrents',) + logger.submit_errors() ([#3586](https://github.com/SickChill/SickChill/issues/3586))
* Fixes [#3566](https://github.com/SickChill/SickChill/issues/3566) and some camelCase to snake_case ([#3567](https://github.com/SickChill/SickChill/issues/3567))

### v2017.03.31-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.31-1...v2017.03.31-2)

* Fixes [#3558](https://github.com/SickChill/SickChill/issues/3558) - Missed a return

### v2017.03.31-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.30-2...v2017.03.31-1)

* Fixes [#3517](https://github.com/SickChill/SickChill/issues/3517) - Http errors in log about torrent client url

### v2017.03.30-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.30-1...v2017.03.30-2)

* Fix providers config not working ([#3542](https://github.com/SickChill/SickChill/issues/3542))

### v2017.03.30-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.29-1...v2017.03.30-1)

* Fix js-gettext, for the last time I hope ([#3523](https://github.com/SickChill/SickChill/issues/3523))

### v2017.03.29-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.28-2...v2017.03.29-1)

* Hotfix Javascript ([#3512](https://github.com/SickChill/SickChill/issues/3512))

### v2017.03.28-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.28-1...v2017.03.28-2)

* Dont try to verify a URL that might need auth

### v2017.03.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.25-1...v2017.03.28-1)

* GSN (USA) network logo ([#3499](https://github.com/SickChill/SickChill/issues/3499))

### v2017.03.25-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.24-4...v2017.03.25-1)

* Grunt and update translations
* Allow daemonizing on osx. Fixes [#3491](https://github.com/SickChill/SickChill/issues/3491)
* Putio client refactor to address authorization issues ([#3490](https://github.com/SickChill/SickChill/issues/3490))

### v2017.03.24-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.24-3...v2017.03.24-4)

* New T411 domain ([#3486](https://github.com/SickChill/SickChill/issues/3486))

### v2017.03.24-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.24-2...v2017.03.24-3)

* Try to fix new tag message ([#3483](https://github.com/SickChill/SickChill/issues/3483))
* Patch socket.getaddrinfo so that dns resolution in requests returns ip4 addresses rather than ip6, since some of our providers have dns for ip6 that does not resolve. This is better than forcing users to disable ip6. Fixes [#3450](https://github.com/SickChill/SickChill/issues/3450) ([#3482](https://github.com/SickChill/SickChill/issues/3482))

### v2017.03.24-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.24-1...v2017.03.24-2)

* Allow using an env variable to set changes file path in grunt task
* Further try and force utf-8 when sending requests to t411, could not test because the api is down right now. [#3418](https://github.com/SickChill/SickChill/issues/3418) ([#3481](https://github.com/SickChill/SickChill/issues/3481))
* Fix build, test more of browser.py ([#3480](https://github.com/SickChill/SickChill/issues/3480))
* Rebase sickrage.github.io before push and change main repo back to develop after pushing tags

### v2017.03.24-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.22-1...v2017.03.24-1)

* Pycharm code inspection on install script
* Custom CSS ([#3459](https://github.com/SickChill/SickChill/issues/3459))
* cd to opt first and extra comments for progress ([#3479](https://github.com/SickChill/SickChill/issues/3479))
* 3359 ([#3475](https://github.com/SickChill/SickChill/issues/3475))
* Fixes [SickRage/old-sickrage-issues#1494](https://github.com/SickRage/old-sickrage-issues/issues/1494) ([#3473](https://github.com/SickChill/SickChill/issues/3473))
* Integrate Codecov ([#3461](https://github.com/SickChill/SickChill/issues/3461))

### v2017.03.22-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.21-1...v2017.03.22-1)

* Hate that I cant test this without pushing it to develop FIRST
* Fix grunt tagging, bad command substitution
* Add log  on git_tag_new
* Enable stdout on git_tag_new
* jshint gruntfile
* Some changes, try to fix grunt release/publish
* Revert more bad bad consecutive ifs fixes
* Fix [#3463](https://github.com/SickChill/SickChill/issues/3463) failed to create hardlink on Windows
* Revert consecutive ifs fix that broke checking naming validity.
* Duplicate key in dict
* Fix 3640 - Add API key setting for Join.
* Change IMDB parser to html.parse.
* Possible fix for [#3443](https://github.com/SickChill/SickChill/issues/3443)
* Fix TNTVillage Leechers/Seeders extractor, thanks @cybertex1969
* Caching site-packages breaks tox. Cache .tox
* Cache site-packages in appveyor, redirect stderr to nul on del *.db in tox.ini
* Fix error
* Improve appveyor.yml for speed
* Fix npm cache path
* remove console.log from Gruntfile.js

### v2017.03.21-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.20-4...v2017.03.21-1)

* Fix git_list_tags
* Use @@@ instead of 12851$ to prevent shell expansion problems
* Patches ([#3451](https://github.com/SickChill/SickChill/issues/3451))
* Cross-platform tox.ini ([#3453](https://github.com/SickChill/SickChill/issues/3453))
* Fix small bug in tornado, not catching AttributeError when no multiprocessing is available and trying to check os.sysconfig on Windows
* Try setting up appveyor tests
* Add twit and missing korean network icons

### v2017.03.20-4

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.20-3...v2017.03.20-4)

* Use unidecode for network images, rename stod2 image

### v2017.03.20-3

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.20-2...v2017.03.20-3)

* Fix auto pushing changelog commit

### v2017.03.20-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.20-1...v2017.03.20-2)

* Update translations
* More workaround for nzb.su - [#3413](https://github.com/SickChill/SickChill/issues/3413)

### v2017.03.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.19-2...v2017.03.20-1)

* https://github.com/jharding/grunt-exec#accessing-grunt-object
* Update translations, cannot newrelease just after update_trans
* Grunt additions ([#3445](https://github.com/SickChill/SickChill/issues/3445))
* Work on Gruntfile.js ([#3436](https://github.com/SickChill/SickChill/issues/3436))
* Remove accidentally added png
* Fix network images for [#3431](https://github.com/SickChill/SickChill/issues/3431)

### v2017.03.19-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.19-1...v2017.03.19-2)

* Add channel 5 (uk) network image - [#3431](https://github.com/SickChill/SickChill/issues/3431)
* Cleanup some templating, remove resorting of show lists and iterable … ([#3433](https://github.com/SickChill/SickChill/issues/3433))
* Workaround to fix "Unknown" languages in general config
* Fix mocha tests and remove 'test' folder.
* Optimize /locale static route
* COMING_EPS_MISSED_RANGE fallback to min_val/max_val instead of def_val
([#3429](https://github.com/SickChill/SickChill/issues/3429))
* Add yarn.lock (npm alternative)
* Don't display shows in the showList if they are in the queue to be removed
* Cleanup some templating, remove resorting of show lists and iterable container type changes
* Update some bower/npm packages,
* Fix shecdule_missed_range default to be like min_max
* Use a proper label in confirm dialog for delete show.
* Grunt
* Update translations
* Update translations
* Dont need a config helper method for coming_eps_missed_range
* Closes [#3431](https://github.com/SickChill/SickChill/issues/3431)
* camelCase to snake_case in tvcache.py
* camelCase to snake_case in show_queue.py
* yarn, grunt
* Should fix [#3413](https://github.com/SickChill/SickChill/issues/3413) - If they don't specify tvdbid in their searching caps then they can take the spam of the q param
* Add ncu to dev depends, grunt

### v2017.03.19-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.16-1...v2017.03.19-1)

* Fixes [#3420](https://github.com/SickChill/SickChill/issues/3420) ([#3429](https://github.com/SickChill/SickChill/issues/3429))
* Fixes [#3083](https://github.com/SickChill/SickChill/issues/3083) - nzb providers categories resetting ([#3423](https://github.com/SickChill/SickChill/issues/3423))
* Quote showname when it is being used in url parameter ([#3419](https://github.com/SickChill/SickChill/issues/3419))
* Further locale support for Javascript files ([#3402](https://github.com/SickChill/SickChill/issues/3402))
* Properly escape sender email in notifications page ([#3412](https://github.com/SickChill/SickChill/issues/3412))

### v2017.03.16-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.13-1...v2017.03.16-1)

* Update translations
* Noinspection for six.moves
* Add min/max values for check_setting_int/float ([#3409](https://github.com/SickChill/SickChill/issues/3409))
* Some small modifications and fixes ([#3401](https://github.com/SickChill/SickChill/issues/3401))
* Fix mismatched checkboxes and labels 'for' attribute ([#3405](https://github.com/SickChill/SickChill/issues/3405))
* Small additions and fixes ([#3392](https://github.com/SickChill/SickChill/issues/3392))

### v2017.03.13-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.08-1...v2017.03.13-1)

* Clean up path building for transmission, fix bug for torrent download path with transmission ([#3387](https://github.com/SickChill/SickChill/issues/3387))
* Possible fix for Deluge client and some more small stuff ([#3381](https://github.com/SickChill/SickChill/issues/3381))
* Make some adjustments to tpb, update translations, cleanup
* Fix todo in config.py ([#3376](https://github.com/SickChill/SickChill/issues/3376))
* Extend locale support to include javascript files ([#3367](https://github.com/SickChill/SickChill/issues/3367))
* Relative episode location manual search AJAX ([#3364](https://github.com/SickChill/SickChill/issues/3364))

### v2017.03.08-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.04-1...v2017.03.08-1)

* NOTE: Post Processor is still going through changes, this may or may not work well for you.
* Auto download UnRAR.exe for Windows users (revisited) ([#3354](https://github.com/SickChill/SickChill/issues/3354))
* Fix delete associated files on rename ([#3343](https://github.com/SickChill/SickChill/issues/3343))
* SickRage restart adjustments ([#3353](https://github.com/SickChill/SickChill/issues/3353))
* Hotfix unrar on windows. Dont try to download unrar.exe ([#3349](https://github.com/SickChill/SickChill/issues/3349))
* added explanatory comments to tests/sickrage/show tests ([#3344](https://github.com/SickChill/SickChill/issues/3344))
* Fix [#3317](https://github.com/SickChill/SickChill/issues/3317) - reference addShow parameters by name ([#3337](https://github.com/SickChill/SickChill/issues/3337))
* Schedule missed episodes ([#3335](https://github.com/SickChill/SickChill/issues/3335))
* Fix MassUpdate tablesorter ([#3333](https://github.com/SickChill/SickChill/issues/3333))
* Hotfix unrar on windows. Dont try to download unrar.exe
* Some small tweaks ([#3330](https://github.com/SickChill/SickChill/issues/3330))
* Hotfix unrar download
* Alter metadata writers logging, fix for site_message, showlist 'active' images (+1) ([#3298](https://github.com/SickChill/SickChill/issues/3298))
* Update FAQ link in README.md ([#3328](https://github.com/SickChill/SickChill/issues/3328))
* Fix [#3322](https://github.com/SickChill/SickChill/issues/3322)
* Hotfix unrar tool check
* Adjust unrar location code to try and autofind unrar, and possibly download unrarw32.exe and use that on windows. ([#3321](https://github.com/SickChill/SickChill/issues/3321))
* Fix [#3305](https://github.com/SickChill/SickChill/issues/3305) - No need to force changing push url, setting developer = 1 will make it not touch your remotes at all.

### v2017.03.04-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.02-1...v2017.03.04-1)

* Remove images that are no longer used.
* Clean up restart js and template... make it work correctly again ([#3320](https://github.com/SickChill/SickChill/issues/3320))
* Fix logout link, web address in doc level licenses ([#3319](https://github.com/SickChill/SickChill/issues/3319))
* Fix ajax subtitles search and spinner/icons. Move ajaxEpSubtitles into core.js, clean up more template code ([#3318](https://github.com/SickChill/SickChill/issues/3318))
* Added ilCorsaroNero Provider ([#3315](https://github.com/SickChill/SickChill/issues/3315))
* Move more img tags over to span class for icons
* Fix loading shows layout in show list ([#3312](https://github.com/SickChill/SickChill/issues/3312))
* Fix spinners on manual search, ajaxEpSearch, schedule. Needs some more work and moved into core.js ([#3308](https://github.com/SickChill/SickChill/issues/3308))
* Show 'Use SR Metdata' when 'Subtitles' are checked ([#3302](https://github.com/SickChill/SickChill/issues/3302))
* Fix exception when booting after update due to missing twilio notify_git_update
* Change format pattern for anime_type = 2 ([#3301](https://github.com/SickChill/SickChill/issues/3301))
* Fix [#2292](https://github.com/SickChill/SickChill/issues/2292) - Ensure post data and params are encoded to utf-8 if they contain unicode ([#3304](https://github.com/SickChill/SickChill/issues/3304))

### v2017.03.02-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.03.01-1...v2017.03.02-1)

* New Feature - Post-Processor: Follow symlinks ([#3294](https://github.com/SickChill/SickChill/issues/3294))
* New Feature - unpack 'Treat as video' option to treat RARs as video files ([#3271](https://github.com/SickChill/SickChill/issues/3271))
* Fix [#3288](https://github.com/SickChill/SickChill/issues/3288)
* Fix [#3218](https://github.com/SickChill/SickChill/issues/3218) ([#3270](https://github.com/SickChill/SickChill/issues/3270))
* Fix [#3268](https://github.com/SickChill/SickChill/issues/3268) ([#3269](https://github.com/SickChill/SickChill/issues/3269))

### v2017.03.01-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.02.28-2...v2017.03.01-1)

* Fixes [#3240](https://github.com/SickChill/SickChill/issues/3240) - Only process release_name when called with nzb_to_media… ([#3267](https://github.com/SickChill/SickChill/issues/3267))
* Show 'Split in tabs' only when 'Split show lists' is enabled. ([#3265](https://github.com/SickChill/SickChill/issues/3265))
* Fix new_file\_\_path problem when pp but not renaming.
* Fix errant AA in log
* Fixes [#3263](https://github.com/SickChill/SickChill/issues/3263)
* Fixes [#3264](https://github.com/SickChill/SickChill/issues/3264)
* Check if is video_files empty in process_media() ([#3261](https://github.com/SickChill/SickChill/issues/3261))
* Fixes [#3260](https://github.com/SickChill/SickChill/issues/3260) - Dropdowns out of order
* Fixes [#3258](https://github.com/SickChill/SickChill/issues/3258)
* Fixes [#3258](https://github.com/SickChill/SickChill/issues/3258)
* Fixes [#3254](https://github.com/SickChill/SickChill/issues/3254)
* Fixes [#3092](https://github.com/SickChill/SickChill/issues/3092) and [#3101](https://github.com/SickChill/SickChill/issues/3101) - Work on QualityChooser ([#3247](https://github.com/SickChill/SickChill/issues/3247))
* Remove duplicate showTabs id
* Refactor home screen to allow split in tabs

### v2017.02.28-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.02.28-1...v2017.02.28-2)

* Fix [#3252](https://github.com/SickChill/SickChill/issues/3252) + [#3257](https://github.com/SickChill/SickChill/issues/3257) + Rollback to normal show size calculation. ([#3255](https://github.com/SickChill/SickChill/issues/3255))
* Fix syntax errors... ([#3251](https://github.com/SickChill/SickChill/issues/3251))
* Some attempted fixes ([#3250](https://github.com/SickChill/SickChill/issues/3250))

### v2017.02.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.02.24-1...v2017.02.28-1)

* Fix coming episodes ordering. Fixes [#3243](https://github.com/SickChill/SickChill/issues/3243) ([#3244](https://github.com/SickChill/SickChill/issues/3244))
* Fix Immortalseed RSS parameters ([#3242](https://github.com/SickChill/SickChill/issues/3242))
* More sqlie3.Row
* Allow to turn off searching subtitles for specials globally ([#3241](https://github.com/SickChill/SickChill/issues/3241))
* Only delete RAR files after they're processed. +1 ([#3237](https://github.com/SickChill/SickChill/issues/3237))
* Adapt anime SxxExx regex ([#3239](https://github.com/SickChill/SickChill/issues/3239))
* Small tweak to list_associated_files

### v2017.02.24-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.02.20-1...v2017.02.24-1)

* Fixes [#3200](https://github.com/SickChill/SickChill/issues/3200)
* Fix for Post Processing extracted folder deletion ([#3207](https://github.com/SickChill/SickChill/issues/3207))
* Several fixes ([#3203](https://github.com/SickChill/SickChill/issues/3203))
* Fix [#3184](https://github.com/SickChill/SickChill/issues/3184). Set locale when starting SR with upstart ([#3202](https://github.com/SickChill/SickChill/issues/3202))
* Limetorrents fix + Unpack directory new feature ([#3199](https://github.com/SickChill/SickChill/issues/3199))
* Add "Scrambled" to removeWordsList ([#3197](https://github.com/SickChill/SickChill/issues/3197))
* Rework on post processing logic for associated files ([#3193](https://github.com/SickChill/SickChill/issues/3193))

### v2017.02.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.02.15-1...v2017.02.20-1)

* Added support for Github token auth, ([#3185](https://github.com/SickChill/SickChill/issues/3185))
* Add seeso network logo ([#3182](https://github.com/SickChill/SickChill/issues/3182))
* A workaround for [#1377](https://github.com/SickChill/SickChill/issues/1377) ([#3178](https://github.com/SickChill/SickChill/issues/3178))
* Fixes [#132](https://github.com/MGaetan89/ShowsRage/issues/132) Replaces [#3180](https://github.com/SickChill/SickChill/issues/3180)
* Switch to new BTN api hostname ([#3177](https://github.com/SickChill/SickChill/issues/3177))
* Fix for accents on elitetorrent ([#3176](https://github.com/SickChill/SickChill/issues/3176))
* Fixes [#3152](https://github.com/SickChill/SickChill/issues/3152) - Add torrenting.com prefix to remove_non_release_groups
* Fixes [#3159](https://github.com/SickChill/SickChill/issues/3159)
* Some more changes to try and fix [#3116](https://github.com/SickChill/SickChill/issues/3116)
* Simplify massEDitSubmit code a bit and fix an edge case problem when switching show root
* flatten_folders -> season_folders (part 1) ([#3171](https://github.com/SickChill/SickChill/issues/3171))
* Discord Notification Enhancements ([#3162](https://github.com/SickChill/SickChill/issues/3162))

### v2017.02.15-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.02.12-2...v2017.02.15-1)

* Fix [#3130](https://github.com/SickChill/SickChill/issues/3130)
* fix [#3146](https://github.com/SickChill/SickChill/issues/3146) ([#3151](https://github.com/SickChill/SickChill/issues/3151))
* Fix: Season collapse & General config label typo ([#3144](https://github.com/SickChill/SickChill/issues/3144))
* Proper description for media_format parameter and add same parameter to ShowGetBanner API ([#3149](https://github.com/SickChill/SickChill/issues/3149))
* Try to fix [#3148](https://github.com/SickChill/SickChill/issues/3148)
* Feature: Selective history logs removal ([#3138](https://github.com/SickChill/SickChill/issues/3138))

### v2017.02.12-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.02.11-1...v2017.02.12-2)

* Fix [#3134](https://github.com/SickChill/SickChill/issues/3134) - Checking for tv-search on newznab when supportedparams is not provided
* Fix [#3136](https://github.com/SickChill/SickChill/issues/3136) - No need to filter through tvdb results anyways. They should be matching it on their end.

### v2017.02.11-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.02.02-1...v2017.02.11-1)

* Add media_format optional parameter for show.getposter api command. ([#3118](https://github.com/SickChill/SickChill/issues/3118))
* Fix [#1328](https://github.com/SickChill/SickChill/issues/1328), update translation files
* Fix [#3102](https://github.com/SickChill/SickChill/issues/3102)
* Fix [#3100](https://github.com/SickChill/SickChill/issues/3100)
* Fix show poster popover on hover when posters are small
* Try and fix [#3052](https://github.com/SickChill/SickChill/issues/3052)
* Add hdtorrents.it favicon
* Add hdtorrents.it, images for filelist and archetorrent Closes [#2914](https://github.com/SickChill/SickChill/issues/2914)
* Dont need to have reports when github isnt available.
* Discord Notification Support ([#3080](https://github.com/SickChill/SickChill/issues/3080))

### v2017.02.02-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.28-2...v2017.02.02-1)

* Dont ignore TV_DOWNLOAD_DIR if it is hidden.
* django-like Site messages ([#3065](https://github.com/SickChill/SickChill/issues/3065))
* Network Logo: yes (Israel) ([#3067](https://github.com/SickChill/SickChill/issues/3067))
* Fix [#1907](https://github.com/SickChill/SickChill/issues/1907)
* Fix [#3060](https://github.com/SickChill/SickChill/issues/3060)
* Fix [#3060](https://github.com/SickChill/SickChill/issues/3060)
* Fix [#3056](https://github.com/SickChill/SickChill/issues/3056)
* Fix request in [#2685](https://github.com/SickChill/SickChill/issues/2685)
* Fixed a label that was linked to wrong element ([#3054](https://github.com/SickChill/SickChill/issues/3054))
* Maybe Fix [#2975](https://github.com/SickChill/SickChill/issues/2975)
* Move SxEE regex up ([#3038](https://github.com/SickChill/SickChill/issues/3038))

### v2017.01.28-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.28-1...v2017.01.28-2)

* Skip scene detection when rescanning files ([#3004](https://github.com/SickChill/SickChill/issues/3004))

### v2017.01.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.26-1...v2017.01.28-1)

* New provider : ArcheTorrent (French Tracker) ([#3006](https://github.com/SickChill/SickChill/issues/3006))
* Fix github login credentials check ([#3034](https://github.com/SickChill/SickChill/issues/3034))
* Try to fix constant unrarring - [#2994](https://github.com/SickChill/SickChill/issues/2994) ([#3007](https://github.com/SickChill/SickChill/issues/3007))
* Ignore synology system folders ([#3005](https://github.com/SickChill/SickChill/issues/3005))

### v2017.01.26-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.25-1...v2017.01.26-1)

* Try to make unrar just a bit smoother on windows - [#2992](https://github.com/SickChill/SickChill/issues/2992)
* Attempt to fix [#2994](https://github.com/SickChill/SickChill/issues/2994)
* Merge branch 'master' into develop
* Fixes [#2993](https://github.com/SickChill/SickChill/issues/2993)
* Fix tvdb indexer search with special characters ([#2980](https://github.com/SickChill/SickChill/issues/2980))
* Fix mass update table for show without network ([#2978](https://github.com/SickChill/SickChill/issues/2978))
* Update home.mako ([#2990](https://github.com/SickChill/SickChill/issues/2990))
* UNRAR set paths ([#2987](https://github.com/SickChill/SickChill/issues/2987))
* Add torrent provider nCore ([#2985](https://github.com/SickChill/SickChill/issues/2985))
* Disable overwriting testing cassettes

### v2017.01.25-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.19-1...v2017.01.25-1)

* Fix [#2967](https://github.com/SickChill/SickChill/issues/2967) ([#2972](https://github.com/SickChill/SickChill/issues/2972))
* Genres bug ([#2969](https://github.com/SickChill/SickChill/issues/2969))
* Fix [#2965](https://github.com/SickChill/SickChill/issues/2965) + [#1789](https://github.com/SickChill/SickChill/issues/1789) ([#2966](https://github.com/SickChill/SickChill/issues/2966))
* Fix the imdb image regex so that the images on '/addShows/popularShows' ([#2964](https://github.com/SickChill/SickChill/issues/2964))
* Add skytorrents ([#2957](https://github.com/SickChill/SickChill/issues/2957))
* Fix [#2951](https://github.com/SickChill/SickChill/issues/2951) - This will be a merge conflict with merging develop, dont overlook!
* Fix bulkcheck in displayShow for seasons ([#2958](https://github.com/SickChill/SickChill/issues/2958))
* Initialize HTTPServer correctly for xheaders ([#2955](https://github.com/SickChill/SickChill/issues/2955))
* Fix tablesorter on mass update page, Fixes [#2951](https://github.com/SickChill/SickChill/issues/2951) ([#2954](https://github.com/SickChill/SickChill/issues/2954))
* Fixes ([#2946](https://github.com/SickChill/SickChill/issues/2946))
* Add Anime support for SxEE ([#2949](https://github.com/SickChill/SickChill/issues/2949))
* Fix scene search ([#2938](https://github.com/SickChill/SickChill/issues/2938))
* More work on rtorrent lib Fixes [#2934](https://github.com/SickChill/SickChill/issues/2934) Fixes [#2936](https://github.com/SickChill/SickChill/issues/2936)
* TRAKT_REMOVE_SHOW_FROM_SICKRAGE will also check for Canceled series, Fixes [#2921](https://github.com/SickChill/SickChill/issues/2921)
* Fix magnets in rtorrent, Fixes [#2880](https://github.com/SickChill/SickChill/issues/2880)
* Update certifi
* Update main.mako ([#2924](https://github.com/SickChill/SickChill/issues/2924))
* Small adjustment
* Change cert/key len to 4096 to appease debian
* Dont enable sickrage background by default
* fix filelist provider - unknown download link ([#2918](https://github.com/SickChill/SickChill/issues/2918))
* Fix [#1269](https://github.com/SickChill/SickChill/issues/1269)
* Fix [#2897](https://github.com/SickChill/SickChill/issues/2897) ([#2910](https://github.com/SickChill/SickChill/issues/2910))
* Fix layout issue on show details page ([#2909](https://github.com/SickChill/SickChill/issues/2909))
* Custom Background, fix file browser bug when browsing for files (not dirs) ([#2907](https://github.com/SickChill/SickChill/issues/2907))
* More clean
* Fix recursion with disk_usage caused by refactor, rewrite much of pp
* Fix bug in tv.py
* Fix bug in pp, more refactoring
* Fix is_sync_file tests
* Some more refactoring
* Rename is_rarfile to is_rar_file
* Rename isMediaFile to is_media_file
* Adjust validate_dir, remove part from sync files, adjust logger so exceptions show in log viewer
* Fixes [#2898](https://github.com/SickChill/SickChill/issues/2898)
* Fix anime episode search
* Fix tests
* Adjust code to work with rarfile rather than unrar2
* Remove unrar2, update rarfile
* Add custom_url support to torrentday, Fixes [#2834](https://github.com/SickChill/SickChill/issues/2834) ([#2877](https://github.com/SickChill/SickChill/issues/2877))
* Fix pycharm warnings (mostly)
* Make calling super init first in subclasses init work.
* Suppress abstract class warning for api classes Rename class names to match pep8 camelCase Call super init correctly
* Pp adjustments ([#2870](https://github.com/SickChill/SickChill/issues/2870))
* Fix some queue task initialization issues, add new param to the PP task to force return result of the task, currently disabled ([#2867](https://github.com/SickChill/SickChill/issues/2867))
* Fix [#2659](https://github.com/SickRage/SickRage/issues/2659) ([#2862](https://github.com/SickChill/SickChill/issues/2862))
* Use 3 digit episode numbers for anime ([#2855](https://github.com/SickChill/SickChill/issues/2855))
* NZBtoMedia needs updated
* Switch from getopt to argparse, replaces [#737](https://github.com/SickChill/SickChill/issues/737) ([#2853](https://github.com/SickChill/SickChill/issues/2853))
* fov regex update ([#2851](https://github.com/SickChill/SickChill/issues/2851))
* Add a test around isRarFile
* Fix content and enhance email notification

### v2017.01.19-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.10-1...v2017.01.19-1)

* Fix magnets in rtorrent, Fixes [#2880](https://github.com/SickChill/SickChill/issues/2880)
* Fix anime episode search
* Fixes [#2898](https://github.com/SickChill/SickChill/issues/2898)
* Add custom_url support to torrentday, Fixes [#2834](https://github.com/SickChill/SickChill/issues/2834) ([#2877](https://github.com/SickChill/SickChill/issues/2877))

### v2017.01.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.07-1...v2017.01.10-1)

* Fix nzbToMedia issue by allowing to force being the next item in the queue to run, allows force_clean in nzbtomedia (must update to nzbToMedia nightly to work!)
* Fix some queue task initialization issues, add new param to the PP task to force return result of the task, currently disabled ([#2867](https://github.com/SickChill/SickChill/issues/2867))
* Fix [#2659](https://github.com/SickRage/SickRage/issues/2659) ([#2862](https://github.com/SickChill/SickChill/issues/2862))
* Switch from getopt to argparse, replaces [#737](https://github.com/SickChill/SickChill/issues/737) ([#2853](https://github.com/SickChill/SickChill/issues/2853))
* fov regex update ([#2851](https://github.com/SickChill/SickChill/issues/2851))
* Add a test around isRarFile
* Use 3 digit episode numbers for anime ([#2855](https://github.com/SickChill/SickChill/issues/2855))
* NZBtoMedia needs updated

### v2017.01.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.05-1...v2017.01.07-1)

* Add delete to api pp command, add icacls support ([#2850](https://github.com/SickChill/SickChill/issues/2850))
* Fix nzbtomedia with new pp queue (hackfix until nzbtomedia can be updated)
* Fix small bug with log viewer code
* Update translations

### v2017.01.05-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.02-1...v2017.01.05-1)

* Fixes [#1600](https://github.com/SickChill/SickChill/issues/1600) ([#2843](https://github.com/SickChill/SickChill/issues/2843)) - Api Errors 512, etc
* Log page auto-updating, don't need to spam refresh anymore ([#2842](https://github.com/SickChill/SickChill/issues/2842))
* Add a queue for post processor, fixes issue of auto-pp running on top of itself and/manual ([#2839](https://github.com/SickChill/SickChill/issues/2839))
* Fix show_queue and search_queue errors causing the schedulers to die, and fix issue where the queueItems were never removed from the queue when finished
* Fix TorrentLeech, Fixes [#2837](https://github.com/SickChill/SickChill/issues/2837)
* Fix bs code in rTorrent lib that caused a bunch of hard to trace rTorrent bugs, [#2829](https://github.com/SickChill/SickChill/issues/2829)
* Update extratorrent.py ([#2836](https://github.com/SickChill/SickChill/issues/2836))

### v2017.01.02-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2017.01.01-1...v2017.01.02-1)

* Update extratorrent.py ([#2828](https://github.com/SickChill/SickChill/issues/2828))
* Fix [#2826](https://github.com/SickChill/SickChill/issues/2826) ([#2827](https://github.com/SickChill/SickChill/issues/2827))
* Club Illico Network logo ([#2825](https://github.com/SickChill/SickChill/issues/2825))

### v2017.01.01-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.12.30-1...v2017.01.01-1)

* Make sure the show location exists or at least the root dir exists and is set for the show dir. Fixes [#2521](https://github.com/SickChill/SickChill/issues/2521)
* Update "Bot" name ([#2819](https://github.com/SickChill/SickChill/issues/2819))
* Update add torrent paused for rtorrent ([#2820](https://github.com/SickChill/SickChill/issues/2820))
* Fix [#2690](https://github.com/SickChill/SickChill/issues/2690) - Show location encoding error with latin-1 when changing root dir in mass edit or location in editShow Set utf-8 for accept-encoding and encoding of some js files Fix problem where users got confused that the filebrowser didnt keep the location they typed in the location filebrowser but didnt hit enter, now it uses the location in the text box always, which is also updated when you click dirs

### v2016.12.30-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.12.27-1...v2016.12.30-1)

* Fix [#2815](https://github.com/SickChill/SickChill/issues/2815) - Anime regex matching wrong
* Fix up linux desktop notifications, add some missing notifications
* Catch some unnecessary gi.repository warnings, remove some unnecessary error logs
* Support for adding torrents as paused to rTorrent
* AuthException is when they provide wrong user/pass, its not an error

### v2016.12.27-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.12.20-2...v2016.12.27-1)

* Fix [#2079](https://github.com/SickChill/SickChill/issues/2079)
* bobbysteel - Remove dead provders: bluetigers btdigg ilovetorrents, replaces [#2720](https://github.com/SickChill/SickChill/issues/2720) ([#2801](https://github.com/SickChill/SickChill/issues/2801))
* Fix score detection ([#2800](https://github.com/SickChill/SickChill/issues/2800))
* Fix missed js in trendingShows and other issues, Fixes [#2725](https://github.com/SickChill/SickChill/issues/2725)
* Use proxy everywhere when proxy is set: imdb, tvdb. Remove proxy_indexers setting Fixes [#2685](https://github.com/SickChill/SickChill/issues/2685)

### v2016.12.20-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.12.20-1...v2016.12.20-2)

* Update subliminal to 2.1.0.dev

### v2016.12.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.12.18-1...v2016.12.20-1)

* Remove network_timezones lib and make network_timezones.py use lowercase network keys ([#2721](https://github.com/SickChill/SickChill/issues/2721))

### v2016.12.18-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.12.15-1...v2016.12.18-1)

* Reduce noise from the episode parser. ([#2709](https://github.com/SickChill/SickChill/issues/2709))
* Fix regex for RARBG.mp4, Fixes [#2705](https://github.com/SickChill/SickChill/issues/2705) Fix tests and add RARBG.mp4 to test strings.
* Popup auth for putio when you click test, user needs to make sure a popup blocker doesnt block it
* If file name has more than 4 episode numbers, make sure it doesnt match since it isnt a real episode its a compilation. Fixes [#2706](https://github.com/SickChill/SickChill/issues/2706)
* Include twilio notification service ([#2693](https://github.com/SickChill/SickChill/issues/2693))
* Added Pushover priority ([#2707](https://github.com/SickChill/SickChill/issues/2707))
* Include 2160p TV shows in search categories ([#2704](https://github.com/SickChill/SickChill/issues/2704))

### v2016.12.15-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.10.28-1...v2016.12.15-1)

* Try and set upstream on branch before checking latest commit hash from remote, Fixes [#2657](https://github.com/SickChill/SickChill/issues/2657) ([#2700](https://github.com/SickChill/SickChill/issues/2700))
* issuee with refresh paused s show ([#2694](https://github.com/SickChill/SickChill/issues/2694))
* Add torrent9.biz provider ([#2681](https://github.com/SickChill/SickChill/issues/2681))
* added option to disable autorefresh for shows paused and ended ([#2683](https://github.com/SickChill/SickChill/issues/2683))

### v2016.10.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.10.20-1...v2016.10.28-1)

* Add cookie auth to ipt, Fixes [#2511](https://github.com/SickChill/SickChill/issues/2511)
* Newpct hdtv by url ([#2524](https://github.com/SickChill/SickChill/issues/2524))
* IRIB TV1 (Tehran Iran) ([#2520](https://github.com/SickChill/SickChill/issues/2520))

### v2016.10.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.10.18-1...v2016.10.20-1)

* Add custom_url option for IPT, Fixes [#2511](https://github.com/SickChill/SickChill/issues/2511) Fix custom_url for TPB
* Tagger resolution improvements ([#2431](https://github.com/SickChill/SickChill/issues/2431))
* Images - networks: adjusted Rai logos ratios and added new Italian networks ([#2513](https://github.com/SickChill/SickChill/issues/2513))
* Typo in apibuilder causes double parameter ([#2509](https://github.com/SickChill/SickChill/issues/2509))

### v2016.10.18-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.10.11-1...v2016.10.18-1)

* Fixes [#2508](https://github.com/SickChill/SickChill/issues/2508) - It's only a visual issue since PP can only run once at a time anyways
* Fix size parsing for TPB Use categories and check only tv-shows and hd shows for rss in TPB Convert URL for TPB before requesting to avoid a 302 (The 301 is expected due to the .se redirector to best mirror) Fix an issue with title parsing, sometimes had js in the title
* Rai network logos ([#2491](https://github.com/SickChill/SickChill/issues/2491))
* Elitetorrent seeders ([#2469](https://github.com/SickChill/SickChill/issues/2469))
* Optimize imports
* Clean up logger a bit, fix no-member warning for log

### v2016.10.11-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.10.07-1...v2016.10.11-1)

* Mostly bug fixes
* Replaces [#2436](https://github.com/SickChill/SickChill/issues/2436) (elitetorrents throttling)
* Try to fix [#2292](https://github.com/SickChill/SickChill/issues/2292) (slack notification exception)
* Update GenericProvider.py ([#2461](https://github.com/SickChill/SickChill/issues/2461))
* Ability to select which root dir to show shows from on home page ([#2458](https://github.com/SickChill/SickChill/issues/2458))
* Fix [#2308](https://github.com/SickChill/SickChill/issues/2308) - Plex request will never go through proxy
* Update guessit and rebulk
* Compare lowercase for showlist sort ([#2454](https://github.com/SickChill/SickChill/issues/2454))
* Remove header updates who are incorrectly overwriting UA.
* Fix [#2445](https://github.com/SickChill/SickChill/issues/2445), [#2415](https://github.com/SickChill/SickChill/issues/2415), [#2177](https://github.com/SickChill/SickChill/issues/2177), [#2444](https://github.com/SickChill/SickChill/issues/2444), [#2428](https://github.com/SickChill/SickChill/issues/2428)

### v2016.10.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.10.05-1...v2016.10.07-1)

* Fix adding shows with ' in the name ([#2441](https://github.com/SickChill/SickChill/issues/2441))
* Add cloudflare-scrape
* Remove shutil_custom.copyfile_custom hack. Official one should work fine, and uses a smaller buffer (No reason to use 128MB of mem to copy a file) ([#2435](https://github.com/SickChill/SickChill/issues/2435))

### v2016.10.05-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.09.28-1...v2016.10.05-1)

* Attempt to fix [#2429](https://github.com/SickChill/SickChill/issues/2429), and also show proper parser result in the log ([#2434](https://github.com/SickChill/SickChill/issues/2434))
* Added FileList.ro torrent provider ([#1145](https://github.com/SickChill/SickChill/issues/1145))
* Fix [#1874](https://github.com/SickChill/SickChill/issues/1874) ([#2420](https://github.com/SickChill/SickChill/issues/2420))

### v2016.09.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.09.18-1...v2016.09.28-1)

* Update subliminal to 2.1.0.dev
* Fix wrong season for season banners and posters [#2011](https://github.com/SickChill/SickChill/issues/2011)

### v2016.09.18-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.09.10-1...v2016.09.18-1)

* Add openSans to grunt's mainFiles to suppress warning and include css
* Added NZBFinder.ws as default provider ([#2179](https://github.com/SickChill/SickChill/issues/2179))
* Issue 1907 ([#2344](https://github.com/SickChill/SickChill/issues/2344))
* providers/scenetime: Fix broken search after site changes ([#2335](https://github.com/SickChill/SickChill/issues/2335))
* Fixed Dave network logo ([#2326](https://github.com/SickChill/SickChill/issues/2326))
* Added HorribleSubs as provider ([#2246](https://github.com/SickChill/SickChill/issues/2246))
* Outline poster with table ([#2320](https://github.com/SickChill/SickChill/issues/2320))

### v2016.09.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.09.03-1...v2016.09.10-1)

(origin/develop, develop) Update pullapprove.yaml
* Fixes [#2311](https://github.com/SickChill/SickChill/issues/2311) ([#2317](https://github.com/SickChill/SickChill/issues/2317))
* Use Torrentz2 ([#2312](https://github.com/SickChill/SickChill/issues/2312))
* replaced banner.png ([#2309](https://github.com/SickChill/SickChill/issues/2309))
* Fix dupe import in itasa
* Parser exception ([#2302](https://github.com/SickChill/SickChill/issues/2302))
* Various UI tweaks ([#2298](https://github.com/SickChill/SickChill/issues/2298))

### v2016.09.03-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.09.01-1...v2016.09.03-1)

* Fix slack error breaking post processing when NOTIFY_SUBTITLE settings are used.
* Fix icon wrapping in cubmenu on error viewer

### v2016.09.01-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.08.25-1...v2016.09.01-1)

* Add NTV (JP) logo ([#2283](https://github.com/SickChill/SickChill/issues/2283))
* Fix notification responsiveness [#2274](https://github.com/SickChill/SickChill/issues/2274) ([#2277](https://github.com/SickChill/SickChill/issues/2277))
* Adding Slack notification for snatches and downloads ([#2276](https://github.com/SickChill/SickChill/issues/2276))
* Add x265 categories to Torrentday provider ([#2263](https://github.com/SickChill/SickChill/issues/2263))
* Fix add show from imdb popular
* Fix imdb popular page parsing due to change in imdb site ([#2257](https://github.com/SickChill/SickChill/issues/2257))

### v2016.08.25-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.08.20-1...v2016.08.25-1)

(origin/develop, develop) Fixes [#1907](https://github.com/SickChill/SickChill/issues/1907) ([#2256](https://github.com/SickChill/SickChill/issues/2256))
* Fix [#1621](https://github.com/SickChill/SickChill/issues/1621) ([#2254](https://github.com/SickChill/SickChill/issues/2254))
* Fix Debian/Ubuntu install script ([#2242](https://github.com/SickChill/SickChill/issues/2242))
* Fix form submit for firefox ([#2238](https://github.com/SickChill/SickChill/issues/2238))
* Fix reverse symlink menu item in settings ([#2235](https://github.com/SickChill/SickChill/issues/2235))
* Fix 'Error: [Errno 1] Operation not permitted:' when using SymLink ([#2231](https://github.com/SickChill/SickChill/issues/2231))

### v2016.08.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.07.31-1...v2016.08.20-1)

* Fix iptorrents
* Remove torrentz
* Fix some page formatting/label
* Fix massEdit for users with srHome prefix

### v2016.07.31-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.07.10-1...v2016.07.31-1)

* Support reverse symlinking
* Fix `stupid` regex and tests
* Add support for retrying subtitle downloads
* Disable KAT
* More responsive ui changes

### v2016.07.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.06.14-1...v2016.07.10-1)

* Change "No Show Object found for show with indexerID" log message to warning ([#2059](https://github.com/SickChill/SickChill/issues/2059))
* fix upstart to use default folder when using installer script ([#2053](https://github.com/SickChill/SickChill/issues/2053))
* For installer script: if folder not exist, clone repo ([#2054](https://github.com/SickChill/SickChill/issues/2054))
* ItaSa: fix manage season number ([#2038](https://github.com/SickChill/SickChill/issues/2038))
* Fixed typo which loaded the cookies setting into api_key variable. ([#2048](https://github.com/SickChill/SickChill/issues/2048))
* Enable cookies field for all TorrentProviders, if they have the provider.enable_cookies attribute set. ([#2034](https://github.com/SickChill/SickChill/issues/2034))
* remove trailing comma from list of columns to select when checking for duplicate shows ([#2029](https://github.com/SickChill/SickChill/issues/2029))
* Use unique seasons when searching ([#2027](https://github.com/SickChill/SickChill/issues/2027))
* Updates qbittorrent api calls to reflect changes made in qbittorrent with version 3.3.5. Ensure backward compatibility with older versions of qbt. ([#1996](https://github.com/SickChill/SickChill/issues/1996))
* Fixes [#1976](https://github.com/SickChill/SickChill/issues/1976) - encoding userid/password before logging in to SMTP server ([#1977](https://github.com/SickChill/SickChill/issues/1977))
* Fix for torrentday

### v2016.06.14-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.05.20-1...v2016.06.14-1)

* Feature to metadata for subtitles, add retry for itasa using 'rip suffix'
* Small fixes

### v2016.05.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.05.12-1...v2016.05.20-1)

* Fixes [#1802](https://github.com/SickChill/SickChill/issues/1802)
* Update author typo
* Rewrite xthor to use api ([#1818](https://github.com/SickChill/SickChill/issues/1818))
* Added some lines for translation ([#1803](https://github.com/SickChill/SickChill/issues/1803))
* Fixes [#1775](https://github.com/SickChill/SickChill/issues/1775)
* Subtitle improvement ([#1784](https://github.com/SickChill/SickChill/issues/1784))
* Fix offset checkboxes in config pages ([#1780](https://github.com/SickChill/SickChill/issues/1780))
* Responsive ui - round 2 ([#1767](https://github.com/SickChill/SickChill/issues/1767))
* Small tweakes to the icons/css ([#1766](https://github.com/SickChill/SickChill/issues/1766))
* newpct rss ayer ([#1745](https://github.com/SickChill/SickChill/issues/1745))

### v2016.05.12-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.05.09-2...v2016.05.12-1)

* Fixes jquery for adding scene exceptions, black/whitelist Fixes [#1746](https://github.com/SickChill/SickChill/issues/1746) Fixes [#1747](https://github.com/SickChill/SickChill/issues/1747) Fixes [#1759](https://github.com/SickChill/SickChill/issues/1759)
* Fix season pack search in tvchuk and "fix" titles ([#1752](https://github.com/SickChill/SickChill/issues/1752))
* Fix regexes ([#1750](https://github.com/SickChill/SickChill/issues/1750))
* Fix show info width ([#1755](https://github.com/SickChill/SickChill/issues/1755))
* Fix label in deluge, needs to be lower case ([#1749](https://github.com/SickChill/SickChill/issues/1749))
* Change log to info, no need to be warning ([#1742](https://github.com/SickChill/SickChill/issues/1742))
* Fixes search in windows systems for danishbits ([#1741](https://github.com/SickChill/SickChill/issues/1741))

### v2016.05.09-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.05.09-1...v2016.05.09-2)

* Fix put.io client
* Fix icons on the schedule page
* Fix IndexError in home.mako
* Fix incorrect log when a result is not found on KAT

### v2016.05.09-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.28-1...v2016.05.09-1)

* Fix unable to set label for torrent in qbittorrent
* Update subliminal to 14707b6
* Initial changes moving towards a responsive ui (may be issues to iron out)
* Add some more translations
* Remove postpone if no subs feature, in preparation for a better solution

### v2016.04.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.27-1...v2016.04.28-1)

* Remove Strike and Bitsoup providers, strike is taken down, bitsoup is pay only
* Add german scene release tag 'netflix', matches web-dl
* Update translations

### v2016.04.27-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.17-2...v2016.04.27-1)

* Refactor FilterBadReleases to filter_bad_releases, and adjust the logic:
    **Show specific required/ignored words now totally override global settings if they are set**

    If show ignored words are not set, global ignored words will be used
    If show required words are not set, global required will be used

    If the show has required words, they will be removed from the overall calculated ignored list when evaluating
    If the show has ignored words, they will be removed from the overall calculated rquired words list when evaluating

    If a show has required words which are also in the global ignored words they will override the global ignored and the release will be accepted
    If a show has ignored words which are also in the global required words they will overrid the global required and the release will be discared

    Release must not contain ANY of the final ignored words list, and at least ONE of the final calculated required words.

    Added a unit test to make sure this behavior is as expected and remains that way

    Fixes [#1541](https://github.com/SickChill/SickChill/issues/1541)
    Fixes [#1619](https://github.com/SickChill/SickChill/issues/1619)
    Fixes [#1623](https://github.com/SickChill/SickChill/issues/1623)
    Fixes [#1629](https://github.com/SickChill/SickChill/issues/1629)

* Updated torrentproject to use api magnet ([#1632](https://github.com/SickChill/SickChill/issues/1632))
* Fix Legendas.tv subtitle provider not showing for some people (stevedore...) Fixes [#1626](https://github.com/SickChill/SickChill/issues/1626)
* Fixed [#1623](https://github.com/SickChill/SickChill/issues/1623)
* Fixed [#778](https://github.com/SickRage/sickrage-issues/issues/778)
* Fixed [#1578](https://github.com/SickChill/SickChill/issues/1578)
* Fixed [#1585](https://github.com/SickChill/SickChill/issues/1585)
* Removed phxbit, no longer exists ([#1605](https://github.com/SickChill/SickChill/issues/1605))
* Added put.io & Join logos to the GUI ([#1595](https://github.com/SickChill/SickChill/issues/1595))
* Added putio client and update search providers templates ([#1550](https://github.com/SickChill/SickChill/issues/1550))
* Added Join notifier ([#1588](https://github.com/SickChill/SickChill/issues/1588))
* Updated icon sprite sheet

### v2016.04.17-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.17-1...v2016.04.17-2)

* Update translations
* Move github setup out of sickbeard init to sickrage.common.helper, so a restart isnt required after entering github credentials ([#1533](https://github.com/SickChill/SickChill/issues/1533))
* Fanart background in displayShow ([#1531](https://github.com/SickChill/SickChill/issues/1531))
* Change level of all loggers when enabling debug, so a restart isnt required! ([#1529](https://github.com/SickChill/SickChill/issues/1529))

### v2016.04.17-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.16-1...v2016.04.17-1)

* Fix database upgrade to 43.1
* Update translations
* Add Bulgarian translations

### v2016.04.16-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.14-1...v2016.04.16-1)

* Update translations
* Added more text for translation ([#1504](https://github.com/SickChill/SickChill/issues/1504)) ([#1503](https://github.com/SickChill/SickChill/issues/1503)) ([#1499](https://github.com/SickChill/SickChill/issues/1499))
* Update TtN , remove unnecessary fall back and change size to bytes to… ([#1508](https://github.com/SickChill/SickChill/issues/1508))
* Display banner on DisplayShow page. ([#1518](https://github.com/SickChill/SickChill/issues/1518))
* Add MBC 1 logo ([#1515](https://github.com/SickChill/SickChill/issues/1515))
* Clickable icon to open shows page on http://www.fanart.tv ([#1512](https://github.com/SickChill/SickChill/issues/1512))
* Added some missing buttons for translation ([#1506](https://github.com/SickChill/SickChill/issues/1506)) ([#1507](https://github.com/SickChill/SickChill/issues/1507)) ([#1509](https://github.com/SickChill/SickChill/issues/1509))

### v2016.04.14-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.13-1...v2016.04.14-1)

* Update languages, add a few translation strings

### v2016.04.13-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.12-1...v2016.04.13-1)

* Bump DB version to 43 to avoid issues updating when DB was previously used with SRTV
* Specify encoding for config file
* Update pushbullet info string in webui
* Fix typo in rename-selected url
* Improve handling of windows file operations, fix issue with getting free space
* Temporarily Disabled pymediainfo due to segfaults

### v2016.04.12-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.11-2...v2016.04.12-1)

* Merge pull request [#1469](https://github.com/SickChill/SickChill/issues/1469) from SickRage/neoatomic-develop
* Update translations, add en_GB translation
* Fix a few syntax errors in mako embedded python Fix manageSearches page syntax error for translatable string and clean it up some
* Some additions for the translations.
* Fixes [#1463](https://github.com/SickChill/SickChill/issues/1463)
* Update subliminal to 2.0.rc1 (b48c0c9) VANILLA! ([#1459](https://github.com/SickChill/SickChill/issues/1459))
* Remove itasa subtitle provider and add shooter.cn subtitle provider
* Try to fix [#1446](https://github.com/SickChill/SickChill/issues/1446) [#1445](https://github.com/SickChill/SickChill/issues/1445) ([#1458](https://github.com/SickChill/SickChill/issues/1458))

### v2016.04.11-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.11-1...v2016.04.11-2)

* Add ability to select your language for the web ui in config/general on the interface tab

### v2016.04.11-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.10-1...v2016.04.11-1)

* Fix issue tracker link in readme
* Combine show req/ign words with global ign/req words when checking release names so it doesnt require a word from BOTH ign lists or BOTH req lists
* Fix issue with manual pp and nzbtomedia
* Fix a few str formatting errors and add a few localizable strings

### v2016.04.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.09-1...v2016.04.10-1)

* Update translation strings
* Fix typos related to translations
* Fix selecting subtitle languages

### v2016.04.09-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.08-1...v2016.04.09-1)

* Fix issue matching subtitles from the wrong show to downloads in the PP folder
* Add mediainfo integration for getting video screen size, to help guessing quality from unknown quality files. Can be used for more things in the future
* Translate the rest of the ui, still small tweaks here and there to-do
* Update with latest translations, you guys are on fire

### v2016.04.08-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.04.01-1...v2016.04.08-1)

* Add ability to fully translate the web interface
  Use crowdin.com for managing translations

* Fix issue listing files associated with an episode or video file.
  This fixes subtitles and nfo not being moved during post processing,
  and not being renamed when renaming episodes

  Also fixes PP trying to double process a video, because the video itself
  was also returned as an "associated file"

* Fix issue where show refresh used an insane amount of memory/cpu
  and would hang on broken videos and avi files when quality was
  not detected from the name.

* Fix wrong show/episode air times
* Fix issue sending app image to boxcar2

* Small tweak to make web interface look just a little better on mobile, more to come.

* Fixed [#1373](https://github.com/SickChill/SickChill/issues/1373) ([#1378](https://github.com/SickChill/SickChill/issues/1378))
* Add some weight to episode_numbers, to prefer matching them over absolute numbers in cases where the title has numbers or the word "Episode \d"
* Fall back to SDDVD when it matches SD DVD regex in filename for default named eps coming from sickbeard.
* Backport glob.escape from python 3.4
* Ditch hachoir for purpose of parsing screen height of files when guessing quality, rolled my own avi WxH implementation and use enzyme for mkv
* Add test to make sure providers return results in the proper format and valid values
* Fix TorrentProject requesting trackers with no hash and cure ddos by only requesting when less than 3 seeds, almost dead torrents
* Partial Dutch Translation for Sickrage
* Make sure show specific req/ignored words exist before trying to split them
* Cassettes and tests for public providers' search parsing.
* Must explicitly cast basestrings to int before using int based format specifiers
* Fix AM/PM of show air times
* Add Ilovetorrents provider
* Fix WEB detection
* Disable verify for plex media server, since it is signed with the plex direct wildcard cert (even locally)
* Adjust metadata file log messages
* Fix up tvshow.nfo parsing a bit so it doesnt give warnings when id/tvdbid is an empty string

### v2016.04.01-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.03.31-1...v2016.04.01-1)

* Fixes [#1309](https://github.com/SickChill/SickChill/issues/1309), [#1304](https://github.com/SickChill/SickChill/issues/1304), [#1285](https://github.com/SickChill/SickChill/issues/1285)
* Fix "Unable to determine free space"
* Fix issue where importing existing files that parsed to unknown quality would not change episode status to downloaded
* Fix issue causing incorrect airdates
* Fix issue with timezones causing Synology DSM6 to fail to start
* Fix bug where qualityFromFileMeta was getting double and triple called

### v2016.03.31-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.03.28-2...v2016.03.31-1)

* Highlights:
    Allow sending NZB's to DSM on Synology
    Ignored/Required words for specific shows override global defaults now
    Add channels support for pushbullet
    Hella fixes? xD

* Fix port number in settings gui url note
* Use a set().difference for handling ignored/required words If a word is in the global ignored words and in the show's required words, it is required If a word is in the global required but in the show's ignored, it is ignored
* DSM: Make sure to use nzb client settings when sending nzb, and torrent settings when sending torrents
* Add docstrings
* Add ability to use Synology DSM for nzb also
* Allow trakt checker to continue when imdbid is not known for one show Fixes [#1287](https://github.com/SickChill/SickChill/issues/1287)
* release group sort is now case insensitive
* Fix tuple index out of range
* Make "Available Groups" sort by alphabetical order
* Fix typo from unicode_literals regexing...
* Disable OneRun wrapper for PP, we need a better solution Fixes [#1282](https://github.com/SickChill/SickChill/issues/1282) [#1389](https://github.com/SickRage/sickrage-issues/issues/1389)
...
* Handle when hash or size are missing
* Fix error with multiple search results per provider Thanks @p0psicles
[#1390](https://github.com/SickRage/sickrage-issues/issues/1390)
* Add debian/ubuntu install script contributed by @DirtyCajunRice
* Make sure df returns 1k blocks without the K suffix
* These arent coding errors, whoever made them logger.ERROR should be swatted Fixes [#1263](https://github.com/SickChill/SickChill/issues/1263)
* Make disk_usage return int, and convert it from K to B Assure df returns in KB (default on most systems, but lets be sure) Fixes [#1269](https://github.com/SickChill/SickChill/issues/1269)
* Remove helpers._getTempDir as it is unused Use platform.system instead of os.name in helpers
* Add functions to check for Pushbullet channels

### v2016.03.28-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.03.28-1...v2016.03.28-2)

* Unicode literals for TorrentDay Try and parse size from a dict by default in GenericTorrentProvider
* Split out disk_usage logic so that verify_freespace and getDiskSpaceUsage use the same logic Replaces [#1262](https://github.com/SickChill/SickChill/issues/1262) Fixes [#1259](https://github.com/SickChill/SickChill/issues/1259)
* Update french fansub
* Added Subtile Provider Cache
* Call df in a subprocess, since OSX has a bug with volumes > 4TB when using statvfs. This will work in all unix-like environments Fixes [#1259](https://github.com/SickChill/SickChill/issues/1259)
* Remove nzbToMedia from source control. It auto updates and breaks git pull
* Use cookie auth for DSM Show error messages for error codes returned from DSM according to DSM docs Check DSM version, and fix the download location if it is absolute on DSM6
* Fix transmission test connection Replaces [#1247](https://github.com/SickChill/SickChill/issues/1247)
* Remove alt.binaries.teevee from binsearch provider (no longer exists) Fixes [#1238](https://github.com/SickChill/SickChill/issues/1238)
* Change code back to use original bencode Fix some logs Fixes wrong torrent hash calculation (labels sometimes not working in utorrent) Fixes [#1235](https://github.com/SickChill/SickChill/issues/1235) [#1203](https://github.com/SickChill/SickChill/issues/1203) [#1375](https://github.com/SickRage/sickrage-issues/issues/1375)
* Comment lines that cause most errors with bdecode
* Switch back to official libtorrent bencoder
* Update snyk Use .on('click'... instead of .click(... syntax in js Set a default value for downCurQuality in retryEpisode Use the callback in $.post in js to make sure the reload is after the post finishes, otherwise the reload is before eg. the episode status has changed
* Fix indice error when no results in an omgwtfnzbs search Fixes [#1380](https://github.com/SickRage/sickrage-issues/issues/1380) Fixes [#1225](https://github.com/SickChill/SickChill/issues/1225)
* Dont warn saying incorrect passkey for shazbat when it has no results Fixes [#283](https://github.com/SickRage/sickrage-issues/issues/283)
* showDir is utf-8 when addExisting shows Fixes [#1229](https://github.com/SickChill/SickChill/issues/1229)
* Fix Seeders and Leechers on TtN
* Add a few more non release groups
* Fix brassetv and add others
* Fix web_root prepend for redirects.
* Use tzlocal and pytz for everything except parsing date strings from the name parser
* Add tzlocal and pytz libs

### v2016.03.28-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.03.23-1...v2016.03.28-1)

* Use cookie auth for DSM Show error messages for error codes returned from DSM according to DSM docs Check DSM version, and fix the download location if it is absolute on DSM6
* Fix transmission test connection Replaces [#1247](https://github.com/SickChill/SickChill/issues/1247)
* Remove alt.binaries.teevee from binsearch provider (no longer exists) Fixes [#1238](https://github.com/SickChill/SickChill/issues/1238)
* Change code back to use original bencode Fix some logs Fixes wrong torrent hash calculation (labels sometimes not working in utorrent) Fixes [#1235](https://github.com/SickChill/SickChill/issues/1235) [#1203](https://github.com/SickChill/SickChill/issues/1203) [#1375](https://github.com/SickRage/sickrage-issues/issues/1375)
* Comment lines that cause most errors with bdecode
* Switch back to official libtorrent bencoder
* Update snyk Use .on('click'... instead of .click(... syntax in js Set a default value for downCurQuality in retryEpisode Use the callback in $.post in js to make sure the reload is after the post finishes, otherwise the reload is before eg. the episode status has changed
* Fix indice error when no results in an omgwtfnzbs search Fixes [#1380](https://github.com/SickRage/sickrage-issues/issues/1380) Fixes [#1225](https://github.com/SickChill/SickChill/issues/1225)
* Dont warn saying incorrect passkey for shazbat when it has no results Fixes [#283](https://github.com/SickRage/sickrage-issues/issues/283)
* showDir is utf-8 when addExisting shows Fixes [#1229](https://github.com/SickChill/SickChill/issues/1229)
* Update btn.py
* Fix web_root prepend for redirects.

### v2016.03.23-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.03.22-1...v2016.03.23-1)

* Quantified code, please dont force format tokens to strings, lol Fixes [#1370](https://github.com/SickRage/sickrage-issues/issues/1370)
* Show how many characters the url has exceeded the limit in the alert when operating on too many shows [#1203](https://github.com/SickRage/sickrage-issues/issues/1203)#issuecomment-200097373
* Pass true to loaction.reload, to ensure it doesnt reload from cache Fixes [#1202](https://github.com/SickChill/SickChill/issues/1202)
* Clean up generic client and utorrent client use unicode_literals and str.format()

### v2016.03.22-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.03.20-1...v2016.03.22-1)

* Use unicode_literals in show_queue Use str.format() Lint, and fix some funkyness Normalize text between ui notifications and logger
* Send verify=False for sab requests Fixes [#1201](https://github.com/SickRage/sickrage-issues/issues/1201)
* add number index to string format replacements, normalize the search string log line
* match bs4 search results by direct parameter rather than attrs=
* Use bs4 objects as a method instead of explicitly calling findAll/find_all for shorter code
* Remove unnecessary cookielib
* Unify requests exception handling
* Unicode literals for common, helpers, naming, and tv Fixes [#1340](https://github.com/SickRage/sickrage-issues/issues/1340)
* Disable SSL verify in t411 since their cert does not match Fixes [#1341](https://github.com/SickRage/sickrage-issues/issues/1341)
* Only encode potential extra script params if there is actually a script to run Add some try/except. Might need one to catch the execv error Fixes [#1237](https://github.com/SickRage/sickrage-issues/issues/1237)
* Modified itasa provvider for better scores

### v2016.03.20-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.03.10-1...v2016.03.20-1)

* Change wiki/issues links to main repo
* Clean up gui imports, and some other finagery
* Updating subliminal to [f40e79a](https://github.com/SickChill/SickChill/commit/f40e79a78b7c8c92b83399d4d8778ec54ee8b7d2) plus legendastv and itasa providers
* Avoid `None` as a redundant second argument to `dict.get()` Avoid using `not ... is` instead of `is not`
* Use set comprehension
* Avoid mutable defaults for method parameters
* Avoid using `len(x)` to check if x is empty
* Remove funkyness with torrentday, untested
* Hacky fix for 11.22.63, the warning was never really an error anyways, just a warning on one of the regex iterations that it didnt match to Fixes [#1221](https://github.com/SickRage/sickrage-issues/issues/1221)
* Only show commit hash for ERROR log lines
* Update nzbtomedia reference to V10.14
* Update requests to 2.9.1
* Update certifi to [3850279](https://github.com/SickChill/SickChill/commit/38502797954603558ebf5f2c93f3645279e18158)
* Generate API key more randomly and securely
* Remove unused md5_for_file code and tests Fix mutable parameter default values Remove has_key tests since we no longer override has_key in qualities
* update node dev dependancies change to node 5.6.0 for travis
* Migrated `%` string formating
* Explicitely numbered replacement fields
* Fix string format in sickbeard.helpers
* Allow sep=None for convert_size
* Add .checkignore
* Check api limits and errors with hd4free
* Change NMA URL
* Show commit hash and branch even if we dont know the tag number (source installs especially)
* Fix download link on transmithenet
* Try again for 1086 Fixes [SickRage/sickrage-issues#1086](https://github.com/SickRage/sickrage-issues/issues/1086)
* Cleanup sickbeard.\_\_init\_\_ to remove some global keywords and write out the config nicer
* If adding existing shows, and you have a show in your list with a missing show dir, re-use the existing show object in the db and update it's info rather than skipping it
* Add limit for massupdate url generated by js
* Limit url length generated by addExisting with an ugly js alert =P Temporary solution
* Fixes [#1198](https://github.com/SickRage/sickrage-issues/issues/1198)
* Switch bencode implementation, using https://pypi.python.org/pypi/python-bencode
* update dateutil to d05b837
* Remove some spamminous logging from name_cache, db upgrade checks, and setter sets location (tv.py) Cleanup db.py
* Add missing ITASA globals in sickbeard.\_\_init\_\_
* Some changes to nw timezones, hopefully will make it more reliable.
* Encode file path and episode location to SYS_ENCODING (usually utf-8) before calling popen Fixes [#1086](https://github.com/SickRage/sickrage-issues/issues/1086)
* Add .pullapprove.yml
* Added ItaSA subtitle provider

### v2016.03.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.03.05-1...v2016.03.10-1)

* Don't save filter_Rows state through page refreshes Fixes [#1177](https://github.com/SickRage/sickrage-issues/issues/1177)
* No need to specify timezone in datetime.now() in the footer
* Newznab provider handles show id internally now, and rid is no longer used, so this is stray code that does nothing
* Use a better module property name for hachoir's log
* log ERROR=>DEBUG when show is already being updated and attempted to be done again Fixes [#1165](https://github.com/SickRage/sickrage-issues/issues/1165)
* Fix commit hash update notifications when using source install. Fixes [#1118](https://github.com/SickRage/sickrage-issues/issues/1118)
* Fix auth header for pushbullet [#1118](https://github.com/SickRage/sickrage-issues/issues/1118)
* Add custom notification email subject
* Fix WEB-DL and WEB-Rip detections * Optimize regex * Add WEB detection * Add DLMux detection
* Use sickrage.github.io for url to the icon, instead of rawgit
* Add icon and app name to boxcar notification
* Boxcar2, use requests, unicode literals, str.format
* Oops, need to send the session to getURL
* Rework pushbullet, might need some message improvements
* Rework pushalot notifier Fixes [#1034](https://github.com/SickRage/sickrage-issues/issues/1034)
* update dateutil to c2c9700
* Fix NoneType for CUR_COMMIT_HASH error when github is not available
* Updated "Sync File Extension" list for qBittorrent
* Fix typo in TTN Fixes [#1112](https://github.com/SickRage/sickrage-issues/issues/1112)
* Use request hook for download_file in providers, until we can be sure sessions are working correctly
* Don't require TLD with validators for providers that may be local (bitcannon, torznab, newznab) Fixes [#1117](https://github.com/SickRage/sickrage-issues/issues/1117)
* Rework how session and request parameters are handled Prevents residual params in the session Prevents session getting stuck in stream mode Allows ssl_verify to be disabled without a restart Allows passing verify as a kwarg to disable it on a per request basis Allows passing headers without contaminating the session Removes old code from glype that was poisoning the session/headers/proxies
* Add setup.py and tox
* Add better test coverage to GenericProvider
* Fixes [SickRage/sickrage-issues#1115](https://github.com/SickRage/sickrage-issues/issues/1115)
* Clean up scheduler thread formatting in `sickbeard.\_\_init\_\_` Set show updater to cycle time 1hr again, see if that fixes it not running Delay start of most threads at least a minute or two after startup Fix bug adding cycle time to last_run
* Make show filter on poster view case insensitive match.
* Add anime category for bluetiger provider
* Add code to send email on remote login and sickrage updates Use unicode literals Use str.format
* Fix network timezone reporting
* Refresh show from dir even when it hasnt been updated on tvdb, but do not rebuild metadata (force=False) Fixes [#1089](https://github.com/SickRage/sickrage-issues/issues/1089)
* Don't error when show was already removed from trakt or never was on trakt. Fixes [#1038](https://github.com/SickRage/sickrage-issues/issues/1038)
* Fix errant nzbget string after converting strings
* Fix searching tvdb to add shows when result contains a result that has no firstaired set. Clean up sickbeard.classes
* pre-sort qualities for quality list Fixes [#1087](https://github.com/SickRage/sickrage-issues/issues/1087)
* Hotfix dateutil error for timezone names on Windows
* Fix error where sometimes client did not log into the provider before downloading a torrent or nzb Fix error where sab was calling an undefined method Switch sab code over to completelt requests Pass returns= in all calls to get_url Remove json= and need_bytes= params from getURL and get_url Cleaner \_\_str\_\_ for search result class Remove some dupe logging

### v2016.03.05-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.02.22-1...v2016.03.05-1)

* Use content when downloading nzbs
* Updated the provider icons & added viceland network logo.
* Fix "'NoneType' object has no attribute 'indexerid'" when deleting a show when new shows are being added.
* https://github.com/SickRage/SickRage/commit/[bbd1618](https://github.com/SickChill/SickChill/commit/bbd16184ae6f47d5d260cb08e4dde18cd7c1cd4d)#commitcomment-16505285
* Fix gingadaddy Fix nzb.su and other providers who don't support tvdbid Use dict for result lists in all torrent providers No need to override get_ratio Fix more get_url calls to use the request hook Fix issue with blank download url when using transmission 2.90+ Fix dupe quality from numDict Sort quality lists Much more
* Force mimetypes for commonly misconfigured types, ie: when a user has dreamweaver installed Fixes [#1078](https://github.com/SickRage/sickrage-issues/issues/1078)
* Fix login issue with tvchaosUK, fixes need to double login Fixes [#1077](https://github.com/SickRage/sickrage-issues/issues/1077)
* Update dateutil to 2.5.0 with updated zoneinfo
* Fix tvchaosuk, there is one persistent cookie for CF, then totals 4 cookies when authed Fix tntvillage login, has 3 cookies when logged in. RSS search still disabled in this provider Fixes [#1072](https://github.com/SickRage/sickrage-issues/issues/1072)
* Update T411 domain name
* Change UA for statistical reasons
* Every request in SR was re-initializing the cache, so no request was honoring cachecontrol (like, ever) This is probably why caching to disk was causing breakage, and also why we are spamming xem.
* rewrite, got rid of unnecessary methods and based the provider on abnormal.py
* Made the webbrowser dependency optional
* use str.format instead of %s for search string
* Fix docstrings, quotes and some other coding style issues
* Norbits provider
* Use _ for french adn icon name.
* Move logging commit hash
* Prevent logging "No results found" message
* Fix subtitles indent
* Update subliminal to latest version (c3c0c45)
* Add mako indenting
* 50 Threads? Really? This fix halves VIRT alloc, to halve it again add export MALLOC_ARENA_MAX=2 (or 1) to your runscript on linux)
* Missed a few replace-map typos
* Disable show update on start until it can be improved
* Gui had wrong replacement chars for scene numbers in renamer
* fix: Danishbits provider now works again
* Fixes [#1046](https://github.com/SickRage/sickrage-issues/issues/1046)
* Use a decorator to prevent processing a dir more than once at a time, regardless of caller Fixes [#1028](https://github.com/SickRage/sickrage-issues/issues/1028)
* Fixes [#1042](https://github.com/SickRage/sickrage-issues/issues/1042) Fixes touchFile to use ek and check file exists
* Disable auto pp when postpone if no subs
* Fixes url encoded censored items in logs not being censored.
* Plex: Always return True when getting auth token if username/password aren't configured
* Fix issue where last_update_indexer was using date instead of datetime, use time based updates xml from tvdb instead of day.xml. Even though it is deprecated it works BETTER
* even more fixes
* more fixes
* Quck subtitles improvements
* Check SUBTITLES_MULTI and make subs exceptions as dict
* Delete unwanted subtitles
* Check if sub is enabled before postpone
* update bower_concat
* Revert "Fix SickRage/sickrage-issues/issues/813"
* Show refresh/update should have high priority
* Force "Subtitles Multi-Language" if more than one wanted subtitle language
* Subtitle language exceptions as Dict
* Add PR/Issue templates, move contributing.md to .github
* Add OCS network logo
* Add option to keep only wanted subs
* Delete unwanted subtitles if we don't want them
* Check if show has subtitle enable before postpone PP
* Add "ignore subs" setting in manual PP
* This seems ok
* Remove subliminal patch, grunt like what
* Revert "Updated npm deps"
* Updated npm deps Remove patches (subliminal is not locally patched anymore) Did best Tim Allen impersonation
* Fix TPB when using an invalid proxy
* NewPCT:
  - Unicode literals
  - Fix string quotes
  - Fix get_url override
  - Conformity and cleanup
* Warn about database owner/permissions
* NewPCT:
  - Unicode literals
  - Fix string quotes
  - Fix get_url override
  - Conformity and cleanup
* Make the show updater run on startup Fix it so that it doesnt keep updating the same shows over and over Fix cycleTime for show updater for status page Clean up logging in tv.py when setting the next episode and updating show
* Disable subtitles code db check
* Fix searches with ABNormal Replace double quotes with single quotes as per our decided convention
* Fix searches with ABNormal Replace double quotes with single quotes as per our decided convention
* Catch shutil errors and proper display as error/warning
* Create gists as secret instead of public
* Fixes detection of "nothing found" when search result set is empty for torrentbytes. Fix [#235](https://github.com/SickRage/sickrage-issues/issues/235)#issuecomment-185068695
* Add "(musicbolt.com)" to removewordslist
* Fixes detection of "nothing found" when search result set is empty for torrentbytes. Fix [#235](https://github.com/SickRage/sickrage-issues/issues/235)#issuecomment-185068695
* Pass params through getRSSFeeds to get_url instead of urlencode Update string quotes, u prefix removal and unicode literals for bunsearch, nyaa, omg, rsstorrents, shazbat, womble Clean up and improve those providers
* Add option to ini to allow PMS update without token or user/pass when you dont require authentication config.ini only option for now
* Use provider's get_url for getting rss feeds instead of urllib/httplib2 Fixes bozo, and removes old code Normalizes logging
* Update contributing.md
* Dont run FINDSUBTITLES thread right on SR start
* Allow passing arguments future= and past= for range of weeks from today to add to the webcal http://localhost:8081/calendar?past=2&future=3 both default to 52
* Handle float log sizes Increase default log size to 10MB to reduce rolling over Fix SickRage/sickrage-issues/issues/892 Replaces [#1027](https://github.com/SickChill/SickChill/issues/1027)
* Fix typo preventing confirm modal not showing before submitting errors
* RARBG:
  - Show api error messages
  - Show log when no torrents differentiated from when no data returned
  - Move sleep to prevent hitting request limit and use CPU_PRESETS
* Fix btdigg api url
* It is returns= not response= now
* RARBG:
  - Use unicode literals, remove u prefixes, use " over ' for strings
  - Use .format over token string formatting
  - Pass returns="json"
  - Remove excess logging, pop elements as they are used from the json
* BTDigg:
  - Use unicode_literals, remove u prefixes, use " instead of ' for strings
  - Use .format instead of token string formatting throughout
  - Pass params to get_url, and specify json response type
  - Remove duplicitous logging
  - General BTDigg cleanup
  - Add ! to config_providers since btdigg api is currently not working.
* Revert "fixed, Newznab cats that are disabled, shouldn't be shown in configure options tab."
* Adjust requests hook just a bit
* Use a requests hook for get_url in providers, show post data for post requests
* KAT:
  - Use unicode_literals, remove u prefix, use " for strings
  - Use validators for custom_url
  - Use urljoin throughout
  - BS4Parser for better cleanup
  - Fix issue with magnets
* Fix seeders/leechers log lines
* Providers:
  - Only include freeleech in provider \_\_init\_\_ if provider supports it (same for minseed, minleech, etc)
  - No need to encode search_string, it is encoded in _get_*_search_strings
* TorrentBytes:
  - Use unicode_literals, remote u prefixes, use " over ' for strings
  - Use urljoin throughout
  - Pass search params to requests instead of building the url
  - Pass response="text" to get_url
  - Parse table headers and use for cell indexing
* TPB doesnt have freeleech
* ABNormal code doesnt support freeleech param
* Bitcannon:
  - Use unicode_literals and remove u prefixes
  - Use " over ' for strings
  - Use validators for custom_url
* Add missed dependancy for validator: decorator.py
* No need to check if torrent_table is None, it is handled in the next line to allow the log
* Update torrentleech
  - Use unicode_literals and remove u prefixes
  - Use " over ' for strings
  - Use .format over token formatting
  - Use urljoin over string concat for urls
  - Pass params to get_url instead of urlencoding
* Update search string log line for all providers
* Update BinSearch
  - Use unicode_literals and remove u prefix
  - Use " over ' for strings
  - Use .format over % token string formatting
  - Use urljoin instead of concat for urls
  - Import urljoin, urlencode from requests.compat
* AbNormal Updates
  - Pass response="text" for login and search
  - No need to use named format replacements unless you are using the same replacement more than once
  - Switch back to " over ' for strings
* update "Search Mode:" log line in all providers to use .format
* TPB Updated * Use unicode_literals and remove u prefix * Use " over ' for strings * Use .format over string tokens * Remove extra search url log and pass response='text' to get_url * use validators to validate custom_url
* Add lib/validators to be used with custom_urls and email and ip validation of user input and other places
* Alpharatio strings updates * Remove u prefix from strings * Normalize strings to use " throughout
* Alpharatio updates * Use urljoin over string concat * Use unicode_literals * Remove search url log and pass response param to get_url
* Removed unused urlencode import
* Use params instead of encoding the params and joining them Remove duplicate logging
* Use urljoin instead of concat
* Use unicode literals
* Standardize string formatting
* Standardize strings to use single-quotes
* Import urlencode from requests.compat instead
* Clean up airdate modify timestamp handling and make sure exceptions are caught. Fixes [#914](https://github.com/SickRage/sickrage-issues/issues/914)
* Make sure etree always adds xml declaration for mede8er and specify encoding explicitly Trying to fix [#862](https://github.com/SickRage/sickrage-issues/issues/862)
* Import urlencode from requests.compat instead of urllib
* Allow file globs in "Sync File Extensions" setting to postpone postprocessing
* Remove old_scene_quality Remove quality assertion Refactor sceneQuality => scene_quality Fix anime bluray detection
* Fix getURL calls to use `returns` argument
* Append show name to show search strings regardless of searched season
* Append show name to show search strings regardless of searched season
* Fix logging when result is None fixes SickRage/sickrage-issues/issues/902
* Fix getURL log entry should be debug
* Fix apikey shown in log when = is urlencoded as %3D
* Add URL logging to GenericProvider.get_url
* Add raw response object as a getURL return type Add pending deprecation warnings for getURL arguments json, need_bytes Add pending deprecation warning for getURL returning text
* Don't limit allowed extensions to 3 chars
* Reduce subtitle score to match only Series, Season, Episode and Year
* fixed, Newznab cats that are disabled, shouldn't be shown in configure options tab.
* Fail gracefully and continue PP when setting file timestamp to airdate chokes Fixes [#269](https://github.com/SickRage/sickrage-issues/issues/269)
* Allow changing categories for defautl newznab providers. Caveat: They are on the "Custom Newznab Providers" tab where you change the categories, until the js can be fixed
* Need to use generic exceptions for all seasons, not just season 1
* Need to use generic exceptions for all seasons, not just season 1
* Filter scene exceptions a bit different
* Fromstring is already the tree root -.-
* Explicitly encode in the exception raises for name parser Partial issue of [#12](https://github.com/SickRage/sickrage-issues/issues/12)
* Must use etree.fromstring instead of etree.parse since its a string instead of a stream now in PMS
* Must check if generic exceptions are in the exceptionList already before appending them. Fixes [#852](https://github.com/SickRage/sickrage-issues/issues/852)
* Add explanation about subliminal score math
* Don't show CC button for 'snatched' episodes that used to be 'downloaded' but failed
* Fix SickRage/sickrage-issues/issues/824

### v2016.02.22-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.02.16-1...v2016.02.22-1)

* Use a decorator to prevent processing a dir more than once at a time, regardless of caller Fixes [#1028](https://github.com/SickRage/sickrage-issues/issues/1028)
* Fixes [#1042](https://github.com/SickRage/sickrage-issues/issues/1042) Fixes touchFile to use ek and check file exists
* Disable auto pp when postpone if no subs
* Fixes url encoded censored items in logs not being censored.
* Plex: Always return True when getting auth token if username/password aren't configured
* Fix issue where last_update_indexer was using date instead of datetime, use time based updates xml from tvdb instead of day.xml. Even though it is deprecated it works BETTER
* even more fixes
* more fixes
* Quck subtitles improvements
* Check SUBTITLES_MULTI and make subs exceptions as dict
* Delete unwanted subtitles
* Check if sub is enabled before postpone
* Show refresh/update should have high priority
* Force "Subtitles Multi-Language" if more than one wanted subtitle language
* Subtitle language exceptions as Dict
* Add PR/Issue templates, move contributing.md to .github
* Add option to keep only wanted subs
* Delete unwanted subtitles if we don't want them
* Check if show has subtitle enable before postpone PP
* Add "ignore subs" setting in manual PP
* Remove subliminal patch, grunt like what
* Updated npm deps Remove patches (subliminal is not locally patched anymore)
* Fix TPB when using an invalid proxy
* Warn about database owner/permissions
* NewPCT:
  - Unicode literals
  - Fix string quotes
  - Fix get_url override
  - Conformity and cleanup
* Make the show updater run on startup Fix it so that it doesnt keep updating the same shows over and over Fix cycleTime for show updater for status page Clean up logging in tv.py when setting the next episode and updating show
* Disable subtitles code db check
* Fix searches with ABNormal Replace double quotes with single quotes as per our decided convention
* Catch shutil errors and proper display as error/warning
* Create gists as secret instead of public
* Add "(musicbolt.com)" to removewordslist
* Fixes detection of "nothing found" when search result set is empty for torrentbytes. Fix [#235](https://github.com/SickRage/sickrage-issues/issues/235)#issuecomment-185068695
* Pass params through getRSSFeeds to get_url instead of urlencode Update string quotes, u prefix removal and unicode literals for bunsearch, nyaa, omg, rsstorrents, shazbat, womble Clean up and improve those providers

### v2016.02.16-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.02.11-1...v2016.02.16-1)

* Add option to ini to allow PMS update without token or user/pass when you dont require authentication config.ini only option for now
* Use provider's get_url for getting rss feeds instead of urllib/httplib2 Fixes bozo, and removes old code Normalizes logging
* Update contributing.md
* Dont run FINDSUBTITLES thread right on SR start
* Allow passing arguments future= and past= for range of weeks from today to add to the webcal http://localhost:8081/calendar?past=2&future=3 both default to 52
* Handle float log sizes Increase default log size to 10MB to reduce rolling over Fix SickRage/sickrage-issues/issues/892 Replaces [#1027](https://github.com/SickChill/SickChill/issues/1027)
* Fix typo preventing confirm modal not showing before submitting errors
* RARBG:
  - Show api error messages
  - Show log when no torrents differentiated from when no data returned
  - Move sleep to prevent hitting request limit and use CPU_PRESETS
* RARBG:
  - Use unicode literals, remove u prefixes, use " over ' for strings
  - Use .format over token string formatting
  - Pass returns="json"
  - Remove excess logging, pop elements as they are used from the json
* BTDigg:
  - Use unicode_literals, remove u prefixes, use " instead of ' for strings
  - Use .format instead of token string formatting throughout
  - Pass params to get_url, and specify json response type
  - Remove duplicitous logging
  - General BTDigg cleanup
  - Add ! to config_providers since btdigg api is currently not working.
* TorrentBytes:
  - Use unicode_literals, remote u prefixes, use " over ' for strings
  - Use urljoin throughout
  - Pass search params to requests instead of building the url
  - Pass response="text" to get_url
  - Parse table headers and use for cell indexing
* Bitcannon:
  - Use unicode_literals and remove u prefixes
  - Use " over ' for strings
  - Use validators for custom_url
* TorrentLeech
  - Use unicode_literals and remove u prefixes
  - Use " over ' for strings
  - Use .format over token formatting
  - Use urljoin over string concat for urls
  - Pass params to get_url instead of urlencoding
* KAT:
  - Use unicode_literals, remove u prefix, use " for strings
  - Use validators for custom_url
  - Use urljoin throughout
  - BS4Parser for better cleanup
  - Fix issue with magnets
* AbNormal Updates
  - Pass response="text" for login and search
  - No need to use named format replacements unless you are using the same replacement more than once
  - Switch back to " over ' for strings
* Alpharatio updates * Use urljoin over string concat * Use unicode_literals * Remove search url log and pass response param to get_url
* TPB: * Use unicode_literals and remove u prefix * Use " over ' for strings * Use .format over string tokens * Remove extra search url log and pass response='text' to get_url * use validators to validate custom_url
* BinSearch:
  - Use unicode_literals and remove u prefix
  - Use " over ' for strings
  - Use .format over % token string formatting
  - Use urljoin instead of concat for urls
  - Import urljoin, urlencode from requests.compat
* Use a requests hook for get_url in providers, show post data for post requests
* Fix seeders/leechers log lines
* Providers:
  - Only include freeleech in provider \_\_init\_\_ if provider supports it (same for minseed, minleech, etc)
  - No need to encode search_string, it is encoded in _get_*_search_strings
* Add URL logging to GenericProvider.get_url
* Add raw response object as a getURL return type Add pending deprecation warnings for getURL arguments json, need_bytes Add pending deprecation warning for getURL returning text
* Update search string and mode log line for all providers
* Add lib/validators to be used with custom_urls and email and ip validation of user input and other places
* Import urlencode from requests.compat instead
* Clean up airdate modify timestamp handling and make sure exceptions are caught. Fixes [#914](https://github.com/SickRage/sickrage-issues/issues/914)
* Make sure etree always adds xml declaration for mede8er and specify encoding explicitly Trying to fix [#862](https://github.com/SickRage/sickrage-issues/issues/862)
* Allow file globs in "Sync File Extensions" setting to postpone postprocessing
* Remove old_scene_quality Remove quality assertion Refactor sceneQuality => scene_quality Fix anime bluray detection
* Append show name to show search strings regardless of searched season
* Fix logging when result is None fixes SickRage/sickrage-issues/issues/902
* Fix apikey shown in log when = is urlencoded as %3D
* Don't limit allowed extensions to 3 chars in post processor
* Reduce subtitle score to match only Series, Season, Episode and Year
* Fail gracefully and continue PP when setting file timestamp to airdate chokes Fixes [#269](https://github.com/SickRage/sickrage-issues/issues/269)
* Allow changing categories for default newznab providers. Caveat: They are on the "Custom Newznab Providers" tab where you change the categories, until the js can be fixed
* Use generic exceptions for all seasons, not just season 1

### v2016.02.11-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.02.10-1...v2016.02.11-1)

* Explicitly encode in the exception raises for name parser Partial issue of [#12](https://github.com/SickRage/sickrage-issues/issues/12)
* Must check if generic exceptions are in the exceptionList already before appending them. Fixes [#852](https://github.com/SickRage/sickrage-issues/issues/852)
* Add explanation about subliminal score math
* Don't show CC button for 'snatched' episodes that used to be 'downloaded' but failed
* Fix SickRage/sickrage-issues/issues/824
* Added network logo's  for RMC decouverte and UP TV.
* Use .eu for podnapisi
* Fix cyclic dependancy in notifiers so we can use helpers, clean up some crazy
* Updated subliminal develop (864ecf4) and legendastv provider, adjusted scores for subtitles
* Rewrite a good bit of plex notifier to use requests and maintain headers
* Fix download url generation in alpharatio, danishbits, gft, speed.cd Fixes [#818](https://github.com/SickRage/sickrage-issues/issues/818)
* Fix anime bluray qualities

### v2016.02.10-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.02.09-2...v2016.02.10-1)

* Use json scene exceptions
* Only get scene exceptions matching season we are searching for
* Set "Authentication Failed" as warning
* Fixes issue of MTV not downloading
* Add an API method to clear the logs
* Remove need for ek() in subtitles
* Fixe size on transmithenet

### v2016.02.09-2

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.02.08-1...v2016.02.09-2)

* Use xem absolute numbers for tvdb mapping if tvdb doesnt provide them, fixes american dad if you disable scene numbering
* Dont pass q on rss update, use sickbeard.USENET_RETENTION directly regardless of mode
* Set search string for subsequent scene exceptions after tvdbid has been popped
* Fix provider log message by decoding to utf-8 instead
* Fix daily search in ABNormal.ws Fixes [#768](https://github.com/SickRage/sickrage-issues/issues/768)

### v2016.02.08-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.02.07-1...v2016.02.08-1)

* Fix decode by using utf-8 instead Fix unnecessary decode on urlencoded string
* Make sickbeard.gh work even when github login settings are incorrect so that the updater still works Lint sickbeard.\_\_init\_\_
* Revert "Add 5020 (foreign) to default newznab providers (and some missing nzb…"
* Add 5020 (foreign) to default newznab providers (and some missing nzbs.org cats)
* Fix Unicode decoding errors in newznab logging and ex
* Display exception text from NameParser in validateDir
* Fix for nzb indexers who dont support tvdbid or happen to have missed a tvdbid mapping for some shows/episodes. Fixes [#667](https://github.com/SickRage/sickrage-issues/issues/667) Fixes [#782](https://github.com/SickRage/sickrage-issues/issues/782)
* Fix "No processable items found in folder" by building name cache on startup... /slap miigotu and his miibugs
* Change config mako for nzb also
* Swap settings order "Alternate search mode as fallback is fine" and "Season search mode"
* Update nzbToMedia to V10.13 thanks to @clinton-hall
* Standardize providers
* Add log message to warn user and/or help debug possible issues
* Dont unpack again if files were previously unpacked when
* Show log message when not able to search provider
* Fix issue when release is RARred
* Use div or span when using css to apply an image, not an img tag
* Change width of infoTable to 100% in config.mako
* Revert "Fetch only current branch. Not all branches"
* Make sure - is at the end of character groups in regex to avoid future mistakes, even if they arent preceeded by another char Add , as a seperator between episode and extra_info for normal regex Fixes [#771](https://github.com/SickRage/sickrage-issues/issues/771)
* Fix schedule so it doesnt bork when db upgrade
* Remove the rest of the unnecessary len() in if's Rework the find_search_results a bit to use scene numbers depending if the show is scene or not to determine if the result matches or should be skipped, it was quite iffy, and still is.
* Fix bug that caused plex server/client password to be set to all * when saving notifications if you did not type them in after loading the page
* Use a better exception text for InvalidShow and InvalidName.
* Normalize more name_parser.parse calls and exception handling
* Use the string passed when raising InvalidNameException or InvalidShowException to avoid maintaining log text in too many places.
* Fix small mistake in name_parser, use better variable names in quality pills
* No need to use len to check if a list is not empty (name_parser.parser) No need to cast to list before iterating a set (name_cache) Lint name_parser.parser, fix small bug preventing S00 from being able to be parsed
* Rename initial to preferred in quality pill text

### v2016.02.07-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.01.31-1...v2016.02.07-1)

* encode io.open in helper with ek()
* Updated subliminal develop (f245383)
* Updated guessit (28b6789)
* Updated rebulk (68a4588)
* Updated legendastv provider. Fixed a few things in subtitles.py
* Improve bitcannon provider Fixes [#763](https://github.com/SickRage/sickrage-issues/issues/763)
* Re-enable cachecontrol, except use it in memory
* Fix testing providers search types manually
* Rework tvchaosuk and fix daily search
* Fix log showing errors incorrectly by iterating over a string in PP when unrar fails
* Change speed.cd url to use https to make it work for when ppl use the force secure connections on their site
* Switches nzb and torrent method icons on dropdown switch
* Some fixes concerning the icons.
* Added icons to the buttons & clients.
* Use node 5.0.0 instead of 0.12 for build tests, make npm quiet during ci, updated npm deps
* Replaced all menu icons and logos with colored versions.
* Removed duplicate/unused css code.
* Fix bug in PP where rar'd files would say there were no processable items found in folder after extraction
* Fix typeError breaking backlog/manual/failed searches
* Fixes [#736](https://github.com/SickRage/sickrage-issues/issues/736)
* Add editorconfig
* Dont show traceback if error sending torrent
* Dont clear old snatch history in failed.db, see if that fixes some issues with fdh
* Various flaking/code cleanup Change log from debug to info for http status code returned from clients Change log from error to warning when sending to client failed (the request failed, client down or network error maybe)
* Fix Attribute Error object has no attribute 'errno'
* Revert "Added add from popular anime list."
* Revert "Added anidb http client."
* Clean up recommended.py
* Optimize order of usage of parameters in \_\_init\_\_, optimize imports
* Fix spacing, tabs, spelling errors, non-unicode strings, docstrings, license information, encoding declarations, EOF, unused variables
* Group french team fansub, new encompassing anime regex
* Some changes to the help & info page.

### v2016.01.31-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.01.25-1...v2016.01.31-1)

* Fix restart not reloading page
* Add an "Add from anidb popular list" page
* Added UHD quality support (4k, 8k, etc)
* Updated subliminal to latest version
* Updated guessit to v2
* Fix some missing imports and undefined variables
* Fix boxcar2/freemobile sms
* Fix null season numbers being added to db
* Fix adding anime shows causing mako errors
* New icons on the status page
* Fix several providers
* Many small random fixes

### v2016.01.25-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.01.23-1...v2016.01.25-1)

* Fix [#2967](https://github.com/SickChill/SickChill/issues/2967) ([#2972](https://github.com/SickChill/SickChill/issues/2972))
* Genres bug ([#2969](https://github.com/SickChill/SickChill/issues/2969))
* Fix [#2965](https://github.com/SickChill/SickChill/issues/2965) + [#1789](https://github.com/SickChill/SickChill/issues/1789) ([#2966](https://github.com/SickChill/SickChill/issues/2966))
* Fix the imdb image regex so that the images on '/addShows/popularShows' ([#2964](https://github.com/SickChill/SickChill/issues/2964))
* Add skytorrents ([#2957](https://github.com/SickChill/SickChill/issues/2957))
* Fix [#2951](https://github.com/SickChill/SickChill/issues/2951) - This will be a merge conflict with merging develop, dont overlook!
* Fix bulkcheck in displayShow for seasons ([#2958](https://github.com/SickChill/SickChill/issues/2958))
* Initialize HTTPServer correctly for xheaders ([#2955](https://github.com/SickChill/SickChill/issues/2955))
* Fix tablesorter on mass update page, Fixes [#2951](https://github.com/SickChill/SickChill/issues/2951) ([#2954](https://github.com/SickChill/SickChill/issues/2954))
* Fixes ([#2946](https://github.com/SickChill/SickChill/issues/2946))
* Add Anime support for SxEE ([#2949](https://github.com/SickChill/SickChill/issues/2949))
* Fix scene search ([#2938](https://github.com/SickChill/SickChill/issues/2938))
* More work on rtorrent lib Fixes [#2934](https://github.com/SickChill/SickChill/issues/2934) Fixes [#2936](https://github.com/SickChill/SickChill/issues/2936)
* TRAKT_REMOVE_SHOW_FROM_SICKRAGE will also check for Canceled series, Fixes [#2921](https://github.com/SickChill/SickChill/issues/2921)
* Fix magnets in rtorrent, Fixes [#2880](https://github.com/SickChill/SickChill/issues/2880)
* Update certifi
* Update main.mako ([#2924](https://github.com/SickChill/SickChill/issues/2924))
* Small adjustment
* Change cert/key len to 4096 to appease debian
* Dont enable sickrage background by default
* fix filelist provider - unknown download link ([#2918](https://github.com/SickChill/SickChill/issues/2918))
* Fix [#1269](https://github.com/SickChill/SickChill/issues/1269)
* Fix [#2897](https://github.com/SickChill/SickChill/issues/2897) ([#2910](https://github.com/SickChill/SickChill/issues/2910))
* Fix layout issue on show details page ([#2909](https://github.com/SickChill/SickChill/issues/2909))
* Custom Background, fix file browser bug when browsing for files (not dirs) ([#2907](https://github.com/SickChill/SickChill/issues/2907))
* More clean
* Fix recursion with disk_usage caused by refactor, rewrite much of pp
* Fix bug in tv.py
* Fix bug in pp, more refactoring
* Fix is_sync_file tests
* Some more refactoring
* Rename is_rarfile to is_rar_file
* Rename isMediaFile to is_media_file
* Adjust validate_dir, remove part from sync files, adjust logger so exceptions show in log viewer
* Fixes [#2898](https://github.com/SickChill/SickChill/issues/2898)
* Fix anime episode search
* Fix tests
* Adjust code to work with rarfile rather than unrar2
* Remove unrar2, update rarfile
* Add custom_url support to torrentday, Fixes [#2834](https://github.com/SickChill/SickChill/issues/2834) ([#2877](https://github.com/SickChill/SickChill/issues/2877))
* Fix pycharm warnings (mostly)
* Make calling super init first in subclasses init work.
* Suppress abstract class warning for api classes Rename class names to match pep8 camelCase Call super init correctly
* Pp adjustments ([#2870](https://github.com/SickChill/SickChill/issues/2870))
* Fix some queue task initialization issues, add new param to the PP task to force return result of the task, currently disabled ([#2867](https://github.com/SickChill/SickChill/issues/2867))
* Fix [#2659](https://github.com/SickRage/SickRage/issues/2659) ([#2862](https://github.com/SickChill/SickChill/issues/2862))
* Use 3 digit episode numbers for anime ([#2855](https://github.com/SickChill/SickChill/issues/2855))
* NZBtoMedia needs updated
* Switch from getopt to argparse, replaces [#737](https://github.com/SickChill/SickChill/issues/737) ([#2853](https://github.com/SickChill/SickChill/issues/2853))
* fov regex update ([#2851](https://github.com/SickChill/SickChill/issues/2851))
* Add a test around isRarFile
* Fix content and enhance email notification

### v2016.01.23-1

[full changelog](https://github.com/SickChill/SickChill/compare/v2016.01.20-1...v2016.01.23-1)

* Remove duplicate FDH setting
* Add seeds/leechers to some log messages during searches
* Refactor the way we initialize provider caches
* Standardize providers more
* Add ABNormal and PhxBit providers
* Fix newznab issues with pre-aired episodes and maxage, and bad q params
* Fix several UI bugs
* Add SSL Version to help&info page, and make it pretty
* Fix error when PP finds file of same size exists
* Prepare to add ability to add shows from anidb lists (if they are on tvdb)
* Fix confirmed downloads setting for TPB which was only allowing unconfirmed results
* Fix discrepancy between home and display show for show file size when show has multi-eps
* Fix t411
* Fix several NoneType exceptions

### v2016.01.20-1


* Change TPB domain back to .se, use a custom url if it doesnt work
* Fix restart on gentoo
* Randomize default show updater hour between 2-4 am
* Randomize show updater minute during that hour (helps spread load for indexers)
* Adjust some errors to warnings, especially in telegram
* Fix email notifier when using TLS
* Update torrentbytes icon, add some missing network logos
* Fix omgwtfnzbs and newznab improvements
* Fix RARBG
* Update GFTracker provider code to new format
* Switch to nosetests and abandon custom unit test loader
* Fix NZBGet HTTPS setting and sabNZBd Forced Priority setting
* General refactoring and code cleanup

