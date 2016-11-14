**This project exists because**:

+ Heroku can be a pain in the ass when using Git submodules. 
+ Git can be a pain in the ass when using Git submodules! 
+ Composer is awesome but setting up a temporary forked project is discouraged; see: [https://packagist.org/packages/submit](https://packagist.org/packages/submit) 

> 	Do not submit forks of existing packages. If you need to test changes to a package that you forked to patch, use VCS Repositories instead.
	
+ wa0x6e is using a super sweet grunt workflow that compiles his code into a release package (the CakePHP plugin) but the repo doesn’t contain the plugin structure so a strait fork of his codebase won’t run properly as a submodule on heroku

**TL;DR**:
Using this plgin as a strait fork of [Cake-Resque](https://github.com/wa0x6e/Cake-Resque) didn’t work because [wa0x6e](https://github.com/wa0x6e) is using a super sweet grunt workflow that I don’t want to learn how to use just yet. So here I find myself putting a forced fork up on github so I can: use heroku to host, not learn wa0x6e’s workflow (I’m sure it’s very nice…) and still contribute whatever I can to the development of Cake-Resque. 

Source for this fork came from wa0x6e’s [4.1.2](https://github.com/wa0x6e/Cake-Resque/tree/fa3d5ce04cb28f5a64031cbe72476f229d091ed5) release (Mar 28, 2015)

**--snip--**

#CakeResque [![Build Status](https://travis-ci.org/wa0x6e/Cake-Resque.png)](https://travis-ci.org/wa0x6e/Cake-Resque) [![Coverage Status](https://coveralls.io/repos/kamisama/Cake-Resque/badge.png)](https://coveralls.io/r/kamisama/Cake-Resque) [![Dependency Status](https://www.versioneye.com/package/php--kamisama--cake-resque/badge.png)](https://www.versioneye.com/package/php--kamisama--cake-resque) [![Latest Stable Version](https://poser.pugx.org/kamisama/cake-resque/v/stable.png)](https://packagist.org/packages/kamisama/cake-resque)


CakeResque is a CakePHP plugin for Resque, a library for creating background jobs that can be processed offline later.

> Resque (pronounced like "rescue") is a Redis-backed library for creating background jobs, placing those jobs on multiple queues, and processing them later.

Refer to [website](http://cakeresque.kamisama.me) for documentation

*Take a look at [Fresque](https://github.com/kamisama/Fresque) if you want a version for generic PHP application*