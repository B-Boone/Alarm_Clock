# Alarm Clock

A Python-based alarm clock application with a simple graphical user interface (GUI). This project allows users to set alarms, configure settings, and manage alarm sounds.

## Features

- Set and manage alarms
- Customizable alarm sounds
- Configuration file for persistent settings
- Simple and intuitive GUI

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Required libraries: `tkinter`, `configparser`, `pydub`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/B-Boone/alarm_clock.git
   cd alarm_clock
   ```

2. Install the required libraries:
   ```bash
   pip install tkinter configparser pydub
   ```

### Usage

1. Run the `clock_ui.py` script to start the alarm clock application:
   ```bash
   python clock_ui.py
   ```

2. Use the GUI to set alarms and configure settings as needed.

## Project Structure

- `alarm_clock/`: Directory containing main application scripts
- `__pycache__/`: Directory for compiled Python files
- `alarm.wav`: Default alarm sound file
- `clock_config.ini`: Configuration file for storing settings
- `clock_ui.py`: Main GUI application script
- `config_manager.py`: Script for managing configuration settings
- `clockipy.png`: Image file for the application icon

## Configuration

The `clock_config.ini` file stores the alarm clock settings, including alarm times and sound preferences. You can edit this file manually or through the GUI.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any inquiries or feedback, please contact B-Boone at [your-email@example.com].

---

© 2024 B-Boone. All rights reserved.