---
title: Getting started with GitHub Copilot in Neovim
shortTitle: Neovim
product: '{% data reusables.gated-features.copilot %}'
intro: 'Learn how to install {% data variables.product.prodname_copilot %} in Neovim, and start seeing suggestions as you write comments and code.'
versions:
  feature: copilot
topics:
  - Copilot
---

{% data reusables.copilot.copilot-cta-button %}

## About {% data variables.product.prodname_copilot %} and Neovim

{% data reusables.copilot.procedural-intro %}

If you use Neovim, you can view and incorporate suggestions from {% data variables.product.prodname_copilot %} directly within the editor.

## Prerequisites

{% data reusables.copilot.subscription-prerequisite %}

- To use {% data variables.product.prodname_copilot %} in Neovim you must have Neovim version 0.6 or above and Node.js version 17 or below installed. For more information, see the [Neovim documentation](https://neovim.io/doc/) and the [Node.js website](https://nodejs.org/en/).

## Installing the Neovim extension

{% mac %}

{% data reusables.copilot.install-copilot-in-neovim %}
   - To install {% data variables.product.prodname_copilot %} with Neovim's built-in plugin manager, enter the following command in Terminal.

         git clone https://github.com/github/copilot.vim \
            ~/.config/nvim/pack/github/start/copilot.vim

{% data reusables.copilot.config-enable-copilot-in-neovim %}

{% endmac %}


{% windows %}

{% data reusables.copilot.install-copilot-in-neovim %}
   - To install {% data variables.product.prodname_copilot %} with Neovim's built-in plugin manager, enter the following command in Git Bash.

           git clone https://github.com/github/copilot.vim.git \
            $HOME/AppData/Local/nvim/pack/github/start/copilot.vim

{% data reusables.copilot.config-enable-copilot-in-neovim %}

{% endwindows %}


{% linux %}

{% data reusables.copilot.install-copilot-in-neovim %}
   - To install {% data variables.product.prodname_copilot %} with Neovim's built-in plugin manager, enter the following command:

         git clone https://github.com/github/copilot.vim \
            ~/.config/nvim/pack/github/start/copilot.vim

{% data reusables.copilot.config-enable-copilot-in-neovim %}

{% endlinux %}

## Learning to use {% data variables.product.prodname_copilot %} in Neovim

For guidance on using {% data variables.product.prodname_copilot %} in Neovim, you can view the plugin documentation. To see the documentation, open Neovim and run the following command.

  ```
  :help copilot
  ```

## Further reading

- [{% data variables.product.prodname_copilot %}](https://copilot.github.com/)
