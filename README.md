# aegisJsonDecryptor

Simple python script to decrypt Aegis exported json backups.

## Usage
```
python aegisJsonDecryptor.py --input filename.json --output filename.txt
```

## Output
After entering the password that was used to export the vault, the script prints the content of the vault to the terminal (if the ```--output``` parameter is omitted) or creates a text file called ```filename.txt``` with the vault content.

## Dependencies
Requires the package ```cryptography```.

## Testing
Tested with the backup feature in the official Android app (Version 2.2.2).

## Credit
Code copied from https://github.com/beemdevelopment/Aegis/blob/master/docs/decrypt.py.
