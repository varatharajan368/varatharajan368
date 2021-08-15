- 👋 Hi, I’m @varatharajan368
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ... Gmail : varatharajan368@gmail.com

<!---
varatharajan368/varatharajan368 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
makeairdropfile "bsc_address" airdrop_number "filename"

Arguments:
1. "bsc_address"    (string, required) The BSC address to receive tokens
2. airdrop_number    (integer, required) The airdrop number
3. "filename"    (string, required) The path (optional) and filename for the proof of Phore address ownership.
                                      If path is not specified, file is created in Phore data directory.

> phore-cli makeairdropfile "0xA3d49AFA3cD5A66277CBf77e3034d37Ce2be674d" 1 "airdrop.txt"
> curl --user myusername --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "makeairdropfile", "params": ["0xA3d49AFA3cD5A66277CBf77e3034d37Ce2be674d" 1 "airdrop.txt"] }' -H 'content-type: text/plain;' http://127.0.0.1:11772/
