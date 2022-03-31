<!-- # SEED LAUNCH WALKTHROUGH
 -->
## Connect with your wallet and start the wizard

1. Visit [https://launch.prime.xyz/register](https://launch.prime.xyz/register) (for Mainnet) or visit [https://arbitrum.launch.prime.xyz/register](https://arbitrum.launch.prime.xyz/register) (for Arbitrum).
2. Click on ‘Connect to a Wallet’ and accept the [Prime Launch Terms of Service](https://launch.prime.xyz/terms-of-service). Make sure you are connected to the intended network.
    - You need to have a compatible wallet set up. Prime Launch connects to most Ethereum wallets, including Metamask and all wallets compatible with WalletConnect. If you don't have an Ethereum wallet yet, set up a [Metamask account](https://metamask.io/) or use a WalletConnect-enabled mobile wallet like [Rainbow](https://rainbow.me/) or [Argent](https://www.argent.xyz/).
    - You will need to fund your wallet with some ETH for paying the transaction costs needed to setup the launch (~$25 worth of ETH is safe). Most wallets will give you instructions on how to acquire those tokens and ETH.
        
![https://ik.imagekit.io/primedao/Launch_Tutorial_Gifs/1-launch-connect-to-wallet.gif?ik-sdk-version=javascript-1.4.3&updatedAt=1648387811269](https://ik.imagekit.io/primedao/Launch_Tutorial_Gifs/1-launch-connect-to-wallet.gif?ik-sdk-version=javascript-1.4.3&updatedAt=1648387811269)
        
3. Click on ‘Start Seed’
4. Click on ‘Start Registration’.
    - In the future you will be able to choose between different Seed packages. At the moment only one is available (Basic).

## Setup your Project, Token, Seed and Contract Details

1. Be ready to provide the following **General Information:**
    - Project Name
    - Project Website
    - URL of the project’s Whitepaper
    - URL of the project’s Github repository
    - (optional) Links to the project’s Social Media pages
    
Click ‘Next’ to move to the next section of the Wizard
    
2. Be ready to provide the following **Project Details:**
    - A short text to describe your project (max 200 characters). This short description will be visible to users on Featured Launch cards and the Launch Dashboard page.
    - A short text to describe why contributors should engage your project (max 300 characters). This will be will be prominently displayed on the Launch Dashboard page.
    - A short text describe the team behind the project (max 200 characters). Provide responsibilities and any useful background.
    
Click ‘Next’ to move to the next section of the Wizard
    
3. Be ready to provide the following **Token Details:**
    - The native Ethereum address of the token you are offering to contributors.
    - The maximum supply of project tokens to exist over the project's lifetime. If there is no maximum, provide a reasonable estimate.
    - The project token distribution between different stakeholders. Click on ‘+ Add Stakeholder’ to add a new Stakeholder Group.
    - For each group you need to define the amount of token you plan to distribute (or that you have already distributed) to that Stakeholder Group, as well as the Vest and Cliff period (TODO: add link to glossary) for that group.
    
![https://ik.imagekit.io/primedao/Launch_Tutorial_Gifs/Add-Stakeholder-Group_ODCnz2c4b.gif?ik-sdk-version=javascript-1.4.3&updatedAt=1648390554075](https://ik.imagekit.io/primedao/Launch_Tutorial_Gifs/Add-Stakeholder-Group_ODCnz2c4b.gif?ik-sdk-version=javascript-1.4.3&updatedAt=1648390554075)
    
4. Projects who issue tokens in multiple rounds should clearly demarcate the amount of tokens distributed in each round, so for instance you can specify a group for each round.
This is an example of a Stakeholder Group table distribution.
    
![https://ik.imagekit.io/primedao/Launch_Tutorial_Gifs/Example-of-stakeholder-vesting-table-launch_nTToP242J.png?ik-sdk-version=javascript-1.4.3&updatedAt=1648390770887](https://ik.imagekit.io/primedao/Launch_Tutorial_Gifs/Example-of-stakeholder-vesting-table-launch_nTToP242J.png?ik-sdk-version=javascript-1.4.3&updatedAt=1648390770887)
    
Click ‘Next’ to move to the next section of the Wizard
    
5. Next up, you will need to setup the **Seed Details** following these guidelines (you can [get in touch with us](https://primedao.typeform.com/PrimeLaunchSup) to understand how to better setup these details according to your strategy):
    - Select from the dropdown menu the **Funding Token** you want to raise, which is the token that your contributors will have to use to fund your Seed Launch in exchange your project’s tokens.
        - At the moment you can choose between Prime (D2D), Olympus (OHM), Governance OHM (gOHM), Dai Stablecoin (DAI), USD Coin (UDSC), Wrapped Ether (WETH).
    - Define your **Project Token Exchange Ratio** with the funding token. For example, a 1.5 Project Token Exchange Ratio will provide 1 of your project’s token in exchange of 1.5 Funding Token.
    - Define your **Funding Tokens Target** which specifies the minimum amount raised to consider the Seed Launch successful. If the Funding Target is not reached by the end of the seed duration, the contributors have the option to retrieve their contribution.
    - Define **Funding Tokens Maximum** which specifies the maximum amount to be raised in the Seed Launch. Once the Funding Maximum is reached, the seed will automatically end and the vesting period, if there is one, will begin.
    - Define the **Vesting Schedule** for the people that will participate as contributors in the Seed Launch. Input the duration in days in which the Project token is vested. Vesting is released linearly by default. The cliff is the period in which no tokens can be withdrawn or used — they are locked until this date. Please consider to set a starting date that is not sooner than 5 days from now as this will allow PrimeDAO to multisig approve this launch.
    - Define the **Seed Schedule** which is the period in which your Seed Launch will be open for contributions. The schedule can end before the End Date in the case your Seed Launch reaches the Funding Tokens Maximum.
6. (optional) If you want to allow specific address to contribute to your Seed Launch, add a URL to an **allowlist** in .csv format containing the list of addresses that are allowed to purchase Project tokens. The file must be formatted as plain text and each address must be separated from its neighbor addresses by one or more commas, spaces, tabs or carriage returns. Example using only commas:
    
    ```
    0x1234,0x5678,0xabcd,0x7890
    ```
    
7. (optional) If you want your contributors to sign a **legal disclaimer**, add a URL to a file containing the text of the disclaimer. If supplied, all contributors must accept the disclaimer in order to access the launch. The disclaimer must be formatted as plain text or Markdown. [(More info about Markdown)](https://www.markdownguide.org/getting-started/)
8. (optional) Toggle the **Geoblock** in case you want to prevents the following list of geographic locations from contributing to your launch: Afghanistan, Cuba, Ethiopia, Guyana, Iran, Iraq, North Korea, Sudan, Syria, United States, United States Minor Outlying Islands, Venezuela, Yemen, the Crimea.
    
9. Define the **Administrator wallet address**. The Seed Administrator has the ability to pause and close the seed, alter the allowlist and withdraw funding tokens.
You can define the address you’re connected to the website with by clicking ‘I will be the administrator’. Alternatively you can choose another address to be administrator by simply input that address in the Seed Administrator text field.

Click ‘Next’ to move to the next section of the Wizard
    
10. Define the **Contact Details** (e-mail address) and add any additional remarks that you might have for us.  

Click ‘Next’ to move to the next section of the Wizard, the **Seed Summary.**
    
11. You will see a recap of all the data you have input to setup your Seed Launch. Please thoroughly review the details of your seed submission before proceeding, as it’s your sole responsibility in case some details are wrong.

Click ‘Proceed’ to move to the final section of the Wizard.
    
12. In the last section of the Wizard you will be asked to:
    - Read carefully
    - Tick the boxes to agree to the [Prime Launch Terms of Service](https://launch.prime.xyz/terms-of-service), to confirm that you have reviewed the details of your launch submission (in the previous step) and they are correct, and that you have read the [Privacy Policy](https://launch.prime.xyz/terms-of-service), including the [Prime Launch Cookie Use](https://launch.prime.xyz/terms-of-service).
    - Click on ‘Submit’ to create a request for creation of the Seed that will be reviewed by PrimeDAO and subsequently displayed in the Prime Launch interface. The approval takes place in the [Prime Launch multisig wallet](https://gnosis-safe.io/app/rin:0x2E46E481d57477A0663a7Ec61E7eDc65F4cb7F5C/transactions) and generally take 5-7 days.
    - Confirm the contract interaction in your wallet and awaits confirmation.
    - You will be redirected to a page that provides you with the Seed configuration stored in the JSON format in IPFS. **Please save this URL as it can allow us to debug potential problem. Note that it takes a moment to generate the JSON file on IPFS so be patient.**
13. Once approved, we will inform you to your contact e-mail and the Seed Admin will have to fund the Seed with the correct amount of project tokens. The amount of project tokens to fund is calculated as **Funding Tokens Maximum** divided by **Project Token Exchange Ratio** plus the fee (which at the moment is 0% for all launches). In order to fund you need to connect with the Seed Administrator wallet to the [Admin Dashboard](https://launch.prime.xyz/admin/seeds/dashboard).
After adding the funds, the Seed is initialized. The Seed will automatically be live and available for people to contribute on your start date.