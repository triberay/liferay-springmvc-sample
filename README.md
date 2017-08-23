
<a href="https://travis-ci.org/triberay/liferay-springmvc-sample">
    <img src="https://travis-ci.org/triberay/liferay-springmvc-sample.svg?branch=master" alt="Travis CI" />
</a>
<a href="https://codecov.io/gh/triberay/liferay-springmvc-sample">
    <img src="https://codecov.io/gh/triberay/liferay-springmvc-sample/branch/master/graph/badge.svg" alt="Coverage" />
</a>
<a href="https://sonarcloud.io/dashboard/index/com.triberay:triberay-springmvc-sample">
    <img src="https://sonarcloud.io/api/badges/gate?key=com.triberay:triberay-springmvc-sample" alt="Quality Gate" />
</a>

# A sample Spring MVC portlet for Liferay 7 & DXP

Just a basic portlet build with [Spring Portlet MVC](https://docs.spring.io/spring/docs/current/spring-framework-reference/html/portlet.html). The module can be build with both [Gradle](https://gradle.org/) or [Maven](https://maven.apache.org/).

The base for the portlet was generated using the [maven archetype](https://dev.liferay.com/develop/tutorials/-/knowledge_base/7-0/generating-new-projects-using-archetypes) as provided by [Liferay](https://www.liferay.com)

The following modifications or additions have been added on top of the generated code:
* Upgraded the Spring version to 4.3.10-RELEASE
* First name of the user is added in the hello message
* Unit tests
* [Travis CI](https://travis-ci.org/triberay/liferay-springmvc-sample) configuration for continuous integration (see [.travis.yml](https://github.com/triberay/liferay-springmvc-sample/blob/master/.travis.yml))
* Code coverage with [JaCoCo](http://www.eclemma.org/jacoco/) & [Codecov.io](https://codecov.io/) 
* Code analysis with [SonarCloud](https://sonarcloud.io/dashboard/index/com.triberay:triberay-springmvc-sample)