---
title: Interact with your Wallet
weight: 1
chapter: true
---

# Interact with your Wallet

## Open your Wallet

On Mac and Windows, you can open your wallet simply by clicking on the **AionWallet** application.

On Linux you need to run the `aion_ui.sh` file.

![Aion Desktop Wallet Homescreen](https://files.readme.io/8bdf0f4-Screen_Shot_2018-09-18_at_15.42.02.png)

## Create a New Account

You can create a completely brand new account within the blockchain, or recover an account into this wallet using your **Mnemonic** and **Password**.

To create a completely brand new account:

1. Click **Add account**.
2. Create an **Account name.** This can be changed later if you want.
3. Enter a strong **Password**.
4. Confirm your **Password**.
5. Save and backup the seed mnemonic that is shown. You will need this if you wish to recover your wallet later.

To recover a previously used account that is somewhere in the blockchain:

1. Click **Add account**.
2. Under **Recover from seed**, enter the **Mnemonic** and **Password** associated with your account.
3. The recovered account is now shown under the **Accounts** tab.

### Multiple Accounts

Once an account has been created or recovered, you can quickly add further accounts by clicking **Add account**. You do not have to enter a password or record another mnemonic, as all accounts are held within the one wallet.

## Import Account

There are three options to import an existing account:

- [Keystore File](#section-keystore-file)
- [Private Key](#section-private-key)
- [Ledger](#section-ledger)

There is a **Remember Me** option when importing accounts. Selecting this will display your imported accounts even if you re-launch your wallet. If this option is not selected, you will have to reimport these accounts if you re-launch the Aion Desktop Wallet.

### Keystore File

1. Click **Import account**.
2. Select **Keystore file**.
3. Click **Keystore UTC File**, navigate to your keystore file, and click **Open**.
4. Enter the associated **Password**.
5. Click **Import**.

![Importing a Keystore File](https://files.readme.io/ea46060-Import_Keystore.gif)

### Private Key

1. Click **Import account**.
2. Select **Private key**.
3. Enter your **Private key** and **Password** combination.
4. Click **Import**.

### Ledger

1. Click **Import account**.
2. Select **Ledger**.
3. Click **Connect to Ledger**.

## Export Account

You may wish to save your accounts created on the Aion Wallet elsewhere. In this case, you will need to export the wallet (using the icon right of the accounts listing) and save the keystore file in your desired location. The password you input here will be the new password to access the keystore file:

1. Go to **Accounts**.
2. Click the **Export** button on the account you wish to export.
3. Click **Keystore File Destination**.
4. Navigate to where you want to save the file to, and click **Open**.
5. Enter a **Password** for this file.
6. Click **OK**.

![Exporting a Keystore file from the Aion Desktop Wallet](https://files.readme.io/b1c5599-Export_Keystore.gif)

## Send `AION`

You have the option to transact `AION` and send it to another wallet. The receiving wallet must accept native `AION` coins.

1. Click the **Lock** icon to unlock the account you wish to send `AION` coin from.
2. Go to the **Send** tab.
3. Under **New transaction** input the **Address** you are sending `AION` coin to.
4. Enter the **Amount to send** in `AION` coin. Your **Account balance** must be higher than value in the **Amount to send** field. Keep in mind that every transaction comes with an `Energy` payment. If you want to send the entire contents of an account to another account click **Send all**. The Aion Desktop Wallet will calculate how much `Energy` you need, and deduct it from your total.
5. Click on **Generate transaction** to send the `AION`.

![Send Transaction Screen](https://files.readme.io/b8ca336-5.png)

### Handling Errors

Sometimes things get hung-up when sending a transaction, so the wallet tries to display helpful error messages when possible.

#### `Sending transaction...`

If this message shows for more than a few seconds, make sure that your Aion node is fully synced. You transaction will not occur unless it is up to date.

![Node not synced error.](https://files.readme.io/54ba642-4-sendnotsync.png)

#### `You have transactions that require your attention!`

This often means that the transaction failed. Click the notification to resubmit the transaction.

![Failed to send error.](https://files.readme.io/ee6dcd9-4-failsend.png)

### Receive `AION`

Under the **Receive** tab of the desktop wallet, you can send your public wallet address by:

- Scanning the QR code to display the wallet address.
- Sharing your **Account address**.

![Aion Desktop Wallet send tab](https://files.readme.io/53f5f2f-6.png)