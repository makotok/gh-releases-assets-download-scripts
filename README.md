# GitHub Releases assets download scripts

This Gradle script is a script to download the Releases assets.

## Usage

```
gradlew -Pusername=<GitHub username> -Ppassword=<GitHub password or accessToken> -Powner=<Repository owner> -PrepoName=<Repository name> -P tagName=<Release tag name>
```
## Examples

```sh
# Download assets: https://github.com/pixijs/pixi.js/releases/tag/v4.8.7

# Using username and password.
gradlew -Pusername=taro -Ppassword=xxxxx -Powner=pixijs -PrepoName=pixi.js -PtagName=v4.8.7

# Using personal access tokens.
gradlew -Ppassword=6dbxxxxxxx -Powner=pixijs -PrepoName=pixi.js -PtagName=v4.8.7
```
