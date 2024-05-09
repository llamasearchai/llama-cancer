# llama-cancer

![LlamaCancer Logo](docs/images/llamacancer_logo.png)

## Installation

```bash
pip install -e .
```

## Usage

```python
from llama_cancer import LlamaCancerClient

# Initialize the client
client = LlamaCancerClient(api_key="your-api-key")
result = client.query("your query")
print(result)
```

## Features

- Fast and efficient
- Easy to use API
- Comprehensive documentation

## Development

### Setup

```bash
# Clone the repository
git clone https://github.com/nikjois/llama-cancer.git
cd llama-cancer

# Install development dependencies
pip install -e ".[dev]"
```

### Testing

```bash
pytest
```

## License

MIT

## Author

Nik Jois (nikjois@llamasearch.ai)
