# Gleanr

Gleanr is a read-it-later application that lets you save articles, web pages, and other content to read when you have time.


##  🚀 Getting Started

- Clone the repository:
```sh
git clone git@github.com:Gleanr/compose-dev.git gleanr && cd gleanr
```
- Initialize submodules:
```sh
git submodule update --init --remote
```
- Builds/rebuilds the project:
```sh
make build
```
- Starting the project that was previously built
```sh
make up
```
- Open http://localhost:5173 to view the app in your browser
- API docs - http://localhost:8080

## 🏗️ Tech Stack
- **Frontend**: Vue.js 3, PrimeVue
- **Backend**: Python, FastAPI
- **Database**: Postgres