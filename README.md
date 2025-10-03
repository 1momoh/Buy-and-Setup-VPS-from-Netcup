# Buy & Setup VPS from Netcup

Netcup is one of the best VPS providers, known for its high-performance and affordable servers.

Link: https://www.netcup.com/en/

<img width="1080" height="572" alt="image" src="https://github.com/user-attachments/assets/914412a2-0768-434f-9fd3-8cbae732f2c6" />


## Choosing a Server
**NOTE:** If you want to run both an RPC and an Aztec node on your VPS, I'll suggest the "VPS 4000 ARM G11" model.

<img width="358" height="595" alt="image" src="https://github.com/user-attachments/assets/788fd9a9-d0c6-4397-8602-22a8bded69fa" />


Click on "Order Now".

Fill in your details and confirm your order.

## Payment
After ordering, you will receive an email with your Customer Control Panel (CCP) login credentials. Use the CCP to manage your payments and complete the purchase for your server.

CCP Website: https://www.customercontrolpanel.de/


**Note:** I successfully paid using my Bybit Visa card from the Bybit app. Try what will work for you.

*DM on [Telegram](https://t.me/ofalamin) for a $5 coupon code.*

## Managing Your VPS
After your payment is processed, you will receive another email containing your VPS details and Server Control Panel (SCP) login credentials. The SCP is where you can manage your VPS.

SCP Website: https://www.servercontrolpanel.de/SCP/

## Connecting to Your VPS
To connect to your VPS via SSH, you need a client. We recommend downloading and using **Termius**.

Your login details (check your email):

**Hostname/IP:** (Provided in email)

**Username:** root

**Password:** (Provided in email)

**Port:** 22

## Changing VPS Language to English
If you browsed Netcup in English, your server should default to English. If your VPS is in German, follow these steps:

1. Connect to your VPS via SSH.

2. Run the following command:

```bash
  sudo dpkg-reconfigure locales
```

3. You will see a list of locales. Use the arrow keys to navigate.

4. Press the spacebar to deselect any German locales (e.g., de_DE.UTF-8).

5. Navigate to and select en_US.UTF-8 by pressing space (a * should appear).

6. Press the Tab key to jump to the <OK> button and press Enter.

7. The next screen will ask for the default locale. Select en_US.UTF-8 again and press Enter.

8. Your system language will now be updated to English.

