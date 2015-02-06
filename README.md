# test-pring-boot-hello-world
Prueba de spring boot hello world

Spring Boot mas-starter-web permite crear un api rest rapidamente con muy poco codigo.
al heredar de spring-boot-strted-parent, puedo correrlo desde maven con el siguiente comando

<pre>mvn spring-boot:run</pre>

Plugins para maven
spring-boot.maven-plugin, permite crear un jar
Si no heredo del parent de spring tengo que agregar la siguiente execution
<pre>
<executions>
	<execution>
		<goals>
			<goal>repackage</goal>
		</goals>
	</execution>
</executions>
</pre>
