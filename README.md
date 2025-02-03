# VLAYER

I believe almost everyone who joined waitlist have gotten access to test with the api/product.
Here is a simple way to get your self positioned.

## Requirements:
***Linux***: Only Ubuntu 24.04 LTS or newer versions with x86_64 CPU architecture are supported. Other Linux distributions may work but are not officially supported.
***Mac***: Macs with Intel CPUs are not supported. Use an M1/M2/M3 mac.

### Prerequisites
Before working with vlayer, ensure the following tools are installed:
* [Git](https://git-scm.com/downloads), 
* [Foundary](https://book.getfoundry.sh/getting-started/installation) and,
* [Bun](https://bun.sh/).

To make it easy, here are the commands
Git for Linux Users 
```
sudo apt-get install git
```
for Mac/Os
Install Homebrew first
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Git MacOs
```
brew install git
```

Install Foundry
```
curl -L https://foundry.paradigm.xyz | bash
```

Install Bun
```
curl -fsSL https://bun.sh/install | bash
```

# Get Vlayer
To install vlayerup, run the following command in your terminal, then follow the onscreen instructions.
```
curl -SL https://install.vlayer.xyz | bash
```
This will install vlayerup and make it available in your CLI.

To confirm installation
```
vlayer --version
```
This should output the recent vlayer version, confirming you can now use the command.

# PART 2
Vlayer is capable of 2 functions and that is to Proof and Verify. These 2 functions are subdivided into:

* Time Travel: Execute a smart contract on historical data.
* Teleport: Execute a smart contract across different blockchain networks.
* Web proof: Access verified web content, including APIs and websites.
* Email proof: Access verified email content.

## Testing
To test this functions, you will need to create a new project using the below commands:

```
mkdir vlayer && cd vlayer
```

Run this command to initialize a new vlayer project:
```
vlayer init project-name
```

