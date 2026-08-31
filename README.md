# File-integrity-checker
This is a simple Python-based application with a GUI that allows users to monitor and verify the integrity of files. By calculating and storing the hash values of files, the application can determine whether a file has been modified, tampered with, or corrupted.

FEATURES
Add Files
Add a file to the system, calculate its hash, and store it in a local database (file_hashes.json).
Verify Integrity
-Check if a file is unchanged by comparing its current hash with the stored hash.
GUI-Based Interface
-User-friendly Tkinter interface with buttons for easy navigation.
SHA-256 Hashing
-Uses the SHA-256 algorithm for a secure and accurate integrity check.

TECNOLOGIES USED
Python 3.x
Tkinter (for GUI)
Hashlib (for hash calculations)
JSON (for database storage)
