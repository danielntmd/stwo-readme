# Stwo

## About

Stwo is a Rust implementation of a [CSTARK](https://eprint.iacr.org/2024/278) prover and verifier.

## Disclaimer

Stwo is a work in progress.

# Installation instructions

## Building using the dockerfile

The root directory contains a dedicated Dockerfile which automatically builds the package.
You should have docker installed (see https://docs.docker.com/get-docker/).

Clone the repository:

```bash
git clone https://github.com/starkware-libs/stwo.git
```

Build the docker image:

```bash
cd stwo
docker build .github/runners -t actions-runner:latest
```

Run the docker image:
```bash
docker run actions-runner
```

## License

This project is licensed under the **Apache 2.0 license**.

See [LICENSE](LICENSE) for more information.
