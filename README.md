# nextcloud-deck-import

This code was imported from [@svbergerem](https://gist.github.com/svbergerem) [gist](https://gist.github.com/svbergerem/5914d7f87764901aefddba125af99938).

This is mainly to show how to use the script with a Nextcloud instance using self signed certificates.

The code in master branch have the original code and branch self-signed-certs will have the adjusted code.

## Before run the script

If you have 2FA configured, you need to temporarly disable it.
Reenable it after import is finished.

## How to run

1. Clone repository
   ```
   git clone https://github.com/keitalbame/nextcloud-deck-export-import.git
   ```
   If you want the self signed certificate version:
   ```
   git clone https://github.com/keitalbame/nextcloud-deck-export-import.git -b self-signed-certs
   ```
2. Change to folder
   ```
   cd nextcloud-deck-export-import
   ```
3. Adapt variables for your instances:
   * urlFrom
   * authFrom
   * urlTo
   * authTo
4. Run python script
   ```
   python nextcloud-deck-export-import.py
   ```
