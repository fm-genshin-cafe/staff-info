Our server has an extra security lever that prevents unwanted perpetrators from causing havoc in the server.

In order to enable Discovery for our server (so that anyone can search for our server using Discord's "Explore Public Servers" function), we would have to fulfill a list of requirements - one of them is to enable 2FA server-wide. While this doesn't require everyone that joins the server to have 2FA enabled, it does mean that anyone with admin privileges won't get to use them unless they enable it. If you haven't enabled it yet, you will likely see this pop up:

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/b6d85395-fe52-414f-9408-3561eb1c5f90/cantletyoudothat.png)

The specific permissions that are disabled ("Admin privileges") include:

> Kick Members, Ban Members, Administrator, Manage Channels, Manage Server, Manage Roles, and Manage Messages.

Clicking the Resolve link in the popup will bring you directly to the security tab in your User Settings menu, where you can follow the following listed steps to get that set up and regain your Admin powers.

# Setup on Desktop

Start by clicking the lil' cog down by your username and avatar.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/1ffc33b9-d0c7-4a83-9f9a-3d24fbbf0c38/setting-up-2fa-first-step.png)

DON'T GO ANYWHERE. You'll directly land on "My Account", which will offer Two-Factor Authentication right underneath your account info.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/4e7376ea-4467-486d-a667-3e9068c1cef6/capture13.jpg)

Once you click the enable button, you'll see a new 3 step prompt pop up. To begin the 2FA process, you'll either need to download  ***Google Authenticator***  or  ***Authy***  on your mobile device from your app store. Either one of these programs will work here.

## Google Authenticator

If you're using Google Authenticator, you'll be prompted to choose your input method, either scanning a barcode or entering a provided key:

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/310ed1d0-8b58-449c-a37a-4fcf00e9255f/gasetup.png)

Either one of these will work fine (since Discord provides both input methods) but keep in mind, Google Authenticator on Android will need you to install another barcode scanning app if you want to use that option. They require the ZXingBarcode Scanner app, which is totally fine and dandy:

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/f6922a40-fe7f-4918-a822-9a7ffe85c37f/zxing.png)

> You can always just input the code provided in Discord - no Barcode Scanner required.

## Authy

Within Authy, you'll first need to enter your phone number and email to authenticate your phone:

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/e1e68c16-1dd5-4f64-ac8b-6ac0a0f9df60/aaa.png)

You'll see a new pop-up with the option to verify via phone call or text message. Internal testing has yielded results that claim that the most recent smartphones are in fact capable of making and receiving phone calls, despite how rare this phenomenon appears.

Once you've authenticated your device, go ahead and press the "+" button in the center to add a new authentication account. Finally, you'll reach the "Authenticator Accounts" screen. You'll have the option to scan a QR code, or enter the code manually.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/809d6c20-45e1-41ca-9669-ca5d1b8a4ccb/scantimesrs.png)

## After setting up the app, what now?

Use Authy's or Google Authenticator's QR scanner on the QR code provided within Discord here, or simply enter the 2FA key manually, both works:

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/2b6efc4b-c8af-422b-9a89-e6ad5f9718bc/qrtime.png)

Then, the app will generate a 6 digit code that is the final piece to enabling 2FA in Discord. Enter it in on Discord, and you're good to go.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/ca2e34b4-0455-4dc6-90f5-5810ae233d10/codetime.png)

Once you've enabled 2FA successfully, you'll have a fancy little box pop up with a couple suggestions to help make sure you can access your account in case of an emergency:

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/a71413b2-4607-49f5-9b0c-9bc8714d0b92/you-did-it.png)

You can now link your phone number to your account to help act as a backup method for obtaining 2FA codes. This is to help should you be worried about losing access to your authenticator app say by dropping your phone in water/lava/a hippo/etc.

Make sure to also download your backup codes. Keep them safe, and loved. Tuck a paper copy of them in your diary, or your dairy. Your choice.

If you didn't have time to add your phone as back up? Or forgot to download your backup codes? It's all good, You can still do this in your account settings! Your settings screen will now look like this:

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/85837a71-41dd-4423-8460-e58fb2f07fd0/my-account.png)

 **Step 1.** Click that 'Enable SMS Authentication' button.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/794745e6-da27-4bb6-a1bf-7cd5b73a87a5/enter-phone-number.png)

Step 2. Verify that number in Discord.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/55e52267-cfcc-4aaa-8fa9-ba19b622562a/enter-code.png)

After you have enabled SMS Authentication, your login screen will look like this:

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/32546804-57f2-4220-b87d-552338dd0f3c/login-screen.png)

Now when you login, if the feature is enabled, you will have a link to request an SMS with a code to authenticate yourself as a backup option.

> Note: To download your backup codes, simply click on the 'View Backup Codes' button and enter your password. Should you ever have to reset 2FA on your account - make sure to save a new set of Backup Codes, as each set is unique to when you enable 2FA on your account.

# Setup on Mobile

## iOS

On iOS, press the cog icon to access your User Settings > then press Account

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/382e8bcf-9aae-47b7-8f7d-47320ae4b476/combo-1.jpg)

Once you click the Enable Two-Factor Auth button, you'll see a new 3 step prompt pop up. To begin the 2FA process, you'll either need to download Google Authenticator or Authy on your mobile device.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/f0375925-fc6a-45ae-b401-e9cebf9ee2f3/combo-2.jpg)

Once you have either Google Authenticator or Authy installed, you will be prompted to connect your account to the authentication app. [(Click here for instructions)](https://bip.so/genshinimpactcafe/new-canvas-38464c?blockUUID=e60e6d26-9efb-46b7-b597-47a5fe98866d)

Once you connected, you've enabled 2FA successfully! 🎉

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/845612c6-6cb7-4e81-adc2-9804c729c0b8/combo-3.jpg)

You can link your phone number to your account to help act as a backup method for obtaining 2FA codes. This is to help should you be worried about losing access to your authenticator app say by dropping your phone in water/lava/a hippo/etc.

Make sure to also download your backup codes. Keep them safe, and loved.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/07653b48-5496-44fd-959e-359f09bc03d3/7.jpg)

## Android

On Android, press the cog icon to access your User Settings > then press Account

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/5086e8a3-ea4f-43ca-af8b-425f97c2b812/combo-1-1.jpg)

Once you click the Enable Two-Factor Auth button, you'll see a new 3 step prompt pop up. To begin the 2FA process, you'll either need to download Google Authenticator or Authy on your mobile device.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/1a9da121-df36-4b3c-8f9b-79d2bfbdab03/combo-2-1.jpg)

Once you have either Google Authenticator or Authy installed, you will be prompted to connect your account to the authentication app. [(Click here for instructions)](https://bip.so/genshinimpactcafe/new-canvas-38464c?blockUUID=e60e6d26-9efb-46b7-b597-47a5fe98866d)

Once you connected, you've enabled 2FA successfully! 🎉

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/bac6835e-9eeb-452e-9bc2-424421238f7b/combo-3-1.jpg)

You can link your phone number to your account to help act as a backup method for obtaining 2FA codes. This is to help should you be worried about losing access to your authenticator app say by dropping your phone in water/lava/a hippo/etc.

Make sure to also download your backup codes. Keep them safe, and loved.

![Image](https://d1uyo0yzpsnvfq.cloudfront.net/4586/0/blocks/0a34a49e-8b28-4c27-9893-e69ff2bc10e7/7-1.jpg)

And that wraps up Discord's Two-Factor Authentication! Once you have everything setup, you can exercise your powerful admin privilege!
