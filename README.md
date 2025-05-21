# dioxus-note
cat dioxus note test app

## Install SurrealDB 
```bash
curl -sSf https://install.surrealdb.com | sh
```
  - SurrealDB inmemory
    ```bash
    surreal start memory
    ```
  - SurrealDB file [yt](https://youtu.be/Pr6T0Phjvgc?t=402)
    ```bash
    surreal start file:catnote.db
    ```
## Install Dioxus [docs](https://dioxuslabs.com/learn/0.6/getting_started)
  - build dioxus-cli [yt used](https://youtu.be/_Klr2PQxvQ8?list=PLJEZDlUEtOf5rZjVFnijy6wSW-laKiY0l&t=29) [yt notused](https://youtu.be/Pr6T0Phjvgc?t=411)
  ```bash
  cargo install dioxus-cli --locked
  ```
  - built dioxus-cli [from docs](https://dioxuslabs.com/learn/0.6/getting_started/#install-the-dioxus-cli)
  ```bash
  cargo binstall dioxus-cli
  ```
## Creat project
```bash
dx new dioxus-note
```
