# moqume.github.io

## Local Development

### Prerequisites

Install Hugo (extended version):
```bash
sudo snap install hugo --channel=extended
```

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/moqume/moqume.github.io.git
   cd moqume.github.io
   ```

2. Initialize the theme submodule:
   ```bash
   git submodule update --init --recursive
   ```

3. Start the development server:
   ```bash
   hugo server --environment dev
   ```

4. Open your browser to `http://localhost:1313`

The development environment uses the `config/dev/config.yaml` configuration which enables draft posts and uses a local base URL.
