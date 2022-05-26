# go-file-server

A simple file server written in Go, designed for ShareX

**Preview**
![](https://i.imgur.com/IyUO5D2.gif)
![](https://fs.plexidev.org/api/pICAQZm.gif)

**Usage**

1. Install [Go](https://go.dev) ([Ubuntu](https://github.com/golang/go/wiki/Ubuntu))
2. Clone repo `git clone https://github.com/lorencerri/sharex-server-golang`
3. Install dependencies `go get`
4. Copy & modify `example.config.yml` -> `config.yml`
5. Run program `go run .`

**API**
| Method | Endpoint |
| ---: | :--- |
| POST | /api/upload |
| GET | /api/{file} |
| GET | /api/{file}/stats |
| GET | /api/{file}/delete/{key} |

**TODO**

-   Frontend & move API to /api/ endpoint
-   File stats
