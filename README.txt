Simply install this POM locally by running:
	mvn clean install

Then refer to it as the parent POM in other projects as follows:
	<parent>
		<groupId>com.github.greysoft.greybuild</groupId>
		<artifactId>grey-build-common</artifactId>
		<version>current version</version>
	</parent>
