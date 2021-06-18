# Description
Manual tests of our natively developed apps are performed for Android via Firebase and for iOS via TestFlight. Release candidates of the versions to be published are provided via these tools and must be tested at short notice.
## Motivation
In order to be able to guarantee a structured and reliable manual test execution, we will create a documentation of the tests. These will be carried out for release candidates and only if they are successful will the related release be published.
The tests must be written in a way that allows people outside the industry but technically skilled to perform these tests.
This test documentation will later be used to build automatic tests, e.g. via tools like "Appium".
# Specification
- Tests with focus on "Machine Owner" as a user
- We will use Markdown files for test case documentation
	- The test cases for iOS and Android will be separated
		- Same test cases but different scenarios are possible
	- Each test case will get its own Markdown file
- We will write complete test cases containing the following information:
	- Name: Name of test case (e.g. "Search for a machine")
		- A test case can be derived from a feature but also from a bug or a technical issue solved in the past
	- Test description: General description of what will be tested and covered by the test (e.g. "We test for correct functionality of the machine search within the app. The search is tested at all points and with all possible search parameters.")
	- Scenario: One scenario of test case (e.g. "A user searches for "123" on the machine overview page")
		- It is possible that one test case contains more than one scenario
	- Precondition: What is needed to validate that the test was successfully (e.g. "Use the Rest APIs /search endpoint to get the result for "123"")
	- Input: What will trigger the start of the test (e.g. "When pressing on the search bar on the machine overview page AND type in "123" AND press the search button right to the sear bar")
	- Expected Result: The expected reaction and outcome (e.g.  "Then a loading bar appears for less then x seconds AND the machine list shows the same results as our Rest APIs /search endpoint")
## Scope
- Before the release
	- Functional/feature testing
	- Testing of open bug issues / verification of bugfixes
	- Checking the release notes and changelog of the stores
- After the release
	- Is the download working fine and login possible
	- Does the Maps are loading fine (signing key issues)
	- Is the changelog available
	- Slack channel notification with changelog created
	- Maybe clean up test environment (stop Firebase/TestFlight testing)
## In clarification
- Share test case documentation in Android and iOS dev repo
	- New folder for test case description (later automated tests)
	- Review der Test Cases before merging
- After the release tests
	- Maybe clean up test environment (stop Firebase/TestFlight testing)
		- force users to switch to live version