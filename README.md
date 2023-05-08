# VitoWeightLossChallenge
A blockchain and incentive based weight loss challenge smart contract

# Purpose and Background
The purpose of this contract is to provide an incentive to an individual to lose weight and be healthy.  As a fan of the podcast "The Biggest Problem in The Universe" ([biggestproblem.show](https://biggestproblem.show/)) I wanted to create an incentive based weight loss challenge for one of the hosts with the ohter host officiating.

# How It Works
The person losing the weight is declared and their wallet will be the beneficiary of all donated funds.

The officiant of the contest is declared and their associated wallet will enter the starting weight, set the weight loss goal in pounds (default is 100 pounds), and set the time frame for the challenge to complete in days. The Officiant will also enter the final weight starting on the last day of the challenge and up to 7 days afterwards. 

The smart contract will provide an address where wallets can donate to the weight loss goal. The smart contract will hold all funds until Dick Masterson inputs the final weight. The funds will be dispersed on a percentage basis to the Weight Loss Participants wallet and to the donators wallets with the percentage being the percent of total pounds lost divided by the weight loss goal. If the percentage is negative all funds will be returned to the donators. If the percentage is higher than 100 percent then the percentage is set to 100%. 
