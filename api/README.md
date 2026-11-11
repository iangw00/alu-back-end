# API

Python scripts that use the [JSONPlaceholder](https://jsonplaceholder.typicode.com) REST API to gather employee TODO list data and export it in different formats.

## Requirements

- Python 3
- `requests` module (`pip3 install requests`)

## Files

| File | Description |
|------|-------------|
| `0-gather_data_from_an_API.py` | Takes an employee ID and prints their TODO list progress and completed task titles |
| `1-export_to_CSV.py` | Takes an employee ID and exports all their tasks to `USER_ID.csv` |
| `2-export_to_JSON.py` | Takes an employee ID and exports all their tasks to `USER_ID.json` |
| `3-dictionary_of_list_of_dictionaries.py` | Exports all tasks from all employees to `todo_all_employees.json` |

## Usage

```bash
python3 0-gather_data_from_an_API.py 2
python3 1-export_to_CSV.py 2
python3 2-export_to_JSON.py 2
python3 3-dictionary_of_list_of_dictionaries.py
```

## Example output

```
$ python3 0-gather_data_from_an_API.py 2
Employee Ervin Howell is done with tasks(8/20):
     distinctio vitae autem nihil ut molestias quo
     voluptas quo tenetur perspiciatis explicabo natus
     aliquam aut quasi
     ...
```

## Author

iangw00
