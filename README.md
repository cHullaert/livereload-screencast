
# Command

gradle -t build
gradle liveReload

#Code 

``` groovy
buildscript {
	repositories {
		jcenter()
	}

	dependencies {
		classpath 'org.kordamp.gradle:livereload-gradle-plugin:0.2.1'
	}
}
apply plugin: 'org.kordamp.gradle.livereload'

```

port	
used by the LiveReload Sever. Type: int. Default: 35729.

docRoot	
the main directory from which files will be served. Type: String. Default build/livereload

# links

https://github.com/aalmiray/livereload-gradle-plugin
http://localhost:35729/
https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei