# ffmpeg-completion

bash-completion script for FFmpeg

### Requirements

- FFmpeg
- bash-completion

If you do not have `bash-completion` package installed, run following commands.

```bash
# for CentOS
$ sudo yum install epel-release
$ sudo yum install --enablerepo=epel bash-completion

# for Ubuntu
$ sudo apt-get install bash-completion
```

### How to use

1. Clone this repository

    ```bash
    $ git clone https://github.com/clerk67/ffmpeg-completion.git
    ```

1. Source ffmpeg script.

    ```bash
    $ cd ffmpeg-completion
    $ source ffmpeg
    ```

1. Enter `ffmpeg -f` to your terminal and hit the `Tab` key twice!

### Automatic activation

- Put `ffmpeg` script to `/etc/bash_completion.d` or `/usr/share/bash-completion/completions` . Scripts in these directories will be automatically sourced every time you start the shell.
- Also, you can add `source /path/to/ffmpeg-completion-script` to your `.bashrc` instead of the first approach.
