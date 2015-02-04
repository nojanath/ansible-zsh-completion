# ansible-zsh-completion

Zsh completion file for Ansible version 1.8.2

The files in this repo provide completion for the following ansible commands:

 * ansible
 * ansible-doc
 * ansible-galaxy (TODO)
 * ansible-playbook
 * ansible-pull (TODO)
 * ansible-vault (TODO)

## How do I use this?

Put the files in a directory inside fpath

    print -l $fpath

If using oh-my-zsh, you can put it in ~/.oh-my-zsh/completions/
