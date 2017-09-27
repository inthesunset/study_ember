# Mentor-follower study on Emberjs
## <1> Over which time period/range did you look at that?  
  (6 years old up to now)
(I checked the atime and find the time span)
2011.04.30(this repo starts from 2011.04.24 and it's still alive now) - 2015.12.19

## <2> What kind of mentors are there, How many followers they have, are these people they started earlier or late?  
```
#Here is a summary of this matrix:  
summary(ember_authors)
                                   follower                                       mentor          score
 Jay Phelps|hello@jayphelps.com        :  571   Peter Wagenet|peter.wagenet@gmail.com:  781   Min.   :  0.00316
 Robert Jackson|robert.w.jackson@me.com:  544   Erik Bryn|erik.bryn@gmail.com        :  641   1st Qu.:  0.01322
 Miguel Camba|miguel.camba@gmail.com   :  534   Yehuda Katz|wycats@gmail.com         :  634   Median :  0.03000
 Martin Muñoz|im.mmun@gmail.com        :  511   tomhuda|tomhuda@tilde.io             :  622   Mean   :  0.26644
 Stefan Penner|stefan.penner@gmail.com :  505   Stefan Penner|stefan.penner@gmail.com:  600   3rd Qu.:  0.08548
 Ilya Radchenko|ilya@burstcreations.com:  472   tchak|paul@chavard.net               :  531   Max.   :252.28434
 (Other)                               :47582   (Other)                              :46910
 ```

Let's first pick high score mentor-follower relationship pairs to study:  
*Pick score > 10, 192 pairs of m-f achieved.  *
### Mentors
```
Frequencies of mentors among (score > 10)them.
1                        Robert Jackson|robert.w.jackson@me.com   29
2                         Peter Wagenet|peter.wagenet@gmail.com   23
3                         Stefan Penner|stefan.penner@gmail.com   16
4                                      tomhuda|tomhuda@tilde.io   16
5                                Jay Phelps|hello@jayphelps.com   13
6                                  Yehuda Katz|wycats@gmail.com    9
7                         Charles Jolley|charles@sproutcore.com    8
8                             Kris Selden|kris.selden@gmail.com    8
9                                Martin Muñoz|im.mmun@gmail.com    8
10                       Matthew Beale|matt.beale@madhatted.com    7
11                                Erik Bryn|erik.bryn@gmail.com    6
12 Tom Dale and Yehuda Katz|engineering+tomdale+wycats@tilde.io    6
13                               tomhuda|tomhuda@strobecorp.com    5
14                        Trek Glowacki|trek.glowacki@gmail.com    4
15                        Lance Pollard|lancejpollard@gmail.com    3
16                                      machty|machty@gmail.com    3
17                                       tchak|paul@chavard.net    3
18                                  Tom Dale|tom@sproutcore.com    3
19                                Dan Gebhardt|dan@cerebris.com    2
20                      Justin Brown|justinbrown.work@gmail.com    2
21                                Luke Melia|luke@lukemelia.com    2
22                          Mike Andrzejewski|mike.aski@free.fr    2
23                       Ryunosuke SATO|tricknotes.rs@gmail.com    2
24                               Stanley Stuart|stanley@stan.li    2
25                           Teddy Zeenny|teddyzeenny@gmail.com    2
26                               Trek Glowacki|trek@groupon.com    2
27                  Alex Navasardyan|alex.navasardyan@yahoo.com    1
28                                       bmac|bmac325@GMail.com    1
29                              Edward Faulkner|ef@alum.mit.edu    1
30                              Piotr Sarnacki|drogus@gmail.com    1
31                                     Tom Dale|tom@tomdale.net    1
32                            Tony Coconate|me@tonycoconate.com    1
```
-  Note: there is a difference between the num of commits showing on github and the one retrieved from git log, probably because of the way github calculates -- "Contributions to master, excluding merge commits"
```
#The 32 mentors, first commit time, commit nums
Robert Jackson|robert.w.jackson@me.com;1376078704;2013.08.09;2036
Peter Wagenet|peter.wagenet@gmail.com;1307752340;2011.06.11;789
Stefan Penner|stefan.penner@gmail.com;1317441759;2011.10.01;762
tomhuda|tomhuda@tilde.io;1325288772;2011.12.30;288
Jay Phelps|hello@jayphelps.com;1368054013;2013.05.08;62
Yehuda Katz|wycats@gmail.com;1308783197;2011.06.22;345
Charles Jolley|charles@sproutcore.com;1305679083;2011.05.18;46
Kris Selden|kris.selden@gmail.com;1323198863;2011.12.06;294
Martin Muñoz|im.mmun@gmail.com;1377241148;2013.08.23;229
Matthew Beale|matt.beale@madhatted.com;1359141357;2013.01.25;278
Erik Bryn|erik.bryn@gmail.com;1306377925;2011.05.26;379
Tom Dale and Yehuda Katz|engineering+tomdale+wycats@tilde.io;1421803613;2015.01.21;127
tomhuda|tomhuda@strobecorp.com;1304195051;2011.04.30;202
Trek Glowacki|trek.glowacki@gmail.com;1309283466;2011.06.28;133
Lance Pollard|lancejpollard@gmail.com;1335904528;2012.05.01;6
machty|machty@gmail.com;1358567912;2013.01.29;219
tchak|paul@chavard.net;1308821603;2011.06.23;95
Tom Dale|tom@sproutcore.com;1306735187;2011.05.30;133
Dan Gebhardt|dan@cerebris.com;1326235190;2012.01.10;86
Justin Brown|justinbrown.work@gmail.com;1327104398;2012.01.21;56
Luke Melia|luke@lukemelia.com;1325878682;2012.01.06;89
Mike Andrzejewski|mike.aski@free.fr;1324369719;2011.12.20;17
Ryunosuke SATO|tricknotes.rs@gmail.com;1360849781;2013.02.14;223
Stanley Stuart|stanley@stan.li;1386471406;2013.12.08;45
Teddy Zeenny|teddyzeenny@gmail.com;1351547567;2012.10.29;110
Trek Glowacki|trek@groupon.com;1343058322;2012.07.23;69
Alex Navasardyan|alex.navasardyan@yahoo.com;1365652774;2013.04.11;78
bmac|bmac325@GMail.com;1376792032;2013.08.18;46
Edward Faulkner|ef@alum.mit.edu;1309725379;2011.07.03;205
Piotr Sarnacki|drogus@gmail.com;1313460851;2011.08.16;17
Tom Dale|tom@tomdale.net;1335938918;2012.05.02;97
Tony Coconate|me@tonycoconate.com;1402524361;2014.06.11;3
```

- **Observation 1:  Tony Coconate 3 unique commits => score 10, Lance Pollard 6 unique commits => score (83,43,31), Cases where few commits result in strong m-f score**
- **Observation 2: More commits would have more pairs of m-f(looks like it's kind of linear)**
- **Observation 3: Most of them starts before 2013(included). (14 starts in 2011, 7 in 2012, 9 in 2013, 1 in 2014, 1 in 2015)**

### Followers
```
Frequencies of followers among 47 followers:
bmac|bmac325@GMail.com    1
Chad Hietala|chadhietala@gmail.com    1
Christian Wesselhoeft|christian@cwesselhoeft.com    1
Colin Campbell|colin@strobecorp.com    1
Doug Yun|yun.douglas@gmail.com    1
Erich Ocean|erich.ocean@me.com    1
Michael Crismali|michael.crismali@gmail.com    1
Mike Andrzejewski|mike.aski@free.fr    1
Piotr Sarnacki|drogus@gmail.com    1
Sean Doyle|sean.p.doyle24@gmail.com    1
Steven Hancock|stevenh512@gmail.com    1
Teddy Zeenny|teddyzeenny@gmail.com    1
Tom Dale|engineering@tilde.io    1
Tom Dale|tom@tomdale.net    1
Tomhuda Katzdale|tomhuda@tilde.io    1
tomhuda|tomhuda@strobecorp.com    1
Trek Glowacki|trek@groupon.com    1
twinturbo|me@broadcastingadam.com    1
Alex Navasardyan|twokul@users.noreply.github.com    2
Colin Campbell|colin.campbell@gmail.com    2
Edward Faulkner|ef@alum.mit.edu    2
Jo Liss|joliss42@gmail.com    2
Tom Dale|tom@sproutcore.com    2
tomhuda|tomhuda@tilde.io    2
Dan Gebhardt|dan@cerebris.com    3
machty|machty@gmail.com    3
Ryunosuke SATO|tricknotes.rs@gmail.com    3
tchak|paul@chavard.net    3
Trek Glowacki|trek.glowacki@gmail.com    3
Erik Bryn|erik.bryn@gmail.com    4
Ilya Radchenko|ilya@burstcreations.com    4
Marten Schilstra|mail@martenschilstra.nl    4
Miguel Camba|miguel.camba@gmail.com    4
Tom Dale and Yehuda Katz|engineering+tomdale+wycats@tilde.io    4
Christian Wesselhoeft|hi@xtian.us    5
Justin Brown|justinbrown.work@gmail.com    5
Kris Selden|kris.selden@gmail.com    5
Lance Pollard|lancejpollard@gmail.com    5
Alex Navasardyan|alex.navasardyan@gmail.com    6
Stanley Stuart|stanley@stan.li    6
Peter Wagenet|peter.wagenet@gmail.com    7
Matthew Beale|matt.beale@madhatted.com    8
Martin Muñoz|im.mmun@gmail.com    9
Yehuda Katz|wycats@gmail.com    9
Jay Phelps|hello@jayphelps.com   19
Stefan Penner|stefan.penner@gmail.com   19
Robert Jackson|robert.w.jackson@me.com
```

-  The corresponding data for followers is shown as follows:   
```  
#The 47 mentors, first commit time, time in readable format, commits nums
Alex Navasardyan|alex.navasardyan@gmail.com;1419891674;2014.12.29;14
Alex Navasardyan|twokul@users.noreply.github.com;1394844850;2014.03.15;79
bmac|bmac325@GMail.com;1376792032;2013.08.18;46
Chad Hietala|chadhietala@gmail.com;1402544480;2014.06.12;28
Christian Wesselhoeft|christian@cwesselhoeft.com;1365300434;2013.04.07;29
Christian Wesselhoeft|hi@xtian.us;1441907037;2015.09.10;14
Colin Campbell|colin.campbell@gmail.com;1308765839;2011.06.22;9
Colin Campbell|colin@strobecorp.com;1304482012;2011.05.04;16
Dan Gebhardt|dan@cerebris.com;1326235190;2012.01.10;86
Doug Yun|yun.douglas@gmail.com;1406599832;2014.07.29;57
Edward Faulkner|ef@alum.mit.edu;1309725379;2011.07.03;205
Erich Ocean|erich.ocean@me.com;1306401216;2011.05.26;8
Erik Bryn|erik.bryn@gmail.com;1306377925;2011.05.26;379
Ilya Radchenko|ilya@burstcreations.com;1388788935;2014.01.03;65
Jay Phelps|hello@jayphelps.com;1368054013;2013.05.08;62
Jo Liss|joliss42@gmail.com;1329339265;2012.02.15;111
Justin Brown|justinbrown.work@gmail.com;1327104398;2012.01.21;56
Kris Selden|kris.selden@gmail.com;1323198863;2011.12.06;294
Lance Pollard|lancejpollard@gmail.com;1335904528;2012.05.01;6
machty|machty@gmail.com;1358567912;2013.01.19;219
Marten Schilstra|mail@martenschilstra.nl;1431355296;2015.05.11;74
Martin Muñoz|im.mmun@gmail.com;1377241148;2013.08.23;229
Matthew Beale|matt.beale@madhatted.com;1359141357;2013.01.25;278
Michael Crismali|michael.crismali@gmail.com;1376963178;2013.08.20;13
Miguel Camba|miguel.camba@gmail.com;1407803109;2014.08.12;133
Mike Andrzejewski|mike.aski@free.fr;1324369719;2011.12.20;17
Peter Wagenet|peter.wagenet@gmail.com;1307752340;2011.06.11;789
Piotr Sarnacki|drogus@gmail.com;1313460851;2011.08.16;17
Robert Jackson|robert.w.jackson@me.com;1376078704;2013.08.09;2036
Ryunosuke SATO|tricknotes.rs@gmail.com;1360849781;2013.02.14;223
Sean Doyle|sean.p.doyle24@gmail.com;1416934183;2014.11.25;25
Stanley Stuart|stanley@stan.li;1386471406;2013.12.08;45
Stefan Penner|stefan.penner@gmail.com;1317441759;2011.10.01;762
Steven Hancock|stevenh512@gmail.com;1316386595;2011.09.18;3
tchak|paul@chavard.net;1308821603;2011.06.23;95
Teddy Zeenny|teddyzeenny@gmail.com;1351547567;2012.10.29;110
Tom Dale and Yehuda Katz|engineering+tomdale+wycats@tilde.io;1421803613;2015.01.21;127
Tom Dale|engineering@tilde.io;1418698548;2014.12.16;41
Tom Dale|tom@sproutcore.com;1306735187;2011.05.30;133
Tom Dale|tom@tomdale.net;1335938918;2012.05.02;97
Tomhuda Katzdale|tomhuda@tilde.io;1340047279;2012.06.18;30
tomhuda|tomhuda@strobecorp.com;1304195051;2011.04.30;202
tomhuda|tomhuda@tilde.io;1325288772;2011.12.30;288
Trek Glowacki|trek.glowacki@gmail.com;1309283466;2011.06.28;133
Trek Glowacki|trek@groupon.com;1343058322;2012.07.23;69
twinturbo|me@broadcastingadam.com;1352410352;2012.11.08;36
Yehuda Katz|wycats@gmail.com;1308783197;2011.06.22;345
```
-  **First commit distribution: (17 starts in 2011, 9 starts in 2012, 10 starts in 2013, 8 starts in 2014, 3 starts in 2015)**

### 47 followers v.s. 32 mentors:
- These 4 are not in followers(only in mentors):
```
Charles Jolley|charles@sproutcore.com;1305679083;2011.05.18;46
Luke Melia|luke@lukemelia.com;1325878682;2012.01.06;89
Alex Navasardyan|alex.navasardyan@yahoo.com;1365652774;2013.04.11;78
Tony Coconate|me@tonycoconate.com;1402524361;2014.06.11;3
```

-  These 19 are not in mentors(only in followers)
```
Alex Navasardyan|alex.navasardyan@gmail.com;1419891674;2014.12.29;14
Alex Navasardyan|twokul@users.noreply.github.com;1394844850;2014.03.15;79
Chad Hietala|chadhietala@gmail.com;1402544480;2014.06.12;28
Christian Wesselhoeft|christian@cwesselhoeft.com;1365300434;2013.04.07;29
Christian Wesselhoeft|hi@xtian.us;1441907037;2015.09.10;14
Colin Campbell|colin.campbell@gmail.com;1308765839;2011.06.22;9
Colin Campbell|colin@strobecorp.com;1304482012;2011.05.04;16
Doug Yun|yun.douglas@gmail.com;1406599832;2014.07.29;57
Erich Ocean|erich.ocean@me.com;1306401216;2011.05.26;8
Ilya Radchenko|ilya@burstcreations.com;1388788935;2014.01.03;65
Jo Liss|joliss42@gmail.com;1329339265;2012.02.15;111
Marten Schilstra|mail@martenschilstra.nl;1431355296;2015.05.11;74
Michael Crismali|michael.crismali@gmail.com;1376963178;2013.08.20;13
Miguel Camba|miguel.camba@gmail.com;1407803109;2014.08.12;133
Sean Doyle|sean.p.doyle24@gmail.com;1416934183;2014.11.25;25
Steven Hancock|stevenh512@gmail.com;1316386595;2011.09.18;3
Tom Dale|engineering@tilde.io;1418698548;2014.12.16;41
Tomhuda Katzdale|tomhuda@tilde.io;1340047279;2012.06.18;30
twinturbo|me@broadcastingadam.com;1352410352;2012.11.08;36
```
-  28 developers are same among highest 192 pairs of m-f.


### Questions
1. What is the productive ratio between the mentors and followers?  
In succession paper, the productivity is measured by the number of tasks assigned, would it make more sense to consider the frequency of commits/file changes as the factor of the productivity?

### In process
1. For these 192 pairs of m-f, generating their commit history within this period to learn  
  -  where did they come from?
  -  Is emberjs their primary or secondary project?
  -  where are they heading?
  -  How was their productivity in other projects?

### Suggestions

## <3> where do they come from, where do they go to, do they start from emberjs?
- Denifitions:
  1. If the first commit author Au1 made to project A is prior to the one made to emberjs/ember.js, we say developer Au1 comes from project A.
  2. If the first commit author Au1 made to project A is after the one made to emberjs/ember.js, we say developer Au1 go to project A.
  3. If the first commit author Au1 made is to emberjs/ember.js, we say developer Au1 starts from emberjs/ember.js


- Procedures:
  1. For each of the 51 developers, we get a list of projects/repos through an author2project map which consists of developer and the projects he or she made commits to.
  2. Considering the fact that there are lots of forked repos(github fork) which themselves are just  by-products of the process of project development, we use github API to find their source projects(the /source/full_name field in the response from GET /repos/:owner/:repo) which substantially narrowed down the scope.
  3. We cloned these projects to local machine and ran git log to extract commit history of each clone.
  4. For each project of one developer, grab the time stamp of his first commit and compare it with the one in emberjs/ember.js and determine it's a project the developer come from or go to.
  5. If one developer comes from no project, then he starts from emberjs.


-  Here is the result:
  -  42 out of 51 developers don't start from emberjs
  -  Here are the rest 9 developers who started from emberjs:
     ```
     Alex Navasardyan <twokul@users.noreply.github.com>
     Martin Muñoz <im.mmun@gmail.com>
     Michael Crismali <michael.crismali@gmail.com>
     Mike Andrzejewski <mike.aski@free.fr>
     Teddy Zeenny <teddyzeenny@gmail.com>
     Tom Dale <engineering@tilde.io>
     Tomhuda Katzdale <tomhuda@tilde.io>
     tomhuda <tomhuda@tilde.io>
     Trek Glowacki <trek@groupon.com>
     ```
     The detailed file is /gamma/audris/yma/gitlogDeltaall/MF.stas/9developers.headings, **they likely to touch repos in one owner(one group or one developer) e.g. tildeio,broccolijsbroccolijs,emberjs,ember-cli**
  -  Among 42 developers, many developers came from same projects:
     ```
     # The first column represents how man developers come from the project following.
      2 brynary/webrat
      2 erikhuda/thor
      2 krisselden/guard-rsync
      2 rails-learning/railsguide-zh
      2 sproutcore/website
      2 teamcapybara/capybara
      2 twokul/githubsearch
      2 wycats/guides
      2 wycats/handlebars.js
      3 ember-cli/ember-cli
      3 sproutcore/guides
      3 sproutcore/Todos-Example
      3 sproutit/sproutcore
      4 sproutit/sproutcore-abbot
      5 emberjs/website
      5 idolweb/activejob-lock
      7 sproutcore/abbot
     11 rails/rails
     12 sproutcore/sproutcore
     ```
  -  Among 42 developers, many developers went to same projects:
     ```
     # The first column represents how man developers went to the project following.
     ...
     3 broccolijs/broccoli-filter
     3 broccolijs/broccoli-funnel
     3 cibernox/ember-cli-yuidoc
     3 DavyJonesLocker/ember-suave
     3 dgeb/grunt-ember-templates
     3 ebryn/ember-component-css
     3 ember-cli/core-object
     3 ember-cli/ember-cli-htmlbars
     3 ember-cli/ember-cli-htmlbars-inline-precompile
     3 ember-cli/ember-cli-shims
     3 ember-cli/ember-export-application-global
     3 ember-cli/ember-resolver
     3 ember-cli/ember-twiddle
     3 ember-data/active-model-adapter
     3 ember-fastboot/ember-cli-fastboot
     3 emberjs-addons/sproutcore-datastore
     3 emberjs/ember-data-fixture-adapter
     3 emberjs/emberjs.github.com
     3 emberjs/ember-mocha
     3 emberjs/ember-rails
     3 emberjs/ember-states
     3 emberjs/list-view
     3 emberjs/starter-kit
     3 inkredabull/sonific8tr
     3 joliss/broccoli-sass
     3 kellyselden/broccoli-jscs
     3 kurko/ember-json-api
     3 livingsocial/rake-pipeline
     3 poteto/ember-cli-flash
     3 rwjblue/ember-cli-divshot
     3 sproutcore/website
     3 stefanpenner/broccoli-stew
     3 stefanpenner/es6-promise
     3 thefrontside/emberx-select
     3 tomdale/is-ember-fast-yet
     3 yapplabs/ember-modal-dialog
     3 yapplabs/ember-wormhole
     4 abuiles/ember-watson
     4 DockYard/ember-validations
     4 ef4/fast-sourcemap-concat
     4 ember-cli/broccoli-caching-writer
     4 ember-cli-deploy/ember-cli-deploy
     4 ember-cli/ember-cli-mocha
     4 ember-cli/ember-try
     4 ember-decorators/ember-decorators
     4 krisselden/morph-range
     4 stefanpenner/broccoli-persistent-filter
     4 stefanpenner/ember-moment
     4 tildeio/htmlbars
     4 tildeio/rsvp.js
     4 wycats/handlebars-site
     5 ember-cli/broccoli-es6modules
     5 emberjs/ember-inflector
     5 pretenderjs/pretender
     5 samselikoff/ember-cli-mirage
     5 tildeio/route-recognizer
     6 emberjs/ember-dev
     6 emberjs/emberjs-build
     6 emberjs/ember-qunit
     6 tomhuda/metamorph.js
     7 emberjs/ember-test-helpers
     7 tildeio/router.js
     9 BackburnerJS/backburner.js
     9 Nopik/emberjs-hacks
    10 emberjs/guides
    12 emberjs/rfcs
    13 emberjs/data
    18 ember-cli/ember-cli
    18 emberjs/website
    ```
  - Can we find any loops here? Meaning one came from project A while another one went to project A.  
    Yes we can. By running script filter.nonsense3.py, we find the loops as follows(seperated by semi-colon)(THELOOPS):
     ```
     # The first field represents the project, the second one represents fromers, the third one represents the toers
     DavyJonesLocker/es6_module_transpiler-rails;Doug Yun <yun.douglas@gmail.com>;Robert Jackson <robert.w.jackson@me.com>,Christian Wesselhoeft <christian@cwesselhoeft.com>
    emberjs/data;Matthew Beale <matt.beale@madhatted.com>;Stefan Penner <stefan.penner@gmail.com>,Jo Liss <joliss42@gmail.com>,Sean Doyle <sean.p.doyle24@gmail.com>,Yehuda Katz <wycats@gmail.com>,Justin Brown <justinbrown.work@gmail.com>,Ryunosuke SATO <tricknotes.rs@gmail.com>,Ilya Radchenko <ilya@burstcreations.com>,Teddy Zeenny <teddyzeenny@gmail.com>,Erik Bryn <erik.bryn@gmail.com>,tchak <paul@chavard.net>,Stanley Stuart <stanley@stan.li>,bmac <bmac325@GMail.com>,Mike Andrzejewski <mike.aski@free.fr>,tomhuda <tomhuda@tilde.io>,Robert Jackson <robert.w.jackson@me.com>,Tom Dale <tom@sproutcore.com>
    idolweb/activejob-lock;Miguel Camba <miguel.camba@gmail.com>,Tony Coconate <me@tonycoconate.com>,Piotr Sarnacki <drogus@gmail.com>,Dan Gebhardt <dan@cerebris.com>,Luke Melia <luke@lukemelia.com>;tomhuda <tomhuda@strobecorp.com>
    cibernox/ember-cpm;Miguel Camba <miguel.camba@gmail.com>;Robert Jackson <robert.w.jackson@me.com>,Luke Melia <luke@lukemelia.com>
    bundler/bundler;Yehuda Katz <wycats@gmail.com>;tomhuda <tomhuda@tilde.io>
    ember-fastboot/simple-dom;Tom Dale and Yehuda Katz <engineering+tomdale+wycats@tilde.io>;Tom Dale <engineering@tilde.io>,Tom Dale <tom@tomdale.net>,Kris Selden <kris.selden@gmail.com>
    twokul/leek;Alex Navasardyan <alex.navasardyan@gmail.com>;Robert Jackson <robert.w.jackson@me.com>,Alex Navasardyan <twokul@users.noreply.github.com>
    rwjblue/builds.emberjs.com;Alex Navasardyan <alex.navasardyan@gmail.com>;Alex Navasardyan <alex.navasardyan@yahoo.com>,Robert Jackson <robert.w.jackson@me.com>
    DockYard/ember-validations;Doug Yun <yun.douglas@gmail.com>;Miguel Camba <miguel.camba@gmail.com>,Alex Navasardyan <alex.navasardyan@yahoo.com>,Robert Jackson <robert.w.jackson@me.com>,Ryunosuke SATO <tricknotes.rs@gmail.com>
    emberjs-addons/sproutcore-statechart;Steven Hancock <stevenh512@gmail.com>;Colin Campbell <colin.campbell@gmail.com>,Kris Selden <kris.selden@gmail.com>
    DockYard/reefpoints;Doug Yun <yun.douglas@gmail.com>;Alex Navasardyan <alex.navasardyan@yahoo.com>,Robert Jackson <robert.w.jackson@me.com>,Alex Navasardyan <twokul@users.noreply.github.com>
    siebertm/ember-docs;Peter Wagenet <peter.wagenet@gmail.com>;Colin Campbell <colin@strobecorp.com>
    tchak/barber;twinturbo <me@broadcastingadam.com>;tchak <paul@chavard.net>
    inkredabull/sonific8tr;Tom Dale <tom@sproutcore.com>;Yehuda Katz <wycats@gmail.com>,Peter Wagenet <peter.wagenet@gmail.com>,tomhuda <tomhuda@strobecorp.com>
    rails/rails;Miguel Camba <miguel.camba@gmail.com>,Stefan Penner <stefan.penner@gmail.com>,Jo Liss <joliss42@gmail.com>,Luke Melia <luke@lukemelia.com>,Edward Faulkner <ef@alum.mit.edu>,Tony Coconate <me@tonycoconate.com>,Doug Yun <yun.douglas@gmail.com>,Piotr Sarnacki <drogus@gmail.com>,Dan Gebhardt <dan@cerebris.com>,Yehuda Katz <wycats@gmail.com>,twinturbo <me@broadcastingadam.com>;tomhuda <tomhuda@strobecorp.com>,Michael Crismali <michael.crismali@gmail.com>,Christian Wesselhoeft <christian@cwesselhoeft.com>
    twokul/bookie;Alex Navasardyan <alex.navasardyan@gmail.com>;Alex Navasardyan <alex.navasardyan@yahoo.com>
    twokul/ember-api;Alex Navasardyan <alex.navasardyan@gmail.com>;Trek Glowacki <trek.glowacki@gmail.com>,Trek Glowacki <trek@groupon.com>
    ember-fastboot/ember-cli-fastboot;Tom Dale and Yehuda Katz <engineering+tomdale+wycats@tilde.io>;Tom Dale <tom@tomdale.net>,Robert Jackson <robert.w.jackson@me.com>,Edward Faulkner <ef@alum.mit.edu>
    emberjs/website;Doug Yun <yun.douglas@gmail.com>,Chad Hietala <chadhietala@gmail.com>,Dan Gebhardt <dan@cerebris.com>,Stanley Stuart <stanley@stan.li>,Tom Dale <tom@tomdale.net>;Miguel Camba <miguel.camba@gmail.com>,Matthew Beale <matt.beale@madhatted.com>,Edward Faulkner <ef@alum.mit.edu>,Teddy Zeenny <teddyzeenny@gmail.com>,Alex Navasardyan <alex.navasardyan@yahoo.com>,Peter Wagenet <peter.wagenet@gmail.com>,machty <machty@gmail.com>,Marten Schilstra <mail@martenschilstra.nl>,Stefan Penner <stefan.penner@gmail.com>,Justin Brown <justinbrown.work@gmail.com>,Jay Phelps <hello@jayphelps.com>,bmac <bmac325@GMail.com>,Yehuda Katz <wycats@gmail.com>,Robert Jackson <robert.w.jackson@me.com>,Tom Dale <tom@sproutcore.com>,Trek Glowacki <trek.glowacki@gmail.com>,Ryunosuke SATO <tricknotes.rs@gmail.com>,Tom Dale <engineering@tilde.io>,Trek Glowacki <trek@groupon.com>,Jo Liss <joliss42@gmail.com>,tomhuda <tomhuda@tilde.io>,Erik Bryn <erik.bryn@gmail.com>
    wycats/handlebars.js;Yehuda Katz <wycats@gmail.com>,tomhuda <tomhuda@strobecorp.com>;Martin Muñoz <im.mmun@gmail.com>,Peter Wagenet <peter.wagenet@gmail.com>,tomhuda <tomhuda@tilde.io>,machty <machty@gmail.com>
    erikhuda/thor;Yehuda Katz <wycats@gmail.com>,Piotr Sarnacki <drogus@gmail.com>;tomhuda <tomhuda@tilde.io>
    DockYard/ember-easy-form;Doug Yun <yun.douglas@gmail.com>;Jay Phelps <hello@jayphelps.com>,Robert Jackson <robert.w.jackson@me.com>
    emberjs-addons/sproutcore-datastore;Piotr Sarnacki <drogus@gmail.com>;Colin Campbell <colin.campbell@gmail.com>,Charles Jolley <charles@sproutcore.com>,Edward Faulkner <ef@alum.mit.edu>
    rwjblue/ember-cli-esnext;Christian Wesselhoeft <hi@xtian.us>;Jo Liss <joliss42@gmail.com>,Robert Jackson <robert.w.jackson@me.com>
    emberjs/list-view;Alex Navasardyan <alex.navasardyan@gmail.com>;Stefan Penner <stefan.penner@gmail.com>,Alex Navasardyan <alex.navasardyan@yahoo.com>,Luke Melia <luke@lukemelia.com>
    ember-cli/ember-cli;Christian Wesselhoeft <hi@xtian.us>,Alex Navasardyan <alex.navasardyan@gmail.com>,Chad Hietala <chadhietala@gmail.com>;Stefan Penner <stefan.penner@gmail.com>,Tom Dale <tom@tomdale.net>,Trek Glowacki <trek@groupon.com>,Jo Liss <joliss42@gmail.com>,Sean Doyle <sean.p.doyle24@gmail.com>,Dan Gebhardt <dan@cerebris.com>,Luke Melia <luke@lukemelia.com>,Justin Brown <justinbrown.work@gmail.com>,Matthew Beale <matt.beale@madhatted.com>,Ilya Radchenko <ilya@burstcreations.com>,Alex Navasardyan <twokul@users.noreply.github.com>,Jay Phelps <hello@jayphelps.com>,Peter Wagenet <peter.wagenet@gmail.com>,Edward Faulkner <ef@alum.mit.edu>,Christian Wesselhoeft <christian@cwesselhoeft.com>,bmac <bmac325@GMail.com>,Piotr Sarnacki <drogus@gmail.com>,Trek Glowacki <trek.glowacki@gmail.com>,Robert Jackson <robert.w.jackson@me.com>,Kris Selden <kris.selden@gmail.com>
    emberjs/starter-kit;Tom Dale <tom@sproutcore.com>;Yehuda Katz <wycats@gmail.com>,Peter Wagenet <peter.wagenet@gmail.com>,tomhuda <tomhuda@strobecorp.com>
    sproutcore/docs;Peter Wagenet <peter.wagenet@gmail.com>;Colin Campbell <colin.campbell@gmail.com>,Colin Campbell <colin@strobecorp.com>
    wycats/rake-pipeline-web-filters;twinturbo <me@broadcastingadam.com>;Kris Selden <kris.selden@gmail.com>,Luke Melia <luke@lukemelia.com>
    ember-cli/ember-resolver;Christian Wesselhoeft <hi@xtian.us>;Teddy Zeenny <teddyzeenny@gmail.com>,Ryunosuke SATO <tricknotes.rs@gmail.com>,Jo Liss <joliss42@gmail.com>,Robert Jackson <robert.w.jackson@me.com>
    DockYard/ember-async-button;Doug Yun <yun.douglas@gmail.com>;Robert Jackson <robert.w.jackson@me.com>
    sproutcore/website;Peter Wagenet <peter.wagenet@gmail.com>,Tom Dale <tom@sproutcore.com>;Colin Campbell <colin.campbell@gmail.com>,tomhuda <tomhuda@strobecorp.com>,Colin Campbell <colin@strobecorp.com>
    emberjs/emberjs.github.com;Tom Dale <tom@tomdale.net>;Peter Wagenet <peter.wagenet@gmail.com>,Robert Jackson <robert.w.jackson@me.com>,Tom Dale <tom@sproutcore.com>
     ```

- **Notice I don't take projects starting after 2015.12.19 into consideration.**
## Is emberjs/ember.js a primary or secondary project to one developer?
- Measurements:
  - <1> Given the assumption that every commit represents a similar amount of effort to one developer, if developer A made more commits to P1 than to another project P2, we say P1 is A's primary project and project P2 is A's secondary project.
  - <2> Given the assumption that every commit within one project represents a similar amount of effort to any developer in a particular project, we calculate two ratios:
    - the ratio R1 of developer A's contribution to project P1 = the number of commits A made to P1 over the number of commits all developers made to P1
    - the ratio R2 of developer A's contribution to project P2 = the number of commits A made to P2 over the number of commits all developers made to P2
    If R1 > R2, we say P1 is A's primary project and project P2 is A's secondary project.  
  **while determining the primary and secondary project, we fix one project as emberjs/ember.js**


- Notices:
  1. For each developer we extract the time span(e.g. from t1 to t2) of his commits in emberjs/ember.js and remove projects in which the developer's commit time span(from t3 to t4) doesn't overlap his emberjs time span(t1 to t2), because he doesn't work on these 2 different projects simultaneously.
  2. For measurement 1, we calculate the number of commits which were made before 2015.12.19
  3. For measurement 2, we focus on the overlapping time period(the overlaps of t1 to t2 and t3 to t4)

  
- Result:
  1. Based on measurement 1, everyone in 51 developers works on one or more primary projects comparing to emberjs. (Surprise!)
  2. Based on measurement 2, 30 out of 51 developers work on one or more primary projects comparing to emberjs while the rest 21 developers work on emberjs as their primary project.
  So who are the 21 developers?
  ```
  Alex Navasardyan <alex.navasardyan@yahoo.com>
  Christian Wesselhoeft <christian@cwesselhoeft.com>
  Christian Wesselhoeft <hi@xtian.us>
  Erik Bryn <erik.bryn@gmail.com>
  Justin Brown <justinbrown.work@gmail.com>
  Kris Selden <kris.selden@gmail.com>
  machty <machty@gmail.com>
  Marten Schilstra <mail@martenschilstra.nl>
  Martin Muñoz <im.mmun@gmail.com>
  Matthew Beale <matt.beale@madhatted.com>
  Mike Andrzejewski <mike.aski@free.fr>
  Peter Wagenet <peter.wagenet@gmail.com>
  Robert Jackson <robert.w.jackson@me.com>
  Tom Dale and Yehuda Katz <engineering+tomdale+wycats@tilde.io>
  Tom Dale <engineering@tilde.io>
  Tom Dale <tom@sproutcore.com>
  Tomhuda Katzdale <tomhuda@tilde.io>
  tomhuda <tomhuda@strobecorp.com>
  tomhuda <tomhuda@tilde.io>
  Trek Glowacki <trek.glowacki@gmail.com>
  Yehuda Katz <wycats@gmail.com>
  ```
  Should we dig out what kind of feature they share?

  .
