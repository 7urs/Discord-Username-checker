# CloudChecker !!Tokenless!!

CloudChecker is a Python script for checking the availability of Discord usernames using a list of combinations and proxies. It leverages multi-threading to perform checks concurrently.

## Features
- Username availability check on Discord API
- Multi-threaded for faster execution
- Proxy support for avoiding rate limits
- RPS (Requests Per Second) monitoring
- Error logging for troubleshooting
- Should work on linux


## Getting Started

### Prerequisites
- Python 3.x
- requests

## Installation


### For windows user
1. Run `run.bat`
   
### Text Tutorial
1. Clone the repository:

```bash
git clone https://github.com/Cloudzik1337/DiscordUsernameChecker.git
cd DiscordUsernameChecker
```
2. Install requirements
```bash
pip install -r requirements.txt
```
3. Run cloud_checker.py
```bash
python cloud_checker.py
```

## Usage
1. Configure your proxies by adding them to the proxies.txt file.
2. [CheapProxies](https://www.wtfproxy.com/?ref=o8hX4mfY5hfhFUSZEl146) here 3 usd / gb
3. (Proxyless) works but thread sleeps on ratelimit (ultra slow)
4. Customize the script by adjusting parameters like the length of the usernames, the number of threads, etc.
5. Execute the script, and it will start checking the availability of Discord usernames.
## Usage Dictionary Validator
1. Run file
2. Enter ammount of thread (for smaller than 5k dont use more than 5)
3. Similiar + Hits will be saved to BetterNames.txt
## Additional Information
1. telegram: pokerstare
2. Discord: overweep
