
# Java Socket API Example App: Whois Client

This sample displays what's going on in your app. It dumps the environment and lots more.

See the [Google App Engine standard environment documentation][ae-docs] for more
detailed instructions.

[ae-docs]: https://cloud.google.com/appengine/docs/java/

## Setup

Use either:

* `gcloud init`
* `gcloud auth application-default login`

## Maven
### Running locally

    $ mvn appengine:run

### Deploying

    $ mvn appengine:deploy

<!--
## Intelij Idea
Limitations - Appengine Standard support in the Intellij plugin is only available for the Ultimate Edition of Idea.

### Install and Set Up Cloud Tools for IntelliJ

To use Cloud Tools for IntelliJ, you must first install IntelliJ IDEA Ultimate edition.

Next, install the plugins from the IntelliJ IDEA Plugin Repository.

To install the plugins:

1. From inside IDEA, open File > Settings (on Mac OS X, open IntelliJ IDEA > Preferences).
1. In the left-hand pane, select Plugins.
1. Click Browse repositories.
1. In the dialog that opens, select Google Cloud Tools.
1. Click Install.
1. Click Close.
1. Click OK in the Settings dialog.
1. Click Restart (or you can click Postpone, but the plugins will not be available until you do restart IDEA.)

### Running locally

### Deploying
 -->

This small example application demonstrates the use of the App Engine Socket API to query a Whois server.

To build, install [maven](http://maven.apache.org/), then run `mvn package`.
You can run the local dev app server via `mvn appengine:devserver` and deploy via `mvnappengine:update`.
