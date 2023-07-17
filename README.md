# JSON to DOCX

A simple python script to convert JSON to DOCX.

## Installation

```bash
clone
cd json-to-docx
pip3 install -r requirements.txt
```

## Usage

```bash
python3 json-to-docx.py
```

Once you run this, it will generate a `data.docx` file in the same directory. You can change the input and output file names in the script. Eventually, I will add command line arguments to make it more flexible.

## JSON (input) Example:

```json
[
  {
    "name": "John",
    "age": 30,
    "city": "New York"
  },
  {
    "name": "Jane",
    "age": 25,
    "city": "Los Angeles"
  }
]
```

## DOCX (output) Example:

| name | age | city        |
| ---- | --- | ----------- |
| John | 30  | New York    |
| Jane | 25  | Los Angeles |

## Screenshots

![Screenshot](/screenshot.png)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

MIT
