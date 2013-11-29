Firedup
=======

Fired Up is a Firebase "Boilerplate" App Repo 
<p>Author: Brian Hooper (a.k.a. "NoogaGeek")<br/>
Date: 11/29/2013</p>
<h3>Pre-requisites</h3>
<p>
	<ul>
		<li>Download and Install Node.js at http://nodejs.org/</li>
		<li>Version: v0.10.22 as of this post 11/29/2013</li>
	</ul>
</p>
<p>Verify Node Installation, Open Terminal Window</p>
``` 
$ node --version  [Enter]
$ v0.10.22
```
<br/>

<p>Verify NPM Installation, In Terminal Window</p>
``` 
$ npm --version  [Enter]
$ v1.3.14
```
<br/>

<p>Install Bower Grunt-CLI and Yeoman using NPM, In Terminal Window</p>
``` 
$ sudo npm install -g bower grunt-cli yo [Enter]
```
<br/>

<p>Verify Bower Grunt-CLI and Yeoman Installation, In Terminal Window</p>
``` 
$ bower --version  [Enter]
$ v1.2.7

$ grunt --version  [Enter]
$ v0.1.11

$ yo --version  [Enter]
$ v1.0.4
```
<br/>
<p>Install Basic Webapp and Angular Generators, In Terminal Window</p>
```
$ sudo npm install -g generator-webapp  [Enter] # installs basic webapp generator

$ sudo npm install -g generator-angular  [Enter] # installs angular generator  
```
<br/>

<p>Use Yeoman to Generate Angular Application Scaffold, In Terminal Window</p>
```
$ yo angular  [Enter]  # scaffold out a AngularJS project
```
<br/>

<p>Use Bower to install Angular-UI dependency, In Terminal Window</p>
```
$ bower install angular-ui  [Enter]  # install a dependency for your project from Bower
```
<br/>

<p>Use Grunt to run Karma test and start your app</p>
```
$ grunt test  [Enter] # test your app
$ grunt server  [Enter] # preview your app
```
<br/>

<h3>For additional info on generator-angular visit</h3>
https://github.com/yeoman/generator-angular

<p>Use Bower to install Twitter Bootstrap 3 Dependencies</p>
```
$ bower install bootstrap  [Enter] 
```
<br/>


<p>Use Bower to install Firebase and Angular-Fire Dependencies</p>
```
$ bower install firebase  [Enter] 
$ bower install angular-fire  [Enter]
```
<br/>