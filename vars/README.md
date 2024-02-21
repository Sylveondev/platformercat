These are variables used by the launcher to handle basically everything.

version.txt is used for creating a list of versions the game supports and registers the download link to the version. If multiple versions are found, the top most version will be picked if the user has not ran the game before. Newer versions should be on top to ensure the user runs the latest version of the game.

releaseNotes.txt is used to view the current release's release notes. That is all really.

launcherversion.txt is the current version of the launcher. If a newer version is available, the launcher will open the page where the launcher is downloaded. The download link is in the Resources.resx file of the visual studio solution.