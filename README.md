# BashBot
> Work In Progress

BashBot brings the power of OpenAI's `gpt-3.5-turbo` to your command-line, plus gives you the additional ability to work in the console while talking to ChatGPT, autosaving code that ChatGPT generates, and giving you the ability to quickly save, run, and view that generated code.

## Usage
```shell
// starting BashBot session with autosave = on and language = JS
$: bashbot -s js

```

## Special Keywords:
These words, if entered by themselves during a BashBot session, will trigger different things locally but will not be sent as a prompt to ChatGPT:
* console: opens the system console, use `exit_console` to return to the BashBot session
* run: run the last saved code
* open: open the last saved code in vim in the terminal
* exit: terminate the BashBot session


## Languages:
Through the `-s` flag, code generated in these languages will be saved, and can be executed without leaving the BashBot session.
* Python
* JavaScript
* JSX (React)
* C
