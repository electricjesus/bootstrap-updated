# Meteor Bootstrap Package. 

Boostrap version: v2.3.2

This is a drop-in replacement for meteor's core bootstrap package. It doesn't do anything special, just replaces core.

The idea is that this package should be updated more frequently than core.

Also fixes the white icons bug.

### Installation

The preferred method is to add this package directly into your [Meteorite](https://github.com/oortcloud/meteorite)'s `smart.json` package file:

```javascript
{
  "packages": {
    "bootstrap-updated" : { 
	"branch" : "master",
	"git" : "https://github.com/electricjesus/bootstrap-updated.git"
    }
  }
}
```

Then run `mrt install`.

### Don't have Meteorite, yet?

It's easy! Just run `sudo -H npm install -g meteorite` (provided you already have the latest Node/NPM). For more info visit this page:

https://github.com/oortcloud/meteorite#installing-meteorite


### Other notes:

If you use this package, make sure to remove the original bootstrap package (if already using it) from Meteor:

```bash
meteor remove bootstrap
```

### Disclaimer

This fork's purpose is for my own personal documentation on how I use this package by @erikpukinskis. I cannot guarantee that everything here would work the same way on your respective systems. 

But if you do encounter stuff, please do not hesitate to submit an issue and I'll try to help you out!

