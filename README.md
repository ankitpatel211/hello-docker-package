# hello-docker-package

## A command line execution of a GHCR (github container registry) package

Try docker commands by following below steps inorder to push container registry package to the github packages

### Steps

1. Create an image
2. Run an image for a desire output
3. Create a PAT (personal access token) for a personal authentication
4. Authenticate yourself by logging in for a github account access
5. Push an image using your github account

#### Token & username authentication

```sh
export $CR_PAT=<Token>
echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
```
