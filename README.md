# Real Rate Triangular Arbitrage in Uniswap V3

### Step 1

```shell
git clone https://github.com/natashagp/tri-arb-real-rate-uniswap-v3.git
```

### Step 2

Change to directory tri-arb-real-rate-uniswap-v3

```shell
cd tri-arb-real-rate-uniswap-v3
```

### Step 3

Install packages as a clean install. This is important to ensure that your versions are exactly the same as in this project.
```shell
npm ci
```

In case this command doesn't work use
```shell
npm install
```

### Step 3

Configure your own ```.env``` file, as shown in the ```.env.example``` file.
Create a ```.env``` file and add your ```PROVIDER_URL``` to be able to run this project.
To create your ```PROVIDER_URL```  you can use [Alchemy](https://www.alchemy.com/) or [Infura](https://www.infura.io/).

### Step 4

Run the project

```shell
node main.js
```

When a real rate triangular arbitrage is found, you will see something like this in your terminal.

![arbitrage_found](https://github.com/user-attachments/assets/26c99810-8691-4c23-b9e2-1ab6ad796c25)
