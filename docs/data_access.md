# Data Access

This page outlines how to access AMOC-related data from our repositories.

## amocarray

The [`amocarray`](https://github.com/AMOCcommunity/amocarray) package provides access to standardized data from mooring arrays including:
- MOVE
- RAPID
- OSNAP
- SAMBA

You can install it via pip:

```bash
pip install amocarray
```

Then load data using:

```python
import amocarray
ds = amocarray.read_move(...)
```

More detailed examples are available in each array’s section.
