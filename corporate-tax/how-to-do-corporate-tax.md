# How to do Corporate Tax (Vennootschapsbelasting) for your personal holding

If you own a Besloten Vennootschap (B.V.) in The Netherlands, you need to do file your corporate tax statement each year. If you’ve set up your startup with a personal holding for each founder (as per the default company structure that Rockstart offers), each founder has own B.V. for their personal holding, and together you have one B.V. for your actual company, of which your personal B.V. owns a parts of the shares.

Of course there are other setups possible, but this guide assumes the following:

* Each founder has their own personal holding B.V.
* Each personal holding B.V. owns a part of the shares of the actual company (that owns the IP of your startup, is the employer of your employees etc.)
* You are using your personal holding B.V. just as the shareholder of your actual company, e.g. you don’t send any invoices, or make any costs with this B.V.
* You do not invoice your startup’s B.V. from your personal holding with management fees or something similar. Instead, you’re just an employee of your startup’s B.V.
* During this fiscal year, you didn’t get acquired or ceased to exist as a company

## Example
* Alice and Bob are the founders of Unicorn Startup B.V.
* Alice has a personal holding called Alice Holding B.V. that owns 50% of the shares in Unicorn Startup B.V.
* Bob has a personal holding called Bob Holding B.V. that also owns 50% of the shares in Unicorn Startup B.V.

> (The actual percentage of shares can be different of course. Alice’s holding could have 60% of the shares while Bob’s holding could have 40% of the shares.)

* Alice and Bob don’t do anything else with their personal holdings. They do not send invoices from their holding to Unicorn Startup B.V., or any other companies. They do not pay for any costs (like a mobile phone, a data plan, or a laptop) with their personal holding.

If any of these assumptions do not apply to your situation, please check with an accountant that knows about the Dutch tax law to advise you. If all assumptions do apply, please continue.

