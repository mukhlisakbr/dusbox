# dusbox

Quickly turn your server into a media box for downloads, uploads, and streaming with Docker, Aria2, AriaNg, Filebrowser, and Jellyfin.

### Quick Start

```sh
cp .env.sample .env
# Edit the .env file to change values as needed
docker compose up -d
```

### Accessing Services

| Service         | URL                                                        |
| --------------- | ---------------------------------------------------------- |
| **AriaNg**      | [https://domain.com](https://domain.com)                   |
| **Filebrowser** | [https://domain.com/files](https://domain.com/files)       |
| **Jellyfin**    | [https://domain.com/jellyfin](https://domain.com/jellyfin) |

Auto SSL is enabled by default, so make sure your domain is pointing to your server first.
