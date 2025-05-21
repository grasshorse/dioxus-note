# dioxus-note
cat dioxus note test app
- [yt DRAWS note](https://www.youtube.com/watch?v=Pr6T0Phjvgc) and source [github MoonKraken DrawsNotes](https://github.com/MoonKraken/DrawsNotes/tree/main)
- [yt dioxus series](https://www.youtube.com/playlist?list=PLJEZDlUEtOf5rZjVFnijy6wSW-laKiY0l) and [yt rust-dioxus](https://www.youtube.com/@SyedHussimDev/videos)
- [yt ToDo sqlite](https://www.youtube.com/watch?v=vmw31Sjx77k)
- [SurrealDB](https://surrealdb.com/) browser app [https://surrealist.app/overview](https://surrealist.app/overview)
## Install SurrealDB 
```bash
curl -sSf https://install.surrealdb.com | sh
```
  - [SurrealDB install](https://surrealdb.com/install)
  - inmemory
    ```bash
    surreal start memory
    ```
  - file [yt](https://youtu.be/Pr6T0Phjvgc?t=402)
    ```bash
    surreal start file:catnote.db
    ```
## Install Dioxus [docs](https://dioxuslabs.com/learn/0.6/getting_started)
  - build dioxus-cli [yt used](https://youtu.be/_Klr2PQxvQ8?list=PLJEZDlUEtOf5rZjVFnijy6wSW-laKiY0l&t=29) [yt notused](https://youtu.be/Pr6T0Phjvgc?t=411)
  ```bash
  cargo install dioxus-cli --locked
  ```
  - built dioxus-cli [from docs](https://dioxuslabs.com/learn/0.6/getting_started/#install-the-dioxus-cli) NOTE: did not work for me in wsl CyberTruck used ^^^above build
  ```bash
  cargo binstall dioxus-cli
  ```
## Creat project
```bash
dx new dioxus-note
```
- cd dioxus-note
- dx serve