## Walkthrough through the app
To file your corporate tax return, you need to download the appropriate app from [www.belastingdienst.nl](http://www.belastingdienst.nl). Which app you exactly need depends on the year and your operating system. I will be using the _Aangifte vennootschapsbelasting 2015_ app as my personal holding was started in the beginning of 2015. Because of that, the Dutch tax service asked me to to my corporate tax return for 2015 and 2016 in one go. Normally, you would file a tax report for just one (fiscal) year, but when a B.V. was started during the year, they let you combine it like this. You can find out which period you need to file a tax report for in the letter you got from the tax service (in one of their nice blue envelopes).

![screenshot](images/1-algemene-gegevens.png)

This screen is easy. Fill out the name of your holding (“Naam belastingplichtige”), and the identification number (RSIN) of your holding. You can find this number in the letters from the tax service. Usually it’s on the letter next to the word “Kenmerk” and it can start with 8550.

The dates are the start and end of your bookyear, in this case it’s more than 1 year and I copied this from the letter I got from the tax service.

I’m not using a tax consultant, so last one can be “Nee” (no).

![screenshot](images/2-verkort.png)

This screen is to check if you are eligible for a shortened version of the tax report. If your holding has more than 5% of the shares of another entity (which it has) you’re not eligible for a shortened version and thus we need to enter a lot of stuff.

![screenshot](images/3-bijzonder-situaties.png)

This screen is to check if there are any special situations applicable to your holding. This is not the case, so everything can be answered as “Nee” (no).

![screenshot](images/4-tarief-2016.png)

This screen lets you define different tax tariffs, but you can just use the defaults.

![screenshot](images/5-belastingplichtige.png)

This screen lets you add more info about the nature of your holding. I just entered the description of the activities of my holding, which is “Financiële Holding” (Financial Holding). All the other questions can be answered with “Nee” (no).

![screenshot](images/6-aandelen-en-transacties.png)

This screen lets you enter whether or not your holding has any shareholders (_aandeelhouders_) (yes) and if there were any special transactions (no).

![screenshot](images/7-tegenbewijsregeling.png)

This question can also be answered with “Nee” (no)

![screenshot](images/8-deelnemingen.png)

This screen asks you questions about any participations you have in other companies. Even though you do, all the questions can be answered with “Nee” (no).

![screenshot](images/9-toelichtingen.png)

This screen lets you add any remarks on the previous answered questions. I don’t have any, you probably don’t have them either.

![screenshot](images/10-balans.png)

Now we have to make a balance sheet. The program will guide us through all the steps required to create one. This screen is first, it will ask you if the valuation system has been changed (no) and if this is the first time you are filing a corporate tax report (yes in my case, could be no in yours).

![screenshot](images/11-immaterieel.png)

This screen lets you define your Intangible Assets (_Immateriële vaste activa_). There’s no Goodwill so I left it empty (this goes for the entire balance sheet, if something is 0, you can leave it empty instead of filling in a zero). For the second column I’ve added 51 euro, as the shares of my holding are worth €1 (100 shares of €0,01 each) and I had to pay €50 to the Chamber of Commerce (_KvK_) to register my holding. The other setup costs for the B.V. have been paid by Rockstart so I left them off the balance.

![screenshot](images/11a-immaterieel-specs.png)

This is to specify the intangible assets in case their fiscal costs are different than the costs you’ve put in the previous screen. In my case I left them the same.

![screenshot](images/12-materieel.png)

This screen is to enter your Tangible Property (_Materiële vaste activa_). The holding has none, so I left it all empty.


![screenshot](images/13-financieel.png)

This screen is to enter the Financial Assets (_Financiële vaste activa_). I only entered the amount of €50 here in the participations columns, as my holding as 5000 shares of €0,01 each in my startups’ B.V., which comes to a total of €50.

![screenshot](images/14-voorraden.png)

On this screen you enter any supplies or stocks (_voorraden_) you have. My holding doesn’t have any, so I left it empty. You’re likely to have none either.

![screenshot](images/15-vorderingen.png)

Here you enter any claims (_vorderingen_) you have to various parties, like debitors, the tax service for VAT and any other claims. My holding doesn’t have any, so I left it empty. You’re likely to have none either.

![screenshot](images/16-effecten.png)

Here you enter any securities (_effecten_) your holding has. I don’t have any and you probably don’t have either, so leave this empty.

![screenshot](images/17-liquide.png)

On this screen you enter any cash or money on the bank your holding has. Again, I’ve got nothing for my holding, so I left it empty. This is strictly for your own holding, so not any money you have personally or that your startup’s B.V. might have.

![screenshot](images/18-ondernemingsvermogen.png)

On this screen you declare your holding’s estate (_Ondernemingsvermogen_). I’ve entered €101 here as the combination of the money I paid for the shares in my startup’s B.V., the money I paid to buy my own shares in my holding and the money needed to pay for the Chamber of Commerce registration.

![screenshot](images/19-voorzieningen.png)

Here you declare any provisions (_voorzieningen_) your holding has. We can leave this empty again.

![screenshot](images/20-langlopende-schulden.png)

This if for long-term debts. My holding doesn’t have any, yours probably neither. So I left it empty.

![screenshot](images/21-kortlopende-schulden.png)

This if for short-term debts. My holding doesn’t have any, yours probably neither. So I left it empty.

![screenshot](images/22-balansoverzicht.png)

This results in a nice balance sheet. The assets (_activa_) and liabilities (_passiva_) are in balance, as they should. So you’re good to go for this step!

![screenshot](images/23-toelichting-balans.png)

Here you can enter any remarks on either your assets or liabilities on the balance sheet. I left it empty.

![screenshot](images/24-opbrengsten.png)

This is for declaring any revenue / income (_opbrengsten_) for your holding. Since I didn’t do anything with my personal holding except from owning shares in my startup’s B.V., I will leave this empty.

![screenshot](images/25-personeelskosten.png)

This is for declaring all costs for staffing (_personeelskosten_). Since I don’t employ anyone through my holding, this is empty again. 

![screenshot](images/26-afschrijvingen.png)

Here we can add any deprecations (_afschrijvingen_) that your holding has made. Once again, empty.

![screenshot](images/27-waardeveranderingen.png)

Here you add any changes in valuations (_waardeveranderingen_) of your assets. Also empty.

![screenshot](images/28-overige-bedrijfskosten.png)

Here you can add any costs your holding has made (_overige bedrijfskosten_), like for a car, transport, or office space. I didn’t, so empty I left it it empty.

![screenshot](images/29-baten-en-lasten.png)

Here you enter any financial costs and benefits (financiële baten en lasten) for your holding, like dividends (not from your participations), interest on bank accounts, etc. I didn’t have any, so I left it empty.

![screenshot](images/30-resultaat-deelnemingen.png)

Here you enter any financial income your holding got from it’s participations (_resultaat uit deelnemingen_), like dividends.

![screenshot](images/31-buitengewone-baten.png)

You can declare any special benefits (_buitengewone baten_) your holding received here, like profit made on assets. You probably don’t have any, like me.

![screenshot](images/32-buitengewone-lasten.png)

You can declare any special costs (_buitengewone lasten_) your holding paid here. YOu probably don’t have any, like me.

![screenshot](images/33-overzicht-winst-verlies.png)

Finally, this all leads to the income statement (_winst-en-verliesrekening_) for your holding. As you can see I made no money and didn’t have any costs for this year, so the total is €0.

![screenshot](images/34-toelichting.png)

If you want to add any remarks to your income statement, now is the time to do so. I left this empty.

![screenshot](images/35-aandeelhouders.png)

Time for the next section: tell the tax service something about the shareholders of your holding. This would be just you, so enter your full name in the field above for “Naam van de aandeelhouder” (name of shareholder). This is not the name of any B.V. or holding, but your personal name.

You will just have one shareholder, so after entering your own name you can continue to the next screen.

![screenshot](images/36-gegevens-aandeelhouder.png)

Now we add more details about yourself. 

First question is whether or not you’re a natural person and if you have an aanmerkelijk belang (“significant interest”) in your holding. This means you own at least 5% of the shares of your holding. Usually you have the full 100%, so you answer “Ja” (Yes). 

Then it asks if a _burgerservicenummer_ (BSN) (social security number) is known for this person. When you enter “Ja” (yes) you need to specifiy this number. You can find this number in your personal correspondence with the tax service, on your Dutch ID card or passport, or possibly also on your Dutch foreign registration card.

Then you need to specify the nominal value of your shares. You can enter this for normal shares, preferred shares and priority shares. In this case it’s €1 for normal shares, which represent 100% of the capital put into the holding.

Finally, there are no debts to or claims from the shareholder, so we answer “Nee” (no) twice.

![screenshot](images/37-deelnemingen.png)

Now time for the fun part - list all the participations (deelnemingen) your holding has. In my case this is only the participation I have in my startup’s B.V., so I enter it’s name here and go to the next screen.

![screenshot](images/38-gegevens-deelneming.png)

Now you need to enter all details of this participation. We start with the RSIN number of your startups’s B.V. You can find this in the letters you received from the tax service. This number is different from the RSIN of your holding.

Then we enter the percentage of shares that my holding owns. We were with 2 founders and split the shares evenly: 5000 shares of €0,01 each, for a total amount of €50 euro per founder. 

After Rockstart’s participation in our startup’s B.V., our startup’s B.V. issued 870 extra shares for Rockstart, which brought the total shares for each founder down to 46%. If you’re a single founder, or with multiple founders, these numbers differ of course. Please check your Participation and Shareholders Agreement (PSA) between Rockstart and your startup for the actual numbers. Also, if you’ve issued more shares for later participations, this percentage is also different.

What should remain is the nominal value of these shares (€50 in our case). I kept the value for the sacrificed amount (_opgeofferde bedrag_) and the valuation on the balance (_balanswaardering_) the same as this value. The sacrificed amount would be different if your holding bought shares at a different moment in time than at the start of your startup’s B.V.

Since there’s no claims or received interest on this participation, I left the rest of the columns at zero. I also answered all the other questions with no, except from question 3 that asks if the participation has been obtained or increased during the current financial year. In a next year this could be answered with “Nee” (no) again, unless something changed in your participation in the startup’s B.V.

![screenshot](images/39-specificaties.png)

In this screen the specifications of the participation are filled in. I’m not sure why they ask this again, but I’ve entered the same percentage and nominal value as on the previous screen.

![screenshot](images/40-bijtellingen-en-aftrekposten.png)

Here we need to add any additions or deductibles for the calculation of fiscal profit (_fiscalewinstberekening_). In the screenshot I did check one box, but in fact this is not necessary, so just continue without checking any of the boxes.

![screenshot](images/41-mutaties-kapitaal.png)

Here we need to add if there have been any mutations in the capital of your holding during this fiscal year, like a deposit (first field) or a payback (second field). This was not applicable in my situation.

![screenshot](images/42-saldo.png)

Finally a nice overview of our fiscal profit (_fiscalewinstberekening_). As you can see we didn’t make any profit and our net result is €0.

![screenshot](images/43-regelingen-en-situaties.png)

In order to calculate the actual amount of tax you need to pay, you can check all the regulations and situations that apply to your holding. As far as my holding is concerned, none of these apply. The same will probably also go for you, so just continue with all the boxes unchecked.

![screenshot](images/44-niet-vrijgestelde-voordelen.png)

Here we need to declare any non-exempted benefits from your participations. I had none, and so left it empty. This will most likely also be the case for your holding.

![screenshot](images/45-overzicht-deelnemingsvrijstelling.png)

An overview screen again, showing all the participation exemptions that you’re qualified for.

![screenshot](images/46-overzicht-belastbare-winst.png)

Overview of the taxable profit of your holding. It starts with listing your fiscal profit, then it deducts any deductibles and exemptions to finally come to the taxable profit (_belastbare winst_) in the last cell. For me this is €0, which is most likely also the case for you.

![screenshot](images/47-toelichting.png)

Once again, you can add some remarks, this time about the fiscal profit and the taxable profit. I left this empty.

![screenshot](images/48-vermeerderingen.png)

Here we can select if there are any situations for which we should add or deduct any amounts from the taxable profit, for example when we’ve already paid certain taxes during the fiscal year, or when when also made profits outside The Netherlands. In a normal situation, this does not apply to your holding, so leave them all empty.

![screenshot](images/49-deelnemingsverrekening.png)

Here we need to declare any participation settlements for this fiscal year. This should be nothing.

![screenshot](images/50-overzicht-belastingbedrag.png)

The grand overview of the amount of corporate tax you need to pay. It’s €0, yeh!

![screenshot](images/51-overzicht-normaal-tarief.png)

Another overview of the tax you need to pay, this time taking into account you filed a tax report for more than one year, so you can see how it breaks down per calendar year.

![screenshot](images/52-ondertekenen.png)

You’re done! All that’s left is to sign and submit the tax report to the tax service. The question on the top (“Did you in this tax report take any position of which you’d like an explicit answer of the tax service”) can be answered with “Nee” (no). 

Then add your initials, any insertions between your first and last name, your last name, your role in the organisation (“Owner” or _Eigenaar_ will do) and your phone number.

The last three inputs fields are for your username and password (+ repeat password) for the tax service. These are the same you use to log in to [www.belastingdienst.nl](www.belastingdienst.nl).