# Learning and talking

Android集成flutter.

## Chapter 1

~~~~
go get golang.org/x/oauth2
~~~~

Or you can manually git clone the repository to
`$(go env GOPATH)/src/golang.org/x/oauth2`.

See godoc for further documentation and examples.

* [godoc.org/golang.org/x/oauth2](http://godoc.org/golang.org/x/oauth2)
* [godoc.org/golang.org/x/oauth2/google](http://godoc.org/golang.org/x/oauth2/google)

## Policy for new packages

We no longer accept new provider-specific packages in this repo. For
defining provider endpoints and provider-specific OAuth2 behavior, we
encourage you to create packages elsewhere. We'll keep the existing
packages for compatibility.

## Report Issues / Send Patches

This repository uses Gerrit for code changes. To learn how to submit changes to
this repository, see https://golang.org/doc/contribute.html.

The main issue tracker for the oauth2 repository is located at
https://github.com/golang/oauth2/issues.