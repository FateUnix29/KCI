1. Install

```bash
git clone https://github.com/FateUnix29/KCI.gitd
cd KCI
pip install -U . # or --upgrade if you prefer to be explicit
```

2. Usage Example

```python
import kci

# Create a new, blank vehicle in memory
creation = kci.BRV15.Creation(
    # The name that appears on the vehicle ingame.
    ingame_name="Test Vehicle",
    # The name of the folder that the vehicle is saved in.
    folder_name="test_vehicle",
    # The path to the project folder, where the folder_name folder is created.
    project_folder=kci.path.DEFAULT_PROJECT_FOLDER,
    # The author(s) of the vehicle.
    author_steamids=[],
    # The description of the vehicle ingame.
    ingame_description="This is a test vehicle, for the KCI readme demonstration!",
    # Vehicle visibility.
    visibility=kci.metadata.Visibility.PUBLIC,
    # category= ... todo, same for tags
    # A string appended to the end of the .brv, since that works somehow. Magic arbitrary formats.
    brv_appendix="Created by FateUnix29, do not reupload without permission",
)
```