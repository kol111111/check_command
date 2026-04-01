# check_command 🎄

`check_command` is a lightweight CLI utility designed to verify file existence within a Linux system. It provides immediate visual feedback and supports deep recursive searching through subdirectories.

   Note: The command requires the full filename, including the extension (e.g., `image.png`), to perform an accurate search.

##  Key Features
- Simplicity: Minimalist design, easy to integrate into your workflow.
- High Performance: Fast recursive scanning using Python's optimized libraries.
- Visual Clarity: Color-coded output (Green/Red) for instant status recognition.
- Recursive Search: Automatically scans subfolders if the file isn't found in the current directory.

##  Installation

To install `check_command` on your system, run the following commands in your terminal:

```bash
# Clone the repository, set permissions, and install to system path
git clone https://github.com/kol111111/check_command.git
cd check_command && \
chmod +x check && \
sudo cp check /usr/local/bin/
