**GitHub Gists Importer and Searcher**


**Project Description**

GitHub Gists Importer and Searcher is a project that allows you to import Gists from a specific GitHub user's account and store them in an SQLite database. Additionally, you can search through the imported gists using multiple criteria such as creation date or GitHub ID.

**Features**

Import all gists from a specified GitHub user using the GitHub API.

Store the imported data in an SQLite database.

Advanced search support using multiple criteria like GitHub ID and creation date.

Automatic handling of API rate limits.

Support for paginated results if there are many gists.

**API Rate Limit Handling**

The program automatically handles GitHub API rate limits. When the rate limit is near, the program waits until the limit resets before resuming.

**Logging**

The project uses the logging library to log all events, including errors and successes. You can adjust the logging level or format as needed.
