<!-- # LIQUID LAUNCH (LPB) WALKTHROUGH
 -->
## Connect with your wallet and start the wizard

1. Visit [https://launch.prime.xyz/register](https://launch.prime.xyz/register) (for Mainnet) [https://arbitrum.launch.prime.xyz](https://arbitrum.launch.prime.xyz/)/register (for Arbitrum).
2. Click on ‘Connect to a Wallet’ and accept the [Prime Launch Terms of Service](https://launch.prime.xyz/terms-of-service). Make sure you are connected to the intended network.
    - You need to have a compatible wallet set up. Prime Launch connects to most Ethereum wallets, including Metamask and all wallets compatible with WalletConnect. If you don't have an Ethereum wallet yet, set up a [Metamask account](https://metamask.io/) or use a WalletConnect-enabled mobile wallet like [Rainbow](https://rainbow.me/) or [Argent](https://www.argent.xyz/).
    - You will need to fund your wallet with some ETH for paying the transaction costs needed to setup the launch (~$25 worth of ETH is safe). Most wallets will give you instructions on how to acquire those tokens and ETH.
        
![https://ik.imagekit.io/primedao/Launch_Tutorial_Gifs/1-launch-connect-to-wallet.gif?ik-sdk-version=javascript-1.4.3&updatedAt=1648387811269](https://ik.imagekit.io/primedao/Launch_Tutorial_Gifs/1-launch-connect-to-wallet.gif?ik-sdk-version=javascript-1.4.3&updatedAt=1648387811269)
        
3. Click on ‘Start LBP’
4. Click on ‘Start Registration’.
    - In the future you will be able to choose between different LBP packages. At the moment only the *Basic* package is available.

## Setup your Project, Token, LBP and Contract Details

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
    
5. Next up, you will need to setup the **Liquid Launch Details** following these guidelines (you can [get in touch with us](https://primedao.typeform.com/PrimeLaunchSup) to understand how to better setup these details according to your strategy):
    - Select from the dropdown menu the **Funding Token** you want to raise, which is the token that your contributors will have to use to fund your LBP Launch in exchange your project’s tokens.
    
    At the moment you can choose between Prime (D2D), Olympus (OHM), Governance OHM (gOHM), Dai Stablecoin (DAI), USD Coin (UDSC), Wrapped Ether (WETH).
    - Define the total amount of Project Tokens that you will provide to the LBP and the total amount of Funding (Collateral) Tokens that will be supplied to set up your Liquid Launch.
    - Define the Start & End Date and Time as well as the Start & End Weights of your Liquid Launch.
6. LBPs leverage a dynamic weighting that shifts throughout the pool’s lifespan, finding a fair market value by starting at a relatively higher price and lowering the price over time by adjusting the weight ratios if there are no purchases.
    
    The general idea is to start with the pool weights heavily pitched towards your Project Token, and then gradually shift the weights towards the Funding (Collateral) asset by the end of the launch. In this way the majority of your Project Tokens end up being exchanged for the Funding (Collateral) Token you have chosen. By adjusting these parameters the sale can be set to keep the price more or less steady, or declining to a desired minimum (i.e. minimum price target).
    
    Another important thing to keep in mind is that the lower you set the weights of the Funding (Collateral) asset in your LBP, the less upfront capital you would need to seed your launch. In a Prime Liquid Launch, the most pitched ratio in favor of your Project Token that you can set is 2:98, meaning that the pool composition will be 2% your Funding (Collateral) asset, and 98% the Project Token.
    
    However, keep in mind that since the value of your Project Token is proportional to the value of the Funding (Collateral) Token you provide for the launch, the amount of funds you can raise in the launch is limited by the total value of the Funding (Collateral) Tokens you provide to the LBP.
    
    For example, with an LBP weight ratio of 2:98 (Funding Token:Project Token), if your upfront capital is 50K USDC, and your starting price is 10 USDC, the amount of tokens you can sell is [(50K / 0.02) / 10] = approx. 250K tokens. In contrast, if your upfront capital is 1M USDC, you’d be able to sell around 5M worth of tokens.
    
    To learn more about how LBP and weights work please refer to this primer on the [Balancer Documentation](https://docs.balancer.fi/v/v1/guides/smart-pool-templates-gui/liquidity-bootstrapping-pool).
    
    Decide on critical parameters, such as LBP duration, starting and ending weights, and estimate the demand (i.e., expected sale rate), is extremely important. Balancer also provides a [LBP simulator](https://docs.google.com/spreadsheets/d/1t6VsMJF8lh4xuH_rfPNdT5DM3nY4orF9KFOj2HdMmuY/edit?usp=sharing) that allow you to define these parameters according to your expectations. You can also reach out to us and we will help you out to understand and define the most strategic parameters for your launch.
    
7. You can further consult the automatically generated chart in which you can find details on important statistics of the Project Token such as the price and fee percentage. **Implied Market Capitalization** displays the implied market valuation if all Project Tokens are part of the circulating supply. **Price Range** displays the lowest and highest price of the Project Token (in USD) during the launch period. Make sure that this chart reflects your expectations.
So basically what you are doing here is giving **your project’s tokens an initial value by collateralizing them and selecting a start weight.**
    
8. (optional) If you want your contributors to sign a legal disclaimer, add a URL to a file containing the text of the disclaimer. If supplied, all contributors must accept the disclaimer in order to access the launch. The disclaimer must be formatted as plain text or Markdown. [(More info about Markdown)](https://www.markdownguide.org/getting-started/)
    
9. (optional) Toggle the Geoblock in case you want to prevents the following list of geographic locations from contributing to your launch: Afghanistan, Cuba, Ethiopia, Guyana, Iran, Iraq, North Korea, Sudan, Syria, United States, United States Minor Outlying Islands, Venezuela, Yemen, the Crimea. 7. Define the Administrator wallet address.
    
10. The LBP Administrator has the ability to pause and close the LBP, alter the allowlist and withdraw funding tokens.
    
    You can define the address you’re connected to the website with by clicking ‘I will be the administrator’. Alternatively you can choose another address to be administrator by simply input that address in the LBP Administrator text field.

    Click ‘Next’ to move to the next section of the Wizard

11. Define the Contact Details (e-mail address) and add any additional remarks that you might have for us.
    
    Click ‘Next’ to move to the next section of the Wizard, the **LBP Summary.**
    
12. You will see a recap of all the data you have input to setup your LBP Launch. Please thoroughly review the details of your LBP submission before you submit, as it’s your sole responsibility in case some details are wrong.

Click ‘Proceed’ to move to the final section of the Wizard.
    
13. In the last section of the Wizard you will be asked to:
    - Read carefully
    - Tick the boxes to agree to the [Prime Launch Terms of Service](https://launch.prime.xyz/terms-of-service), to confirm that you have reviewed the details of your launch submission (in the previous step) and they are correct, and that you have read the [Privacy Policy](https://launch.prime.xyz/terms-of-service), including the [Prime Launch Cookie Use](https://launch.prime.xyz/terms-of-service).
    - Click on ‘Submit’ to create a request for creation of the LBP that will be reviewed by PrimeDAO and subsequently displayed in the Prime Launch interface. The approval takes place in the [Prime Launch multisig wallet](https://gnosis-safe.io/app/rin:0x2E46E481d57477A0663a7Ec61E7eDc65F4cb7F5C/transactions) and generally take 5-7 days.
    - Confirm the contract interaction in your wallet and awaits confirmation.
    - You will be redirected to a page that provides you with the LBP configuration stored in JSON format in IPFS. **Please save this URL as it can allow us to debug potential problem. Note that it takes a moment to generate the JSON file on IPFS so be patient.**
14. Once approved, we will inform you to your contact e-mail and and the Liquid Launch Administrator will have to fund the LBP with the Project Token and the Funding (Collateral) Tokens previously defined. This can be done by connecting the Liquid Launch Admin wallet to the [Admin Dashboard](https://ethereum-dev-launch-prime.vercel.app/admin/lbps/dashboard)
15. After adding the funds, the LBP will become available in the Prime Launch UI on the start date that you set. However, please note that LBP swapping will be in a "paused" state until, as the LBP administrator, you unpause it to open up swapping. At close time, to ensure an accurate LBP launch, you will need to pause the LBP to turn off swapping. You can also do this in the [Admin Dashboard](https://launch.prime.xyz/admin/lbps/dashboard).    