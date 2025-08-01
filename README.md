# Timezone Converter (Python CLI)

A simple Python command-line tool that displays the current time in any valid timezone using the `pytz` and `datetime` libraries.

## Features

* Convert current UTC time to any valid timezone
* Real-time output in readable 12-hour format
* Easy-to-use input loop (type `"exit"` to quit)
* Supports all timezones listed in `pytz.all_timezones`

## Requirements

* Python 3.x
* `pytz` module (Install via: `pip install pytz`)

## Installation

1. Clone the repository or download the `.py` file:

```bash
git clone https://github.com/your-username/timezone-converter.git
cd timezone-converter
```

2. Install dependencies:

```bash
pip install pytz
```

## Usage

Run the script:

```bash
python timezone_converter.py
```

Then input a timezone when prompted, such as:

```
Asia/Dhaka
America/New_York
Europe/London
Asia/Tokyo
```

To exit the program, type:

```
exit
```

## Example Output

```
Enter a timezone: Asia/Tokyo
Current time in Asia/Tokyo: 2025-07-29 06:45:30 PM
```

## License

This project is open source and available under the [MIT License](LICENSE).

---

