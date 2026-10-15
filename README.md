# Record demo videos from natural language scripts

The agent transforms natural languge instructions from a script file into an MP4 video showing the sequence of steps being performed in the web app UI.

## Requirements

The tool is based on Copilot and needs one of the copilot clients in order to work. It can be run in either Copilot Desktop, Copilot CLI or VS Code's Copilot.

The `run.sh` script mentioned below will run the agent with `copilot` CLI, which needs to be already installed:
```bash
    brew install copilot-cli
```
## Scripts

See the `scripts/demo.md` file for an example script.

## Running

```bash
    ./run.sh scripts/demo.md
```

As it executes, the agent will pop up several browser windows that apear to do things on their own. **This is NORMAL.** 

Do not interact with them, they will go away by themselves.

## Results

Output videos and intermediary artefacts are saved in the `./recordings` directory.
