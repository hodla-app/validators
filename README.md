Hey there, awesome validator folks!

If you want your own personalized page on Hodla, visit  our website https://hodla.org/#validators. Then select the networks where you operate as a validator and proceed to the payment link (payment is in crypto). After that, all you gotta do is to make a PR in this repository, and voilà, we'll work our magic to create your very own space in Hodla.

Creating your space is pretty easy:

0. We have two folders for devnet (devValidators) and mainnet (validators) credentials. If needed, feel free to create your validator page in devnet first. 
1. Head to the "validators" folder and create a new folder with your validator name, please note that the folder must be named in lowercase. Let's say your folder name is "supervalidator", then your link will be **app.hodla.org/supervalidator**.
2. Inside the folder, add a JSON file named **_config.json_**. You can see an example of the format [here](https://github.com/hodla-app/validators/blob/main/devValidators/testval/config.json). Here are some tips:
- Required fields: "name" and "networks" (gotta have at least one element in the networks array). The remaining fields are optional, but if you want a higher conversion rate into staked assets, it's recommended to provide more information!
- Keep your validator name short, think mobile-friendly.
- Describe your validator briefly and snappily; long descriptions can be a bummer on mobile phones. Max: 512 characters.
3. Oh, and don't forget to throw in your cool icon (totally optional, though!). Go for a 512x512 or 1024x1024 PNG format, but if you decided to attach your icon, name it **_logo.png_**, please :) 

Once you've done all that and made a PR, our team will work their magic and, in case of approval, automatically create your personal space in Hodla.

We're stoked to have you on board!
