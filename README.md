# Osmosis Liquidity Pool Calculator
Concentrated Liquidity is coming soon tm to Osmosis Zone. Want to figure out how to best position your liquidity? Just use this calculator!

NOTE: This application is still under development. 

## Aims :dart:

Confused about concentrated liquidity? Want to figure out how to best position your liquidity in pools and potentially earn a profit? Look no further! 

This calculator allows you to simulate liquidity positions on Osmosis Zone and see potential outcomes BEFORE they happen! No more impermanent loss and capitulation for savvy liquidity providers :eyes:

Right now, this bot utilizes [Flipside Crypto](https://flipsidecrypto.xyz/) Osmosis data to monitor transactions. Flipside Crypto does not provide live data, but data on a 12 hour delay. So transactions performed within the last 12 hours will not be immediately available on the application.  

## Setup :hammer:

#### Flipside Crypto

To access the Flipside Crypto dataset, you will need an API key. To obtain an API key, sign up for the app and navigate to the key management page. 

Alternatively, you can visit app.flipsidecrypto.com and sign up for an account using either your Discord, ETH wallet, or email. Write your query in the application's query editor, set an appropriate refresh rate in the upper right corner, and use the API button to generate a URL. Use this URL as a GET request in your code, and the Python json library to parse the query results. 

#### Shiny 

The front-end of this application was created using Shiny for Python. To install Shiny, please follow the installation instructions on the [Shiny webpage](https://shiny.rstudio.com/py/docs/install.html). Please note that Shiny for Python is still in the alpha phase, and thus the package may include bugs. It is not currently recommended to use Shiny for Python for large-scale production applications. 

## Contributions :wave:

Contributions of any form are encouraged and appreciated. Please follow the "fork and pull" Git workflow if you would like to create a new feature: 

1. Fork the repo on Github
2. Clone the repo onto your own machine
3. Create a new branch and commit any changes to this branch
4. Push your work to back up your fork
5. Submit a pull request and request review from jhuhnke

IMPORTANT: Be sure to merge the lastest commit from upstream before submitting a pull request.

The more detailed the branch name and description of the pull request, the better! A thorough description of what you are adding to the codebase will help speed up the review process. 

To report a bug or submit a feature request, please use the issues tab to open and submit an issue. The more detailed the bug report or feature request, the easier it is for me to integrate it into the application!

## Donations :money_with_wings:

Any donations are greatly appreciated and will be put torwards the cost of the deployment server. Extra donations will likely be used to buy the dev a coffee or a beer. 

Osmosis address: osmo1dup5a0hn4lel0kexcsx2yk4arm0hxm0cde6d4h

Cosmos Hub address: cosmos1dup5a0hn4lel0kexcsx2yk4arm0hxm0c9zfar9

ETH address: 0xdB69470D5e86Ae237721Cf1A292B80220d5575EA

Solana address: 2L6j3wZXEByg8jycytabZitDh9VVMhKiMYv7EeJh6R2H

## License :shipit:

This software has a GNU GPLv3 License. Feel free to do anything with this code except distribute a closed source version. 

If you fork or get inspirition from this code, please include proper attribution. 
