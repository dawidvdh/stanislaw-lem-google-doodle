![https://stanislaw-lem-google-doodle.googlecode.com/git/images-raw/intro-finale/easel.png](https://stanislaw-lem-google-doodle.googlecode.com/git/images-raw/intro-finale/easel.png)

## The source code and graphics for the Stanisław Lem Google Doodle that ran on Google homepage in selected countries on November 23, 2011. ##

  * <a href='https://code.google.com/p/stanislaw-lem-google-doodle/source/browse/'><b>Browse the code</b></a>

  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html'>The doodle running in this repository, with debug params</a> (or <a href='http://www.google.com/logos/lem/'>the original doodle</a>)

  * <a href='http://www.html5rocks.com/en/tutorials/doodles/lem/'>HTML5 Rocks article describing technical details of the doodle</a>

  * Send feedback to: _stanislaw-lem-google-doodle@googlegroups.com_


---


## License note ##

We are sharing the code of the doodle under the <a href='http://www.apache.org/licenses/LICENSE-2.0.html'>Apache 2.0 License</a>, but the images and animations accompanying the doodle under the <a href='http://creativecommons.org/licenses/by-nc-sa/3.0/'>Creative Commons BY-NC-SA 3.0 License</a>. The big difference between those two is that the first one allows commercial re-use, whereas the second one forbids it.


---


## Debug URL parameters ##

Attach those URL parameters to the page to play with debug options:

  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html?doodle-debug'>?doodle-debug</a> to enable debugging; adds debug keyboard shortcuts (see below) and you can also combine with any of the following:

  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html?doodle-debug&doodle-show-debug'>&doodle-show-debug</a> to show debug panel
  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html?doodle-debug&doodle-show-clickable'>&doodle-show-clickable</a> to show clickable areas

  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html?doodle-debug&doodle-force-dom'>&doodle-force-dom</a> to force using DOM
  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html?doodle-debug&doodle-force-canvas'>&doodle-force-canvas</a> to force using canvas

  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html?doodle-debug&doodle-first-run'>&doodle-first-run</a> to pretend we’re running for the first time
  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html?doodle-debug&doodle-half-run'>&doodle-half-run</a> to pretend we’re running for the second time, but the first run was half-finished
  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html?doodle-debug&doodle-second-run'>&doodle-second-run</a> to pretend we’re running for the second time
  * <a href='https://stanislaw-lem-google-doodle.googlecode.com/git/index.html?doodle-debug&doodle-old-run'>&doodle-old-run</a> to pretend we’re running for 99th time

  * **&doodle-country=XX** to run as a specific country (e.g. en, pl, de…)

Debug keyboard shortcuts:
  * _Shift_ to fast forward
  * _N_ to skip an interactive level (use only on interactive levels)
  * _T_ to hit the target in level 3

Note: Debug keyboard shortcuts may result in various problems since they are not tested or validated in any way.