# read_file Example

This example demonstrates how to use the `read_file` tool to read the contents of a file.

## Usage

```python
# Using the read_file tool
result = await read_file("/path/to/file.txt")
print(result)
```

## Example Files

This directory contains the following example files:

- `sample.txt`: A simple text file
- `sample.json`: A sample JSON file
- `sample.csv`: A sample CSV file

## Best Practices

1. Always check if a file exists before attempting to read it
2. Handle errors appropriately when a file cannot be read
3. Consider file size limitations when reading large files
4. Use the appropriate encoding for text files

## Related Tools

- `write_file`: Write content to a file
- `get_file_info`: Get information about a file
