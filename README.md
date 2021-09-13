

# discord.py-pagination

discord.py-pagination is a Python library to easily create embed paginators.

<img src="https://cdn.soosbot.com/images/pagination-requirement.svg">

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install discord.py-pagination
```

## Usage

### Quickstart
```python
import Paginator

# Create a list of embeds to paginate.
embeds = [discord.Embed(title="First embed"),
          discord.Embed(title="Second embed"),
          discord.Embed(title="Third embed")]

... # Inside a command.
await Paginator.Simple().start(ctx, pages=embeds)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)