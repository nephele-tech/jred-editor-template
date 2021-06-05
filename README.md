# jred-editor-template

Run J-RED Editor by using [jetty maven plugin](https://wiki.eclipse.org/Jetty/Feature/Jetty_Maven_Plugin).

### Update `.m2/settings.xml` (Maven Settings):
```
	<servers>
  
    		...
  
		<server>
			<id>github</id>
			<username>nephele-tech</username>
			<password>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</password>
		</server>
	</servers>
```

### Run the following commands:
`export JAVA_HOME=<jdk11>`

`git clone https://github.com/nephele-tech/jred-editor-template.git`

`cd jred-edtor-template`

`mvn jetty:run`

J-RED Editor will run at [http://localhost:8080/index.html](http://localhost:8080/index.html).
