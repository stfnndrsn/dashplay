# DashPlay

DashPlay is an easy way to manage screens cycling on a set of dashboards.
You can create as many DashPlay URLs as you want, and organize them the way
you want. You may want to reuse the same DashPlay URL over several screens so
they all display the same dashboards, or you may want to have a different
DashPlay URL for each of them.


DashPlay is free and open-source. No account is required to use it!

<a href="https://dashplay.io">https://dashplay.io</a>

This is a fork of <a href="https://github.com/rs/dashplay">rs/dashplay</a>.

# Documentation

## How to set up the project on Google cloud

## App Engine
`gcloud init`

`gcloud config set project [your-project-name]`

`gcloud app deploy web/web.yaml`
`gcloud app deploy api/api.yaml`
