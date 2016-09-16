## ngImgCropFullExtended
[![Build Status](https://travis-ci.org/CrackerakiUA/ngImgCropFullExtended.svg?branch=master)](https://travis-ci.org/CrackerakiUA/ngImgCropFullExtended)
[![GitHub release](https://img.shields.io/github/release/CrackerakiUA/ngImgCropFullExtended.svg)](https://github.com/CrackerakiUA/ngImgCropFullExtended) [![Join the chat at https://gitter.im/CrackerakiUA/ngImgCropFullExtended](https://badges.gitter.im/CrackerakiUA/ngImgCropFullExtended.svg)](https://gitter.im/CrackerakiUA/ngImgCropFullExtended?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Simple Image Crop directive for AngularJS. Enables to crop a circle, square or rectangle from of an image.


## Live demo

**Test it yourself, upload or choose an image from url in our amazing** [Online test suite](http://crackerakiua.github.io/ngImgCropFullExtended)<br><br>
or pick a Codepen to play around with it<br>
[Codepen: Circle + Chargement Crop](http://codepen.io/Crackeraki/pen/avYNKP)<br>
[Codepen: Square + Init Url Crop + Maximum rendered image](http://codepen.io/Crackeraki/pen/QjmNVM)<br>
[Codepen: Rectangle Crop](http://codepen.io/Crackeraki/pen/XmEdPx)<br>
[Codepen: Rectangle Crop + Crop info](http://codepen.io/Crackeraki/pen/YqKwzZ)<br>
[Codepen: Rectangle With Aspect Crop and Max Init](http://codepen.io/Crackeraki/pen/zvWqJM)<br>
[Codepen: Rectangle + Aspect + Array Crop](http://codepen.io/Crackeraki/pen/jWgmYB)<br>
[Codepen: Rectangle + CSS Crop](https://codepen.io/rickderd/pen/ZOyjRr)<br>
[Codepen: Different sizes](http://codepen.io/ignacio-chiazzo/pen/QNQyRW)<br>

## News

On update 0.5.4 i have fixed resize of the circle, it's looks not perfect, but it's better then bugged we had. If you believe you can fix algorithm of the circle resize, check the line 74 of the crop-area.js


## Contribution

If you want to contribute, please join our [gitter chat](https://gitter.im/CrackerakiUA/ngImgCropFullExtended) and [trello board](https://trello.com/b/ojPTSMax/ngimgcropfullextended) for better organisation. To join trello write reply [HERE.](https://github.com/CrackerakiUA/ngImgCropFullExtended/issues/78)

## Installing

#### Download directly
[Download ngImgCropExtended](https://github.com/CrackerakiUA/ngImgCropExtended/archive/master.zip) files from GitHub

#### Bower
	bower install ngImgCropFullExtended

#### NPM
	npm install ng-img-crop-full-extended

#### Meteor
	meteor add correpw:ng-img-crop-full-extended

#### JSPM
	import "ng-img-crop-full-extended/compile/unminified/ng-img-crop.js";

## How to Use

``` javascript
angular.module('app', ['ngImgCrop'])
.controller(function($scope){
	$scope.myImage = 'https://raw.githubusercontent.com/CrackerakiUA/ngImgCropFullExtended/master/screenshots/live.jpg';
	$scope.myCroppedImage = ''; // in this variable you will have dataUrl of cropped area.
});
```
``` html
<img-crop image="myImage" result-image="myCroppedImage"></img-crop>
```

## Documentation

You can checkout all options under [our wiki page](https://github.com/CrackerakiUA/ngImgCropFullExtended/wiki/Options)

## License

See the [LICENSE](https://github.com/CrackerakiUA/blob/master/LICENSE) file
