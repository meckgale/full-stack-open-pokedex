Before releasing our turn-based strategy mobile game written in Java, we would set up a CI pipeline to keep changes;

As a team of 6 people, we used Checkstyle for linting which is an open-source tool that helps us enforce a common code style and avoid small problems before they reach the main branch.

For testing purposes we used Selenium that supports different kinds of automated tests and fits our needs.

We preferred Apache Maven for building our application because it is widely used in the Java ecosystem, works well with dependency management, and integrates smoothly with automated test runs.

For the CI environment, we preferred cloud-based solution solution because our app is relatively small and we wanted a straightforward setup without maintaining our own CI server. We chose TravisCI because it is easy to configure, integrates well with GitHub repositories, and can automatically run our linting, tests, and build steps on every push or pull request.

This gives the team quick feedback and helps us avoid breaking changes before release.
