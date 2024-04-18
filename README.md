# xsd-to-pojo-plugin
xsd-to-pojo-plugin

<plugin>
				<groupId>org.codehaus.mojo</groupId>
				<artifactId>jaxb2-maven-plugin</artifactId>
				<version>2.5.0</version>
				<executions>
					<execution>
						<goals>
							<goal>xjc</goal>
						</goals>
					</execution>
				</executions>
				<configuration>
					<sources>
						<source>src/main/resources/xsd</source>
					</sources>
					<packageName>com.rajantechies.model</packageName>
				</configuration>
			</plugin>
