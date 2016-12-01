# Jenkins proxy container
Accepts only POST requests matching regex: `(\/github-webhook|.*\/cc\.xml)`
...and passes them through to host named `jenkins`
