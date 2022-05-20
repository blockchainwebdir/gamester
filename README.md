# Connect with Gamers! Develop Games & Get Paid in Crypto!

![MicrosoftTeams-image (4)](https://user-images.githubusercontent.com/104611242/169565131-d30b65cf-5d06-4e3d-a3df-4793631506e9.png)

# Gamester we have inbuilt 1) Escrow agreement 2)Create product services pages 3) Invoice creation and 4) Analytics

Escrow service in which Buyer and Seller can create escrow agreement where buyer will have to lock the funds in smart contract and once buyer reacieves product/service they need to click "finish" by which smart contract will release funds to Seller's wallet.

We have inbuilt product services page creation where Game developers and designers can create pages for their work and share it among their network. Interested client can approach them by sending a message from their Product/Service page.

We have Invoice creation option in which user can create an invoice and send it to the customer. Customers can download the invoice and make a payment in Crypto through this "Pay" button.

we have analytics which will give over views of how your services/product business is performing overall.

# BOBA Network COnfigration

https://github.com/gamester-heckathon/gamester/blob/master/hardhat.config.js


```javascript


require("@nomiclabs/hardhat-waffle"); 
require("dotenv").config({ path: "./.env" });

const pk_1 = process.env.REACT_APP_BOBA_PRIVATE_KEY_1;

module.exports = {
  solidity: "0.8.0",
  networks: {
    boba_rinkeby: {
      url: `https://rinkeby.boba.network`,
      accounts: [pk_1],
    }
  },
};


```

# Homepage

![Screenshot 2022-05-20 at 9 05 49 PM](https://user-images.githubusercontent.com/104611242/169565562-6192b675-1e06-48a3-bef9-f7a469e1e443.png)

# Escrow Agreement

![Screenshot 2022-05-20 at 9 06 31 PM](https://user-images.githubusercontent.com/104611242/169565635-93c6e4fc-f9fd-4359-b542-50c9fad8b58b.png)


# Product & Services

![Screenshot 2022-05-20 at 9 06 43 PM](https://user-images.githubusercontent.com/104611242/169565664-fd585b11-4dcf-4c14-afae-1b4c3d691259.png)


# Hiring

![Screenshot 2022-05-20 at 9 06 50 PM](https://user-images.githubusercontent.com/104611242/169565703-27e7f9a5-767b-482b-b892-9dcb6c76576e.png)


# Invoice

![Screenshot 2022-05-20 at 9 07 02 PM](https://user-images.githubusercontent.com/104611242/169565725-33d25e97-e57a-4488-b910-e230f52d6953.png)


# Invoice Details
![Screenshot 2022-05-20 at 9 07 11 PM](https://user-images.githubusercontent.com/104611242/169565751-b45a0eb9-efca-4e2b-8506-d3bb44da2d42.png)

# Analytics

![Screenshot 2022-05-20 at 9 07 28 PM](https://user-images.githubusercontent.com/104611242/169565813-ef03559c-a562-4324-8c02-52c721d76084.png)


