# Tool for PVD steganography on Python

### Instruction

```
usage: pvd.py [-h] (-e | -d) image

PVD steganography

positional arguments:
  image       Path to container image

options:
  -h, --help  show this help message and exit
  -e          Hide secret message
  -d          Reveal secret message
```

Length of secret message is also hidden inside container (first 4 bytes of extracted data), so the only thing you need to get data is container.
