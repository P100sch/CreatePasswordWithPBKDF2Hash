# Create Password
Creates a 20-character password with 64bit-salt, iteration count and PBKDF2 SHA256 hash.\
Optionally takes a password, salt and iteration count as commandline arguments.\
## Usage
``CreatePassword.go [password [salt [iterationCount]]]``
## Example output
````
Password: a,2rE\>7iw#]w(B%K,u{
Salt: 9RSoXdSGbf6FBtwN8f6M2ZzG3vhWbwc0KRPSDd3TaMl+z8W1XC4MPRQ93Tc8GC5ibWC8YU1bvGylsa/1wevunQ==
Iterations: 615407
Hash: IAiZc2U2mjvM4ut7CfcxfZ8+k2pgVF7KEH3AaUzBm44A
````