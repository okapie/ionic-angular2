# ionic-angular2 1.0.0

## Notices (2016-09-23)

* Default files by creating ionic app doesn't have Angular 'routing'. ([943e453](https://github.com/okapie/ionic-angular2/commit/943e453))

* Typescript compile depends on npm module called 'ionic-gulp-browserify-typescript'.

	* ref: https://www.npmjs.com/package/ionic-gulp-browserify-typescript
	
## Issue (2016-09-24)

* I tried to change angular rc4 to release version. ([5558e27](https://github.com/okapie/ionic-angular2/commit/5558e27))

* But, ionic-angular@2.0.0-beta.11 requires modules shown below.
  
	* @angular/common@2.0.0-rc.4,
  
	* @angular/compiler@2.0.0-rc.4,
  
  	* @angular/core@2.0.0-rc.4,
  
  	* @angular/forms@0.2.0,
  
  	* @angular/http@2.0.0-rc.4,
  
  	* @angular/platform-browser@2.0.0-rc.4,
  
  	* @angular/platform-browser-dynamic@2.0.0-rc.4
	
* After installing the release version, I met two problems show below.
	
	(1) TypeScript error
	
	(2) www/js/app.bundle.js wasn't generate by ionic serve command.
	
	* Even if I make www/js/app.bundle.js by my-self, ionic serve command removed it before building.
	
	* ionic found never www/js/app.bundle.js, didn't compile it finally.