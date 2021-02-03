This project provides the parent POM for building NAF, Mailismus and related projects from source.
You do not need to know about this if you are simply pulling a NAF dependency into your application from the Maven Central repository.

Install this POM locally by running:
	mvn clean install

Then refer to it as the parent POM in other projects as follows:
	<parent>
		<groupId>com.github.greysoft.greybuild</groupId>
		<artifactId>grey-build-common</artifactId>
		<version>current version</version>
	</parent>
