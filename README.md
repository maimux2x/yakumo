# Yakumo

Yakumo is a tool to facilitate using the DeepL API via the command line interface.
You can translate texts on the CLI.
The default source language is Japanese, and the default target language is English.


## Usage

1. Register an account with DeepL to obtain an API Key.
2. Set API Key in Environment Variable.
3. Run the command as in the example.

```
$ bin/yakumo translate こんにちは、世界！
Hello, World!
```

To translate in a non-default language, run the following command:

```
$ bin/yakumo translate Hello, World! --from=EN --to=JA
こんにちは、世界！
```
