# Self-Hosted Cloud using Wasmer 4.0

<p align="center">
  <img src="https://github.com/knarkzel/cloud/blob/master/web/static/thunder.png" width="350">
</p>

This project provides a functional, self-hosted cloud solution using
[Wasmer 4.0](https://wasmer.io/). This enables you to deploy and run
serverless functions, host websites and manage storage right from your
own infrastructure. I believe in the power of decentralization and
this project is a step towards that direction.

This project is currently under active development. This means that
while it is functional, not all intended features may be fully implemented
yet. As it is a work in progress, we strongly recommend that it be
used in a development or testing environment, rather than in a production
setting.

## Roadmap

Here are the core components I'm building:

1. Functions (with Wasmer): Run serverless functions on your own infrastructure. No need to worry about vendor lock-in or expensive cloud costs.
2. Serverless websites (with WASIX): Host your own websites easily and efficiently.
3. Storage: Handle file storage in your self-hosted cloud.

## Ideas for Future Development

I am actively thinking about these features for future releases:

1. Database (with Sqlite, something like Pocketbase): A self-hosted lightweight database solution for small to medium applications.
2. Authentication: An authentication module for managing users and their respective permissions in the self-hosted environment.
3. Logging: A logging module to handle and analyze logs generated by various components.

## Installation & Usage

Head over to releases and download latest executable. If you want to
contribute, get started by running following commands:

```
git clone https://github.com/knarkzel/cloud
cd cloud
nix develop
just dev
```

## License

This project is licensed under the GPLv3 License.

## Support

If you're having any problem, please [raise an issue](https://github.com/knarkzel/cloud/issues/new) on GitHub.

## Stay in Touch

Stay updated with the latest news and updates:

- Follow me on [YouTube](https://youtube.com/@svelterust)
