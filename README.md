# Bank Account Management System in C

A simple console-based application written in C that allows users to create, view, update, and delete bank accounts using file handling.

## Features
- Create new bank accounts
- View all or individual accounts
- Update account names or balances (deposit/withdraw)
- Delete accounts
- Activity logs with timestamps

## How to Compile and Run

### Compile:
```bash
gcc bank_system.c -o bank_system

./bank_system


### 5. **File Structure**
Show what files are included.
```markdown
## File Structure

- `bank_system.c` - Main source code
- `accounts.txt` - Stores account records
- `log.txt` - Tracks log entries with timestamps
- `README.md` - Documentation

## Dependencies

- Standard C Compiler (e.g., GCC)
- No external libraries required

## Known Issues

- No input validation for duplicate account numbers
- No password or security for accessing accounts
- File read/write uses binary mode, which is not human-readable

## Author
Created by Yomna Medhat, 2024.
