# null dependency

null dependency module for npm

## Installation

  `npm install null dependency`

## Usage

```
{
  "name": "usage-example",
  "version": "1.0.0",
  "dependencies": {
    "tedious": "^18.6.1"
  },
  "overrides": {
    "tedious": {
      "@azure/identity": "npm:@teleworld/null-dependency@1.0.0",
      "@azure/keyvault-keys": "npm:@teleworld/null-dependency@1.0.0"
    }
  }
}
```
