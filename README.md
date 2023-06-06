# NFT Drop Claim Page deployed on the Q-testnet network
Example of an NFT Drop Claim Page.

### 1. Customize the Styling

You can change the theme and primary color of the page by updating `primaryColorConst` and `themeConst` in [`parameters.ts`](/src/consts/parameters.ts). 

If you want to go further, you can also update the styles in the respective components by changing the [Tailwind](https://tailwindcss.com/) classes.

### 2. Optional: Add Gasless Transaction Support

If you want to sponsor the gas fees for your user, you can update the `relayerUrlConst` in [`parameters.ts`](/src/consts/parameters.ts) to point to your Open Zeppelin relayer or `biconomyApiKeyConst` and `biconomyApiIdConst` to use Biconomy.