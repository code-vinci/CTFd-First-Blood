# CTFd First Bloods Discord bot

A fancy Discord bot to announce CTFd solves

## Usage

Install with

```bash
cargo install --git https://github.com/code-vinci/CTFd-First-Blood
```

Run with

```bash
CTFd-First-Blood --help
```

## Dockerfile Usage

Build the docker image

```bash
docker build --tag bot .
```

Run a container using the created image and provide the environment variables

```bash
docker run -d --name CTFd-First-Blood \
    -e WEBHOOK_URL=<YOUR_WEBHOOK_URL> \
    -e CTFD_URL=<YOUR_CTFD_APP_URL> \
    -e CTFD_API_KEY=<YOUR_CTFD_API_KEY>
```

Enjoy!

## Contributions

[b3nj4m1no](https://github.com/b3nj4m1no)
