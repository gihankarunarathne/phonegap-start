DocBook Mobile starts with PhoneGap
---

A starting point for PhoneGap apps with DocBook Mobile asserts content.

To get started: fork this repo, modify the config.xml to match your details, and get building!

###Documentaion for customize config.xml

```
<?xml version="1.0" encoding="UTF-8"?>
<widget xmlns		= "http://www.w3.org/ns/widgets"
	xmlns:gap	= "http://phonegap.com/ns/1.0"
	id		= "docbook.xsl.mobile"
	version 	= "1.0.0">
<!--
id: the unique identifier for your application. To support all supported platforms, this must be reverse-domain name style
  (e.g. com.yourcompany.yourapp)
version: use for versioning app as a major/minor/patch style version. It will be a three numbers, such as 0.0.1
versionCode:(optional) when building for Android, you can set the versionCode. 
 -->

	<name>DocBook:Getting Started PhoneGap</name>

	<description>
		A template for getting started with DocBook documentaion for different mobile platforms with using PhoneGap.
	</description>
  
  <!-- IMPORTANT -->
  <preference name="phonegap-version" value="2.0.0"/>
 <!-- Should be same as in 'mobile/build.properties' configuration file & available in PhoneGap Build.
  Refer: https://build.phonegap.com/docs/config-xml to get available phonegap versions -->

  <author href="https://github.com/gihankarunarathne/DocBook-xsl-mobile-decouple" email="gckarunarathne@gmail.com">Gihan Karunarathne
  </author>

	<icon src="icon.png" gap:role="default" />

<!-- <preference name="target-device" value="universal" /> 
  target-device with possible values handset, tablet, or universal -->
<!--  <preference name="orientation" value="portrait" /> 
  orientation with possible values default, landscape, or portrait -->
<!--  <preference name="exit-on-suspend" value="true"/> -->
</widget>
```
