# base412
Building a Simple Price Bot for Base Tokens Python Example:
resp = requests.get("https://api.dexscreener.com/latest/dex/tokens/0x...")
print(resp.json()["pairs"][0]["priceUsd"])
Helps track trending tokens.
