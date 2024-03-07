# IntegriMark Demonstration Vault

This demonstration vault was created from [`integrimark-vault-template`](https://github.com/integrimark/integrimark-vault-template), and a single PDF file was uploaded.

The vault is hosted at: [`https://integrimark.github.io/integrimark-demo-vault/`](https://integrimark.github.io/integrimark-demo-vault/)

Here is a [sample watermarked URL with `lumbroso@seas.upenn.edu`](https://integrimark.github.io/integrimark-demo-vault/kelley_1988.pdf?email=lumbroso%40seas.upenn.edu&key=U2FsdGVkX19%2BGx52d61mhqRDsGxYjCb3gSjPLfDD2qEdBh/4AgpsR9MKxlo3gCVJ). You can see that this is a watermarked version of [the PDF `kelley_1988.pdf` available in this repository](https://github.com/integrimark/integrimark-demo-vault/raw/main/kelley_1988.pdf).

## Generate Your Own Watermarked URL

You can play around with this vault yourself to become familiar with IntegriMark:

- First install the `integrimark` command-line tool:

    ```bash
    pip install integrimark
    ```

- Then clone this repository (which contains the `passwords.json` file):

    ```bash
    git clone https://github.com/integrimark/demo-vault/
    ```

- You can then generate your own watermarked URL using the `integrimark` command-line tool:

    ```bash
    integrimark url demo-vault "lumbroso@seas.upenn.edu"
    ```
