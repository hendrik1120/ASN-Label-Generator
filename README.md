# License

The files in this repository are mainly covered under the MIT-License.

`AveryLabels.py` is public domain, as of the author (see header in that file).

# Requirements

You need to have the DejaVu fonts available.

On macOS with homebrew:

    brew install --cask font-dejavu

# Usage

    # Install requirements using uv
    uv sync --frozen

    # Install requirements using pip
    pip install .

    # Generate labels for year 2023, start at 1, create 16x2 labels
    ./gen-asn.py :81:x3 23:1:x2

    # See gen-asn.py --help for more details
    ./gen-asn.py --help
