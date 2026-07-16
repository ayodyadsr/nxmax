# nxmax

Fast NXDOMAIN checker for large domain lists.

`nxmax` is a lightweight command-line tool that checks whether domains resolve or return **NXDOMAIN**. It is designed for recon workflows where filtering dead or unregistered domains is necessary.

## Features

- Fast DNS resolution
- Detects NXDOMAIN responses
- Simple command-line interface
- Lightweight and dependency-free
- Suitable for large domain lists

## Installation

```bash
git clone https://github.com/<your-username>/nxmax.git
cd nxmax
chmod +x nxmax
```

## Usage

```bash
./nxmax <domain_list_file>
```

### Example

```bash
./nxmax domains.txt
```

Example `domains.txt`:

```
example.com
test.example.com
idonotexist123456.com
```

## Output

The tool reports whether each domain exists or returns **NXDOMAIN**.

## Use Cases

- Bug bounty reconnaissance
- Subdomain validation
- Removing dead domains from target lists
- DNS enumeration workflows

## Requirements

- Linux
- Internet connection
- DNS resolver access

## License

Released under the GNU Affero General Public License v3.0 (AGPL-3.0).

You are free to use, modify, and distribute this software under the terms of the AGPL-3.0 license. If you modify and deploy this software over a network, you must also make the corresponding source code available.

See the [LICENSE](LICENSE) file for the full license text.
