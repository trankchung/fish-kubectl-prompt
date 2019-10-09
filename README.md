# fish-kubectl-prompt "vpistis variant"


Display information about the kubectl current context and namespace in fish prompt.

Normal Prompt: ![normal-prompt](https://raw.githubusercontent.com/vpistis/fish-kubectl-prompt/master/kubect_status_1.png)

Error Prompt: ![error-prompt](https://raw.githubusercontent.com/vpistis/fish-kubectl-prompt/master/kubect_status_error.png)

## CUSTOMIZE

If you want to customize, override the following environment variables.

set KUBECTL_PROMPT_ICON "⎈"
set KUBECTL_PROMPT_SEPARATOR "|"

## Install

With [fisherman]
```
fisher add vpistis/fish-kubectl-prompt
```
[fisherman]: https://github.com/fisherman/fisherman

## Use

You can toggle the prompt on or off like this:
```
kube_ps on
kube_ps off
```

## Credits
This is a variant of the project https://github.com/Ladicle/fish-kubectl-prompt adding toggle on/off from https://github.com/aluxian/fish-kube-prompt and other stuffs.
