# Link Cleaner
Browser extension to clean URLs that are about to be visited from utm_* parameters.

Also cleans tracking parameters on item pages of aliexpress and amazon sites.

For example, this url:
    http://meyerweb.com/eric/thoughts/2017/03/07/welcome-to-the-grid/?utm_source=frontendfocus&utm_medium=email

is changed to:
    http://meyerweb.com/eric/thoughts/2017/03/07/welcome-to-the-grid/

This amazon url:
    https://www.amazon.com/AmazonBasics-Type-C-USB-Male-Cable/dp/B01GGKYQ02/ref=sr_1_1?s=amazonbasics&srs=10112675011&ie=UTF8&qid=1489067885&sr=8-1&keywords=usb-c

is changed to:
    https://www.amazon.com/AmazonBasics-Type-C-USB-Male-Cable/dp/B01GGKYQ02/

This facebook url:
    https://l.facebook.com/l.php?u=https%3A%2F%2Fwww.fsf.org%2Fcampaigns%2F&h=ATP1kf98S0FxqErjoW8VmdSllIp4veuH2_m1jl69sEEeLzUXbkNXrVnzRMp65r5vf21LJGTgJwR2b66m97zYJoXx951n-pr4ruS1osMvT2c9ITsplpPU37RlSqJsSgba&s=1

is changed to https://www.fsf.org/campaigns/

This reddit url:
    https://out.reddit.com/t3_5pq7qd?url=https%3A%2F%2Finternethealthreport.org%2Fv01%2F&token=AQAAZV6JWHBBnIcVjV1wvxVg5gKyCQQSdUhGIvuEUmdPZhxhm8kH&app_name=reddit.com

is changed to:
    https://internethealthreport.org/v01/


You can now visit and bookmark clean links instead of the long,
tracking-enabled ones!


# License
Released under the GPLv3 license
