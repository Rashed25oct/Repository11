# Repository11
How to run
mvn verify -Denv=qa -Dbrowser=ch -Dcucumber.filter.tags="@login"

How to run test in default env and browser
mvn verify -Dcucumber.filter.tags="@smoke"

How to run all test by using default env and browser
mvn verify