# Captain Coder's Project Template

This is a default project template designed to simplify setting up a a generic
project that provides tests, test coverage, and a GitHub workflow that validates
tests continue to pass as well as a test coverage report.

* Creates a solution with 3 .NET projects: Model, Tests, and Console
* Add a `.gitignore` designed for both Visual Studio and Visual Studio Code
* Adds an `.editorconfig`
  * Gives warnings for C# naming conventions / simplifications
  * Gives warnings when coding styles are not met
  * The Tests/ directory follows less strict guides to allow for more readable tests
* Adds a .github/workflow/main.yml
  * Builds, tests, and generates coverage report
  * On Pull Requests, a simple coverage report is added as a comment

