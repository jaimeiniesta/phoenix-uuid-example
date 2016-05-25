# Dummy app for UUID in Phoenix

This is a dummy app to illustrate the failure on https://gist.github.com/jaimeiniesta/39c32bb500a6167f43b272f00b50edb7

In the first commit we have a scaffold for `/posts`, all tests pass.

In the second commit, we change to UUID (you'll need to rollback and migrate your DB), and although it works fine, the tests fail.
