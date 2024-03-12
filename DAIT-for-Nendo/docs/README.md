# DAIT-for-Nendo

DAIT-for-Nendo is a decentralized AI training platform that integrates with the Nendo platform, Cosmos blockchain, and IPFS for data storage. It uses federated learning to train AI models without compromising user data privacy.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Installation

Before you start, make sure you have Node.js and npm installed on your machine.

1. Clone the repository:

```bash
git clone https://github.com/yourusername/DAIT-for-Nendo.git
```

2. Navigate to the project directory:

```bash
cd DAIT-for-Nendo
```

3. Install the dependencies:

```bash
npm install
```

4. Run the setup script:

```bash
./scripts/setup.sh
```

## Usage

To start the federated learning server:

```bash
node federated_learning/server
```

To start the federated learning client:

```bash
node federated_learning/client
```

To interact with the Nendo platform, use the API in the `nendo_integration/api` directory.

## Testing

To run the tests for the smart contracts:

```bash
npm run test:contracts
```

To run the tests for the federated learning functionality:

```bash
npm run test:federated_learning
```

## Contributing

Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

This project is licensed under the terms of the license found in the [LICENSE](../LICENSE) file.