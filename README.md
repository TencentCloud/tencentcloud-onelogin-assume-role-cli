tencentcloud-onelogin-assume-role-cli
========================

Assume an TencentCloud Role and get temporary credentials using Onelogin.

Forked from [onelogin-aws-cli-assume-role](https://github.com/onelogin/onelogin-aws-cli-assume-role) with support for TencentCloud.

## Quick Start using precompiled binary

You can download precompiled jars from the [release page](https://github.com/TencentCloud/tencentcloud-onelogin-cli/releases).

Use the tool to generate TencentCloud credentials and output them to the terminal.

```sh
> java -jar tencentcloud-onelogin-cli.jar
```

Or alternately save them to your TencentCloud credentials file to enable faster access from any terminal.

```sh
> java -jar tencentcloud-onelogin-cli.jar --profile profilename
```

The credentials last for 15 minutes by default, so you can also make it regenerate and update the credentials file by using the `--loop` option.

Use `-help` command option to get the help information.
```sh
> java -jar tencentcloud-onelogin-cli.jar -help
```

#### Github

The project is hosted at github. You can download it from:
* Lastest release: https://github.com/TencentCloud/tencentcloud-onelogin-cli/releases
* Master repo: https://github.com/TencentCloud/tencentcloud-onelogin-cli

