# archiveteam-warrior-heroku
Unofficial experimental easy deployment of Archive Team Warrior to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

The Archive Team Warrior is a virtual archiving appliance. You can run it to help with the ArchiveTeam archiving efforts. It will download sites and upload them to our archive — and it’s really easy to do!

You can learn more about the Archive Team Warrior at https://wiki.archiveteam.org/index.php/ArchiveTeam_Warrior.

**IMPORTANT NOTES**:
- Heroku may suspend your account (and any other accounts you may have) if you use a really large amount of bandwidth over a short period of time. In general, deploying only 1 Warrior to your account and running it with 5 or fewer concurrent items should be fine.
- While the Heroku Warrior image can update project scripts and download new ones, it cannot automatically update project script dependencies. This means that many new and some updated projects may eventually not run on your Warrior. Because of this, it is recommended to delete your Warrior app from Heroku and re-deploy it (using the same steps you are using now) every 1-2 months. (This problem with updating dependencies only applies to Heroku.)
- Free, unverified Heroku accounts have a pool of 550 hours per month, which means that your Warrior will only run for about 74% to 82% of a given month if no other apps are active on your Heroku account. To allow your Warrior for the full month for free, you can verify your credit card with Heroku, which increases your pool to 1000 hours per month.
