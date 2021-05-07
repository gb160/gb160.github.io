### Purchasing Information

We now accept payment via Paypal, Credit/Debit Card, Bitcoin or Ethereum

**It is presumed if you purchase this app you have read and understood the following:**

This app is iOS only.

**FCC is available for all Mavic Air 2, Air2S, Mini 2 & Mini drones**

**5.8GHz band is also available for countries where it's not permitted to use (Russia, Israel etc)**

**Airsense is only available for Mavic Air 2 drones where the model number ends in 3W**

**YOU MUST ARRANGE APP SIGNING YOURSELF**

{% include button_info_signing.html %}

**By purchasing the app it is presumed that you know how to sign the app and install on your device.**


If you have a jailbroken iDevice you wont need to sign the app.

We can guarantee that the current app version will achieve FCC mode with the current firmware, we don't know what the future holds so update the firmware at your own risk.

Due to limited test devices, we can only guarantee the app will work on iOS12, iOS13 and iOS14 ...we hold no responsibility if you're running an older or beta OS and the app doesn't work.

**You will be issued a login that will activate the app on 1 device for 12 months, any attempt to use one login on multiple devices will result in the account being suspended. Your login will be tied to the first device that you authenticate with the app**

The price of the app is £15 (UK/GBR) for a 12 month license, you will be entitled to free updates within that 12 months.

In the case of upgrading/losing your device, it is possible to switch your login to a different device for a further £5 (UK/GBR)

Paypal Note: If you select 'Paying for goods or services' a fee to paypal will be charged, in which case the price is £17 (UK/GBR), you can avoid this extra fee by selecting 'Friends and Family'

If none of this is a problem then purchase by choosing your preferred payment method at the bottom of this page.

**All Payment options are completely secure, all Credit/Debit card purchases are handled directly by Paypal, all crypto purchases are handled directly by Coinbase**

When your payment is complete please send an email using the button below so i can get you up and running as quickly as possible...Notifications (especially Paypal) are often slow.

{% include button_email.html %}

**You will receive your login and installation instruction via the email address you provide**
**If you complete your purchase and get no reply, please check your spam/junk folder**
**Also please note that many Russian email domains (mail.ru etc) block emails from ProtonMail, so if your email address end with '.ru' please use a different one. Gmail/Hotmail/iCloud etc all work fine**


### Contact and Support

If any issues or questions arise, then feel free to contact support:

{% include button_email.html %}

Use this software at your own risk, we accept no responsibility for any damage caused by, or to your DJI device.



###P ayment Methods

# To Purchase with Bitcoin or Etherium, use the button below:

{% include button_crypto.html %}


# To Purchase with Paypal or Credit/Debit card, use the options below:

<div id="smart-button-container">
      <div style="text-align: center;">
        <div id="paypal-button-container"></div>
      </div>
    </div>
  <script src="https://www.paypal.com/sdk/js?client-id=sb&currency=GBP" data-sdk-integration-source="button-factory"></script>
  <script>
    function initPayPalButton() {
      paypal.Buttons({
        style: {
          shape: 'rect',
          color: 'blue',
          layout: 'vertical',
          label: 'paypal',
          
        },

        createOrder: function(data, actions) {
          return actions.order.create({
            purchase_units: [{"description":"Mod DJI Fly 12 Month License","amount":{"currency_code":"GBP","value":15}}]
          });
        },

        onApprove: function(data, actions) {
          return actions.order.capture().then(function(details) {
            alert('Transaction completed by ' + details.payer.name.given_name + '!');
          });
        },

        onError: function(err) {
          console.log(err);
        }
      }).render('#paypal-button-container');
    }
    initPayPalButton();
  </script>

  **All Payment options are completely secure, all Credit/Debit card purchases are handled directly by Paypal, all crypto purchases are handled directly by Coinbase**
