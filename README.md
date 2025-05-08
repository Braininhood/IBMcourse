# Simple Interest Calculator

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](code_of_conduct.md)

A simple bash script that calculates simple interest given principal, annual rate of interest and time period in years.

## Description

This script provides a command-line interface to calculate simple interest based on three inputs:
- Principal amount
- Annual rate of interest
- Time period in years

## Formula

The simple interest is calculated using the formula:
```
simple interest = p * t * r
```
where:
- p = principal amount
- t = time period in years
- r = annual rate of interest

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Braininhood/IBMcourse.git
```

2. Navigate to the project directory:
```bash
cd github-final-project
```

3. Make the script executable:
```bash
chmod +x simple-interest.sh
```

## Usage

Run the script:
```bash
./simple-interest.sh
```

The script will prompt you to enter:
1. Principal amount
2. Rate of interest per year
3. Time period in years

Example:
```
Enter the principal:
1000
Enter rate of interest per year:
5
Enter time period in years:
2
The simple interest is: 
100
```

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Code of Conduct

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details on our code of conduct.

## Author

- Upkar Lidder (IBM)
- [Andrii Berezutskyi](https://github.com/Braininhood)

## Acknowledgments

- Thanks to all contributors who have helped improve this project
- Inspired by the need for simple financial calculations in micro-finance applications
