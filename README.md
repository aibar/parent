[![Build Status](https://travis-ci.org/walkingdevs/parent.svg?branch=master)](https://travis-ci.org/walkingdevs/parent)

## Maven parent poms. Nothing special

    <parent>
        <groupId>walkingdevs.maven</groupId>
        <artifactId>parent</artifactId>
        <version>2</version>
        <relativePath/>
    </parent>

    <repositories>
        <repository>
            <id>bintray</id>
            <url>http://dl.bintray.com/walkingdevs/mvn</url>
        </repository>
    </repositories>