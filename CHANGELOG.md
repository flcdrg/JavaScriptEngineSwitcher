Change log
==========

## December 30, 2013 - v1.0.0

* Added support of JavaScript `undefined` type
* In JavaScriptEngineSwitcher.Msie added support of [MSIE JavaScript Engine](http://github.com/Taritsyn/MsieJavaScriptEngine) version 1.2.0

## December 7, 2013 - v0.9.5

 * In JavaScriptEngineSwitcher.V8 the [Noesis Javascript .NET](http://javascriptdotnet.codeplex.com/) was replaced by the [Microsoft ClearScript.V8](http://clearscript.codeplex.com/) library (solves a problem of `V8JsEngine` stable work on 64-bit version of IIS 8.X)
 * In JavaScriptEngineSwitcher.Jurassic added support of [Jurassic](http://jurassic.codeplex.com/) version of September 30 2013
 
## November 19, 2013 - v0.9.3

 * In JavaScriptEngineSwitcher.V8 changed a mechanism for loading the Noesis Javascript .NET assemblies for different processor architectures
 * Deleted a `/configuration/jsEngineSwitcher/v8` configuration section

## September 5, 2013 - v0.9.2

 * Added JavaScriptEngineSwitcher.ConfigurationIntelliSense NuGet package
 
## September 4, 2013 - v0.9.0
 * Initial version uploaded